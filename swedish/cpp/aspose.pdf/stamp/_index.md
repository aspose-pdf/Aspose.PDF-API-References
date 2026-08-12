---
title: "Aspose::Pdf::Stamp-klass"
linktitle: "Stamp"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Stamp-klass. En abstrakt klass för olika typer av stämplar som finns som avstamningar i C++."
type: docs
weight: 17400
url: /sv/cpp/aspose.pdf/stamp/
---
## Stamp class


En abstrakt klass för olika typer av stämplar som kommer som underklasser.

```cpp
class Stamp : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Background](./get_background/)() const | Ställer in eller hämtar ett booleskt värde som indikerar att innehållet är stämplat som bakgrund. Om värdet är true placeras stämpelns innehåll längst ner. Som standard är värdet false, och stämpelns innehåll placeras högst upp. |
| [get_BottomMargin](./get_bottommargin/)() const | Hämtar stampens nedre marginal. |
| virtual [get_Height](./get_height/)() | Önskad höjd på stampen på sidan. |
| [get_HorizontalAlignment](./get_horizontalalignment/)() const | Hämtar horisontell justering av stampen på sidan. |
| [get_LeftMargin](./get_leftmargin/)() const | Hämtar stampens vänstra marginal. |
| [get_Opacity](./get_opacity/)() const | Hämtar ett värde som indikerar stampens opacitet. Värdet är från 0.0 till 1.0. Som standard är värdet 1.0. |
| [get_OutlineOpacity](./get_outlineopacity/)() const | Hämtar ett värde som indikerar stampens konturopacitet. Värdet är från 0.0 till 1.0. Som standard är värdet 1.0. |
| [get_OutlineWidth](./get_outlinewidth/)() const | Hämtar ett värde för stampens konturbredd. Som standard är värdet 1.0. |
| [get_RightMargin](./get_rightmargin/)() const | Hämtar högermarginalen för stämpeln. |
| [get_Rotate](./get_rotate/)() | Ställer in eller hämtar rotationen av stämpelns innehåll enligt [Rotation](../rotation/) värden. [Note](../note/). Denna egenskap är för att ange vinklar som är multiplar av 90 grader (0, 90, 180, 270 grader). För att ange en godtycklig vinkel, använd egenskapen RotateAngle. Om vinkeln som anges av ArbitraryAngle inte är en multipel av 90, returnerar Rotate‑egenskapen [Rotation.None](../rotation/). |
| [get_RotateAngle](./get_rotateangle/)() | Hämtar rotationsvinkeln för stämpeln i grader. Denna egenskap tillåter att ange en godtycklig rotationsvinkel. |
| [get_TopMargin](./get_topmargin/)() const | Hämtar toppmarginalen för stämpeln. |
| [get_VerticalAlignment](./get_verticalalignment/)() const | Hämtar vertikal justering av stämpeln på sidan. |
| virtual [get_Width](./get_width/)() | Önskad bredd på stämpeln på sidan. |
| virtual [get_XIndent](./get_xindent/)() | Horisontell stämpelkoordinat, räknat från vänster. |
| virtual [get_YIndent](./get_yindent/)() | Vertikal stämpelkoordinat, räknat från botten. |
| [get_Zoom](./get_zoom/)() const | Zoomfaktor för stämpeln. Tillåter att skala stämpeln. Observera att paret av egenskaper ZoomX och ZoomY tillåter att ange zoomfaktor för varje axel separat. Inställning av denna egenskap ändrar både ZoomX- och ZoomY-egenskaperna. Om ZoomX och ZoomY är olika, returnerar Zoom‑egenskapen ZoomX‑värdet. |
| [get_ZoomX](./get_zoomx/)() const | Horisontell zoomfaktor för stämpeln. Tillåter att skala stämpeln horisontellt. |
| [get_ZoomY](./get_zoomy/)() const | Vertikal zoomfaktor för stämpeln. Tillåter att skala stämpeln vertikalt. |
| [getStampId](./getstampid/)() | Returnerar stämpelns ID. |
| virtual [Put](./put/)(System::SharedPtr\<Page\>) | Lägger till en stämpel på sidan. |
| [set_Background](./set_background/)(bool) | Ställer in eller hämtar ett booleskt värde som indikerar att innehållet är stämplat som bakgrund. Om värdet är true placeras stämpelns innehåll längst ner. Som standard är värdet false, och stämpelns innehåll placeras högst upp. |
| [set_BottomMargin](./set_bottommargin/)(double) | Ställer in bottenmarginalen för stämpeln. |
| virtual [set_Height](./set_height/)(double) | Önskad höjd på stampen på sidan. |
| [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Ställer in horisontell justering av stämpeln på sidan. |
| [set_LeftMargin](./set_leftmargin/)(double) | Ställer in vänstermarginalen för stämpeln. |
| [set_Opacity](./set_opacity/)(double) | Ställer in ett värde för att ange stämpelns opacitet. Värdet är mellan 0.0 och 1.0. Standardvärdet är 1.0. |
| [set_OutlineOpacity](./set_outlineopacity/)(double) | Ställer in ett värde för att ange stämpelns konturopacitet. Värdet är mellan 0.0 och 1.0. Standardvärdet är 1.0. |
| [set_OutlineWidth](./set_outlinewidth/)(double) | Ställer in ett värde för stämpelns konturbredd. Standardvärdet är 1.0. |
| [set_RightMargin](./set_rightmargin/)(double) | Ställer in högermarginalen för stämpeln. |
| [set_Rotate](./set_rotate/)(Rotation) | Ställer in eller hämtar rotationen av stämpelns innehåll enligt [Rotation](../rotation/) värden. [Note](../note/). Denna egenskap är för att ange vinklar som är multiplar av 90 grader (0, 90, 180, 270 grader). För att ange en godtycklig vinkel, använd egenskapen RotateAngle. Om vinkeln som anges av ArbitraryAngle inte är en multipel av 90, returnerar Rotate‑egenskapen [Rotation.None](../rotation/). |
| [set_RotateAngle](./set_rotateangle/)(double) | Ställer in rotationsvinkeln för stämpeln i grader. Denna egenskap tillåter att ange en godtycklig rotationsvinkel. |
| [set_TopMargin](./set_topmargin/)(double) | Ställer in toppmarginalen för stämpeln. |
| [set_VerticalAlignment](./set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Ställer in vertikal justering av stämpeln på sidan. |
| virtual [set_Width](./set_width/)(double) | Önskad bredd på stämpeln på sidan. |
| virtual [set_XIndent](./set_xindent/)(double) | Horisontell stämpelkoordinat, räknat från vänster. |
| virtual [set_YIndent](./set_yindent/)(double) | Vertikal stämpelkoordinat, räknat från botten. |
| [set_Zoom](./set_zoom/)(double) | Zoomfaktor för stämpeln. Tillåter att skala stämpeln. Observera att paret av egenskaper ZoomX och ZoomY tillåter att ange zoomfaktor för varje axel separat. Inställning av denna egenskap ändrar både ZoomX- och ZoomY-egenskaperna. Om ZoomX och ZoomY är olika, returnerar Zoom‑egenskapen ZoomX‑värdet. |
| [set_ZoomX](./set_zoomx/)(double) | Horisontell zoomfaktor för stämpeln. Tillåter att skala stämpeln horisontellt. |
| [set_ZoomY](./set_zoomy/)(double) | Vertikal zoomfaktor för stämpeln. Tillåter att skala stämpeln vertikalt. |
| [setStampId](./setstampid/)(int32_t) | Ställer in stämpelns [Id](../id/). |
| [Stamp](./stamp/)() |  |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
