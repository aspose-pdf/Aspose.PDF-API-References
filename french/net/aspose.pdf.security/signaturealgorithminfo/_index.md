---
title: Class SignatureAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Security.SignatureAlgorithmInfo. Représente une classe pour des informations sur un algorithme de signature, y compris son type, son standard cryptographique et son algorithme de hachage de résumé.
type: docs
weight: 10000
url: /fr/net/aspose.pdf.security/signaturealgorithminfo/
---
## Classe SignatureAlgorithmInfo

Représente une classe pour des informations sur un algorithme de signature, y compris son type, son standard cryptographique et son algorithme de hachage de résumé.

```csharp
public abstract class SignatureAlgorithmInfo
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
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Obtient le standard cryptographique utilisé pour signer le document PDF. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Obtient l'algorithme de hachage de résumé utilisé pour la signature. Pour un horodatage, il s'agit de l'algorithme de hachage de résumé avec lequel le hachage du contenu du document est signé. |

### Voir aussi

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)