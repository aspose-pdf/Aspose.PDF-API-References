---
title: "Метод Aspose::Pdf::Page::AddImage"
linktitle: "AddImage"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Page::AddImage. Добавляет изображение на страницу и размещает его в середине указанного прямоугольника, сохраняя пропорцию изображения в C++."
type: docs
weight: 300
url: /ru/cpp/aspose.pdf/page/addimage/
---
## Page::AddImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&, bool) method


Добавляет изображение на страницу и размещает его в центре указанного прямоугольника, сохраняя пропорции изображения.

```cpp
void Aspose::Pdf::Page::AddImage(const System::SharedPtr<System::IO::Stream> &imageStream, const System::SharedPtr<Aspose::Pdf::Rectangle> &imageRect, const System::SharedPtr<Aspose::Pdf::Rectangle> &bbox=nullptr, bool autoAdjustRectangle=true)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток изображения. |
| imageRect | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | Позиция изображения. |
| bbox | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | Bbbox изображения. |
| autoAdjustRectangle | bool | Отрегулировать изображение в центре входного прямоугольника. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Rectangle](../../rectangle/)
* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Page::AddImage(const System::SharedPtr\<System::IO::Stream\>\&, System::SharedPtr\<Aspose::Pdf::Rectangle\>, int32_t, int32_t, bool, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) method


Добавляет изображение на страницу и размещает его в зависимости от позиции прямоугольника изображения.

```cpp
void Aspose::Pdf::Page::AddImage(const System::SharedPtr<System::IO::Stream> &imageStream, System::SharedPtr<Aspose::Pdf::Rectangle> imageRect, int32_t imageWidth, int32_t imageHeight, bool saveImageProportions, const System::SharedPtr<Aspose::Pdf::Rectangle> &bbox=nullptr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток изображения. |
| imageRect | System::SharedPtr\<Aspose::Pdf::Rectangle\> | Позиция изображения по умолчанию на странице. |
| imageWidth | int32_t | Ширина изображения. |
| imageHeight | int32_t | Высота изображения. |
| saveImageProportions | bool | Если флаг установлен в true, изображение размещается в позиции прямоугольника; иначе размер прямоугольника становится равным размеру изображения. |
| bbox | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | Bbbox изображения. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Rectangle](../../rectangle/)
* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Page::AddImage(const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) method


Добавляет в страницу поисковое изображение и размещает его в центре указанного прямоугольника, сохраняя пропорции изображения.

```cpp
void Aspose::Pdf::Page::AddImage(const System::String &hocr, const System::SharedPtr<System::IO::Stream> &imageStream, const System::SharedPtr<Aspose::Pdf::Rectangle> &imageRect, const System::SharedPtr<Aspose::Pdf::Rectangle> &bbox=nullptr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| hocr | const System::String\& | hocr изображения. |
| imageStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток изображения. |
| imageRect | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | Позиция изображения. |
| bbox | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | Bbbox изображения. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Rectangle](../../rectangle/)
* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Page::AddImage(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) method


Добавляет изображение на страницу и размещает его в центре указанного прямоугольника, сохраняя пропорции изображения.

```cpp
void Aspose::Pdf::Page::AddImage(const System::String &imagePath, const System::SharedPtr<Aspose::Pdf::Rectangle> &rectangle)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| imagePath | const System::String\& | Путь к изображению. |
| прямоугольник | const System::SharedPtr\<Aspose::Pdf::Rectangle\>\& | Позиция изображения. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Rectangle](../../rectangle/)
* Class [Page](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
