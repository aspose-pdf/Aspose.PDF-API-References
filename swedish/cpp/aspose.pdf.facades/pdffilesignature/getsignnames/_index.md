---
title: "Aspose::Pdf::Facades::PdfFileSignature::GetSignNames‑metod"
linktitle: "GetSignNames"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileSignature::GetSignNames‑metod. Hämtar namnen på alla icke‑tomma signaturer i C++."
type: docs
weight: 2500
url: /sv/cpp/aspose.pdf.facades/pdffilesignature/getsignnames/
---
## PdfFileSignature::GetSignNames method


Hämtar namnen på alla icke‑tomma signaturer.

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Pdf::Facades::PdfFileSignature::GetSignNames(bool onlyActive=true)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| onlyActive | bool | om true, returnera endast aktiva signaturer; annars returnera alla signaturer. |

### ReturnValue

Returnerar en IList<string>.

## Deprecated
Metoden kan producera samma signaturnamn, vilka inte kan särskiljas under verifiering. Använd GetSignatureNames(bool onlyActive) istället.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [String](../../../system/string/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
