---
title: PdfFileSignature.Certify
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileSignature. Certifique o documento com a assinatura MDP. Dados como motivo da assinatura, contato e localização devem ser fornecidos pelas propriedades correspondentes do objeto Signature sig
type: docs
weight: 70
url: /pt/net/aspose.pdf.facades/pdffilesignature/certify/
---
## Certify(int, string, string, string, bool, Rectangle, DocMDPSignature) {#certify}

Certifique o documento com a assinatura MDP. Dados como motivo da assinatura, contato e localização devem ser fornecidos pelas propriedades correspondentes do objeto Signature sig.

```csharp
public void Certify(int page, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, DocMDPSignature docMdpSignature)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| page | Int32 | A página na qual a assinatura é feita. |
| SigReason | String | O motivo da assinatura. |
| SigContact | String | O contato da assinatura. |
| SigLocation | String | A localização da assinatura. |
| visible | Boolean | A visibilidade da assinatura. |
| annotRect | Rectangle | O retângulo da assinatura. |
| docMdpSignature | DocMDPSignature | O tipo de assinatura MDP do documento. |

### Veja Também

* classe [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* classe [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Certify(string, DocMDPSignature) {#certify_1}

Certifique o documento com a assinatura MDP que está colocada em um campo de assinatura já apresentado. Antes de assinar, o campo de assinatura deve estar vazio, ou seja, o campo não deve conter um dicionário de assinatura. Assim, o documento pdf já possui um campo de assinatura, você não deve fornecer o local para carimbar a assinatura, a página correspondente e o retângulo são retirados do campo de assinatura que é encontrado pelo nome da assinatura (veja o parâmetro sigName).

```csharp
public void Certify(string sigName, DocMDPSignature docMdpSignature)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sigName | String | O nome do campo de assinatura. |
| docMdpSignature | DocMDPSignature | O tipo da assinatura, pode ser [`PKCS1`](../../../aspose.pdf.forms/pkcs1/), [`PKCS7`](../../../aspose.pdf.forms/pkcs7/) e [`PKCS7Detached`](../../../aspose.pdf.forms/pkcs7detached/) |

### Veja Também

* classe [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* classe [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)