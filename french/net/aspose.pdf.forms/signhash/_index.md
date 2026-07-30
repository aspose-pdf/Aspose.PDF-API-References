---
title: "Délégué SignHash"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Délégué pour signer de façon personnalisée le hachage du document"
type: docs
weight: 5380
url: /fr/net/aspose.pdf.forms/signhash/
---
## SignHash delegate

Délégué pour signer de façon personnalisée le hachage du document.

```csharp
public delegate byte[] SignHash(byte[] hash, DigestHashAlgorithm digestHashAlgorithm);
```

| Paramètre | Type | Description |
| --- | --- | --- |
| hachage | Byte[] | Hachage d'entrée du document. |
| digestHashAlgorithm | DigestHashAlgorithm | L'algorithme de hachage utilisé pour créer le hachage. La valeur ne sera jamais égale à Auto. |

### Valeur de retour

Signature de sortie.

## Remarques

Notez que, que la signature numérique soit détachée ou non, l'argument hachage sera toujours le hachage final à signer.

### Voir aussi

* enum [DigestHashAlgorithm](../../aspose.pdf/digesthashalgorithm/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


