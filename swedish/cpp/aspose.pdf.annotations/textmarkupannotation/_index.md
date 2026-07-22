---
title: "Aspose::Pdf::Annotations::TextMarkupAnnotation class"
linktitle: "TextMarkupAnnotation"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::TextMarkupAnnotation class. Abstrakt basklass för text markup-annotationer i C++."
type: docs
weight: 11300
url: /sv/cpp/aspose.pdf.annotations/textmarkupannotation/
---
## TextMarkupAnnotation class


Abstrakt basklass för textmarkeringsannotationer.

```cpp
class TextMarkupAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) override | Uppdaterar QuadPoints enligt matrisomvandlingen. |
| [get_QuadPoints](./get_quadpoints/)() | Hämtar en array av punkter som specificerar koordinaterna för n fyrhörningar. Varje fyrhörning omfattar ett ord eller en grupp av sammanhängande ord i den text som ligger under annotationen. |
| [GetMarkedText](./getmarkedtext/)() | Hämtar text under markup-annotation som sträng. |
| [GetMarkedTextFragments](./getmarkedtextfragments/)() | Hämtar text under markup-annotation som [TextFragmentCollection](../). |
| [set_QuadPoints](./set_quadpoints/)(const System::ArrayPtr\<System::SharedPtr\<Point\>\>\&) | Ställer in en array av punkter som specificerar koordinaterna för n fyrhörningar. Varje fyrhörning omfattar ett ord eller en grupp av sammanhängande ord i den text som ligger under annotationen. |
## Se även

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
