---
title: "Aspose::Pdf::Facades::PdfConverter::MergeImagesAsTiff метод"
linktitle: "MergeImagesAsTiff"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfConverter::MergeImagesAsTiff метод. Объединяет список tiff‑потоков в один многокадровый tiff‑поток в C++."
type: docs
weight: 2900
url: /ru/cpp/aspose.pdf.facades/pdfconverter/mergeimagesastiff/
---
## PdfConverter::MergeImagesAsTiff method


Объединяет список потоков TIFF в один поток TIFF с несколькими кадрами.

```cpp
static System::SharedPtr<System::IO::Stream> Aspose::Pdf::Facades::PdfConverter::MergeImagesAsTiff(const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::IO::Stream>>> &inputImagesStreams)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputImagesStreams | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::IO::Stream\>\>\>\& | Список tiff‑потоков. |

### ReturnValue

Многокадровый tiff‑поток.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [List](../../../system.collections.generic/list/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
