---
title: "Aspose::Pdf::Facades::PdfConverter::GetNextImage method"
linktitle: "GetNextImage"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfConverter::GetNextImage method. Сохраняет изображение в поток в формате изображения по умолчанию — jpeg в C++."
type: docs
weight: 1500
url: /ru/cpp/aspose.pdf.facades/pdfconverter/getnextimage/
---
## PdfConverter::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&) method


Сохраняет изображение в поток с форматом изображения по умолчанию — jpeg.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток для сохранения изображения. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&) method


Сохраняет изображение в поток с указанным размером страницы.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<PageSize> &pageSize)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток для сохранения изображения. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Размер страницы изображения. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) method


Сохраняет изображение в поток с указанным размером страницы.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток для сохранения изображения. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Размер страницы изображения. |
| формат | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Формат изображения. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) method


Сохраняет изображение в поток с заданным размером страницы, форматом изображения и качеством.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, int32_t quality)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток для сохранения изображения. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Размер страницы изображения. |
| формат | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Формат изображения. |
| качество | int32_t | Качество JPEG‑файла (0~100), 0 — самое низкое, 100 — самое высокое. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) method


Сохраняет изображение в поток с заданным форматом изображения.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток для сохранения изображения. |
| формат | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Формат изображения. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, double, double, int32_t) method


Сохраняет изображение в поток с указанным форматом изображения, размером и качеством.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, double imageWidth, double imageHeight, int32_t quality)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток для сохранения изображения. |
| формат | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Формат изображения. |
| imageWidth | double | Ширина изображения, единица измерения — пиксель. |
| imageHeight | double | Высота изображения, единица измерения — пиксель. |
| качество | int32_t | Качество JPEG‑файла (0~100), 0 — самое низкое, 100 — самое высокое. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t, int32_t) method


Сохраняет изображение в поток с указанным форматом изображения, размером и качеством.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, int32_t imageWidth, int32_t imageHeight)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток для сохранения изображения. |
| формат | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Формат изображения. |
| imageWidth | int32_t | Ширина изображения, единица измерения — пиксель. |
| imageHeight | int32_t | Высота изображения, единица измерения — пиксель. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t, int32_t, int32_t) method


Сохраняет изображение в поток с указанным форматом изображения, размерами и качеством.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, int32_t imageWidth, int32_t imageHeight, int32_t quality)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток для сохранения изображения. |
| формат | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Формат изображения. |
| imageWidth | int32_t | Ширина изображения, единица измерения — пиксель. |
| imageHeight | int32_t | Высота изображения, единица измерения — пиксель. |
| качество | int32_t | Качество JPEG‑файла (0~100), 0 — самое низкое, 100 — самое высокое. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) method


Сохраняет изображение в поток с заданным форматом изображения и качеством.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::SharedPtr<System::IO::Stream> &outputStream, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, int32_t quality)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток для сохранения изображения. |
| формат | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Формат изображения. |
| качество | int32_t | Качество JPEG‑файла (0~100), 0 — самое низкое, 100 — самое высокое. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::String\&) method


Сохраняет изображение в файл с форматом изображения по умолчанию — jpeg.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::String &outputFile)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | const System::String\& | Путь к файлу и его имя для сохранения изображения. |

## См. также

* Class [String](../../../system/string/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::String\&, const System::SharedPtr\<PageSize\>\&) method


Сохраняет изображение в файл с указанным размером страницы и форматом изображения по умолчанию — jpeg.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::String &outputFile, const System::SharedPtr<PageSize> &pageSize)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | const System::String\& | Путь к файлу и его имя для сохранения изображения. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Размер страницы изображения. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::String\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) method


Сохраняет изображение в файл с указанным размером страницы и форматом изображения.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::String &outputFile, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | const System::String\& | Путь к файлу и его имя для сохранения изображения. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Размер страницы изображения. |
| формат | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Формат изображения. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::String\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) method


Сохраняет изображение в файл с заданным размером страницы, форматом изображения и качеством.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::String &outputFile, const System::SharedPtr<PageSize> &pageSize, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, int32_t quality)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | const System::String\& | Путь к файлу и его имя для сохранения изображения. |
| pageSize | const System::SharedPtr\<PageSize\>\& | Размер страницы изображения. |
| формат | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Формат изображения. |
| качество | int32_t | Качество JPEG‑файла (0~100), 0 — самое низкое, 100 — самое высокое. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) method


Сохраняет изображение в файл с указанным форматом изображения.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::String &outputFile, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | const System::String\& | Путь к файлу и его имя для сохранения изображения. |
| формат | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Формат изображения. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, double, double, int32_t) method


Сохраняет изображение в файл с указанным форматом изображения, размером изображения и качеством.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::String &outputFile, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, double imageWidth, double imageHeight, int32_t quality)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | const System::String\& | Путь к файлу и его имя для сохранения изображения. |
| формат | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Формат изображения. |
| imageWidth | double | Ширина изображения, единица измерения — пиксели. |
| imageHeight | double | Высота изображения, единица измерения — пиксели.. |
| качество | int32_t | Качество JPEG‑файла (0~100), 0 — самое низкое, 100 — самое высокое. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t, int32_t) method


Сохраняет изображение в файл с заданным форматом изображения и размерами.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::String &outputFile, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, int32_t imageWidth, int32_t imageHeight)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | const System::String\& | Путь к файлу и его имя для сохранения изображения. |
| формат | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Формат изображения. |
| imageWidth | int32_t | Ширина изображения, единица измерения — пиксель. |
| imageHeight | int32_t | Высота изображения, единица измерения — пиксель. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t, int32_t, int32_t) method


Сохраняет изображение в файл с заданным форматом изображения, размерами и качеством.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::String &outputFile, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, int32_t imageWidth, int32_t imageHeight, int32_t quality)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | const System::String\& | Путь к файлу и его имя для сохранения изображения. |
| формат | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Формат изображения. |
| imageWidth | int32_t | Ширина изображения, единица измерения — пиксель. |
| imageHeight | int32_t | Высота изображения, единица измерения — пиксель. |
| качество | int32_t | Качество JPEG‑файла (0~100), 0 — самое низкое, 100 — самое высокое. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfConverter::GetNextImage(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) method


Сохраняет изображение в файл с заданным форматом изображения и качеством.

```cpp
void Aspose::Pdf::Facades::PdfConverter::GetNextImage(const System::String &outputFile, const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format, int32_t quality)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | const System::String\& | Путь к файлу и его имя для сохранения изображения. |
| формат | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | Формат изображения. |
| качество | int32_t | Качество JPEG‑файла (0~100), 0 — самое низкое, 100 — самое высокое. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
