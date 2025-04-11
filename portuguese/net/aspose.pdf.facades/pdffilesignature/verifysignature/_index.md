---
title: PdfFileSignature.VerifySignature
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileSignature. Verifica a validade de uma assinatura
type: docs
weight: 310
url: /pt/net/aspose.pdf.facades/pdffilesignature/verifysignature/
---
## VerifySignature(SignatureName) {#verifysignature}

Verifica a validade de uma assinatura.

```csharp
public bool VerifySignature(SignatureName signName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| signName | SignatureName | O nome da assinatura. |

### Valor de Retorno

Retorna um resultado do tipo bool.

### Veja Também

* classe [SignatureName](../../signaturename/)
* classe [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, ValidationOptions, out ValidationResult) {#verifysignature_1}

Verifica a validade de uma assinatura.

```csharp
public bool VerifySignature(SignatureName signName, ValidationOptions options, 
    out ValidationResult validationResult)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| signName | SignatureName | O nome da assinatura. |
| options | ValidationOptions | As opções de verificação. |
| validationResult | ValidationResult& | O resultado da validação do certificado. |

### Valor de Retorno

Retorna um resultado do tipo bool.

## Observações

Este método permite verificar o certificado de assinatura usando OCSP e/ou CRL (lista de revogação de certificados) para revogação. Este método não verifica a cadeia de certificados e sua validade, mas verifica se o certificado final foi revogado.

### Veja Também

* classe [SignatureName](../../signaturename/)
* classe [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* classe [ValidationResult](../../../aspose.pdf.security/validationresult/)
* classe [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)