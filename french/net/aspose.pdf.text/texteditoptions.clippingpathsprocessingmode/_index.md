---
title: "Énumération TextEditOptions.ClippingPathsProcessingMode"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Énumération Aspose.Pdf.Text.TextEditOptionsClippingPathsProcessingMode. Modes de traitement des chemins de découpe"
type: docs
weight: 11010
url: /fr/net/aspose.pdf.text/texteditoptions.clippingpathsprocessingmode/
---
## TextEditOptions.ClippingPathsProcessingMode enumeration

Modes de traitement des chemins de découpe

```csharp
public enum ClippingPathsProcessingMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| KeepIntact | `0` | Conserve les chemins de découpe de la mise en page de la page originale. (Par défaut) |
| Expand | `1` | Le chemin de découpe original sera agrandi dans le cas où le texte modifié nécessite plus d'espace. |
| Remove | `2` | Le chemin de découpe original sera supprimé dans le cas où le texte modifié nécessite plus d'espace. Attention : comme les chemins de découpe peuvent interagir entre eux, leur suppression peut entraîner un résultat inattendu sur la mise en page de la page. |

### Voir aussi

* class [TextEditOptions](../texteditoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


