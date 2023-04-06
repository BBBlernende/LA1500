# Lern-Bericht
Violet (Yildirim, Meier, Sutter, Salie)

## Einleitung

Wir haben in diesem Projekt mithilfe von Unity einen Dungeon Crawler erstellt.
## Was habe ich gelernt?

Wir haben in diesem Projekt gelernt, wie man in Unity ein Objekt bewegen kann durch Tasteneingaben(Movement).
## Beschreibung

Movement in Unity ist die verwendung von Rigidbody2d und ein paar Zeilen Code um eine Objekt bewgen zu können.
Wir mussten, da es ein 2D Spiel ist, die möglichkeit zur Bewegung hoch und runter ausschalten. Also haben wir in Unity die Z Achse eingefroren, dass wir uns nur auf einer zweidimensionalen Ebene bewegen.
Das haben wir gemacht, indem wir einen Rigidbody2D an das Objekt gebunden haben und dort die Z Achse auf "Freeze" gedrückt.
Danach mussten wir  noch einen Code hinzufügen, wo wir dem Objekt sagen, dass es sich vertikal oder horizontal bewegen kann, wenn wir bestimmte Tasten drücken (WASD).
Wir haben dem Objekt einen float "movespeed" und einen Vector2 "movement" gegeben und dann den Rigidbody2D als "rb" benannt.
Die Achsen konnten wir hinzufügen, indem wir den Vector2 von x an die Horizontale eingabe und den Vector2 von y an die Vertikale gebunden haben.
Zum Schluss mussten wir deklinieren, dass sich das Objekt bewegt, indem man unsere Position + "movement" * unsere Geschwindigkeit und * "fixedDeltaTime".
       
```
public class PlayerController : MonoBehaviour
{

    public float moveSpeed = 5f;

    public Rigidbody2D rb;

    Vector2 movement;

    void Update()
    {
        movement.x = Input.GetAxisRaw("Horizontal");
        movement.y = Input.GetAxisRaw("Vertical");
    }

    void FixedUpdate()
    {
        rb.MovePosition(rb.position + movement * moveSpeed * Time.fixedDeltaTime);
    }
}
```
 
![image](https://user-images.githubusercontent.com/89085881/230308059-0e5a4a52-0d42-4d1b-a5b4-1ee9e4cd250a.png)

## Verifikation

Man kann in den Medien genau sehen, wie und womit man ein Objekt in Unity bewegen kann, man hat Code, Bild von den "Components" und man hat eine deutliche Beschreibung.
# Reflexion zum Arbeitsprozess

👍 Wir fanden sehr schnell Informationen wie Tutorials und konnten diese sehr Fehlerfrei umsetzen.

👎 Wir hatten anfangs Schwierigkeiten und in Unity zurechtzufinden und mussten uns zuerst daran gewöhnen.

**VBV**: Wir werden nächstes Mal weniger auf das Aussehen achten, da wir sehr viel Arbeitskraft für den nicht technischen Teil abgegeben haben.
         Wir werden uns mehr auf das Programieren konzentrieren und weniger auf das Design.
