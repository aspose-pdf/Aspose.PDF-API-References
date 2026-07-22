---
title: "Aspose::Pdf::Annotations::SoundAnnotation::SoundAnnotation konstruktor"
linktitle: "SoundAnnotation"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::SoundAnnotation::SoundAnnotation konstruktor. Skapar en ny ljudannotation på den angivna sidan i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.annotations/soundannotation/soundannotation/
---
## SoundAnnotation::SoundAnnotation(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::String\&) constructor


Skapar en ny ljudanteckning på den angivna sidan.

```cpp
Aspose::Pdf::Annotations::SoundAnnotation::SoundAnnotation(const System::SharedPtr<Aspose::Pdf::Page> &page, const System::SharedPtr<Rectangle> &rect, const System::String &soundFile)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | const System::SharedPtr\<Aspose::Pdf::Page\>\& | Dokumentets sida där annotationen ska skapas. |
| rect | const System::SharedPtr\<Rectangle\>\& | Annotationsrektangeln som definierar annotationens placering på sidan. |
| soundFile | const System::String\& | En ljudfil som definierar ljudet som ska spelas när annotationen aktiveras. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Rectangle](../../../aspose.pdf/rectangle/)
* Class [String](../../../system/string/)
* Class [SoundAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## SoundAnnotation::SoundAnnotation(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::String\&, const System::SharedPtr\<SoundSampleData\>\&) constructor


Skapar en ny ljudanteckning på den angivna sidan.

```cpp
Aspose::Pdf::Annotations::SoundAnnotation::SoundAnnotation(const System::SharedPtr<Aspose::Pdf::Page> &page, const System::SharedPtr<Rectangle> &rect, const System::String &soundFile, const System::SharedPtr<SoundSampleData> &soundSampleData)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | const System::SharedPtr\<Aspose::Pdf::Page\>\& | Dokumentets sida där annotationen ska skapas. |
| rect | const System::SharedPtr\<Rectangle\>\& | Annotationsrektangeln som definierar annotationens placering på sidan. |
| soundFile | const System::String\& | En ljudfil som definierar ljudet som ska spelas när annotationen aktiveras. |
| soundSampleData | const System::SharedPtr\<SoundSampleData\>\& | Ett ljudsamplingsdata innehåller extra ljudparametrar såsom samplingsfrekvens, bitar per prov och så vidare. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Rectangle](../../../aspose.pdf/rectangle/)
* Class [String](../../../system/string/)
* Class [SoundSampleData](../../soundsampledata/)
* Class [SoundAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
