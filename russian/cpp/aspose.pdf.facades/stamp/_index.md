---
title: "Aspose::Pdf::Facades::Stamp класс"
linktitle: "Stamp"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::Stamp класс. Класс, представляющий штамп в C++."
type: docs
weight: 3500
url: /ru/cpp/aspose.pdf.facades/stamp/
---
## Stamp class


Класс, представляющий штамп.

```cpp
class Stamp : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [BindImage](./bindimage/)(const System::String\&) | Устанавливает изображение в качестве штампа. |
| [BindImage](./bindimage/)(const System::SharedPtr\<System::IO::Stream\>\&) | Устанавливает изображение, которое будет использоваться в качестве штампа. |
| [BindLogo](./bindlogo/)(const System::SharedPtr\<FormattedText\>\&) | Устанавливает текст в качестве штампа. |
| [BindPdf](./bindpdf/)(const System::String\&, int32_t) | Устанавливает PDF‑файл и номер страницы, которые будут использоваться в качестве штампа. |
| [BindPdf](./bindpdf/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t) | Устанавливает PDF‑файл и номер страницы, которые будут использоваться в качестве штампа. |
| [BindTextState](./bindtextstate/)(const System::SharedPtr\<Text::TextState\>\&) | Устанавливает состояние текста штампа. |
| [get_BlendingSpace](./get_blendingspace/)() const | Получает значение [BlendingColorSpace](../blendingcolorspace/), определяющее цветовое пространство, используемое для выполнения операций прозрачности и смешивания на странице. |
| [get_IsBackground](./get_isbackground/)() const | Получает статус фона. Если true, штамп будет размещён как фон спампированной страницы. По умолчанию установлено false. |
| [get_Opacity](./get_opacity/)() | Получает непрозрачность штампа. |
| [get_PageNumber](./get_pagenumber/)() const | Получает номер страницы. |
| [get_Pages](./get_pages/)() const | Получает массив с номерами страниц, которые будут затронуты штампом. Если Pages = null, затронуты все страницы документа. |
| [get_Quality](./get_quality/)() const | Получает качество штампа‑изображения в процентах. Допустимые значения 0..100%. |
| [get_Rotation](./get_rotation/)() const | Получает вращение штампа в градусах. |
| [get_StampId](./get_stampid/)() const | Получает идентификатор штампа. |
| [set_BlendingSpace](./set_blendingspace/)(BlendingColorSpace) | Устанавливает значение [BlendingColorSpace](../blendingcolorspace/), определяющее цветовое пространство, используемое для выполнения операций прозрачности и смешивания на странице. |
| [set_IsBackground](./set_isbackground/)(bool) | Устанавливает статус фона. Если true, штамп будет размещён как фон спампированной страницы. По умолчанию установлено false. |
| [set_Opacity](./set_opacity/)(float) | Устанавливает непрозрачность штампа. |
| [set_PageNumber](./set_pagenumber/)(int32_t) | Устанавливает номер страницы. |
| [set_Pages](./set_pages/)(const System::ArrayPtr\<int32_t\>\&) | Устанавливает массив с номерами страниц, которые будут затронуты штампом. Если Pages = null, затронуты все страницы документа. |
| [set_Quality](./set_quality/)(int32_t) | Устанавливает качество штампа‑изображения в процентах. Допустимые значения 0..100%. |
| [set_Rotation](./set_rotation/)(float) | Устанавливает вращение штампа в градусах. |
| [set_StampId](./set_stampid/)(int32_t) | Устанавливает идентификатор штампа. |
| [SetImageSize](./setimagesize/)(float, float) | Устанавливает размер штампа‑изображения. [Image](../../aspose.pdf/image/) будет масштабироваться в соответствии с указанными значениями. |
| [SetOrigin](./setorigin/)(float, float) | Устанавливает позицию на странице, где будет размещён штамп. |
| [Stamp](./stamp/)() | Конструктор объекта [Stamp](./). |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
