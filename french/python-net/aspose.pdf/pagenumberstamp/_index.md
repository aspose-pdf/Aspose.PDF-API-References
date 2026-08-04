---
title: "PageNumberStamp"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente le tampon du numéro de page et est utilisé pour numéroter les pages."
type: docs
weight: 1140
url: /fr/python-net/aspose.pdf/pagenumberstamp/
---

## PageNumberStamp class

Représente le tampon du numéro de page et est utilisé pour numéroter les pages.

Le type PageNumberStamp expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| PageNumberStamp(format) | Initialise une nouvelle instance de la classe PageNumberStamp |
| PageNumberStamp() | Initialise une nouvelle instance de la classe [PageNumberStamp](/pdf/python-net/aspose.pdf/pagenumberstamp/). Le format est défini sur "#". |
| PageNumberStamp(formatted_text) | Initialise une nouvelle instance de la classe PageNumberStamp |
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
| draw | Cette propriété détermine comment le tampon est dessiné sur la page. Si Draw = true, le tampon est dessiné comme des opérateurs graphiques et si draw = false, le tampon est dessiné comme du texte. |
| treat_y_indent_as_base_line | Définit l'origine des coordonnées pour placer le texte.<br/>            Si TreatYIndentAsBaseLine = true (valeur par défaut lorsque Draw = true) la valeur YIndent sera traitée comme la ligne de base du texte.<br/>            Si TreatYIndentAsBaseLine = false (valeur par défaut lorsque Draw = false) la valeur YIndent sera traitée comme le bas (ligne de descente) du texte. |
| word_wrap | Définit le retour à la ligne. Si cette propriété est définie sur true et qu'une valeur Width est spécifiée, le texte sera réparti sur plusieurs lignes pour s'adapter à la largeur spécifiée. Valeur par défaut : false. |
| justify | Définit la justification du texte. Si cette propriété est définie sur true, les bords gauche et droit du texte sont alignés. Valeur par défaut : false. |
| scale | Définit le redimensionnement du texte. Si cette propriété est définie sur true et qu'une valeur Width est spécifiée, le texte sera mis à l'échelle afin de s'adapter à la largeur spécifiée. |
| valeur | Obtient ou définit la valeur chaîne utilisée comme tampon sur la page. |
| text_state | Obtient les propriétés texte du tampon. Voir [text_state](/pdf/python-net/aspose.pdf/textstamp/) pour plus de détails. |
| text_alignment | Alignement du texte à l'intérieur du tampon. |
| max_row_width | Hauteur maximale de ligne pour l'option WordWrap. |
| format | Valeur de chaîne pour le tamponnage des numéros de page. <br/>            La valeur doit inclure le caractère '#' qui est remplacé par le numéro de page lors du tamponnage. |
| starting_number | Obtient ou définit la valeur du numéro de la page de départ. Les autres pages seront numérotées à partir de cette valeur. |
| numbering_style | Style de numérotation utilisé par ce tampon. |
## Méthodes
| Nom | Description |
| :- | :- |
| put(page) | Ajoute le numéro de page. |
| set_stamp_id(value) | Définit l'ID du tampon. |
| get_stamp_id() | Renvoie l'ID du tampon. |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

