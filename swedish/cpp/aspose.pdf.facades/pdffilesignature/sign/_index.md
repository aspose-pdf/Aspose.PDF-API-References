---
title: "Aspose::Pdf::Facades::PdfFileSignature::Sign metod"
linktitle: "Signera"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileSignature::Sign metod. Signera dokumentet med den angivna typ av signatur som placeras i ett redan befintligt signaturfält. Före signering måste signaturfältet vara tomt, d.v.s. fältet får inte innehålla signatur‑dictionary. Således har pdf-dokumentet redan ett signaturfält, du bör inte ange platsen för att stämpla signaturen, motsvarande sida och rektangel tas från signaturfältet som hittas via signaturnamnet (se SigName‑parameter). Sådana data som signaturorsak, kontakt och plats måste tillhandahållas av motsvarande egenskaper i Signature‑objektet sig i C++."
type: docs
weight: 3600
url: /sv/cpp/aspose.pdf.facades/pdffilesignature/sign/
---
## PdfFileSignature::Sign(const System::String\&, const System::SharedPtr\<Forms::Signature\>\&) method


Signera dokumentet med den angivna typens signatur som placeras i ett redan presenterat signaturfält. Före signering måste signaturfältet vara tomt, d.v.s. fältet får inte innehålla en signaturordbok. Således har PDF‑dokumentet redan ett signaturfält, du bör inte ange platsen för att stämpla signaturen; motsvarande sida och rektangel tas från signaturfältet som hittas via signaturens namn (se SigName parameter). Sådan data som signaturorsak, kontakt och plats måste tillhandahållas via motsvarande egenskaper i Signature‑objektet sig.

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Sign(const System::String &SigName, const System::SharedPtr<Forms::Signature> &sig)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| SigName | const System::String\& | Namnet på signaturfältet. |
| sig | const System::SharedPtr\<Forms::Signature\>\& | Typen av signaturen kan vara PKCS1 (Pkcs1Signature-objekt), PKCS7 och PKCS7 detached (Pkcs7Signature-objekt) |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../../aspose.pdf.forms/signature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::Sign(const System::String\&, const System::String\&, const System::String\&, const System::String\&, const System::SharedPtr\<Forms::Signature\>\&) method


Signera dokumentet med den angivna typens signatur som placeras i ett redan presenterat signaturfält. Före signering måste signaturfältet vara tomt, d.v.s. fältet får inte innehålla en signaturordbok. Således har PDF‑dokumentet redan ett signaturfält, du bör inte ange platsen för att stämpla signaturen; motsvarande sida och rektangel tas från signaturfältet som hittas via signaturens namn (se SigName parameter).

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Sign(const System::String &SigName, const System::String &SigReason, const System::String &SigContact, const System::String &SigLocation, const System::SharedPtr<Forms::Signature> &sig)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| SigName | const System::String\& | Namnet på signaturfältet. |
| SigReason | const System::String\& | Anledningen till signaturen. |
| SigContact | const System::String\& | Kontakt för signaturen. |
| SigLocation | const System::String\& | Plats för signaturen. |
| sig | const System::SharedPtr\<Forms::Signature\>\& | Typen av signaturen kan vara PKCS1, PKCS7 och PKCS7Detached. |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../../aspose.pdf.forms/signature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::Sign(int32_t, bool, System::Drawing::Rectangle, const System::SharedPtr\<Forms::Signature\>\&) method


Signera dokumentet med den angivna typens signatur.

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Sign(int32_t page, bool visible, System::Drawing::Rectangle annotRect, const System::SharedPtr<Forms::Signature> &sig)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | int32_t | Sidnumret där signaturen görs. |
| visible | bool | Synligheten för signaturen. |
| annotRect | System::Drawing::Rectangle | Rektangeln för signaturen. |
| sig | const System::SharedPtr\<Forms::Signature\>\& | Typen av signaturen kan vara PKCS1, PKCS7 och PKCS7Detached. Sådan data som signaturorsak, kontakt och plats måste redan finnas i detta objekt (se motsvarande egenskaper). |

## Se även

* Class [Rectangle](../../../system.drawing/rectangle/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../../aspose.pdf.forms/signature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::Sign(int32_t, const System::String\&, const System::String\&, const System::String\&, const System::String\&, bool, System::Drawing::Rectangle, const System::SharedPtr\<Forms::Signature\>\&) method


Signera dokumentet med den angivna typens signatur som placeras i ett redan presenterat signaturfält. Före signering bör PDF‑dokumentet redan ha ett signaturfält; motsvarande sida och rektangel tas från signaturfältet som hittas via signaturens namn (se SigName parameter).

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Sign(int32_t page, const System::String &SigName, const System::String &SigReason, const System::String &SigContact, const System::String &SigLocation, bool visible, System::Drawing::Rectangle annotRect, const System::SharedPtr<Forms::Signature> &sig)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | int32_t | Sidnumret där signaturen görs. |
| SigName | const System::String\& | Namnet på signaturfältet. |
| SigReason | const System::String\& | Anledningen till signaturen. |
| SigContact | const System::String\& | Kontakt för signaturen. |
| SigLocation | const System::String\& | Plats för signaturen. |
| visible | bool | Synligheten för signaturen. |
| annotRect | System::Drawing::Rectangle | Rektangeln för signaturen. |
| sig | const System::SharedPtr\<Forms::Signature\>\& | Typen av signaturen kan vara PKCS1, PKCS7 och PKCS7Detached. |

## Se även

* Class [String](../../../system/string/)
* Class [Rectangle](../../../system.drawing/rectangle/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../../aspose.pdf.forms/signature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::Sign(int32_t, const System::String\&, const System::String\&, const System::String\&, bool, System::Drawing::Rectangle) method


Skapa en signatur i PDF‑dokumentet.

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Sign(int32_t page, const System::String &SigReason, const System::String &SigContact, const System::String &SigLocation, bool visible, System::Drawing::Rectangle annotRect)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | int32_t | Sidnumret där signaturen görs. |
| SigReason | const System::String\& | Anledningen till signaturen. |
| SigContact | const System::String\& | Kontakt för signaturen. |
| SigLocation | const System::String\& | Plats för signaturen. |
| visible | bool | Synligheten för signaturen. |
| annotRect | System::Drawing::Rectangle | Rektangeln för signaturen. |

## Se även

* Class [String](../../../system/string/)
* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::Sign(int32_t, const System::String\&, const System::String\&, const System::String\&, bool, System::Drawing::Rectangle, const System::SharedPtr\<Forms::Signature\>\&) method


Signera dokumentet med den angivna typens signatur.

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Sign(int32_t page, const System::String &SigReason, const System::String &SigContact, const System::String &SigLocation, bool visible, System::Drawing::Rectangle annotRect, const System::SharedPtr<Forms::Signature> &sig)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | int32_t | Sidnumret där signaturen görs. |
| SigReason | const System::String\& | Anledningen till signaturen. |
| SigContact | const System::String\& | Kontakt för signaturen. |
| SigLocation | const System::String\& | Plats för signaturen. |
| visible | bool | Synligheten för signaturen. |
| annotRect | System::Drawing::Rectangle | Rektangeln för signaturen. |
| sig | const System::SharedPtr\<Forms::Signature\>\& | Typen av signaturen kan vara PKCS1, PKCS7 och PKCS7Detached. |

## Se även

* Class [String](../../../system/string/)
* Class [Rectangle](../../../system.drawing/rectangle/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../../aspose.pdf.forms/signature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
