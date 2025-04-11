---
title: Class RsaAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Security.RsaAlgorithmInfo. Representa una clase para la información sobre el algoritmo de firma RSA
type: docs
weight: 9990
url: /es/net/aspose.pdf.security/rsaalgorithminfo/
---
## Clase RsaAlgorithmInfo

Representa una clase para la información sobre el algoritmo de firma RSA.

```csharp
public sealed class RsaAlgorithmInfo : KeyedSignatureAlgorithmInfo
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
| readonly [KeySize](../../aspose.pdf.security/keyedsignaturealgorithminfo/keysize/) | Obtiene el tamaño de la clave criptográfica utilizada por el algoritmo de firma. |

### Véase también

* clase [KeyedSignatureAlgorithmInfo](../keyedsignaturealgorithminfo/)
* espacio de nombres [Aspose.Pdf.Security](../../aspose.pdf.security/)
* ensamblado [Aspose.PDF](../../)