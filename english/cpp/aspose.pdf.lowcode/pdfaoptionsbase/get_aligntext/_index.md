---
title: Aspose::Pdf::LowCode::PdfAOptionsBase::get_AlignText method
linktitle: get_AlignText
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LowCode::PdfAOptionsBase::get_AlignText method. Gets a value indicating whether additional means are necessary to preserve text alignment during the PDF/A conversion process in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf.lowcode/pdfaoptionsbase/get_aligntext/
---
## PdfAOptionsBase::get_AlignText method


Gets a value indicating whether additional means are necessary to preserve text alignment during the PDF/A conversion process.

```cpp
bool Aspose::Pdf::LowCode::PdfAOptionsBase::get_AlignText()
```

## Remarks


**true**

if the text alignment gets changed and additional actions are necessary to restore it; otherwise, **false**

. 

When set to **true**

, the conversion process will attempt to restore the original text segment bounds. For the most of the documents there is no need to change this property from the default **false**

value, as the text alignment doesn't change during the default conversion process. 
## See Also

* Class [PdfAOptionsBase](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
