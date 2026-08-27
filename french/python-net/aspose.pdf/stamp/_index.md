---
title: "Stamp"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Une classe abstraite pour différents types de tampons qui sont des descendants."
type: docs
weight: 1440
url: /fr/python-net/aspose.pdf/stamp/
---

## Stamp class

Une classe abstraite pour différents types de tampons qui sont des descendants.

Le type Stamp expose les membres suivants :
## Propriétés
| Nom | Description |
| :- | :- |
| background | Définit ou obtient une valeur booléenne qui indique que le contenu est estampillé en arrière-plan.<br/>            Si la valeur est vraie, le contenu du tampon est placé en bas.<br/>            Par défaut, la valeur est fausse, le contenu du tampon est placé en haut. |
| opacité | Obtient ou définit une valeur indiquant l'opacité du tampon. La valeur est comprise entre 0.0 et 1.0.<br/>            Par défaut, la valeur est 1.0. |
| outline_opacity | Obtient ou définit une valeur indiquant l'opacité du contour du tampon. La valeur est comprise entre 0.0 et 1.0.<br/>            Par défaut, la valeur est 1.0. |
| outline_width | Obtient ou définit une valeur de la largeur du contour du tampon.<br/>            Par défaut, la valeur est 1.0. |
| rotate | Définit ou obtient la rotation du contenu du tampon selon les valeurs [Rotation](/pdf/python-net/aspose.pdf/rotation/).<br/> Note. Cette propriété est destinée aux angles qui sont des multiples de 90 degrés (0, 90, 180, 270 degrés).<br/> Pour définir un angle arbitraire, utilisez la propriété RotateAngle. <br/> Si l'angle défini par ArbitraryAngle n'est pas un multiple de 90, la propriété Rotate renvoie Rotation.None. |
| x_indent | Coordonnée horizontale du tampon, à partir de la gauche. |
| y_indent | Coordonnée verticale du tampon, à partir du bas. |
| horizontal_alignment | Obtient ou définit l'alignement horizontal du tampon sur la page. |
| vertical_alignment | Obtient ou définit l'alignement vertical du tampon sur la page. |
| left_margin | Obtient ou définit la marge gauche du tampon. |
| right_margin | Obtient ou définit la marge droite du tampon. |
| bottom_margin | Obtient ou définit la marge inférieure du tampon. |
| top_margin | Obtient ou définit la marge supérieure du tampon. |
| zoom_x | Facteur de zoom horizontal du tampon. Permet de redimensionner le tampon horizontalement. |
| largeur | Largeur souhaitée du tampon sur la page. |
| hauteur | Hauteur souhaitée du tampon sur la page. |
| zoom_y | Facteur de zoom vertical du tampon. Permet de redimensionner le tampon verticalement. |
| zoom | Facteur de zoom du tampon. Permet de redimensionner le tampon.<br/> Veuillez noter que la paire de propriétés ZoomX et ZoomY permet de définir le facteur de zoom pour chaque axe séparément. <br/> La définition de cette propriété modifie les propriétés ZoomX et ZoomY. <br/> Si ZoomX et ZoomY sont différents, la propriété Zoom renvoie la valeur de ZoomX. |
| rotate_angle | Obtient ou définit l'angle de rotation du tampon en degrés.<br/> Cette propriété permet de définir un angle de rotation arbitraire. |
## Méthodes
| Nom | Description |
| :- | :- |
| put(page) | Ajoute un tampon sur la page. |
| set_stamp_id(value) | Définit l'ID du tampon. |
| get_stamp_id() | Renvoie l'ID du tampon. |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

