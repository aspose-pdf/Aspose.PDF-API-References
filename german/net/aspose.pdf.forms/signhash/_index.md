---
title: Delegate SignHash
second_title: Aspose.PDF for .NET API Reference
description: Delegate für benutzerdefiniertes Signieren des Dokumenten-Hashes
type: docs
weight: 5260
url: /de/net/aspose.pdf.forms/signhash/
---
## SignHash-Delegate

Delegate für benutzerdefiniertes Signieren des Dokumenten-Hashes.

```csharp
public delegate byte[] SignHash(byte[] hash, DigestHashAlgorithm digestHashAlgorithm);
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hash | Byte[] | Eingabe-Hash des Dokuments. |
| digestHashAlgorithm | DigestHashAlgorithm | Der verwendete Digest-Algorithmus zur Erstellung des Hashs. Der Wert wird niemals gleich Auto sein. |

### Rückgabewert

Ausgangs-Signatur.

## Anmerkungen

Beachten Sie, dass der Hash-Parameter, unabhängig davon, ob die digitale Signatur getrennt ist oder nicht, immer der endgültige Hash sein wird, der signiert werden soll.

### Siehe auch

* enum [DigestHashAlgorithm](../../aspose.pdf/digesthashalgorithm/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)