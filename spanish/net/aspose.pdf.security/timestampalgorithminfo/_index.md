---
title: Class TimestampAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Security.TimestampAlgorithmInfo. Representa una clase para la información sobre el algoritmo de firma de timestamp
type: docs
weight: 10030
url: /es/net/aspose.pdf.security/timestampalgorithminfo/
---
## Clase TimestampAlgorithmInfo

Representa una clase para la información sobre el algoritmo de firma de timestamp.

```csharp
public sealed class TimestampAlgorithmInfo : SignatureAlgorithmInfo
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
| readonly [ContentHashAlgorithm](../../aspose.pdf.security/timestampalgorithminfo/contenthashalgorithm/) | Obtiene el algoritmo de hash que ha hecho hash del contenido del documento y luego lo ha firmado utilizando [`DigestHashAlgorithm`](../signaturealgorithminfo/digesthashalgorithm/). |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Obtiene el estándar criptográfico utilizado para firmar el documento PDF. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Obtiene el algoritmo de hash de resumen utilizado para la firma. Para un timestamp, este es el algoritmo de hash de resumen con el que se firma el hash del contenido del documento. |

### Véase También

* clase [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* espacio de nombres [Aspose.Pdf.Security](../../aspose.pdf.security/)
* ensamblaje [Aspose.PDF](../../)