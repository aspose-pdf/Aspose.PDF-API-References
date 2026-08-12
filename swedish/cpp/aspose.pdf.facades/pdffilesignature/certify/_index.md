---
title: "Aspose::Pdf::Facades::PdfFileSignature::Certify metod"
linktitle: "Certify"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileSignature::Certify metod. Certifiera dokumentet med MDP‑signaturen som placeras i ett redan befintligt signaturfält. Innan signering måste signaturfältet vara tomt, d.v.s. fältet får inte innehålla en signatur‑dictionary. Eftersom pdf‑dokumentet redan har ett signaturfält bör du inte ange platsen för att stämpla signaturen; motsvarande sida och rektangel tas från signaturfältet som hittas via signaturnamnet (se parametern sigName) i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.pdf.facades/pdffilesignature/certify/
---
## PdfFileSignature::Certify(const System::String\&, const System::SharedPtr\<Forms::DocMDPSignature\>\&) method


Certifiera dokumentet med MDP‑signaturen som är placerad i ett redan befintligt signaturfält. Innan signering måste signaturfältet vara tomt, d.v.s. fältet får inte innehålla en signatur‑dictionary. Således har pdf‑dokumentet redan ett signaturfält; du ska inte ange platsen för att stämpla signaturen, motsvarande sida och rektangel tas från signaturfältet som hittas via signaturnamnet (se parametern sigName).

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Certify(const System::String &sigName, const System::SharedPtr<Forms::DocMDPSignature> &docMdpSignature)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sigName | const System::String\& | Namnet på signaturfältet. |
| docMdpSignature | const System::SharedPtr\<Forms::DocMDPSignature\>\& | Typen av signaturen, kan vara [Aspose::Pdf::Forms::PKCS1](../../../aspose.pdf.forms/pkcs1/), [Aspose::Pdf::Forms::PKCS7](../../../aspose.pdf.forms/pkcs7/) och [Aspose::Pdf::Forms::PKCS7Detached](../../../aspose.pdf.forms/pkcs7detached/) |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::Certify(int32_t, const System::String\&, const System::String\&, const System::String\&, bool, System::Drawing::Rectangle, const System::SharedPtr\<Forms::DocMDPSignature\>\&) method


Certifiera dokumentet med MDP‑signaturen. Sådana data som signaturorsak, kontakt och plats måste tillhandahållas via motsvarande egenskaper i Signature‑objektet sig.

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Certify(int32_t page, const System::String &SigReason, const System::String &SigContact, const System::String &SigLocation, bool visible, System::Drawing::Rectangle annotRect, const System::SharedPtr<Forms::DocMDPSignature> &docMdpSignature)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | int32_t | Sidan där signaturen görs. |
| SigReason | const System::String\& | Anledningen till signaturen. |
| SigContact | const System::String\& | Kontakt för signaturen. |
| SigLocation | const System::String\& | Plats för signaturen. |
| visible | bool | Synligheten för signaturen. |
| annotRect | System::Drawing::Rectangle | Rektangeln för signaturen. |
| docMdpSignature | const System::SharedPtr\<Forms::DocMDPSignature\>\& | Dokumentets MDP-typ för signaturen. |

## Se även

* Class [String](../../../system/string/)
* Class [Rectangle](../../../system.drawing/rectangle/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
