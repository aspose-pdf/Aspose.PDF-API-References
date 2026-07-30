---
title: "Classe EcdsaAlgorithmInfo"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Security.EcdsaAlgorithmInfo. Représente une classe contenant les informations sur l'algorithme de signature ECDSA"
type: docs
weight: 10130
url: /fr/net/aspose.pdf.security/ecdsaalgorithminfo/
---
## EcdsaAlgorithmInfo class

Représente une classe contenant les informations sur l'algorithme de signature ECDSA.

```csharp
public sealed class EcdsaAlgorithmInfo : KeyedSignatureAlgorithmInfo
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
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | Obtient l'algorithme de hachage de digest utilisé pour la signature. Pour un horodatage, il s'agit de l'algorithme de hachage de digest avec lequel le hachage du contenu du document est signé. |
| readonly [EccName](../../aspose.pdf.security/ecdsaalgorithminfo/eccname/) | Obtient le nom de la courbe elliptique utilisée par l'ECDSA. |
| readonly [KeySize](../../aspose.pdf.security/keyedsignaturealgorithminfo/keysize/) | Obtient la taille de la clé cryptographique utilisée par l'algorithme de signature. |

### Voir aussi

* class [KeyedSignatureAlgorithmInfo](../keyedsignaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


