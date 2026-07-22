---
title: "Aspose::Pdf::Rectangle klass"
linktitle: "Rectangle"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Rectangle klass. Klassen representerar en rektangel i C++."
type: docs
weight: 16300
url: /sv/cpp/aspose.pdf/rectangle/
---
## Rectangle class


Klass representerar rektangel.

```cpp
class Rectangle : public System::ICloneable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Center](./center/)() | Returnerar koordinaterna för rektangelns centrum. |
| [Clone](./clone/)() override | Klonar objektet [Rectangle](./). |
| [Contains](./contains/)(const System::SharedPtr\<Point\>\&, bool) | Bestämmer om en given punkt ligger inom rektangeln. |
| [ContainsLine](./containsline/)(double, double, double, double) | Bestämmer om rektangeln innehåller en linje som representeras av två punkter. |
| [ContainsPoint](./containspoint/)(double, double) | Bestämmer om den givna punkten finns inom rektangeln. |
| [Equals](./equals/)(const System::SharedPtr\<Rectangle\>\&) | Kontrollera om rektanglar är lika, d.v.s. har samma position och storlek. |
| static [FromRect](./fromrect/)(System::Drawing::Rectangle) | Initierar en ny rektangel från given instans av [System.Drawing.Rectangle](../../system.drawing/rectangle/). |
| static [FromRect](./fromrect/)(System::Drawing::RectangleF) | Initierar en ny rektangel från given instans av [System.Drawing.Rectangle](../../system.drawing/rectangle/). |
| static [get_Empty](./get_empty/)() | Tom rektangel. |
| [get_Height](./get_height/)() | Höjd på rektangel. |
| [get_IsEmpty](./get_isempty/)() const | Kontrollerar om rektangeln är tom. |
| [get_IsPoint](./get_ispoint/)() | Kontrollerar om rektangeln är en punkt, d.v.s. LLX är lika med URX och LLY är lika med URY. |
| [get_IsTrivial](./get_istrivial/)() | Kontrollerar om rektangeln är trivial, d.v.s. har noll storlek och position. |
| [get_LLX](./get_llx/)() const | X-koordinat för nedre vänstra hörnet. |
| [get_LLY](./get_lly/)() const | Y-koordinat för nedre vänstra hörnet. |
| static [get_Trivial](./get_trivial/)() | Initierar en trivial rektangel, d.v.s. en rektangel med noll position och storlek. |
| [get_URX](./get_urx/)() const | X-koordinat för övre högra hörnet. |
| [get_URY](./get_ury/)() const | Y-koordinat för övre högra hörnet. |
| [get_Width](./get_width/)() | Bredd på rektangeln. |
| [Intersect](./intersect/)(const System::SharedPtr\<Rectangle\>\&) | Skär två rektanglar. |
| [IsIntersect](./isintersect/)(const System::SharedPtr\<Rectangle\>\&) | Bestämmer om denna rektangel skär med en annan rektangel. |
| [Join](./join/)(const System::SharedPtr\<Rectangle\>\&) | Förenar rektanglar. |
| [MoveBy](./moveby/)(double, double) | Flyttar rektangeln med de angivna delta-värdena. |
| [NearEquals](./nearequals/)(const System::SharedPtr\<Rectangle\>\&, double) | Kontrollerar om rektanglar är nästan lika, d.v.s. har nästan samma (upp till delta) position och storlek. |
| static [Parse](./parse/)(const System::String\&) | Försök att tolka strängen och extrahera rektangelkomponenterna llx, lly, urx, ury från den. |
| [Rectangle](./rectangle/)(double, double, double, double, bool) | Konstruktor för [Rectangle](./). |
| [Rotate](./rotate/)(Rotation) | Rotera rektangeln med den angivna vinkeln. |
| [Rotate](./rotate/)(int32_t) | Rotera rektangeln med den angivna vinkeln. |
| [set_LLX](./set_llx/)(double) | X-koordinat för nedre vänstra hörnet. |
| [set_LLY](./set_lly/)(double) | Y-koordinat för nedre vänstra hörnet. |
| [set_URX](./set_urx/)(double) | X-koordinat för övre högra hörnet. |
| [set_URY](./set_ury/)(double) | Y-koordinat för övre högra hörnet. |
| [ToPoints](./topoints/)() | Konverterar rektangeln till en array av punkter ("QuadPoints"). |
| [ToRect](./torect/)() | Konverterar rektangeln till en instans av [System.Drawing.Rectangle](../../system.drawing/rectangle/). Flyttalspositioner och storlek trunkeras. |
| [ToString](./tostring/)() const override | Hämtar rektangelns strängrepresentation. |
## Se även

* Class [ICloneable](../../system/icloneable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
