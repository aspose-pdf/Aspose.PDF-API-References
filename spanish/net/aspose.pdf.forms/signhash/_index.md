---
title: Delegate SignHash
second_title: Aspose.PDF for .NET API Reference
description: Delegado para firmar el hash del documento de forma personalizada
type: docs
weight: 5260
url: /es/net/aspose.pdf.forms/signhash/
---
## Delegado SignHash

Delegado para firmar el hash del documento de forma personalizada.

```csharp
public delegate byte[] SignHash(byte[] hash, DigestHashAlgorithm digestHashAlgorithm);
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hash | Byte[] | Hash de entrada del documento. |
| digestHashAlgorithm | DigestHashAlgorithm | El algoritmo de resumen utilizado para crear el hash. El valor nunca será igual a Auto. |

### Valor de Retorno

Firma de salida.

## Observaciones

Tenga en cuenta que, ya sea que la firma digital esté separada o no, el argumento hash siempre será el hash final que se firmará.

### Véase También

* enum [DigestHashAlgorithm](../../aspose.pdf/digesthashalgorithm/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)