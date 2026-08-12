---
title: "System::Drawing::Rectangle class"
linktitle: "Rectangle"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Rectangle class. Representerar ett rektangulärt område i en bild som definieras av heltals‑X‑ och Y‑koordinater för dess övre vänstra hörn samt dess bredd och höjd. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig System::SmartPtr class för att hantera objekt av denna typ i C++."
type: docs
weight: 1900
url: /sv/cpp/system.drawing/rectangle/
---
## Rectangle class


Representerar ett rektangulärt område i en bild som definieras av heltals‑X‑ och Y‑koordinater för dess övre vänstra hörn samt dess bredd och höjd. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig [System::SmartPtr](../../system/smartptr/) class för att hantera objekt av denna typ.

```cpp
class Rectangle
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [Ceiling](./ceiling/)(const RectangleF\&) | Skapar ett [Rectangle](./)-objekt från det angivna [RectangleF](../rectanglef/)-objektet genom att avrunda [RectangleF](../rectanglef/)-objektets positions‑ och storleksvärden till nästa högre heltal. |
| [Contains](./contains/)(int, int) const | Bestämmer om den angivna punkten ligger inom rektangeln som representeras av det aktuella objektet. |
| [Contains](./contains/)(const Point\&) const | Bestämmer om den angivna punkten ligger inom rektangeln som representeras av det aktuella objektet. |
| [Contains](./contains/)(const Rectangle\&) const | Bestämmer om den angivna rektangeln ligger inom rektangeln som representeras av det aktuella objektet. |
| [Equals](./equals/)(const Rectangle\&) const | Bestämmer om rektanglarna som representeras av det aktuella och det angivna objektet är identiska. |
| static [FromLTRB](./fromltrb/)(int, int, int, int) | Skapar ett nytt [Rectangle](./)-objekt som representerar en rektangel med de angivna kantpositionerna. |
| [get_Bottom](./get_bottom/)() const | Returnerar y-koordinaten för rektangelns nedre kant som representeras av det aktuella objektet. |
| [get_Height](./get_height/)() const | Returnerar rektangelns höjd som representeras av det aktuella objektet. |
| [get_IsEmpty](./get_isempty/)() const | Bestämmer om X- och Y-koordinaterna för det övre vänstra hörnet av rektangeln som representeras av det aktuella objektet samt dess bredd och höjd har värdet 0. |
| [get_Left](./get_left/)() const | Returnerar X-koordinaten för rektangelns vänstra kant som representeras av det aktuella objektet. |
| [get_Location](./get_location/)() const | Returnerar en instans av klassen [Point](../point/) som anger platsen för rektangelns övre vänstra hörn som representeras av det aktuella objektet. |
| [get_Right](./get_right/)() const | Returnerar X-koordinaten för rektangelns högra kant som representeras av det aktuella objektet. |
| [get_Size](./get_size/)() const | Returnerar en instans av klassen [Size](../size/) som anger rektangelns bredd och höjd som representeras av det aktuella objektet. |
| [get_Top](./get_top/)() const | Returnerar Y-koordinaten för rektangelns övre kant som representeras av det aktuella objektet. |
| [get_Width](./get_width/)() const | Returnerar rektangelns bredd som representeras av det aktuella objektet. |
| [get_X](./get_x/)() const | Returnerar X-koordinaten för det övre vänstra hörnet av rektangeln som representeras av det aktuella objektet. |
| [get_Y](./get_y/)() const | Returnerar Y-koordinaten för det övre vänstra hörnet av rektangeln som representeras av det aktuella objektet. |
| [GetHashCode](./gethashcode/)() const | Returnerar en hashkod för det aktuella objektet. |
| [Inflate](./inflate/)(int, int) | Ökar bredden och höjden på rektangeln som representeras av det aktuella objektet, samtidigt som den geometriska mittens position bibehålls. Bredden och höjden ökas i båda riktningarna med de angivna mängderna. |
| [Inflate](./inflate/)(const Size\&) | Ökar bredden och höjden på rektangeln som representeras av det aktuella objektet, samtidigt som den geometriska mittens position bibehålls. Bredden och höjden ökas i båda riktningarna med de mängder som motsvarar bredd- och höjdvärden i det angivna storleksobjektet. |
| static [Inflate](./inflate/)(const Rectangle\&, int, int) | Ökar bredden och höjden på rektangeln som representeras av det angivna objektet, samtidigt som den geometriska mittens position bibehålls. Bredden och höjden ökas i båda riktningarna med de angivna mängderna. |
| [Intersect](./intersect/)(const Rectangle\&) | Ersätter rektangeln som representeras av det aktuella objektet med den rektangel som erhålls genom dess skärning med rektangeln som representeras av det angivna objektet. |
| static [Intersect](./intersect/)(const Rectangle\&, const Rectangle\&) | Returnerar en rektangel som är resultatet av skärningen av de angivna rektanglarna. |
| [IntersectsWith](./intersectswith/)(const Rectangle\&) | Bestämmer om rektanglarna som representeras av det aktuella och det angivna objektet skär varandra. |
| [Offset](./offset/)(const Point\&) | Förskjuter positionen för rektangeln som representeras av det aktuella objektet med de angivna värdena. |
| [Offset](./offset/)(int, int) | Förskjuter positionen för rektangeln som representeras av det aktuella objektet med de angivna värdena. |
| [operator RectangleF](./operatorrectanglef/)() const | Returnerar ett [RectangleF](../rectanglef/)-objekt som representerar en rektangel som är ekvivalent med den rektangel som representeras av det aktuella objektet. |
| [operator!=](./operator!=/)(std::nullptr_t) const | Returnerar alltid true. |
| [operator==](./operator==/)(std::nullptr_t) const | Returnerar alltid falskt. |
| [Rectangle](./rectangle/)() | Skapar en ny instans av [Rectangle](./)-objekt som representerar en rektangel med X- och Y-koordinater samt bredd- och höjdvärden satta till 0. |
| [Rectangle](./rectangle/)(int, int, int, int) | Skapar en ny instans av [Rectangle](./)-objekt som representerar en rektangel med de angivna koordinaterna för dess övre vänstra hörn samt bredd och höjd. |
| [Rectangle](./rectangle/)(const Point\&, const Size\&) | Skapar en ny instans av [Rectangle](./)-objekt som representerar en rektangel där koordinaterna för dess övre vänstra hörn anges som en instans av klassen [Point](../point/) och dess bredd och höjd som en instans av klassen [Size](../size/). |
| [Rectangle](./rectangle/)(const System::Windows::Forms::Screen::Rectangle_\&) | Skapar en ny instans av [Rectangle](./)-objekt som representerar den rektangel som är ekvivalent med den angivna. |
| static [Round](./round/)(const RectangleF\&) | Skapar ett [Rectangle](./)-objekt från det angivna [RectangleF](../rectanglef/)-objektet genom att avrunda [RectangleF](../rectanglef/)-objektets positions- och storleksvärden till närmaste heltal. |
| [set_Height](./set_height/)(int) | Ställer in höjden på rektangeln som representeras av det aktuella objektet. |
| [set_Location](./set_location/)(Point) | Ställer in platsen för rektangelns övre vänstra hörn som representeras av det aktuella objektet. |
| [set_Size](./set_size/)(Size) | Ställer in bredden och höjden på rektangeln som representeras av det aktuella objektet. |
| [set_Width](./set_width/)(int) | Ställer in bredden på rektangeln som representeras av det aktuella objektet. |
| [set_X](./set_x/)(int) | Ställer in X-koordinaten för rektangelns övre vänstra hörn som representeras av det aktuella objektet. |
| [set_Y](./set_y/)(int) | Ställer in Y-koordinaten för rektangelns övre vänstra hörn som representeras av det aktuella objektet. |
| [ToString](./tostring/)() const | Returnerar strängrepresentationen av det aktuella objektet. |
| static [Truncate](./truncate/)(const RectangleF\&) | Skapar ett [Rectangle](./)-objekt från det angivna [RectangleF](../rectanglef/)-objektet genom att trunkera [RectangleF](../rectanglef/)-objektets positions- och storleksvärden till nästa lägre heltal. |
| static [Union](./union/)(const Rectangle\&, const Rectangle\&) | Returnerar en rektangel som är resultatet av föreningen av de angivna rektanglarna. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](./empty/) | En tom rektangel, d.v.s. en rektangel vars plats- och storleksvärden är noll. |
## Se även

* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
