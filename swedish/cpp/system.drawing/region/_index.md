---
title: "System::Drawing::Region-klass"
linktitle: "Region"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Region-klass. Representerar insidan av en grafisk form. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 2100
url: /sv/cpp/system.drawing/region/
---
## Region class


Representerar insidan av en grafisk form. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class Region : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() const | Returnerar en kopia av det aktuella objektet. |
| [Complement](./complement/)(const RectangleF\&) | Ersätter den region som representeras av det aktuella objektet med den del av regionen som definieras av den angivna rektangeln som inte skär med denna region. |
| [Complement](./complement/)(const Rectangle\&) | Ersätter den region som representeras av det aktuella objektet med den del av regionen som definieras av den angivna rektangeln som inte skär med denna region. |
| [Complement](./complement/)(const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Ersätter den region som representeras av det aktuella objektet med den del av regionen som definieras av den angivna banan som inte skär med denna region. |
| [Complement](./complement/)(const SharedPtr\<Region\>\&) | Ersätter den region som representeras av det aktuella objektet med den del av den angivna regionen som inte skär med denna region. |
| [Dispose](./dispose/)() | Frigör alla operativsystemresurser som erhållits av det aktuella objektet. |
| [Equals](./equals/)(const SharedPtr\<Region\>\&, const SharedPtr\<Graphics\>\&) | Bestämmer om den angivna regionen är identisk med den region som representeras av det aktuella objektet på den angivna ritytan. |
| [Exclude](./exclude/)(const RectangleF\&) | Ersätter den region som representeras av det aktuella objektet med resultatet av uteslutning av den region som definieras av den angivna rektangeln från den. |
| [Exclude](./exclude/)(const Rectangle\&) | Ersätter den region som representeras av det aktuella objektet med resultatet av uteslutning av den region som definieras av den angivna rektangeln från den. |
| [Exclude](./exclude/)(const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Ersätter den region som representeras av det aktuella objektet med resultatet av uteslutning av den region som definieras av den angivna banan från den. |
| [Exclude](./exclude/)(const SharedPtr\<Region\>\&) | Ersätter regionen som representeras av det aktuella objektet med resultatet av uteslutning av den angivna regionen från den. |
| [GetBounds](./getbounds/)(const SharedPtr\<Graphics\>\&) const | Hämtar en [RectangleF](../rectanglef/) struktur som representerar en rektangel som avgränsar detta [Region](./) på ritytan för ett [Graphics](../graphics/) objekt. |
| [GetRegionData](./getregiondata/)() const | Returnerar ett RegionData-objekt som innehåller data som definierar regionen som representeras av det aktuella objektet. |
| [GetRegionScans](./getregionscans/)(const SharedPtr\<Drawing2D::Matrix\>\&) const | Returnerar en array av [RectangleF](../rectanglef/) strukturer som approximerar detta [Region](./) efter att den angivna matrisomvandlingen har tillämpats. |
| [Intersect](./intersect/)(const RectangleF\&) | Ersätter regionen som representeras av det aktuella objektet med resultatet av skärning av denna region och en region som definieras av den angivna rektangeln. |
| [Intersect](./intersect/)(const Rectangle\&) | Ersätter regionen som representeras av det aktuella objektet med resultatet av skärning av denna region och en region som definieras av den angivna rektangeln. |
| [Intersect](./intersect/)(const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Ersätter regionen som representeras av det aktuella objektet med resultatet av skärning av denna region och en region som definieras av den angivna banan. |
| [Intersect](./intersect/)(const SharedPtr\<Region\>\&) | Ersätter regionen som representeras av det aktuella objektet med resultatet av skärning av denna region och den angivna regionen. |
| [IsEmpty](./isempty/)(const SharedPtr\<Graphics\>\&) const | Avgör om regionen som representeras av det aktuella objektet har tom inre på den angivna ritytan. |
| [IsInfinite](./isinfinite/)(const SharedPtr\<Graphics\>\&) const | Avgör om regionen som representeras av det aktuella objektet har oändligt inre på den angivna ritytan. |
| [IsVisible](./isvisible/)(const Point\&) const | Avgör om den angivna punkten finns inom regionen som representeras av det aktuella objektet. |
| [IsVisible](./isvisible/)(const PointF\&) const | Avgör om den angivna punkten finns inom regionen som representeras av det aktuella objektet. |
| [IsVisible](./isvisible/)(const Rectangle\&) | Avgör om någon del av den angivna rektangeln finns inom regionen som representeras av det aktuella objektet. |
| [IsVisible](./isvisible/)(const RectangleF\&) | Avgör om någon del av den angivna rektangeln finns inom regionen som representeras av det aktuella objektet. |
| [IsVisible](./isvisible/)(const Point\&, const SharedPtr\<Graphics\>\&) const | Avgör om den angivna punkten finns inom regionen som representeras av det aktuella objektet med hjälp av den angivna Graphics. |
| [IsVisible](./isvisible/)(const PointF\&, const SharedPtr\<Graphics\>\&) const | Avgör om den angivna punkten finns inom regionen som representeras av det aktuella objektet med hjälp av den angivna Graphics. |
| [IsVisible](./isvisible/)(const Rectangle\&, const SharedPtr\<Graphics\>\&) | Avgör om någon del av den angivna rektangeln finns inom regionen som representeras av det aktuella objektet med hjälp av den angivna Graphics. |
| [IsVisible](./isvisible/)(const RectangleF\&, const SharedPtr\<Graphics\>\&) | Avgör om någon del av den angivna rektangeln finns inom regionen som representeras av det aktuella objektet med hjälp av den angivna Graphics. |
| [IsVisible](./isvisible/)(float, float) const | Avgör om den angivna punkten finns inom regionen som representeras av det aktuella objektet. |
| [IsVisible](./isvisible/)(float, float, const SharedPtr\<Graphics\>\&) const | Avgör om den angivna punkten finns inom regionen som representeras av det aktuella objektet med hjälp av den angivna Graphics. |
| [MakeEmpty](./makeempty/)() | Initierar det aktuella objektet med tomt inre. |
| [MakeInfinite](./makeinfinite/)() | Initierar detta regionobjekt med oändligt inre. |
| [Region](./region/)() | Skapar en ny instans av klassen [Region](./). |
| [Region](./region/)(const RectangleF\&) | Skapar en ny instans av klassen [Region](./) som representerar en region definierad av den angivna rektangeln. |
| [Region](./region/)(const Rectangle\&) | Skapar en ny instans av klassen [Region](./) som representerar en region definierad av den angivna rektangeln. |
| [Region](./region/)(const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Skapar en ny instans av klassen [Region](./) som representerar en region definierad av den angivna banan. |
| [Region](./region/)(const SkPath\&) |  |
| [Region](./region/)(const SharedPtr\<Drawing2D::RegionData\>\&) | Skapar en ny instans av klassen [Region](./) som representerar en region definierad av det angivna RegionData-objektet. |
| [Transform](./transform/)(const SharedPtr\<Drawing2D::Matrix\>\&) | Transformerar denna region med den angivna matrisen. |
| [Transform](./transform/)(const SkMatrix\&) | Transformerar denna region med den angivna matrisen. |
| [Translate](./translate/)(int, int) | Flyttar regionens koordinater med den angivna mängden. |
| [Translate](./translate/)(float, float) | Flyttar regionens koordinater med den angivna mängden. |
| [Union](./union/)(const RectangleF\&) | Ersätter regionen som representeras av det aktuella objektet med resultatet av föreningsoperationen av denna region och en region definierad av den angivna rektangeln. |
| [Union](./union/)(const Rectangle\&) | Ersätter regionen som representeras av det aktuella objektet med resultatet av förening av denna region och en region definierad av den angivna rektangeln. |
| [Union](./union/)(const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Ersätter regionen som representeras av det aktuella objektet med resultatet av förening av denna region och en region definierad av den angivna banan. |
| [Union](./union/)(const SharedPtr\<Region\>\&) | Ersätter regionen som representeras av det aktuella objektet med resultatet av förening av denna region och den angivna regionen. |
| [Xor](./xor/)(const RectangleF\&) | Ersätter regionen som representeras av det aktuella objektet med delarna av denna region och den region som definieras av den angivna recangle som inte skär varandra. |
| [Xor](./xor/)(const Rectangle\&) | Ersätter regionen som representeras av det aktuella objektet med delarna av denna region och den region som definieras av den angivna recangle som inte skär varandra. |
| [Xor](./xor/)(const SharedPtr\<Drawing2D::GraphicsPath\>\&) | Ersätter regionen som representeras av det aktuella objektet med delarna av denna region och den region som definieras av den angivna sökvägen som inte skär varandra. |
| [Xor](./xor/)(const SharedPtr\<Region\>\&) | Ersätter regionen som representeras av det aktuella objektet med delarna av denna region och den angivna regionen som inte skär varandra. |
| virtual [~Region](./~region/)() | Destruktor. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
