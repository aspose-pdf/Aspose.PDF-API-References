---
title: "Classe DsaAlgorithmInfo"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Security.DsaAlgorithmInfo classe. Représente une classe contenant les informations sur l'algorithme de signature DSA."
type: docs
weight: 10120
url: /fr/net/aspose.pdf.security/dsaalgorithminfo/
---
## DsaAlgorithmInfo class

Représente une classe contenant les informations sur l'algorithme de signature DSA.

```csharp
public sealed class DsaAlgorithmInfo : KeyedSignatureAlgorithmInfo
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
| readonly [KeySize](../../aspose.pdf.security/keyedsignaturealgorithminfo/keysize/) | Obtient la taille de la clé cryptographique utilisée par l'algorithme de signature. |

### Voir aussi

* class [KeyedSignatureAlgorithmInfo](../keyedsignaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


