---
title: "Classe TimestampAlgorithmInfo"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Security.TimestampAlgorithmInfo class. Représente une classe contenant les informations sur l'algorithme de signature de timestamp"
type: docs
weight: 10210
url: /fr/net/aspose.pdf.security/timestampalgorithminfo/
---
## TimestampAlgorithmInfo class

Représente une classe contenant les informations sur l'algorithme de signature de timestamp.

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
| readonly [ContentHashAlgorithm](../../aspose.pdf.security/timestampalgorithminfo/contenthashalgorithm/) | Obtient l'algorithme de hachage qui a haché le contenu du document puis l'a signé en utilisant [`DigestHashAlgorithm`](../signaturealgorithminfo/digesthashalgorithm/). |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Obtient la norme cryptographique utilisée pour signer le document PDF. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Obtient l'algorithme de hachage de digest utilisé pour la signature. Pour un horodatage, il s'agit de l'algorithme de hachage de digest avec lequel le hachage du contenu du document est signé. |

### Voir aussi

* class [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


