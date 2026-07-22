---
title: "Aspose::Pdf::Annotations::ScreenAnnotation klass"
linktitle: "ScreenAnnotation"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::ScreenAnnotation klass. En skärmanteckning som specificerar ett område på en sida där mediaklipp kan spelas upp i C++."
type: docs
weight: 9800
url: /sv/cpp/aspose.pdf.annotations/screenannotation/
---
## ScreenAnnotation class


En skärmanteckning som specificerar ett område på en sida där mediaklipp kan spelas upp.

```cpp
class ScreenAnnotation : public Aspose::Pdf::Annotations::Annotation,
                         public Aspose::Pdf::Annotations::Annotation::ITitledAnnotation
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepterar besökarobjekt för att bearbeta anteckningen. |
| [get_Action](./get_action/)() | Hämtar en åtgärd som ska utföras när annoteringen aktiveras. |
| [get_AnnotationType](./get_annotationtype/)() override | Hämtar typ av annotation. |
| [get_Title](./get_title/)() override | Hämtar titeln på skärmannoteringen. |
| [ScreenAnnotation](./screenannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::String\&) | Skapar en ny skärmannotering på den angivna sidan. |
| [set_Title](./set_title/)(System::String) override | Ställer in titeln på skärmannoteringen. |
## Se även

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
