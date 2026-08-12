---
title: "Метод Aspose::Pdf::Document::Convert"
linktitle: "Преобразовать"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Document::Convert. Конвертирует документ, используя указанные параметры конвертации, в C++."
type: docs
weight: 500
url: /ru/cpp/aspose.pdf/document/convert/
---
## Document::Convert(const System::SharedPtr\<PdfFormatConversionOptions\>\&) method


Конвертировать документ, используя указанные параметры конвертации.

```cpp
bool Aspose::Pdf::Document::Convert(const System::SharedPtr<PdfFormatConversionOptions> &options)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| опции | const System::SharedPtr\<PdfFormatConversionOptions\>\& | набор параметров для преобразования PDF‑документа |

### ReturnValue

Результат операции

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PdfFormatConversionOptions](../../pdfformatconversionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(const System::SharedPtr\<System::IO::Stream\>\&, Aspose::Pdf::PdfFormat, ConvertErrorAction) method


Конвертировать документ и сохранить ошибки в указанный поток.

```cpp
bool Aspose::Pdf::Document::Convert(const System::SharedPtr<System::IO::Stream> &outputLogStream, Aspose::Pdf::PdfFormat format, ConvertErrorAction action)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputLogStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток, в котором будут сохраняться комментарии. |
| format | Aspose::Pdf::PdfFormat | [Pdf](../../) формат. |
| action | ConvertErrorAction | Действие для объектов, которые нельзя конвертировать |

### ReturnValue

Результат операции

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [PdfFormat](../../pdfformat/)
* Enum [ConvertErrorAction](../../converterroraction/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(const System::SharedPtr\<System::IO::Stream\>\&, Aspose::Pdf::PdfFormat, ConvertErrorAction, ConvertTransparencyAction) method


Конвертировать документ и сохранить ошибки в указанный файл.

```cpp
bool Aspose::Pdf::Document::Convert(const System::SharedPtr<System::IO::Stream> &outputLogStream, Aspose::Pdf::PdfFormat format, ConvertErrorAction action, ConvertTransparencyAction transparencyAction)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputLogStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток, в котором будут сохраняться комментарии. |
| формат | Aspose::Pdf::PdfFormat | PDF‑формат. |
| action | ConvertErrorAction | Действие для объектов, которые нельзя конвертировать |
| transparencyAction | ConvertTransparencyAction | Действие для объектов с маской изображения |

### ReturnValue

Результат операции

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [PdfFormat](../../pdfformat/)
* Enum [ConvertErrorAction](../../converterroraction/)
* Enum [ConvertTransparencyAction](../../converttransparencyaction/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(const System::String\&, Aspose::Pdf::PdfFormat, ConvertErrorAction) method


Конвертировать документ и сохранить ошибки в указанный файл.

```cpp
bool Aspose::Pdf::Document::Convert(const System::String &outputLogFileName, Aspose::Pdf::PdfFormat format, ConvertErrorAction action)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputLogFileName | const System::String\& | Путь к файлу, в котором будут сохраняться комментарии. |
| формат | Aspose::Pdf::PdfFormat | PDF‑формат. |
| action | ConvertErrorAction | Действие для объектов, которые нельзя конвертировать |

### ReturnValue

Результат операции

## См. также

* Class [String](../../../system/string/)
* Enum [PdfFormat](../../pdfformat/)
* Enum [ConvertErrorAction](../../converterroraction/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(const System::String\&, Aspose::Pdf::PdfFormat, ConvertErrorAction, ConvertTransparencyAction) method


Конвертировать документ и сохранить ошибки в указанный файл.

```cpp
bool Aspose::Pdf::Document::Convert(const System::String &outputLogFileName, Aspose::Pdf::PdfFormat format, ConvertErrorAction action, ConvertTransparencyAction transparencyAction)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| outputLogFileName | const System::String\& | Путь к файлу, в котором будут сохраняться комментарии. |
| формат | Aspose::Pdf::PdfFormat | PDF‑формат. |
| action | ConvertErrorAction | Действие для объектов, которые нельзя конвертировать |
| transparencyAction | ConvertTransparencyAction | Действие для объектов с маской изображения |

### ReturnValue

Результат операции

## См. также

* Class [String](../../../system/string/)
* Enum [PdfFormat](../../pdfformat/)
* Enum [ConvertErrorAction](../../converterroraction/)
* Enum [ConvertTransparencyAction](../../converttransparencyaction/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(Document::CallBackGetHocr, bool) method


Распознавать изображения внутри документа и добавлять hocr‑строки поверх него.

```cpp
bool Aspose::Pdf::Document::Convert(Document::CallBackGetHocr callback, bool flattenImages=false)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| обратный вызов | Document::CallBackGetHocr | Действие для изображений, которые будут обработаны распознаванием hocr. |
| flattenImages | bool | [Text](../../../aspose.pdf.text/) в pdf‑изображениях может быть нарисован с использованием механики масок, в этом случае изображения должны быть сплющены. |

### ReturnValue

Результат операции. Если в документе нет изображений, возвращает [false](../).

## См. также

* Typedef [CallBackGetHocr](../callbackgethocr/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(Document::CallBackGetHocrWithPage, bool) method


Распознавать изображения внутри документа и добавлять hocr‑строки поверх него.

```cpp
bool Aspose::Pdf::Document::Convert(Document::CallBackGetHocrWithPage callback, bool flattenImages=false)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| обратный вызов | Document::CallBackGetHocrWithPage | Действие для изображений, которые будут обработаны распознаванием hocr. |
| flattenImages | bool | [Text](../../../aspose.pdf.text/) в pdf‑изображениях может быть нарисован с использованием механики масок, в этом случае изображения должны быть сплющены. |

### ReturnValue

Результат операции. Если в документе нет изображений, возвращает [false](../).

## См. также

* Typedef [CallBackGetHocrWithPage](../callbackgethocrwithpage/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(Fixup, const System::SharedPtr\<System::IO::Stream\>\&, bool, const System::ArrayPtr\<System::SharedPtr\<System::Object\>\>\&) method


Конвертировать документ, применяя [Fixup](../../fixup/).

```cpp
bool Aspose::Pdf::Document::Convert(Fixup fixup, const System::SharedPtr<System::IO::Stream> &outputLog, bool onlyValidation=false, const System::ArrayPtr<System::SharedPtr<System::Object>> &parameters=nullptr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fixup | Fixup | Тип [Fixup](../../fixup/). |
| outputLog | const System::SharedPtr\<System::IO::Stream\>\& | Журнал процесса. |
| onlyValidation | bool | Только проверка документа. |
| parameters | const System::ArrayPtr\<System::SharedPtr\<System::Object\>\>\& | Свойства [Fixup](../../fixup/), которые нельзя задать. |

### ReturnValue

Результат операции.

## См. также

* Enum [Fixup](../../fixup/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(Fixup, const System::String\&, bool, const System::ArrayPtr\<System::SharedPtr\<System::Object\>\>\&) method


Конвертировать документ, применяя [Fixup](../../fixup/).

```cpp
bool Aspose::Pdf::Document::Convert(Fixup fixup, const System::String &outputLog, bool onlyValidation=false, const System::ArrayPtr<System::SharedPtr<System::Object>> &parameters=nullptr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fixup | Fixup | Тип [Fixup](../../fixup/). |
| outputLog | const System::String\& | Журнал процесса. |
| onlyValidation | bool | Только проверка документа. |
| parameters | const System::ArrayPtr\<System::SharedPtr\<System::Object\>\>\& | Свойства [Fixup](../../fixup/), которые нельзя задать. |

### ReturnValue

Результат операции.

## См. также

* Enum [Fixup](../../fixup/)
* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&, const System::SharedPtr\<System::IO::Stream\>\&, System::SharedPtr\<SaveOptions\>) method


Конвертирует поток в исходном формате в поток в целевом формате.

```cpp
static void Aspose::Pdf::Document::Convert(const System::SharedPtr<System::IO::Stream> &srcStream, const System::SharedPtr<LoadOptions> &loadOptions, const System::SharedPtr<System::IO::Stream> &dstStream, System::SharedPtr<SaveOptions> saveOptions)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| srcStream | const System::SharedPtr\<System::IO::Stream\>\& | Исходный поток. |
| loadOptions | const System::SharedPtr\<LoadOptions\>\& | Формат исходного потока. |
| dstStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток назначения. |
| saveOptions | System::SharedPtr\<SaveOptions\> | Формат целевого файла. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [LoadOptions](../../loadoptions/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&, const System::String\&, System::SharedPtr\<SaveOptions\>) method


Конвертирует поток в исходном формате в целевой файл в целевом формате.

```cpp
static void Aspose::Pdf::Document::Convert(const System::SharedPtr<System::IO::Stream> &srcStream, const System::SharedPtr<LoadOptions> &loadOptions, const System::String &dstFileName, System::SharedPtr<SaveOptions> saveOptions)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| srcStream | const System::SharedPtr\<System::IO::Stream\>\& | Исходный поток. |
| loadOptions | const System::SharedPtr\<LoadOptions\>\& | Формат исходного потока. |
| dstFileName | const System::String\& | Имя целевого файла. |
| saveOptions | System::SharedPtr\<SaveOptions\> | Формат целевого файла. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [LoadOptions](../../loadoptions/)
* Class [String](../../../system/string/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(const System::String\&, const System::SharedPtr\<LoadOptions\>\&, const System::SharedPtr\<System::IO::Stream\>\&, System::SharedPtr\<SaveOptions\>) method


Конвертирует исходный файл в исходном формате в поток в целевом формате.

```cpp
static void Aspose::Pdf::Document::Convert(const System::String &srcFileName, const System::SharedPtr<LoadOptions> &loadOptions, const System::SharedPtr<System::IO::Stream> &dstStream, System::SharedPtr<SaveOptions> saveOptions)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFileName | const System::String\& | Имя исходного файла. |
| loadOptions | const System::SharedPtr\<LoadOptions\>\& | Формат исходного файла. |
| dstStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток назначения. |
| saveOptions | System::SharedPtr\<SaveOptions\> | Формат целевого потока. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LoadOptions](../../loadoptions/)
* Class [Stream](../../../system.io/stream/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(const System::String\&, const System::SharedPtr\<LoadOptions\>\&, const System::String\&, System::SharedPtr\<SaveOptions\>) method


Конвертирует исходный файл в исходном формате в целевой файл в целевом формате.

```cpp
static void Aspose::Pdf::Document::Convert(const System::String &srcFileName, const System::SharedPtr<LoadOptions> &loadOptions, const System::String &dstFileName, System::SharedPtr<SaveOptions> saveOptions)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFileName | const System::String\& | Имя исходного файла. |
| loadOptions | const System::SharedPtr\<LoadOptions\>\& | Формат исходного файла. |
| dstFileName | const System::String\& | Имя целевого файла. |
| saveOptions | System::SharedPtr\<SaveOptions\> | Формат целевого файла. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LoadOptions](../../loadoptions/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
