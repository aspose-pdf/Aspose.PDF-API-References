---
title: "Aspose::Pdf::Facades::PdfFileSignature::ExtractImage metod"
linktitle: "ExtractImage"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileSignature::ExtractImage metod. Extraherar signaturens bild i C++."
type: docs
weight: 900
url: /sv/cpp/aspose.pdf.facades/pdffilesignature/extractimage/
---
## PdfFileSignature::ExtractImage(const System::SharedPtr\<SignatureName\>\&) method


Extraherar signaturens bild.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Pdf::Facades::PdfFileSignature::ExtractImage(const System::SharedPtr<SignatureName> &signName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signName | const System::SharedPtr\<SignatureName\>\& | Namnet på signaturen. |

### ReturnValue

Om bilden hittades framgångsrikt returneras strömobjektet; annars null.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [SignatureName](../../signaturename/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::ExtractImage(const System::String\&) method


Extraherar signaturens bild.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Pdf::Facades::PdfFileSignature::ExtractImage(const System::String &signName)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signName | const System::String\& | Namnet på signaturen. |

### ReturnValue

Om bilden hittades framgångsrikt returneras strömobjektet; annars null.

## Deprecated
Använd metoden ExtractImage(SignatureName) istället.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
