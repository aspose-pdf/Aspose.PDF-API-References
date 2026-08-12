---
title: "Aspose::Pdf::Annotations::RichMediaAnnotation класс"
linktitle: "RichMediaAnnotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::RichMediaAnnotation класс. Класс описывает RichMediaAnnotation, который позволяет встраивать видео/аудио данные в PDF‑документ в C++."
type: docs
weight: 9700
url: /ru/cpp/aspose.pdf.annotations/richmediaannotation/
---
## RichMediaAnnotation class


Класс описывает [RichMediaAnnotation](./), который позволяет встраивать видео/аудио данные в PDF‑документ.

```cpp
class RichMediaAnnotation : public Aspose::Pdf::Annotations::Annotation
```

## Enums

| Перечисление | Описание |
| --- | --- |
| [ActivationEvent](./activationevent/) | Событие, которое активирует аннотацию. |
| [ContentType](./contenttype/) | Тип мультимедиа. |
## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Принимает посетителя для этой аннотации. |
| [AddCustomData](./addcustomdata/)(const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&) | Добавить пользовательские именованные данные (например, необходимые для flash‑скрипта). |
| [get_ActivateOn](./get_activateon/)() | Событие, которое активирует приложение. |
| [get_AnnotationType](./get_annotationtype/)() override | Получает тип аннотации. |
| [get_Content](./get_content/)() | Данные Rich Media контента. |
| [get_CustomFlashVariables](./get_customflashvariables/)() const | Устанавливает или получает flash‑переменные, которые передаются плееру. |
| [get_CustomPlayer](./get_customplayer/)() const | Устанавливает или получает пользовательский flash‑плеер для воспроизведения видео/аудио данных. |
| [get_Type](./get_type/)() | Получает тип контента. Возможные значения: Audio, Video. |
| [RichMediaAnnotation](./richmediaannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Инициализирует [RichMediaAnnotation](./). |
| [set_ActivateOn](./set_activateon/)(RichMediaAnnotation::ActivationEvent) | Событие, которое активирует приложение. |
| [set_CustomFlashVariables](./set_customflashvariables/)(const System::String\&) | Устанавливает или получает flash‑переменные, которые передаются плееру. |
| [set_CustomPlayer](./set_customplayer/)(const System::SharedPtr\<System::IO::Stream\>\&) | Устанавливает или получает пользовательский flash‑плеер для воспроизведения видео/аудио данных. |
| [set_Type](./set_type/)(RichMediaAnnotation::ContentType) | Устанавливает тип контента. Возможные значения: Audio, Video. |
| [SetContent](./setcontent/)(const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&) | Установить поток содержимого. |
| [SetPoster](./setposter/)(const System::SharedPtr\<System::IO::Stream\>\&) | Установить постер аннотации. |
| [Update](./update/)() | Обновляет данные с указанными параметрами. |
## См. также

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
