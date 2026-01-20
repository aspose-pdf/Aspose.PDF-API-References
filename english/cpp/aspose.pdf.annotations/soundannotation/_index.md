---
title: Aspose::Pdf::Annotations::SoundAnnotation class
linktitle: SoundAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::SoundAnnotation class. Represents a sound annotation that contains sound recorded from the computer''s microphone or imported from a file in C++.'
type: docs
weight: 10000
url: /cpp/aspose.pdf.annotations/soundannotation/
---
## SoundAnnotation class


Represents a sound annotation that contains sound recorded from the computer's microphone or imported from a file.

```cpp
class SoundAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepts visitor object to process the annotation. |
| [get_AnnotationType](./get_annotationtype/)() override | Gets type of annotation. |
| [get_Icon](./get_icon/)() | Gets an icon to be used in displaying the annotation. |
| [get_SoundData](./get_sounddata/)() | Gets a sound object defining the sound to be played when the annotation is activated. |
| [set_Icon](./set_icon/)(SoundIcon) | Sets an icon to be used in displaying the annotation. |
| [SoundAnnotation](./soundannotation/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>, System::String) | Creates new Sound annotation on the specified page. |
| [SoundAnnotation](./soundannotation/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>, System::String, System::SharedPtr\<SoundSampleData\>) | Creates new Sound annotation on the specified page. |
## See Also

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
