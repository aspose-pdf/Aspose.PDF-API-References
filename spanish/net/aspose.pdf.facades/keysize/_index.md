---
title: Enum KeySize
second_title: Aspose.PDF for .NET API Reference
description: Enum KeySize de Aspose.Pdf.Facades. Define diferentes tamaños de clave que se pueden usar para cifrar documentos pdf
type: docs
weight: 4390
url: /es/net/aspose.pdf.facades/keysize/
---
## Enumeración KeySize

Define diferentes tamaños de clave que se pueden usar para cifrar documentos pdf.

```csharp
public enum KeySize
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| x40 | `0` | Clave de 40 bits. Tal tamaño de clave se utiliza con el algoritmo RC4 y proporciona un bajo nivel de seguridad. Sin embargo, las versiones antiguas de documentos pdf solo se pueden cifrar con tales claves (v. 1.3 y anteriores); |
| x128 | `1` | Clave de 128 bits. Tanto los algoritmos RC4 como AES pueden usar tal tamaño de clave. |
| x256 | `2` | Clave de 256 bits. Tal tamaño de clave solo se puede usar con AES y es reconocido por las últimas versiones de Adobe Reader (a partir de la v.9). |

### Véase también

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)