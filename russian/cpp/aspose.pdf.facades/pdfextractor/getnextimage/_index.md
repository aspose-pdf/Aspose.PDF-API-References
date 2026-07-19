---
title: "Aspose::Pdf::Facades::PdfExtractor::GetNextImage метод"
linktitle: "GetNextImage"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfExtractor::GetNextImage метод. Получает следующее изображение из PDF‑файла и сохраняет его в поток в C++."
type: docs
weight: 1700
url: /ru/cpp/aspose.pdf.facades/pdfextractor/getnextimage/
---
## PdfExtractor::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&) method


Получить следующее изображение из PDF‑файла и сохранить его в поток.

```cpp
bool Aspose::Pdf::Facades::PdfExtractor::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток, в который будут сохранены данные изображения |

### ReturnValue

True, если изображение успешно извлечено.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfExtractor::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) method


Получает следующее изображение из PDF‑файла и сохраняет его в поток в заданном формате изображения.

```cpp
bool Aspose::Pdf::Facades::PdfExtractor::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток, в который будут сохранены данные изображения |
| формат | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Формат изображения. |

### ReturnValue

True, если изображение успешно извлечено.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfExtractor::GetNextImage(const System::String\&) method


Получает следующее изображение из PDF‑документа. [Note](../../../aspose.pdf/note/): метод ExtractImage должен быть вызван до использования этого метода.

```cpp
bool Aspose::Pdf::Facades::PdfExtractor::GetNextImage(const System::String &outputFile)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | const System::String\& | Файл, в который будет сохранено изображение |

### ReturnValue

True, если изображение успешно извлечено

## См. также

* Class [String](../../../system/string/)
* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfExtractor::GetNextImage(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) method


Получает следующее изображение из PDF‑документа в заданном формате изображения. [Note](../../../aspose.pdf/note/): метод ExtractImage должен быть вызван до использования этого метода.

```cpp
bool Aspose::Pdf::Facades::PdfExtractor::GetNextImage(const System::String &outputFile, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | const System::String\& | Файл, в который будет сохранено изображение |
| формат | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Формат изображения. |

### ReturnValue

True, если изображение успешно извлечено

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfExtractor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
