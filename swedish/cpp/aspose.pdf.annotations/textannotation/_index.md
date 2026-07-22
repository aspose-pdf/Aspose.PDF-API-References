---
title: "Aspose::Pdf::Annotations::TextAnnotation klass"
linktitle: "TextAnnotation"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::TextAnnotation klass. Representerar en textanteckning som är en ''klistrig lapp'' fäst vid en punkt i PDF-dokumentet i C++."
type: docs
weight: 11100
url: /sv/cpp/aspose.pdf.annotations/textannotation/
---
## TextAnnotation class


Representerar en textannotation som är en 'klistrig lapp' fäst vid en punkt i PDF-dokumentet.

```cpp
class TextAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepterar besökarobjekt för att bearbeta anteckningen. |
| [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) override | Åsidosätter definitionen i basklassen med en tom kropp. |
| [get_AnnotationType](./get_annotationtype/)() override | Hämtar typ av annotation. |
| [get_Icon](./get_icon/)() | Hämtar en ikon som ska användas för att visa annotationen. |
| [get_Open](./get_open/)() | Hämtar en flagga som specificerar om annotationen initialt ska visas öppen. |
| [set_Icon](./set_icon/)(TextIcon) | Ställer in en ikon som ska användas för att visa annotationen. |
| [set_Open](./set_open/)(bool) | Ställer in en flagga som specificerar om annotationen initialt ska visas öppen. |
| [TextAnnotation](./textannotation/)(const System::SharedPtr\<Document\>\&) | Konstruktor för annotation när den används i Generator. |
| [TextAnnotation](./textannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Skapar ny [Text](../../aspose.pdf.text/) annotation på den angivna sidan. |
## Se även

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
