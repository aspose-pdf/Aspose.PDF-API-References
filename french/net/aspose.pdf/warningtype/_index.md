---
title: "Énumération WarningType"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.WarningType enum. Type d'avertissement représenté par l'énumération"
type: docs
weight: 11480
url: /fr/net/aspose.pdf/warningtype/
---
## WarningType enumeration

L'énumération représente le type d'avertissement.

```csharp
public enum WarningType
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| SourceFileCorruption | `0` | Le fichier est corrompu. |
| DataLoss | `1` | Le texte, le graphique, l'image ou d'autres données sont complètement manquants soit de l'arbre du document après le chargement, soit du document créé après l'enregistrement. |
| MajorFormattingLoss | `2` | Pertes de mise en forme majeures par rapport au document original. Ceci s'applique aux cas où la perte de mise en forme est importante mais que les données sont toujours présentes. |
| MinorFormattingLoss | `3` | Pertes de mise en forme mineures par rapport au document original. Ceci concerne les pertes mineures de fidélité. |
| CompatibilityIssue | `4` | Problème connu qui empêchera le document d'être ouvert par certains agents utilisateurs, ou par des versions antérieures d'agents utilisateurs. |
| InvalidInputStreamType | `5` | Type de flux d'entrée invalide |
| UnexpectedContent | `99` | Le fichier contient un contenu inattendu. |

### Voir aussi

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


