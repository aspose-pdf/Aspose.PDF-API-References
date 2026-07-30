---
title: "Énumération ExplicitDestinationType"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Annotations.ExplicitDestinationType enum. Énumère les types de destinations explicites."
type: docs
weight: 1780
url: /fr/net/aspose.pdf.annotations/explicitdestinationtype/
---
## ExplicitDestinationType enumeration

Énumère les types de destinations explicites.

```csharp
public enum ExplicitDestinationType
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| XYZ | `0` | Affiche la page avec les coordonnées (left, top) positionnées dans le coin supérieur gauche de la fenêtre et le contenu de la page agrandi par le facteur zoom. Une valeur nulle pour l'un des paramètres left, top ou zoom indique que la valeur actuelle de ce paramètre doit être conservée inchangée. Une valeur de zoom de 0 a la même signification qu'une valeur nulle. |
| Fit | `1` | Affiche la page avec son contenu agrandi juste assez pour que la page entière tienne dans la fenêtre à la fois horizontalement et verticalement. Si les facteurs de zoom horizontaux et verticaux requis sont différents, utilisez le plus petit des deux, en centrant la page dans la fenêtre dans l'autre dimension. |
| FitH | `2` | Affiche la page avec la coordonnée verticale top positionnée au bord supérieur de la fenêtre et le contenu de la page agrandi juste assez pour que la largeur totale de la page tienne dans la fenêtre. Une valeur nulle pour top indique que la valeur actuelle de ce paramètre doit être conservée inchangée. |
| FitV | `3` | Affiche la page avec la coordonnée horizontale left positionnée au bord gauche de la fenêtre et le contenu de la page agrandi juste assez pour que la hauteur totale de la page tienne dans la fenêtre. Une valeur nulle pour left indique que la valeur actuelle de ce paramètre doit être conservée inchangée. |
| FitR | `4` | Affiche la page avec son contenu agrandi juste assez pour que le rectangle spécifié par les coordonnées left, bottom, right et top tienne entièrement dans la fenêtre à la fois horizontalement et verticalement. Si les facteurs de zoom horizontaux et verticaux requis sont différents, utilisez le plus petit des deux, en centrant le rectangle dans la fenêtre dans l'autre dimension. Une valeur nulle pour l'un des paramètres peut entraîner un comportement imprévisible. |
| FitB | `5` | Affiche la page avec son contenu agrandi juste assez pour que sa boîte englobante tienne entièrement dans la fenêtre à la fois horizontalement et verticalement. Si les facteurs de zoom horizontaux et verticaux requis sont différents, utilisez le plus petit des deux, en centrant la boîte englobante dans la fenêtre dans l'autre dimension. |
| FitBH | `6` | Affiche la page avec la coordonnée verticale top positionnée au bord supérieur de la fenêtre et le contenu de la page agrandi juste assez pour que la largeur totale de sa boîte englobante tienne dans la fenêtre. Une valeur nulle pour top indique que la valeur actuelle de ce paramètre doit être conservée inchangée. |
| FitBV | `7` | Affiche la page avec la coordonnée horizontale left positionnée au bord gauche de la fenêtre et le contenu de la page agrandi juste assez pour que la hauteur totale de sa boîte englobante tienne dans la fenêtre. Une valeur nulle pour left indique que la valeur actuelle de ce paramètre doit être conservée inchangée. |

### Voir aussi

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


