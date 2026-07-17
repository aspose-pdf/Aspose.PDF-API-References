---
title: Aspose::Pdf::Facades::PdfFileSignature::ExtractImage method
linktitle: ExtractImage
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileSignature::ExtractImage method. Extracts signature''s image in C++.'
type: docs
weight: 900
url: /cpp/aspose.pdf.facades/pdffilesignature/extractimage/
---
## PdfFileSignature::ExtractImage(const System::SharedPtr\<SignatureName\>\&) method


Extracts signature's image.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Pdf::Facades::PdfFileSignature::ExtractImage(const System::SharedPtr<SignatureName> &signName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | The name of signature. |

### ReturnValue

If image was successfully found than returns stream object; otherwise, null.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [SignatureName](../../signaturename/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::ExtractImage(const System::String\&) method


Extracts signature's image.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Pdf::Facades::PdfFileSignature::ExtractImage(const System::String &signName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| signName | const System::String\& | The name of signature. |

### ReturnValue

If image was successfully found than returns stream object; otherwise, null.

## Deprecated
Use ExtractImage(SignatureName) method instead. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
