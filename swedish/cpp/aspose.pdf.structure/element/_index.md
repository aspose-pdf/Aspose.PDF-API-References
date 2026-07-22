---
title: "Aspose::Pdf::Structure::Element klass"
linktitle: "Element"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Structure::Element klass. Klass som representerar baselementet i den logiska strukturen i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.structure/element/
---
## Element class


Klass som representerar baselementet i den logiska strukturen.

```cpp
class Element : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [get_ActualText](./get_actualtext/)() | (Valfritt; PDF 1.4) [Text](../../aspose.pdf.text/) som är en exakt ersättning för strukturelementet och dess barn. Denna ersättningstext (som bör tillämpas på så liten en del av innehållet som möjligt) är användbar när man extraherar dokumentets innehåll för att stödja tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål. |
| virtual [get_Alt](./get_alt/)() | (Valfritt) En alternativ beskrivning av strukturelementet och dess barn i mänskligt läsbar form, vilket är användbart när man extraherar dokumentets innehåll för att stödja tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål. |
| [get_Children](./get_children/)() | Hämtar samling av underordnade element. |
| virtual [get_E](./get_e/)() | (Valfritt; PDF 1.5) Den utökade formen av en förkortning. |
| virtual [get_Lang](./get_lang/)() | (Valfritt; PDF 1.4) Ett språk som specificerar det naturliga språket för all text i strukturelementet, förutom där det åsidosätts av språkspecifikationer för inbäddade strukturelement eller markerat innehåll. |
| [Remove](./remove/)() | Ta bort element. |
| virtual [set_ActualText](./set_actualtext/)(System::String) | (Valfritt; PDF 1.4) [Text](../../aspose.pdf.text/) som är en exakt ersättning för strukturelementet och dess barn. Denna ersättningstext (som bör tillämpas på så liten en del av innehållet som möjligt) är användbar när man extraherar dokumentets innehåll för att stödja tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål. |
| virtual [set_Alt](./set_alt/)(System::String) | (Valfritt) En alternativ beskrivning av strukturelementet och dess barn i mänskligt läsbar form, vilket är användbart när man extraherar dokumentets innehåll för att stödja tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål. |
| virtual [set_E](./set_e/)(System::String) | (Valfritt; PDF 1.5) Den utökade formen av en förkortning. |
| virtual [set_Lang](./set_lang/)(System::String) | (Valfritt; PDF 1.4) Ett språk som specificerar det naturliga språket för all text i strukturelementet, förutom där det åsidosätts av språkspecifikationer för inbäddade strukturelement eller markerat innehåll. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Structure](../)
* Library [Aspose.PDF for C++](../../)
