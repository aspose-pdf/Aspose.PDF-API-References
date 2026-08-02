---
title: "PdfFileSignature.TryExtractCertificate"
second_title: "Referência da API Aspose.PDF para .NET"
description: "Método PdfFileSignature. Extrai o certificado X.509 único da assinatura."
type: docs
weight: 310
url: /pt/net/aspose.pdf.facades/pdffilesignature/tryextractcertificate/
---
## TryExtractCertificate(SignatureName, out X509Certificate2) {#tryextractcertificate_1}

Extrai o certificado X.509 único da assinatura.

```csharp
public bool TryExtractCertificate(SignatureName signName, out X509Certificate2 certificate)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| signName | SignatureName | O nome da assinatura. |
| certificate | X509Certificate2& | Se um certificado for encontrado, retorna o objeto de certificado X.509 único; caso contrário, null. |

### Valor de retorno

Um certificado verdadeiro foi encontrado.

### Veja Também

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtractCertificate(SignatureName, out Stream) {#tryextractcertificate}

Extrai o certificado X.509 único da assinatura como um fluxo.

```csharp
public bool TryExtractCertificate(SignatureName signName, out Stream stream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| signName | SignatureName | O nome da assinatura. |
| stream | Stream& | Se um certificado for encontrado, retorna o fluxo de certificado único X.509; caso contrário, null. |

### Valor de retorno

Um certificado verdadeiro foi encontrado.

### Veja Também

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


