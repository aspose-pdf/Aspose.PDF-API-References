---
title: "Aspose::Pdf::Annotations::ColorBarAnnotation class"
linktitle: "ColorBarAnnotation"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::ColorBarAnnotation class. Klass som representerar ColorBarAnnotation‑annotation. Egenskapen Color ignoreras, istället används ColorsOfCMYK‑färgen. Vid skapande bestämmer förhållandet mellan bredd och höjd annotationens orientering – horisontell eller vertikal. Därefter kontrolleras att annoteringsrektangeln ligger utanför TrimBox, och om den inte gör det flyttas den till den närmaste platsen utanför TrimBox med hänsyn till annotationens orientering. Det är möjligt att minska bredden (höjden) så att annotationen får plats utanför TrimBox. Om det inte finns utrymme för layouten kan bredd/höjd sättas till noll (i så fall finns annotationen på sidan men visas inte) i C++."
type: docs
weight: 1900
url: /sv/cpp/aspose.pdf.annotations/colorbarannotation/
---
## ColorBarAnnotation class


Klass som representerar [ColorBarAnnotation](./) annotation. Egenskapen [Color](../../aspose.pdf/color/) ignoreras, istället används [ColorsOfCMYK](../colorsofcmyk/) färg. Vid skapande bestämmer förhållandet mellan bredd och höjd annotationens orientering – horisontell eller vertikal. Därefter kontrolleras att annoteringsrektangeln ligger utanför TrimBox, och om den inte gör det flyttas den till den närmaste platsen utanför TrimBox med hänsyn till annotationens orientering. Det är möjligt att minska bredden (höjden) så att annotationen får plats utanför TrimBox. Om det inte finns utrymme för layouten kan bredd/höjd sättas till noll (i så fall finns annotationen på sidan men visas inte).

```cpp
class ColorBarAnnotation : public Aspose::Pdf::Annotations::PrinterMarkAnnotation
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepterar besökarobjekt för att bearbeta anteckningen. |
| [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) override | Uppdatera parametrar och utseende enligt matrisomvandlingen och flytta utanför TrimBox om nödvändigt. |
| [ColorBarAnnotation](./colorbarannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, ColorsOfCMYK) | Skapar ny ColorBar‑annotation på den angivna sidan. |
| [get_AnnotationType](./get_annotationtype/)() override | Hämtar typ av annotation. |
| [get_ColorOfCMYK](./get_colorofcmyk/)() const | Hämtar färg (en av cyan, magenta, gul, svart) som annotationen ritar med. |
| [set_ColorOfCMYK](./set_colorofcmyk/)(ColorsOfCMYK) | Ställer in färg (en av cyan, magenta, gul, svart) som annotationen ritar med. |
## Se även

* Class [PrinterMarkAnnotation](../printermarkannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
