---
title: Class RsaAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Security.RsaAlgorithmInfo. Représente une classe pour les informations sur l'algorithme de signature RSA
type: docs
weight: 9990
url: /fr/net/aspose.pdf.security/rsaalgorithminfo/
---
## Classe RsaAlgorithmInfo

Représente une classe pour les informations sur l'algorithme de signature RSA.

```csharp
public sealed class RsaAlgorithmInfo : KeyedSignatureAlgorithmInfo
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
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | Obtient la norme cryptographique utilisée pour signer le document PDF. |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Obtient l'algorithme de hachage de résumé utilisé pour la signature. Pour un horodatage, c'est l'algorithme de hachage de résumé avec lequel le hachage du contenu du document est signé. |
| readonly [KeySize](../../aspose.pdf.security/keyedsignaturealgorithminfo/keysize/) | Obtient la taille de la clé cryptographique utilisée par l'algorithme de signature. |

### Voir aussi

* classe [KeyedSignatureAlgorithmInfo](../keyedsignaturealgorithminfo/)
* espace de noms [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)