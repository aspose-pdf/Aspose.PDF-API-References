---
title: Aspose::Pdf::LowCode::PdfAOptionsBase::get_PdfAVersion method
linktitle: get_PdfAVersion
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LowCode::PdfAOptionsBase::get_PdfAVersion method. Gets the version of the PDF/A standard to be used for validation or conversion in C++.'
type: docs
weight: 1300
url: /cpp/aspose.pdf.lowcode/pdfaoptionsbase/get_pdfaversion/
---
## PdfAOptionsBase::get_PdfAVersion method


Gets the version of the PDF/A standard to be used for validation or conversion.

```cpp
PdfAStandardVersion Aspose::Pdf::LowCode::PdfAOptionsBase::get_PdfAVersion() const
```

## Remarks


The version of the PDF/A standard. This can be one of the values from the [PdfAStandardVersion](../../pdfastandardversion/) enumeration. 

The PDF/A standard version is used to determine the compliance level for PDF/A validation and conversion. If the version is set to [PdfAStandardVersion::Auto](../../pdfastandardversion/), the system will automatically determine the appropriate PDF/A standard version for validation based on the document metadata. For the PDF/A conversion process the [PdfAStandardVersion::Auto](../../pdfastandardversion/) defaults to the PDF/A-1b standard version. 
## See Also

* Enum [PdfAStandardVersion](../../pdfastandardversion/)
* Class [PdfAOptionsBase](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
