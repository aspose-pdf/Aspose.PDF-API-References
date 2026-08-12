---
title: "Конструктор Aspose::Pdf::Annotations::SoundAnnotation::SoundAnnotation"
linktitle: "SoundAnnotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Конструктор Aspose::Pdf::Annotations::SoundAnnotation::SoundAnnotation. Создаёт новую звуковую аннотацию на указанной странице в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.annotations/soundannotation/soundannotation/
---
## SoundAnnotation::SoundAnnotation(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::String\&) constructor


Создаёт новую звуковую аннотацию на указанной странице.

```cpp
Aspose::Pdf::Annotations::SoundAnnotation::SoundAnnotation(const System::SharedPtr<Aspose::Pdf::Page> &page, const System::SharedPtr<Rectangle> &rect, const System::String &soundFile)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | const System::SharedPtr\<Aspose::Pdf::Page\>\& | Страница документа, где должна быть создана аннотация. |
| rect | const System::SharedPtr\<Rectangle\>\& | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| soundFile | const System::String\& | Звуковой файл, определяющий звук, который будет воспроизводиться при активации аннотации. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Rectangle](../../../aspose.pdf/rectangle/)
* Class [String](../../../system/string/)
* Class [SoundAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## SoundAnnotation::SoundAnnotation(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::String\&, const System::SharedPtr\<SoundSampleData\>\&) constructor


Создаёт новую звуковую аннотацию на указанной странице.

```cpp
Aspose::Pdf::Annotations::SoundAnnotation::SoundAnnotation(const System::SharedPtr<Aspose::Pdf::Page> &page, const System::SharedPtr<Rectangle> &rect, const System::String &soundFile, const System::SharedPtr<SoundSampleData> &soundSampleData)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | const System::SharedPtr\<Aspose::Pdf::Page\>\& | Страница документа, где должна быть создана аннотация. |
| rect | const System::SharedPtr\<Rectangle\>\& | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| soundFile | const System::String\& | Звуковой файл, определяющий звук, который будет воспроизводиться при активации аннотации. |
| soundSampleData | const System::SharedPtr\<SoundSampleData\>\& | Объект sound sample data содержит дополнительные параметры звука, такие как частота дискретизации, количество бит на образец и т.д. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Rectangle](../../../aspose.pdf/rectangle/)
* Class [String](../../../system/string/)
* Class [SoundSampleData](../../soundsampledata/)
* Class [SoundAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
