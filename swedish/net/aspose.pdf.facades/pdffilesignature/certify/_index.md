---
title: "PdfFileSignature.Certify"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileSignature‑metod. Certifiera dokumentet med MDP‑signaturen. Sådana data som signaturorsak, kontakt och plats måste tillhandahållas av motsvarande egenskaper i Signature‑objektet sig."
type: docs
weight: 70
url: /sv/net/aspose.pdf.facades/pdffilesignature/certify/
---
## Certify(int, string, string, string, bool, Rectangle, DocMDPSignature) {#certify}

Certifiera dokumentet med MDP-signaturen. Sådan data som signaturens anledning, kontakt och plats måste tillhandahållas via motsvarande egenskaper i Signature-objektet sig.

```csharp
public void Certify(int page, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, DocMDPSignature docMdpSignature)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | Int32 | Sidan där signaturen görs. |
| SigReason | String | Anledningen till signaturen. |
| SigContact | String | Kontakt för signaturen. |
| SigLocation | String | Plats för signaturen. |
| synlig | Boolean | Synligheten för signaturen. |
| annotRect | Rectangle | Rektangeln för signaturen. |
| docMdpSignature | DocMDPSignature | Dokumentets MDP‑typ för signaturen. |

### Se även

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Certify(string, DocMDPSignature) {#certify_1}

Certifiera dokumentet med MDP-signaturen som placeras i ett redan presenterat signaturfält. Innan signering måste signaturfältet vara tomt, d.v.s. fältet får inte innehålla en signaturdictionary. Således har pdf-dokumentet redan ett signaturfält, du ska inte ange platsen för att stämpla signaturen; motsvarande sida och rektangel tas från signaturfältet som hittas via signaturnamnet (se parametern sigName).

```csharp
public void Certify(string sigName, DocMDPSignature docMdpSignature)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sigName | String | Namnet på signaturfältet. |
| docMdpSignature | DocMDPSignature | Typen av signaturen, kan vara [`PKCS1`](../../../aspose.pdf.forms/pkcs1/), [`PKCS7`](../../../aspose.pdf.forms/pkcs7/) och [`PKCS7Detached`](../../../aspose.pdf.forms/pkcs7detached/) |

### Se även

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


