---
title: "Aspose::Pdf::Annotations::LinkAnnotation klass"
linktitle: "LinkAnnotation"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::LinkAnnotation klass. Representerar antingen en hypertextlänk till en destination någon annanstans i dokumentet eller en åtgärd som ska utföras i C++."
type: docs
weight: 6000
url: /sv/cpp/aspose.pdf.annotations/linkannotation/
---
## LinkAnnotation class


Representerar antingen en hypertextlänk till en destination någon annanstans i dokumentet eller en åtgärd som ska utföras.

```cpp
class LinkAnnotation : public Aspose::Pdf::Annotations::Annotation
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepterar besökarobjekt för att bearbeta anteckningen. |
| [get_Action](./get_action/)() | En åtgärd som ska utföras när länkanoteringen aktiveras. |
| [get_AnnotationType](./get_annotationtype/)() override | Hämtar typ av annotation. |
| [get_Destination](./get_destination/)() | En destination som ska visas när annoteringen aktiveras. |
| [get_Highlighting](./get_highlighting/)() | Den visuella effekten som ska användas när musknappen trycks ned eller hålls ned inne i dess aktiva område. |
| [LinkAnnotation](./linkannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Skapar en ny Link-annotering på den angivna sidan. |
| [set_Action](./set_action/)(const System::SharedPtr\<PdfAction\>\&) | En åtgärd som ska utföras när länkanoteringen aktiveras. |
| [set_Destination](./set_destination/)(const System::SharedPtr\<IAppointment\>\&) | En destination som ska visas när annoteringen aktiveras. |
| [set_Highlighting](./set_highlighting/)(HighlightingMode) | Den visuella effekten som ska användas när musknappen trycks ned eller hålls ned inne i dess aktiva område. |
## Se även

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
