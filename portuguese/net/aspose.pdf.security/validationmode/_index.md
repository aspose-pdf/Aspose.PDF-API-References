---
title: Enum ValidationMode
second_title: Aspose.PDF for .NET API Reference
description: Enum ValidationMode do Aspose.Pdf.Security. Especifica o modo de validação para processos de validação de assinatura PDF
type: docs
weight: 10060
url: /pt/net/aspose.pdf.security/validationmode/
---
## Enumeração ValidationMode

Especifica o modo de validação para processos de validação de assinatura PDF.

```csharp
public enum ValidationMode
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| None | `0` | Representa um modo onde a validação não é realizada. |
| OnlyCheck | `1` | Representa o modo em que a validação é feita, mas seu resultado não afeta a validação da assinatura digital. Você pode verificar o resultado da validação por conta própria. |
| Strict | `2` | Representa o modo em que a validação é feita e seu resultado afeta a validação da assinatura digital. Se o certificado não puder ser verificado, a assinatura digital será considerada inválida. Você pode verificar o resultado da validação por conta própria. |

### Veja Também

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)