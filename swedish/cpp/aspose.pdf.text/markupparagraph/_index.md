---
title: "Aspose::Pdf::Text::MarkupParagraph class"
linktitle: "MarkupParagraph"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::MarkupParagraph class. Representerar ett stycke i C++."
type: docs
weight: 2100
url: /sv/cpp/aspose.pdf.text/markupparagraph/
---
## MarkupParagraph class


Representerar ett stycke.

```cpp
class MarkupParagraph : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_ContinuationPageNumbers](./get_continuationpagenumbers/)() const | Lista med sidnummer där stycket fortsätts. Den kommer att matcha sidan där stycket startade om det fortsätter i nästa kolumn på samma sida. |
| [get_Fragments](./get_fragments/)() | [Collection](../../aspose.pdf/collection/) av icke tomma [TextFragment](../textfragment/) objekt i stycket. |
| [get_Lines](./get_lines/)() const | Rader i stycket. Varje rad representeras av en lista med textfragment. |
| [get_Points](./get_points/)() | Punkter i polygon som beskriver stycket. Startpunkten är det nedre vänstra hörnet av stycket. Och följande punkter är i moturs sekvens. |
| [get_SecondaryPoints](./get_secondarypoints/)() const | Punkter i sekundär polygon som beskriver styckets fortsättning. Den kommer inte att vara null om stycket fortsätts i nästa kolumn eller sida. Startpunkten är det nedre vänstra hörnet av stycket. Och följande punkter är i moturs sekvens. |
| [get_Text](./get_text/)() | Hämtar styckets text. |
| [set_Text](./set_text/)(const System::String\&) | Ställer in styckets text. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
