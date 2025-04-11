---
title: PdfFileSignature.Certify
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature-metod. Certifiera dokumentet med MDP-signaturen. Sådana data som signaturorsak, kontakt och plats måste tillhandahållas av motsvarande egenskaper hos Signature-objektet sig
type: docs
weight: 70
url: /sv/net/aspose.pdf.facades/pdffilesignature/certify/
---
## Certify(int, string, string, string, bool, Rectangle, DocMDPSignature) {#certify}

Certifiera dokumentet med MDP-signaturen. Sådana data som signaturorsak, kontakt och plats måste tillhandahållas av motsvarande egenskaper hos Signature-objektet sig.

```csharp
public void Certify(int page, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, DocMDPSignature docMdpSignature)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | Int32 | Sidan där signaturen görs. |
| SigReason | String | Anledningen till signaturen. |
| SigContact | String | Kontakten för signaturen. |
| SigLocation | String | Platsen för signaturen. |
| visible | Boolean | Synligheten av signaturen. |
| annotRect | Rectangle | Rektangeln för signaturen. |
| docMdpSignature | DocMDPSignature | Dokumentets MDP-typ av signaturen. |

### Se Även

* klass [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* klass [PdfFileSignature](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Certify(string, DocMDPSignature) {#certify_1}

Certifiera dokumentet med MDP-signaturen som placeras i redan presenterat signaturfält. Innan signeringen måste signaturfältet vara tomt, dvs. fältet får inte innehålla signaturordbok. Eftersom pdf-dokumentet redan har signaturfält, bör du inte ange platsen för att stämpla signaturen, motsvarande sida och rektangel tas från signaturfältet som hittas med signaturnamnet (se sigName-parametern).

```csharp
public void Certify(string sigName, DocMDPSignature docMdpSignature)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sigName | String | Namnet på signaturfältet. |
| docMdpSignature | DocMDPSignature | Typen av signaturen, kan vara [`PKCS1`](../../../aspose.pdf.forms/pkcs1/), [`PKCS7`](../../../aspose.pdf.forms/pkcs7/) och [`PKCS7Detached`](../../../aspose.pdf.forms/pkcs7detached/) |

### Se Även

* klass [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* klass [PdfFileSignature](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)