---
title: "ValidationMethod"
linktitle: "ValidationMethod"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um enum que define o método usado para validação de certificado."
type: docs
weight: 10
url: /pt/java/com.aspose.pdf.security.certificatevalidation/validationmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMethod, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMethod, com.aspose.ms.System.Enum, com.aspose.pdf.security.certificatevalidation.ValidationMethod

```
public final class ValidationMethod extends com.aspose.ms.System.Enum
```

Representa um enum que define o método usado para validação de certificado.

## Campos

| Campo | Descrição |
| --- | --- |
| [All](#All) | Usa todos os métodos disponíveis (OCSP e CRL) para validação de certificados. |
| [Auto](#Auto) | Determina automaticamente o melhor método para validação de certificados. |
| [Crl](#Crl) | Valida certificados usando o método Certificate Revocation List (CRL). |
| [Ocsp](#Ocsp) | Usa o Online Certificate Status Protocol (OCSP) para validação de certificados. OCSP é um protocolo que fornece o status de validação de um certificado consultando diretamente a Autoridade Certificadora (CA) emissora. |

### All {#All}
```
public static final int All
```

Usa todos os métodos disponíveis (OCSP e CRL) para validação de certificados.

### Auto {#Auto}
```
public static final int Auto
```

Determina automaticamente o melhor método para validação de certificados.

### Crl {#Crl}
```
public static final int Crl
```

Valida certificados usando o método Certificate Revocation List (CRL).

### Ocsp {#Ocsp}
```
public static final int Ocsp
```

Usa o Online Certificate Status Protocol (OCSP) para validação de certificados. OCSP é um protocolo que fornece o status de validação de um certificado consultando diretamente a Autoridade Certificadora (CA) emissora.
