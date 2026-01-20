---
title: Aspose::Pdf::Facades::PdfFileSignature::GetSignNames method
linktitle: GetSignNames
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileSignature::GetSignNames method. Gets the names of all not empty signatures in C++.'
type: docs
weight: 2500
url: /cpp/aspose.pdf.facades/pdffilesignature/getsignnames/
---
## PdfFileSignature::GetSignNames method


Gets the names of all not empty signatures.

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Pdf::Facades::PdfFileSignature::GetSignNames(bool onlyActive=true)
```


| Parameter | Type | Description |
| --- | --- | --- |
| onlyActive | bool | if true, return only active signatures; otherwise, return all signatures. |

### ReturnValue

Return an IList<string>.

## Deprecated
The method can produce the same signature names, which cannot be distinguished during verification. Use GetSignatureNames(bool onlyActive) instead. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [String](../../../system/string/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
