---
title: Class TimestampAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Security.TimestampAlgorithmInfo. Représente une classe pour les informations sur l'algorithme de signature de timestamp
type: docs
weight: 10030
url: /fr/net/aspose.pdf.security/timestampalgorithminfo/
---
## Classe TimestampAlgorithmInfo

Représente une classe pour les informations sur l'algorithme de signature de timestamp.

```csharp
public sealed class TimestampAlgorithmInfo : SignatureAlgorithmInfo
```

## Propriétés

| Nom | Description |
| --- | --- |
| [SignatureName](../../aspose.pdf.security/signaturealgorithminfo/signaturename/) { get; } | Obtient le nom du champ de signature. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [ToString](../../aspose.pdf.security/signaturealgorithminfo/tostring/)() | Convertit l'objet d'information actuel en sa représentation sous forme de chaîne. |

## Champs

| Nom | Description |
| --- | --- |
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | Obtient le type de l'algorithme de signature utilisé pour signer le document PDF. |
| readonly [ContentHashAlgorithm](../../aspose.pdf.security/timestampalgorithminfo/contenthashalgorithm/) | Obtient l'algorithme de hachage qui a haché le contenu du document et l'a ensuite signé en utilisant [`DigestHashAlgorithm`](../signaturealgorithminfo/digesthashalgorithm/). |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Obtient la norme cryptographique utilisée pour signer le document PDF. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Obtient l'algorithme de hachage de résumé utilisé pour la signature. Pour un timestamp, il s'agit de l'algorithme de hachage de résumé avec lequel le hachage du contenu du document est signé. |

### Voir aussi

* classe [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* espace de noms [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)