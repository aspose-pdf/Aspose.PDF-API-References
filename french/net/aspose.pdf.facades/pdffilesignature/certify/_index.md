---
title: "PdfFileSignature.Certify"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "PdfFileSignature méthode. Certifie le document avec la signature MDP. Des données telles que la raison de la signature, le contact et l'emplacement doivent être fournies par les propriétés correspondantes de l'objet Signature sig"
type: docs
weight: 70
url: /fr/net/aspose.pdf.facades/pdffilesignature/certify/
---
## Certify(int, string, string, string, bool, Rectangle, DocMDPSignature) {#certify}

Certifiez le document avec la signature MDP. Des données telles que la raison de la signature, le contact et le lieu doivent être fournies via les propriétés correspondantes de l'objet Signature sig.

```csharp
public void Certify(int page, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, DocMDPSignature docMdpSignature)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| page | Int32 | La page sur laquelle la signature est faite. |
| SigReason | String | La raison de la signature. |
| SigContact | String | Le contact de la signature. |
| SigLocation | String | Le lieu de la signature. |
| visible | Boolean | La visibilité de la signature. |
| annotRect | Rectangle | Le rectangle de la signature. |
| docMdpSignature | DocMDPSignature | Le type MDP du document de la signature. |

### Voir aussi

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Certify(string, DocMDPSignature) {#certify_1}

Certifiez le document avec la signature MDP qui est placée dans le champ de signature déjà présenté. Avant la signature, le champ de signature doit être vide, c’est‑à‑dire qu’il ne doit pas contenir de dictionnaire de signature. Ainsi le document pdf possède déjà un champ de signature, vous ne devez pas fournir l’emplacement pour apposer la signature, la page et le rectangle correspondants sont pris à partir du champ de signature trouvé par le nom de signature (voir le paramètre sigName).

```csharp
public void Certify(string sigName, DocMDPSignature docMdpSignature)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sigName | String | Le nom du champ de signature. |
| docMdpSignature | DocMDPSignature | Le type de la signature, peut être [`PKCS1`](../../../aspose.pdf.forms/pkcs1/), [`PKCS7`](../../../aspose.pdf.forms/pkcs7/) et [`PKCS7Detached`](../../../aspose.pdf.forms/pkcs7detached/) |

### Voir aussi

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


