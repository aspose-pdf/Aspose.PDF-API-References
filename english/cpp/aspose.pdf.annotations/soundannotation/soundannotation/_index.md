---
title: Aspose::Pdf::Annotations::SoundAnnotation::SoundAnnotation constructor
linktitle: SoundAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::SoundAnnotation::SoundAnnotation constructor. Creates new Sound annotation on the specified page in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.annotations/soundannotation/soundannotation/
---
## SoundAnnotation::SoundAnnotation(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::String\&) constructor


Creates new Sound annotation on the specified page.

```cpp
Aspose::Pdf::Annotations::SoundAnnotation::SoundAnnotation(const System::SharedPtr<Aspose::Pdf::Page> &page, const System::SharedPtr<Rectangle> &rect, const System::String &soundFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | const System::SharedPtr\<Aspose::Pdf::Page\>\& | The document's page where annotation should be created. |
| rect | const System::SharedPtr\<Rectangle\>\& | The annotation rectangle, defining the location of the annotation on the page. |
| soundFile | const System::String\& | A sound file defining the sound to be played when the annotation is activated. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Rectangle](../../../aspose.pdf/rectangle/)
* Class [String](../../../system/string/)
* Class [SoundAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## SoundAnnotation::SoundAnnotation(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::String\&, const System::SharedPtr\<SoundSampleData\>\&) constructor


Creates new Sound annotation on the specified page.

```cpp
Aspose::Pdf::Annotations::SoundAnnotation::SoundAnnotation(const System::SharedPtr<Aspose::Pdf::Page> &page, const System::SharedPtr<Rectangle> &rect, const System::String &soundFile, const System::SharedPtr<SoundSampleData> &soundSampleData)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | const System::SharedPtr\<Aspose::Pdf::Page\>\& | The document's page where annotation should be created. |
| rect | const System::SharedPtr\<Rectangle\>\& | The annotation rectangle, defining the location of the annotation on the page. |
| soundFile | const System::String\& | A sound file defining the sound to be played when the annotation is activated. |
| soundSampleData | const System::SharedPtr\<SoundSampleData\>\& | A sound sample data contains extra of sound parameters such as sampling rate, bits per sample and so on. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Rectangle](../../../aspose.pdf/rectangle/)
* Class [String](../../../system/string/)
* Class [SoundSampleData](../../soundsampledata/)
* Class [SoundAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
