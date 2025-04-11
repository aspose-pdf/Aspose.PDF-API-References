---
title: Delegate SignHash
second_title: Aspose.PDF for .NET API Reference
description: Delega per firma personalizzata della hash del documento
type: docs
weight: 5260
url: /it/net/aspose.pdf.forms/signhash/
---
## Delegato SignHash

Delegate per firmare in modo personalizzato l'hash del documento.

```csharp
public delegate byte[] SignHash(byte[] hash, DigestHashAlgorithm digestHashAlgorithm);
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hash | Byte[] | Hash di input del documento. |
| digestHashAlgorithm | DigestHashAlgorithm | L'algoritmo di digestione utilizzato per creare l'hash. Il valore non sarà mai uguale a Auto. |

### Valore di Ritorno

Firma di output.

## Osservazioni

Nota che, sia che la firma digitale sia staccata o meno, l'argomento hash sarà sempre l'hash finale da firmare.

### Vedi Anche

* enum [DigestHashAlgorithm](../../aspose.pdf/digesthashalgorithm/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)