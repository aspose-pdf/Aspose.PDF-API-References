---
title: Aspose::Pdf::PdfPageStamp class
linktitle: PdfPageStamp
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PdfPageStamp class. Class represents stamp which uses PDF page as stamp in C++.'
type: docs
weight: 15100
url: /cpp/aspose.pdf/pdfpagestamp/
---
## PdfPageStamp class


Class represents stamp which uses PDF page as stamp.

```cpp
class PdfPageStamp : public Aspose::Pdf::Stamp
```

## Methods

| Method | Description |
| --- | --- |
| [get_PdfPage](./get_pdfpage/)() const | Gets page which will be used as stamp. |
| [PdfPageStamp](./pdfpagestamp/)(System::SharedPtr\<Page\>) | Constructor of [PdfPageStamp](./). |
| [PdfPageStamp](./pdfpagestamp/)(System::String, int32_t) | Creates [Pdf](../) page stamp from specifed page of the document in specified file. |
| [PdfPageStamp](./pdfpagestamp/)(System::SharedPtr\<System::IO::Stream\>, int32_t) | Creates [Pdf](../) page stamp from specifed page in the document from the stream. |
| [Put](./put/)(System::SharedPtr\<Page\>) override | Put stamp on the specified page. |
| [set_PdfPage](./set_pdfpage/)(System::SharedPtr\<Page\>) | Sets page which will be used as stamp. |
## See Also

* Class [Stamp](../stamp/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
