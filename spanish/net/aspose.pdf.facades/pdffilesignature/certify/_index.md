---
title: PdfFileSignature.Certify
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileSignature. Certifique el documento con la firma MDP. Se deben proporcionar datos como el motivo de la firma, el contacto y la ubicación a través de las propiedades correspondientes del objeto Signature sig.
type: docs
weight: 70
url: /es/net/aspose.pdf.facades/pdffilesignature/certify/
---
## Certify(int, string, string, string, bool, Rectangle, DocMDPSignature) {#certify}

Certifique el documento con la firma MDP. Se deben proporcionar datos como el motivo de la firma, el contacto y la ubicación a través de las propiedades correspondientes del objeto Signature sig.

```csharp
public void Certify(int page, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, DocMDPSignature docMdpSignature)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | Int32 | La página en la que se realiza la firma. |
| SigReason | String | El motivo de la firma. |
| SigContact | String | El contacto de la firma. |
| SigLocation | String | La ubicación de la firma. |
| visible | Boolean | La visibilidad de la firma. |
| annotRect | Rectangle | El rectángulo de la firma. |
| docMdpSignature | DocMDPSignature | El tipo de firma MDP del documento. |

### Ver También

* clase [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* clase [PdfFileSignature](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## Certify(string, DocMDPSignature) {#certify_1}

Certifique el documento con la firma MDP que se coloca en el campo de firma ya presentado. Antes de firmar, el campo de firma debe estar vacío, es decir, el campo no debe contener un diccionario de firma. Así, el documento pdf ya tiene un campo de firma, no debe proporcionar el lugar para estampar la firma, la página correspondiente y el rectángulo se toman del campo de firma que se encuentra por el nombre de la firma (ver parámetro sigName).

```csharp
public void Certify(string sigName, DocMDPSignature docMdpSignature)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sigName | String | El nombre del campo de firma. |
| docMdpSignature | DocMDPSignature | El tipo de la firma, podría ser [`PKCS1`](../../../aspose.pdf.forms/pkcs1/), [`PKCS7`](../../../aspose.pdf.forms/pkcs7/) y [`PKCS7Detached`](../../../aspose.pdf.forms/pkcs7detached/) |

### Ver También

* clase [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* clase [PdfFileSignature](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)