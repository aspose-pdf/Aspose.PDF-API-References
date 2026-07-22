---
title: "Aspose::Pdf::Facades::PdfFileSignature::ExtractCertificate‑metod"
linktitle: "ExtractCertificate"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileSignature::ExtractCertificate‑metod. Extraherar signaturens enkla X.509‑certifikat som en ström i C++."
type: docs
weight: 800
url: /sv/cpp/aspose.pdf.facades/pdffilesignature/extractcertificate/
---
## PdfFileSignature::ExtractCertificate(const System::SharedPtr\<SignatureName\>\&) method


Extraherar signaturens enda X.509‑certifikat som en ström.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Pdf::Facades::PdfFileSignature::ExtractCertificate(const System::SharedPtr<SignatureName> &signName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | Namnet på signaturen. |

### ReturnValue

Om ett certifikat hittas returneras X.509‑enkelt certifikat; annars null.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [SignatureName](../../signaturename/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::ExtractCertificate(const System::String\&) method


Extraherar signaturens enda X.509‑certifikat som en ström.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Pdf::Facades::PdfFileSignature::ExtractCertificate(const System::String &signName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signName | const System::String\& | Namnet på signaturen. |

### ReturnValue

Om certifikatet hittades returneras ett enskilt X.509‑certifikat; annars null.

## Deprecated
Använd ExtractCertificate(SignatureName)-metoden istället.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
