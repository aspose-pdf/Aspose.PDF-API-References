---
title: "Aspose::Pdf::Facades::PdfFileMend::AddImage метод"
linktitle: "AddImage"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileMend::AddImage метод. Добавляет изображение на указанные страницы PDF‑документа в заданных координатах в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf.facades/pdffilemend/addimage/
---
## PdfFileMend::AddImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float) method


Добавляет изображение на указанные страницы PDF‑документа в заданных координатах.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(const System::SharedPtr<System::IO::Stream> &imageStream, const System::ArrayPtr<int32_t> &pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | const System::SharedPtr\<System::IO::Stream\>\& | Входной поток изображения. |
| pageNums | const System::ArrayPtr\<int32_t\>\& | Количество страниц, которые получат изображение. |
| lowerLeftX | float | Нижний левый x прямоугольника изображения. |
| lowerLeftY | float | Нижний левый y прямоугольника изображения. |
| upperRightX | float | Верхний правый x прямоугольника изображения. |
| upperRightY | float | Верхний правый y прямоугольника изображения. |

### ReturnValue

True если успешно, иначе false.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) method


Добавляет изображение на указанные страницы PDF‑документа в заданных координатах.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(const System::SharedPtr<System::IO::Stream> &imageStream, const System::ArrayPtr<int32_t> &pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, const System::SharedPtr<CompositingParameters> &compositingParameters)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | const System::SharedPtr\<System::IO::Stream\>\& | Входной поток изображения. |
| pageNums | const System::ArrayPtr\<int32_t\>\& | Количество страниц, которые получат изображение. |
| lowerLeftX | float | Нижний левый x прямоугольника изображения. |
| lowerLeftY | float | Нижний левый y прямоугольника изображения. |
| upperRightX | float | Верхний правый x прямоугольника изображения. |
| upperRightY | float | Верхний правый y прямоугольника изображения. |
| compositingParameters | const System::SharedPtr\<CompositingParameters\>\& | Параметры композитинга графики для изображений. |

### ReturnValue

True если успешно, иначе false.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, float, float, float, float) method


Добавляет изображение на указанную страницу PDF‑документа в заданных координатах.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(const System::SharedPtr<System::IO::Stream> &imageStream, int32_t pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | const System::SharedPtr\<System::IO::Stream\>\& | Входной поток изображения. |
| pageNum | int32_t | Количество страниц, которые получат изображение. |
| lowerLeftX | float | Нижний левый x прямоугольника изображения. |
| lowerLeftY | float | Нижний левый y прямоугольника изображения. |
| upperRightX | float | Верхний правый x прямоугольника изображения. |
| upperRightY | float | Верхний правый y прямоугольника изображения. |

### ReturnValue

True если успешно, иначе false.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) method


Добавляет изображение на указанную страницу PDF‑документа в заданных координатах.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(const System::SharedPtr<System::IO::Stream> &imageStream, int32_t pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, const System::SharedPtr<CompositingParameters> &compositingParameters)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | const System::SharedPtr\<System::IO::Stream\>\& | Входной поток изображения. |
| pageNum | int32_t | Количество страниц, которые получат изображение. |
| lowerLeftX | float | Нижний левый x прямоугольника изображения. |
| lowerLeftY | float | Нижний левый y прямоугольника изображения. |
| upperRightX | float | Верхний правый x прямоугольника изображения. |
| upperRightY | float | Верхний правый y прямоугольника изображения. |
| compositingParameters | const System::SharedPtr\<CompositingParameters\>\& | Параметры композитинга графики для изображения. |

### ReturnValue

True если успешно, иначе false.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(const System::String\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float) method


Добавляет изображение на указанные страницы PDF‑документа в заданных координатах.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(const System::String &imageName, const System::ArrayPtr<int32_t> &pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| imageName | const System::String\& | Путь к входному файлу изображения. |
| pageNums | const System::ArrayPtr\<int32_t\>\& | Количество страниц, которые получат изображение. |
| lowerLeftX | float | Нижний левый x прямоугольника изображения. |
| lowerLeftY | float | Нижний левый y прямоугольника изображения. |
| upperRightX | float | Верхний правый x прямоугольника изображения. |
| upperRightY | float | Верхний правый y прямоугольника изображения. |

### ReturnValue

True если успешно, иначе false.

## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(const System::String\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) method


Добавляет изображение на указанные страницы PDF‑документа в заданных координатах.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(const System::String &imageName, const System::ArrayPtr<int32_t> &pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, const System::SharedPtr<CompositingParameters> &compositingParameters)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| imageName | const System::String\& | Путь к входному файлу изображения. |
| pageNums | const System::ArrayPtr\<int32_t\>\& | Количество страниц, которые получат изображение. |
| lowerLeftX | float | Нижний левый x прямоугольника изображения. |
| lowerLeftY | float | Нижний левый y прямоугольника изображения. |
| upperRightX | float | Верхний правый x прямоугольника изображения. |
| upperRightY | float | Верхний правый y прямоугольника изображения. |
| compositingParameters | const System::SharedPtr\<CompositingParameters\>\& | Параметры композитинга графики для изображений. |

### ReturnValue

True если успешно, иначе false.

## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(const System::String\&, int32_t, float, float, float, float) method


Добавляет изображение на указанную страницу PDF‑документа в заданных координатах.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(const System::String &imageName, int32_t pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| imageName | const System::String\& | Путь к входному файлу изображения. |
| pageNum | int32_t | Количество страниц, которые получат изображение. |
| lowerLeftX | float | Нижний левый x прямоугольника изображения. |
| lowerLeftY | float | Нижний левый y прямоугольника изображения. |
| upperRightX | float | Верхний правый x прямоугольника изображения. |
| upperRightY | float | Верхний правый y прямоугольника изображения. |

### ReturnValue

True если успешно, иначе false.

## См. также

* Class [String](../../../system/string/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileMend::AddImage(const System::String\&, int32_t, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) method


Добавляет изображение на указанную страницу PDF‑документа в заданных координатах.

```cpp
bool Aspose::Pdf::Facades::PdfFileMend::AddImage(const System::String &imageName, int32_t pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, const System::SharedPtr<CompositingParameters> &compositingParameters)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| imageName | const System::String\& | Путь к входному файлу изображения. |
| pageNum | int32_t | Количество страниц, которые получат изображение. |
| lowerLeftX | float | Нижний левый x прямоугольника изображения. |
| lowerLeftY | float | Нижний левый y прямоугольника изображения. |
| upperRightX | float | Верхний правый x прямоугольника изображения. |
| upperRightY | float | Верхний правый y прямоугольника изображения. |
| compositingParameters | const System::SharedPtr\<CompositingParameters\>\& | Параметры композитинга графики для изображений. |

### ReturnValue

True если успешно, иначе false.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* Class [PdfFileMend](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
