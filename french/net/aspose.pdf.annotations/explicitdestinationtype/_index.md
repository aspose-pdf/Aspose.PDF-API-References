---
title: Enum ExplicitDestinationType
second_title: Aspose.PDF for .NET API Reference
description: Enum ExplicitDestinationType d'Aspose.Pdf.Annotations. Énumère les types de destinations explicites
type: docs
weight: 1690
url: /fr/net/aspose.pdf.annotations/explicitdestinationtype/
---
## Énumération ExplicitDestinationType

Énumère les types de destinations explicites.

```csharp
public enum ExplicitDestinationType
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| XYZ | `0` | Affiche la page avec les coordonnées (gauche, haut) positionnées dans le coin supérieur gauche de la fenêtre et le contenu de la page agrandi par le facteur de zoom. Une valeur nulle pour l'un des paramètres gauche, haut ou zoom spécifie que la valeur actuelle de ce paramètre doit être conservée inchangée. Une valeur de zoom de 0 a la même signification qu'une valeur nulle. |
| Fit | `1` | Affiche la page avec son contenu agrandi juste assez pour que l'ensemble de la page tienne dans la fenêtre à la fois horizontalement et verticalement. Si les facteurs d'agrandissement horizontal et vertical requis sont différents, utilisez le plus petit des deux, centrant la page dans la fenêtre dans l'autre dimension. |
| FitH | `2` | Affiche la page avec la coordonnée verticale haut positionnée au bord supérieur de la fenêtre et le contenu de la page agrandi juste assez pour que toute la largeur de la page tienne dans la fenêtre. Une valeur nulle pour haut spécifie que la valeur actuelle de ce paramètre doit être conservée inchangée. |
| FitV | `3` | Affiche la page avec la coordonnée horizontale gauche positionnée au bord gauche de la fenêtre et le contenu de la page agrandi juste assez pour que toute la hauteur de la page tienne dans la fenêtre. Une valeur nulle pour gauche spécifie que la valeur actuelle de ce paramètre doit être conservée inchangée. |
| FitR | `4` | Affiche la page avec son contenu agrandi juste assez pour que le rectangle spécifié par les coordonnées gauche, bas, droit et haut tienne entièrement dans la fenêtre à la fois horizontalement et verticalement. Si les facteurs d'agrandissement horizontal et vertical requis sont différents, utilisez le plus petit des deux, centrant le rectangle dans la fenêtre dans l'autre dimension. Une valeur nulle pour l'un des paramètres peut entraîner un comportement imprévisible. |
| FitB | `5` | Affiche la page avec son contenu agrandi juste assez pour que sa boîte englobante tienne entièrement dans la fenêtre à la fois horizontalement et verticalement. Si les facteurs d'agrandissement horizontal et vertical requis sont différents, utilisez le plus petit des deux, centrant la boîte englobante dans la fenêtre dans l'autre dimension. |
| FitBH | `6` | Affiche la page avec la coordonnée verticale haut positionnée au bord supérieur de la fenêtre et le contenu de la page agrandi juste assez pour que toute la largeur de sa boîte englobante tienne dans la fenêtre. Une valeur nulle pour haut spécifie que la valeur actuelle de ce paramètre doit être conservée inchangée. |
| FitBV | `7` | Affiche la page avec la coordonnée horizontale gauche positionnée au bord gauche de la fenêtre et le contenu de la page agrandi juste assez pour que toute la hauteur de sa boîte englobante tienne dans la fenêtre. Une valeur nulle pour gauche spécifie que la valeur actuelle de ce paramètre doit être conservée inchangée. |

### Voir aussi

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)