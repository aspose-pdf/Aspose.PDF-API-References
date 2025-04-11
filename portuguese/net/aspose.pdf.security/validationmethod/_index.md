---
title: Enum ValidationMethod
second_title: Aspose.PDF for .NET API Reference
description: Enum ValidationMethod do Aspose.Pdf.Security. Representa um enum que define o método usado para validação de certificados
type: docs
weight: 10050
url: /pt/net/aspose.pdf.security/validationmethod/
---
## Enumeração ValidationMethod

Representa um enum que define o método usado para validação de certificados.

```csharp
public enum ValidationMethod
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Auto | `0` | Determina automaticamente o melhor método para validação de certificados. |
| Ocsp | `1` | Usa o Protocolo de Status de Certificado Online (OCSP) para validação de certificados. OCSP é um protocolo que fornece o status de validação de um certificado consultando diretamente a Autoridade Certificadora (CA) emissora. |
| Crl | `2` | Valida certificados usando o método da Lista de Revogação de Certificados (CRL). |
| All | `3` | Usa todos os métodos disponíveis (OCSP e CRL) para validação de certificados. |

### Veja Também

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)