---
title: "Aspose::Pdf::Annotations::SoundAnnotation класс"
linktitle: "SoundAnnotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::SoundAnnotation класс. Представляет звуковую аннотацию, содержащую звук, записанный с микрофона компьютера или импортированный из файла в C++."
type: docs
weight: 10000
url: /ru/cpp/aspose.pdf.annotations/soundannotation/
---
## SoundAnnotation class


Представляет звуковую аннотацию, содержащую звук, записанный с микрофона компьютера или импортированный из файла.

```cpp
class SoundAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Принимает объект‑посетитель для обработки аннотации. |
| [get_AnnotationType](./get_annotationtype/)() override | Получает тип аннотации. |
| [get_Icon](./get_icon/)() | Получает значок, используемый для отображения аннотации. |
| [get_SoundData](./get_sounddata/)() | Получает объект звука, определяющий звук, который будет воспроизводиться при активации аннотации. |
| [set_Icon](./set_icon/)(SoundIcon) | Устанавливает значок, используемый для отображения аннотации. |
| [SoundAnnotation](./soundannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::String\&) | Создаёт новую звуковую аннотацию на указанной странице. |
| [SoundAnnotation](./soundannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::String\&, const System::SharedPtr\<SoundSampleData\>\&) | Создаёт новую звуковую аннотацию на указанной странице. |
## См. также

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
