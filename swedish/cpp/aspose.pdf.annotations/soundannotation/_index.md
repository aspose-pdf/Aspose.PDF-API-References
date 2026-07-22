---
title: "Aspose::Pdf::Annotations::SoundAnnotation klass"
linktitle: "SoundAnnotation"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::SoundAnnotation-klass. Representerar en ljudanteckning som innehåller ljud inspelat från datorns mikrofon eller importerat från en fil i C++."
type: docs
weight: 10000
url: /sv/cpp/aspose.pdf.annotations/soundannotation/
---
## SoundAnnotation class


Representerar en ljudanteckning som innehåller ljud inspelat från datorns mikrofon eller importerat från en fil.

```cpp
class SoundAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepterar besökarobjekt för att bearbeta anteckningen. |
| [get_AnnotationType](./get_annotationtype/)() override | Hämtar typ av annotation. |
| [get_Icon](./get_icon/)() | Hämtar en ikon som ska användas för att visa annotationen. |
| [get_SoundData](./get_sounddata/)() | Hämtar ett ljudobjekt som definierar ljudet som ska spelas när anteckningen aktiveras. |
| [set_Icon](./set_icon/)(SoundIcon) | Ställer in en ikon som ska användas för att visa annotationen. |
| [SoundAnnotation](./soundannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::String\&) | Skapar en ny ljudanteckning på den angivna sidan. |
| [SoundAnnotation](./soundannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::String\&, const System::SharedPtr\<SoundSampleData\>\&) | Skapar en ny ljudanteckning på den angivna sidan. |
## Se även

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
