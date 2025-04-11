---
title: Delegate SignHash
second_title: Aspose.PDF for .NET API Reference
description: Délégué pour signer de manière personnalisée le hachage du document
type: docs
weight: 5260
url: /fr/net/aspose.pdf.forms/signhash/
---
## Délégué SignHash

Délégué pour signer de manière personnalisée le hachage du document.

```csharp
public delegate byte[] SignHash(byte[] hash, DigestHashAlgorithm digestHashAlgorithm);
```

| Paramètre | Type | Description |
| --- | --- | --- |
| hash | Byte[] | Hachage d'entrée du document. |
| digestHashAlgorithm | DigestHashAlgorithm | L'algorithme de hachage utilisé pour créer le hachage. La valeur ne sera jamais égale à Auto. |

### Valeur de retour

Signature de sortie.

## Remarques

Notez que, que la signature numérique soit détachée ou non, l'argument de hachage sera toujours le hachage final à signer.

### Voir aussi

* enum [DigestHashAlgorithm](../../aspose.pdf/digesthashalgorithm/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)