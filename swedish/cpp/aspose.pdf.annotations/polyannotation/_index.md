---
title: "Aspose::Pdf::Annotations::PolyAnnotation klass"
linktitle: "PolyAnnotation"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::PolyAnnotation klass. Abstrakt basklass för poly‑annotationer i C++."
type: docs
weight: 8400
url: /sv/cpp/aspose.pdf.annotations/polyannotation/
---
## PolyAnnotation class


Abstrakt basklass för poly-anteckningar.

```cpp
class PolyAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) override | Uppdaterar punkterna i Vertices enligt matrisomvandlingen. |
| [get_EndingStyle](./get_endingstyle/)() | Hämtar stil för andra radslutet. |
| [get_Intent](./get_intent/)() | Hämtar avsikten för polygon‑ eller polylinje‑annoteringen. |
| [get_InteriorColor](./get_interiorcolor/)() | Hämtar den inre färgen som används för att fylla annoteringens linjeändar. |
| [get_Measure](./get_measure/)() | [Measure](../measure/) enheter som specificeras för denna annotering. |
| [get_StartingStyle](./get_startingstyle/)() | Hämtar stilen för den första linjeändan. |
| [get_Vertices](./get_vertices/)() | Hämtar en array av punkter som representerar de horisontella och vertikala koordinaterna för varje hörn. |
| [set_EndingStyle](./set_endingstyle/)(LineEnding) | Ställer in stilen för den andra linjeändan. |
| [set_Intent](./set_intent/)(PolyIntent) | Ställer in avsikten för polygon‑ eller polylinje‑annoteringen. |
| [set_InteriorColor](./set_interiorcolor/)(const System::SharedPtr\<Aspose::Pdf::Color\>\&) | Ställer in den inre färgen som används för att fylla annoteringens linjeändar. |
| [set_Measure](./set_measure/)(const System::SharedPtr\<Aspose::Pdf::Annotations::Measure\>\&) | [Measure](../measure/) enheter som specificeras för denna annotering. |
| [set_StartingStyle](./set_startingstyle/)(LineEnding) | Ställer in stilen för den första linjeändan. |
| [set_Vertices](./set_vertices/)(const System::ArrayPtr\<System::SharedPtr\<Point\>\>\&) | Ställer in en array av punkter som representerar de horisontella och vertikala koordinaterna för varje hörn. |
## Se även

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
