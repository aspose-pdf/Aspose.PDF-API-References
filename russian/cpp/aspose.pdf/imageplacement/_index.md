---
title: "Класс Aspose::Pdf::ImagePlacement"
linktitle: "ImagePlacement"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::ImagePlacement. Представляет характеристики изображения, размещённого на странице документа Pdf в C++."
type: docs
weight: 8000
url: /ru/cpp/aspose.pdf/imageplacement/
---
## ImagePlacement class


Представляет характеристики изображения, размещённого на странице документа [Pdf](../).

```cpp
class ImagePlacement : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_CompositingParameters](./get_compositingparameters/)() const | Получает параметры композитинга графического состояния, активные для изображения, размещённого на странице. |
| [get_Image](./get_image/)() const | Получает связанный объект ресурса [XImage](../ximage/). |
| [get_Matrix](./get_matrix/)() const | Текущая матрица преобразования для этого изображения. |
| [get_Operator](./get_operator/)() const | [Operator](../operator/) используется для отображения изображения. |
| [get_Page](./get_page/)() const | Получает страницу, содержащую изображение. |
| [get_Rectangle](./get_rectangle/)() const | Получает прямоугольник [Image](../image/). |
| [get_Resolution](./get_resolution/)() const | Получает разрешение [Image](../image/). |
| [get_Rotation](./get_rotation/)() const | Получает угол вращения [Image](../image/). |
| [Hide](./hide/)() | Удалить изображение со страницы. |
| [Replace](./replace/)(const System::SharedPtr\<System::IO::Stream\>\&) | Заменить изображение в коллекции другим изображением. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&) | Сохраняет изображение с соответствующими преобразованиями: масштабирование, вращение и разрешение. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Сохраняет изображение с соответствующими преобразованиями: масштабирование, вращение и разрешение. |
## Примечания


Когда изображение размещается на странице, оно может иметь размеры, отличные от физических размеров, определённых в [Resources](../resources/). Объект [ImagePlacement](./) предназначен для предоставления такой информации, как размеры, разрешение и т.д.
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
