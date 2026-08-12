---
title: "Aspose::Pdf::Facades::PdfFileSignature::ExtractImage метод"
linktitle: "ExtractImage"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileSignature::ExtractImage метод. Извлекает изображение подписи'' в C++."
type: docs
weight: 900
url: /ru/cpp/aspose.pdf.facades/pdffilesignature/extractimage/
---
## PdfFileSignature::ExtractImage(const System::SharedPtr\<SignatureName\>\&) method


Извлекает изображение подписи.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Pdf::Facades::PdfFileSignature::ExtractImage(const System::SharedPtr<SignatureName> &signName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | Имя подписи. |

### ReturnValue

Если изображение было успешно найдено, возвращает объект потока; в противном случае — null.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [SignatureName](../../signaturename/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::ExtractImage(const System::String\&) method


Извлекает изображение подписи.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Pdf::Facades::PdfFileSignature::ExtractImage(const System::String &signName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | const System::String\& | Имя подписи. |

### ReturnValue

Если изображение было успешно найдено, возвращает объект потока; в противном случае — null.

## Deprecated
Используйте вместо этого метод ExtractImage(SignatureName).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
