---
title: PdfFileSignature.Certify
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature method. Certify the document with the MDP signature. Such data as signature reason contact and location must be provided by corresponding properties of the Signature object sig
type: docs
weight: 70
url: /net/aspose.pdf.facades/pdffilesignature/certify/
---
## Certify(int, string, string, string, bool, Rectangle, DocMDPSignature) {#certify}

Certify the document with the MDP signature. Such data as signature reason, contact and location must be provided by corresponding properties of the Signature object sig.

```csharp
public void Certify(int page, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, DocMDPSignature docMdpSignature)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Int32 | The page on which signature is made. |
| SigReason | String | The reason of signature. |
| SigContact | String | The contact of signature. |
| SigLocation | String | The location of signature. |
| visible | Boolean | The visiblity of signature. |
| annotRect | Rectangle | The rect of signature. |
| docMdpSignature | DocMDPSignature | The document MDP type of the signature. |

### See Also

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Certify(string, DocMDPSignature) {#certify_1}

Certify the document with the MDP signature which is placed in already presented signature field. Before signing signature field must be empty, i.e. field must not contain signature dictionary. Thus pdf document already has signature field, you should not supply the place to stamp the signature, corresponding page and rectangle are taken from signature field which is found by signature name (see sigName parameter).

```csharp
public void Certify(string sigName, DocMDPSignature docMdpSignature)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sigName | String | The name of the signature field. |
| docMdpSignature | DocMDPSignature | The type of the signature, could be [`PKCS1`](../../../aspose.pdf.forms/pkcs1/), [`PKCS7`](../../../aspose.pdf.forms/pkcs7/) and [`PKCS7Detached`](../../../aspose.pdf.forms/pkcs7detached/) |

### See Also

* class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


