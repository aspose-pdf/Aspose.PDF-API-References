---
title: "System::Drawing::Drawing2D::GraphicsPath klass"
linktitle: "GraphicsPath"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Drawing2D::GraphicsPath klass. Representerar en uppsättning av sammanhängande linjer och kurvor. Objekt av denna klass bör endast allokeras med hjälp av System::MakeObject() funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 600
url: /sv/cpp/system.drawing.drawing2d/graphicspath/
---
## GraphicsPath class


Representerar en uppsättning av sammanhängande linjer och kurvor. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class GraphicsPath : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddArc](./addarc/)(float, float, float, float, float, float) | Lägger till den angivna elliptiska bågen till den bana som representeras av det aktuella objektet. |
| [AddArc](./addarc/)(int, int, int, int, float, float) | Lägger till den angivna elliptiska bågen till den bana som representeras av det aktuella objektet. |
| [AddArc](./addarc/)(const RectangleF\&, float, float) | Lägger till den angivna elliptiska bågen till den bana som representeras av det aktuella objektet. |
| [AddArc](./addarc/)(const Rectangle\&, float, float) | Lägger till den angivna elliptiska bågen till den bana som representeras av det aktuella objektet. |
| [AddBezier](./addbezier/)(const Point\&, const Point\&, const Point\&, const Point\&) | Lägger till den angivna kubiska Bezier-kurvan till den bana som representeras av det aktuella objektet. |
| [AddBezier](./addbezier/)(const PointF\&, const PointF\&, const PointF\&, const PointF\&) | Lägger till den angivna kubiska Bezier-kurvan till den bana som representeras av det aktuella objektet. |
| [AddBezier](./addbezier/)(int, int, int, int, int, int, int, int) | Lägger till den angivna kubiska Bezier-kurvan till den bana som representeras av det aktuella objektet. |
| [AddBezier](./addbezier/)(float, float, float, float, float, float, float, float) | Lägger till den angivna kubiska Bezier-kurvan till den bana som representeras av det aktuella objektet. |
| [AddBeziers](./addbeziers/)(const ArrayPtr\<Point\>\&) | Lägger till en sekvens av sammanhängande kubiska Bezier‑kurvor till den aktuella figuren. |
| [AddBeziers](./addbeziers/)(const ArrayPtr\<PointF\>\&) | Lägger till en sekvens av sammanhängande kubiska Bezier‑kurvor till den aktuella figuren. |
| [AddClosedCurve](./addclosedcurve/)(const ArrayPtr\<PointF\>\&, float) | Lägger till den angivna slutna kurvan till den bana som representeras av det aktuella objektet. |
| [AddClosedCurve](./addclosedcurve/)(const ArrayPtr\<Point\>\&, float) | Lägger till den angivna slutna kurvan till den bana som representeras av det aktuella objektet. |
| [AddCurve](./addcurve/)(const ArrayPtr\<PointF\>\&, float) | Lägger till den angivna kurvan till den bana som representeras av det aktuella objektet. |
| [AddCurve](./addcurve/)(const ArrayPtr\<Point\>\&, float) | Lägger till den angivna kurvan till den bana som representeras av det aktuella objektet. |
| [AddCurve](./addcurve/)(const ArrayPtr\<PointF\>\&, int, int, float) | Lägger till den angivna kurvan till den bana som representeras av det aktuella objektet. |
| [AddCurve](./addcurve/)(const ArrayPtr\<Point\>\&, int, int, float) | Lägger till den angivna kurvan till den bana som representeras av det aktuella objektet. |
| [AddEllipse](./addellipse/)(float, float, float, float) | Lägger till den angivna ellipsen till den bana som representeras av det aktuella objektet. |
| [AddEllipse](./addellipse/)(int, int, int, int) | Lägger till den angivna ellipsen till den bana som representeras av det aktuella objektet. |
| [AddEllipse](./addellipse/)(const RectangleF\&) | Lägger till den angivna ellipsen till den bana som representeras av det aktuella objektet. |
| [AddEllipse](./addellipse/)(const Rectangle\&) | Lägger till den angivna ellipsen till den bana som representeras av det aktuella objektet. |
| [AddLine](./addline/)(const Point\&, const Point\&) | Lägger till den angivna linjen till den bana som representeras av det aktuella objektet. |
| [AddLine](./addline/)(const PointF\&, const PointF\&) | Lägger till den angivna linjen till den bana som representeras av det aktuella objektet. |
| [AddLine](./addline/)(int, int, int, int) | Lägger till den angivna linjen till den bana som representeras av det aktuella objektet. |
| [AddLine](./addline/)(float, float, float, float) | Lägger till den angivna linjen till den bana som representeras av det aktuella objektet. |
| [AddLines](./addlines/)(const ArrayPtr\<PointF\>\&) | Lägger till den angivna serien av sammanhängande linjesegment till den bana som representeras av det aktuella objektet. |
| [AddLines](./addlines/)(const ArrayPtr\<Point\>\&) | Lägger till den angivna serien av sammanhängande linjesegment till den bana som representeras av det aktuella objektet. |
| [AddPath](./addpath/)(const SharedPtr\<GraphicsPath\>\&, bool) | Lägger till den angivna banan till den bana som representeras av det aktuella objektet. |
| [AddPie](./addpie/)(float, float, float, float, float, float) | Lägger till den angivna konturen av pajformen till den bana som representeras av det aktuella objektet. |
| [AddPie](./addpie/)(int, int, int, int, float, float) | Lägger till den angivna konturen av pajformen till den bana som representeras av det aktuella objektet. |
| [AddPie](./addpie/)(const Rectangle\&, float, float) | Lägger till den angivna konturen av pajformen till den bana som representeras av det aktuella objektet. |
| [AddPolygon](./addpolygon/)(const ArrayPtr\<PointF\>\&) | Lägger till den angivna polygonen till den bana som representeras av det aktuella objektet. |
| [AddPolygon](./addpolygon/)(const ArrayPtr\<Point\>\&) | Lägger till den angivna polygonen till den bana som representeras av det aktuella objektet. |
| [AddRectangle](./addrectangle/)(const Rectangle\&) | Lägger till den angivna rektangeln till den bana som representeras av det aktuella objektet. |
| [AddRectangle](./addrectangle/)(const RectangleF\&) | Lägger till den angivna rektangeln till den bana som representeras av det aktuella objektet. |
| [AddRectangles](./addrectangles/)(const ArrayPtr\<Rectangle\>\&) | Lägger till den angivna serien av rektanglar till den bana som representeras av det aktuella objektet. |
| [AddRectangles](./addrectangles/)(const ArrayPtr\<RectangleF\>\&) | Lägger till den angivna serien av rektanglar till den bana som representeras av det aktuella objektet. |
| [AddString](./addstring/)(const String\&, const SharedPtr\<FontFamily\>\&, int, float, Point, const SharedPtr\<StringFormat\>\&) | Lägger till en textsträng till den bana som representeras av det aktuella objektet. |
| [AddString](./addstring/)(const String\&, const SharedPtr\<FontFamily\>\&, int, float, PointF, const SharedPtr\<StringFormat\>\&) | Lägger till en textsträng till den bana som representeras av det aktuella objektet. |
| [AddString](./addstring/)(const String\&, const SharedPtr\<FontFamily\>\&, int, float, Rectangle, const SharedPtr\<StringFormat\>\&) | Lägger till en textsträng till den bana som representeras av det aktuella objektet. |
| [AddString](./addstring/)(const String\&, const SharedPtr\<FontFamily\>\&, int, float, RectangleF, const SharedPtr\<StringFormat\>\&) | Lägger till en textsträng till den bana som representeras av det aktuella objektet. |
| virtual [Clone](./clone/)() | Skapar en kopia av det aktuella objektet. |
| [CloseAllFigures](./closeallfigures/)() | Stänger alla öppna figurer och startar en ny. |
| [CloseFigure](./closefigure/)() | Stänger den aktuella figuren och startar en ny. |
| [Dispose](./dispose/)() | Frigör alla operativsystemresurser som erhållits av det aktuella objektet. |
| [Flatten](./flatten/)() | Plattar ut varje kurva i banan genom att konvertera dem till en serie av sammanhängande linjer. Platthetsvärdet 0.25 används. |
| [Flatten](./flatten/)(const MatrixPtr\&) | Plattar ut varje kurva i banan genom att konvertera dem till en serie av sammanhängande linjer. Platthetsvärdet 0.25 används. |
| [Flatten](./flatten/)(const MatrixPtr\&, float) | Plattar ut varje kurva i banan genom att konvertera dem till en serie av sammanhängande linjer. |
| [get_FillMode](./get_fillmode/)() | Returnerar fyllningsläget för det aktuella objektet. |
| [get_PathData](./get_pathdata/)() | Returnerar ett [PathData](../pathdata/)‑objekt som innehåller de punkter som utgör en bana som representeras av det aktuella objektet och deras typer. |
| [get_PathPoints](./get_pathpoints/)() const | Returnerar en array som innehåller punkter som utgör en bana som representeras av det aktuella objektet. |
| [get_PathTypes](./get_pathtypes/)() const | Returnerar en array som innehåller värden som indikerar typerna för de punkter som utgör en bana som representeras av det aktuella objektet. |
| [get_PointCount](./get_pointcount/)() const | Returnerar antalet punkter i den bana som representeras av det aktuella objektet. |
| [GetBounds](./getbounds/)(const MatrixPtr\&, const SharedPtr\<Pen\>\&) const | Returnerar ett [RectangleF](../../system.drawing/rectanglef/)‑objekt som representerar en rektangel som avgränsar banan som representeras av det aktuella objektet när den transformeras med den angivna matrisen. |
| [GetFigureFlags](./getfigureflags/)() | Returnerar ett värde som är en bitvis kombination av Detail::FigureType‑värden som indikerar vilka typer av figurer som finns i den bana som representeras av det aktuella objektet. |
| [GetLastPoint](./getlastpoint/)() const | Returnerar ett [PointF](../../system.drawing/pointf/)‑objekt som representerar den sista punkten i banan. |
| [GraphicsPath](./graphicspath/)(FillMode) | Skapar en ny instans av klassen [GraphicsPath](./) med det angivna fyllningsläget. |
| [GraphicsPath](./graphicspath/)(const ArrayPtr\<Point\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) | Skapar en ny instans av [GraphicsPath](./)-objektet som representerar den angivna vägen. |
| [GraphicsPath](./graphicspath/)(const ArrayPtr\<PointF\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) | Skapar en ny instans av [GraphicsPath](./)-objektet som representerar den angivna vägen. |
| [GraphicsPath](./graphicspath/)(const SkPath\&) |  |
| [IsOutlineVisible](./isoutlinevisible/)(const PointF\&, const SharedPtr\<Pen\>\&) | Indikerar om den angivna punkten finns inom (under) konturen av denna [GraphicsPath](./) när den ritas med den angivna [Pen](../../system.drawing/pen/). INTE IMPLEMENTERAD. |
| [IsVisible](./isvisible/)(const PointF\&) | Bestämmer om den angivna punkten finns inom vägen som representeras av det aktuella objektet. |
| [IsVisible](./isvisible/)(float, float) | Bestämmer om den angivna punkten finns inom vägen som representeras av det aktuella objektet. |
| [Reset](./reset/)() | Tömmer vägen genom att ta bort alla punkter från den. |
| [Reverse](./reverse/)() | Vänder ordningen på punkterna i PathPoints‑arrayen för denna [GraphicsPath](./). |
| [set_FillMode](./set_fillmode/)(FillMode) | Ställer in fyllningsläget för det aktuella objektet. |
| [SetMarkers](./setmarkers/)() | INTE IMPLEMENTERAD. |
| [StartFigure](./startfigure/)() | Startar en ny figur. |
| [Transform](./transform/)(const MatrixPtr\&) | Transformerar vägen som representeras av det aktuella objektet genom att tillämpa den angivna transformationsmatrisen på den. |
| [Transform](./transform/)(const SkMatrix\&) |  |
| [Widen](./widen/)(const SharedPtr\<Pen\>\&) | Ersätter denna väg med en kontur runt den ursprungliga vägen. |
| [~GraphicsPath](./~graphicspath/)() | Destruktor. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
