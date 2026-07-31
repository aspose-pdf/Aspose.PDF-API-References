---
title: "Delegato SignHash"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Delegato per la firma personalizzata dell'hash del documento"
type: docs
weight: 5380
url: /it/net/aspose.pdf.forms/signhash/
---
## SignHash delegate

Delegato per la firma personalizzata dell'hash del documento.

```csharp
public delegate byte[] SignHash(byte[] hash, DigestHashAlgorithm digestHashAlgorithm);
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hash | Byte[] | Hash di input del documento. |
| digestHashAlgorithm | DigestHashAlgorithm | L'algoritmo di digest utilizzato per creare l'hash. Il valore non sarà mai uguale a Auto. |

### Valore di ritorno

Firma di output.

## Osservazioni

Nota che, indipendentemente dal fatto che la firma digitale sia separata o meno, l'argomento hash sarà sempre l'hash finale da firmare.

### Vedi anche

* enum [DigestHashAlgorithm](../../aspose.pdf/digesthashalgorithm/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


