---
title: Class SignatureAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Security.SignatureAlgorithmInfo. Representa una clase para información sobre un algoritmo de firma, incluyendo su tipo, estándar criptográfico y algoritmo de hash de resumen.
type: docs
weight: 10000
url: /es/net/aspose.pdf.security/signaturealgorithminfo/
---
## Clase SignatureAlgorithmInfo

Representa una clase para información sobre un algoritmo de firma, incluyendo su tipo, estándar criptográfico y algoritmo de hash de resumen.

```csharp
public abstract class SignatureAlgorithmInfo
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [SignatureName](../../aspose.pdf.security/signaturealgorithminfo/signaturename/) { get; } | Obtiene el nombre del campo de firma. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [ToString](../../aspose.pdf.security/signaturealgorithminfo/tostring/)() | Convierte el objeto de información actual a su representación en cadena. |

## Campos

| Nombre | Descripción |
| --- | --- |
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | Obtiene el tipo del algoritmo de firma utilizado para firmar el documento PDF. |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Obtiene el estándar criptográfico utilizado para firmar el documento PDF. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Obtiene el algoritmo de hash de resumen utilizado para la firma. Para un sello de tiempo, este es el algoritmo de hash de resumen con el que se firma el hash del contenido del documento. |

### Véase También

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)