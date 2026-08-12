---
title: "Aspose::Pdf::Annotations::InkAnnotation-klass"
linktitle: "InkAnnotation"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::InkAnnotation-klass. Representerar en frihandsskiss \\\"scribble\\\" bestående av en eller flera separata banor i C++."
type: docs
weight: 5200
url: /sv/cpp/aspose.pdf.annotations/inkannotation/
---
## InkAnnotation class


Representerar en frihands‑\"klotter\" bestående av en eller flera separata banor.

```cpp
class InkAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepterar besökarobjekt för att bearbeta anteckningen. |
| [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) override | Uppdaterar punkterna i InkList enligt matrisomvandlingen. |
| [get_AnnotationType](./get_annotationtype/)() override | Hämtar typ av annotation. |
| [get_CapStyle](./get_capstyle/)() | Stil för bläckanteckningslinjeändar. |
| [get_InkList](./get_inklist/)() | Hämtar en lista med gester som är oberoende linjer som representeras av [Point](../../aspose.pdf/point/)[]-arrayer. |
| [InkAnnotation](./inkannotation/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<System::Collections::Generic::IList\<System::ArrayPtr\<System::SharedPtr\<Point\>\>\>\>\&) | Konstruktor för Ink-annotation för Generator. |
| [InkAnnotation](./inkannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::SharedPtr\<System::Collections::Generic::IList\<System::ArrayPtr\<System::SharedPtr\<Point\>\>\>\>\&) | Skapar en ny Ink-annotation på den angivna sidan. |
| [set_CapStyle](./set_capstyle/)(Aspose::Pdf::Annotations::CapStyle) | Stil för bläckanteckningslinjeändar. |
| [set_InkList](./set_inklist/)(const System::SharedPtr\<System::Collections::Generic::IList\<System::ArrayPtr\<System::SharedPtr\<Point\>\>\>\>\&) | Ställer in en lista med gester som är oberoende linjer som representeras av [Point](../../aspose.pdf/point/)[]-arrayer. |
## Se även

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
