---
title: Aspose::Pdf::Facades::PdfFileSignature::ExtractCertificate method
linktitle: ExtractCertificate
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileSignature::ExtractCertificate method. Extracts signature''s single X.509 certificate as a stream in C++.'
type: docs
weight: 3300
url: /cpp/aspose.pdf.facades/pdffilesignature/extractcertificate/
---
## PdfFileSignature::ExtractCertificate method


Extracts signature's single X.509 certificate as a stream.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<System::IO::Stream> Aspose::Pdf::Facades::PdfFileSignature::ExtractCertificate(System::String signName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| signName | System::String | The name of signature. |

### ReturnValue

If certificate was found returns X.509 single certificate; otherwise, null.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>signName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The name of signature.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
