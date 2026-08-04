---
title: "ExplicitDestinationType"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Énumère les types de destinations explicites."
type: docs
weight: 1020
url: /fr/python-net/aspose.pdf.annotations/explicitdestinationtype/
---

## ExplicitDestinationType enumeration

Énumère les types de destinations explicites.

## Members
| Nom du membre | Description |
| :- | :- |
| XYZ | Affiche la page avec les coordonnées (left,�top) positionnées dans le coin supérieur gauche de la fenêtre<br/>            et le contenu de la page agrandi par le facteur zoom. Une valeur nulle pour l'un des paramètres<br/>            left, top ou zoom indique que la valeur actuelle de ce paramètre doit être conservée telle quelle. <br/>            Une valeur de zoom de 0 a la même signification qu'une valeur nulle. |
| FIT | Affiche la page avec son contenu agrandi juste assez pour faire tenir toute la page dans la fenêtre<br/>            à la fois horizontalement et verticalement. Si les facteurs de grossissement horizontal et vertical requis sont<br/>            différents, utilisez le plus petit des deux, en centrant la page dans la fenêtre dans l'autre dimension. |
| FIT_H | Affiche la page avec la coordonnée verticale top positionnée au bord supérieur de la fenêtre et<br/>            le contenu de la page agrandi juste assez pour faire tenir toute la largeur de la page dans la fenêtre.<br/>            Une valeur nulle pour top indique que la valeur actuelle de ce paramètre doit être conservée telle quelle. |
| FIT_V | Affiche la page avec la coordonnée horizontale left positionnée au bord gauche de la fenêtre<br/>            et le contenu de la page agrandi juste assez pour faire tenir toute la hauteur de la page dans la fenêtre.<br/>            Une valeur nulle pour left indique que la valeur actuelle de ce paramètre doit être conservée telle quelle. |
| FIT_R | Affiche la page avec son contenu agrandi juste assez pour faire tenir le rectangle spécifié par les<br/>            coordonnées left, bottom, right et top entièrement dans la fenêtre à la fois horizontalement et verticalement.<br/>            Si les facteurs de grossissement horizontal et vertical requis sont différents, utilisez le plus petit des<br/>            deux, en centrant le rectangle dans la fenêtre dans l'autre dimension. Une valeur nulle pour l'un des<br/>            paramètres peut entraîner un comportement imprévisible. |
| FIT_B | Affiche la page avec son contenu agrandi juste assez pour faire tenir son cadre de délimitation entièrement dans<br/>            la fenêtre à la fois horizontalement et verticalement. Si les facteurs de grossissement horizontal et vertical requis sont différents, utilisez le plus petit des deux, en centrant le cadre de délimitation dans la fenêtre<br/>            dans l'autre dimension. |
| FIT_BH | Affiche la page avec la coordonnée verticale top positionnée au bord supérieur de la fenêtre et le<br/>            contenu de la page agrandi juste assez pour faire tenir toute la largeur de son cadre de délimitation dans la fenêtre.<br/>            Une valeur nulle pour top indique que la valeur actuelle de ce paramètre doit être conservée telle quelle. |
| FIT_BV | Affiche la page avec la coordonnée horizontale left positionnée au bord gauche de la fenêtre et le<br/>            contenu de la page agrandi juste assez pour faire tenir toute la hauteur de son cadre de délimitation dans la fenêtre.<br/>            Une valeur nulle pour left indique que la valeur actuelle de ce paramètre doit être conservée telle quelle. |

### Voir aussi

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

