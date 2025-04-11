---
title: PdfFileSignature.Certify
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileSignature. Certifiez le document avec la signature MDP. Des données telles que le motif de la signature, le contact et l'emplacement doivent être fournies par les propriétés correspondantes de l'objet Signature sig
type: docs
weight: 70
url: /fr/net/aspose.pdf.facades/pdffilesignature/certify/
---
## Certify(int, string, string, string, bool, Rectangle, DocMDPSignature) {#certify}

Certifiez le document avec la signature MDP. Des données telles que le motif de la signature, le contact et l'emplacement doivent être fournies par les propriétés correspondantes de l'objet Signature sig.

```csharp
public void Certify(int page, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, DocMDPSignature docMdpSignature)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| page | Int32 | La page sur laquelle la signature est faite. |
| SigReason | String | Le motif de la signature. |
| SigContact | String | Le contact de la signature. |
| SigLocation | String | L'emplacement de la signature. |
| visible | Boolean | La visibilité de la signature. |
| annotRect | Rectangle | Le rectangle de la signature. |
| docMdpSignature | DocMDPSignature | Le type de signature MDP du document. |

### Voir aussi

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Certify(string, DocMDPSignature) {#certify_1}

Certifiez le document avec la signature MDP qui est placée dans le champ de signature déjà présenté. Avant de signer, le champ de signature doit être vide, c'est-à-dire que le champ ne doit pas contenir de dictionnaire de signature. Ainsi, le document pdf a déjà un champ de signature, vous ne devez pas fournir l'emplacement pour apposer la signature, la page correspondante et le rectangle sont pris du champ de signature qui est trouvé par le nom de la signature (voir le paramètre sigName).

```csharp
public void Certify(string sigName, DocMDPSignature docMdpSignature)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sigName | String | Le nom du champ de signature. |
| docMdpSignature | DocMDPSignature | Le type de la signature, pourrait être [`PKCS1`](../../../aspose.pdf.forms/pkcs1/), [`PKCS7`](../../../aspose.pdf.forms/pkcs7/) et [`PKCS7Detached`](../../../aspose.pdf.forms/pkcs7detached/) |

### Voir aussi

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)