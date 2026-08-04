---
title: "AttributeName"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente une classe pour les valeurs de nom d'attribut."
type: docs
weight: 50
url: /fr/python-net/aspose.pdf.logicalstructure/attributename/
---

## AttributeName class

Représente une classe pour les valeurs de nom d'attribut.

Le type AttributeName expose les membres suivants:
## Propriétés
| Nom | Description |
| :- | :- |
| nom | Obtient la valeur du nom de l'attribut. |
| attribute_key | Obtient la clé d'attribut. |
| PLACEMENT_BLOCK | Placement d'attribut : Block - Empilé dans la direction de progression du bloc au sein d'une zone de référence englobante ou d'un BLSE parent. |
| PLACEMENT_INLINE | Placement d'attribut : Inline - Compacté dans la direction de progression en ligne au sein d'un BLSE englobant. |
| PLACEMENT_BEFORE | Placement d'attribut : Before - Placé de façon que le bord avant du rectangle d'allocation de l'élément coïncide avec celui de la zone de référence englobante la plus proche. |
| PLACEMENT_START | Placement d'attribut : Start - Placé de façon que le bord de départ du rectangle d'allocation de l'élément coïncide avec celui de la zone de référence englobante la plus proche. |
| PLACEMENT_END | Placement d'attribut : End - Placé de façon que le bord final du rectangle d'allocation de l'élément coïncide avec celui de la zone de référence englobante la plus proche. |
| WRITING_MODE_LR_TB | Mode d'écriture d'attribut : LrTb - Progression en ligne de gauche à droite ; progression du bloc de haut en bas. C'est le mode d'écriture typique pour les systèmes d'écriture occidentaux. |
| WRITING_MODE_RL_TB | Mode d'écriture d'attribut : RlTb - Progression en ligne de droite à gauche ; progression du bloc de haut en bas. C'est le mode d'écriture typique pour les systèmes d'écriture arabes et hébreux. |
| WRITING_MODE_TB_RL | Mode d'écriture d'attribut : TbRl - Progression en ligne de haut en bas ; progression du bloc de droite à gauche. C'est le mode d'écriture typique pour les systèmes d'écriture chinois et japonais. |
| BORDER_STYLE_NONE | Style de bordure d'attribut : None - Aucun bord. Force la valeur calculée de BorderThicknessto à 0. |
| BORDER_STYLE_HIDDEN | Style de bordure d'attribut : Hidden - Identique à None, sauf en ce qui concerne la résolution des conflits de bordure pour les éléments de tableau. |
| BORDER_STYLE_DOTTED | Style de bordure d'attribut : Dotted - La bordure est une série de points. |
| BORDER_STYLE_DASHED | Attribut BorderStyle : Dashed - La bordure est une série de courts segments de ligne. |
| BORDER_STYLE_SOLID | Attribut BorderStyle : Solid - La bordure est un seul segment de ligne. |
| BORDER_STYLE_DOUBLE | Attribut BorderStyle : Double - La bordure est composée de deux lignes pleines. La somme des deux lignes et de l'espace entre elles est égale à la valeur de BorderThickness. |
| BORDER_STYLE_GROOVE | Attribut BorderStyle : Groove - La bordure semble être gravée dans le canevas. |
| BORDER_STYLE_RIDGE | Attribut BorderStyle : Ridge - La bordure semble sortir du canevas (l'opposé de Groove). |
| BORDER_STYLE_INSET | Attribut BorderStyle : Inset - La bordure donne l'impression que toute la boîte est encastrée dans le canevas. |
| BORDER_STYLE_OUTSET | Attribut BorderStyle : Outset - La bordure donne l'impression que toute la boîte sort du canevas (l'opposé de Inset). |
| TEXT_ALIGN_START | Attribut TextAlign : Start - Aligné avec le bord de départ. |
| TEXT_ALIGN_CENTER | Attribut TextAlign : Center - Centré entre les bords de départ et d'arrivée. |
| TEXT_ALIGN_END | Attribut TextAlign : End - Aligné avec le bord d'arrivée. |
| TEXT_ALIGN_JUSTIFY | Attribut TextAlign : Justify - Aligné avec les bords de départ et d'arrivée, avec un espacement interne de chaque ligne élargi, si nécessaire, pour obtenir cet alignement. La dernière (ou unique) ligne ne doit être alignée qu'avec le bord de départ. |
| WIDTH_AUTO | Attribut Width : Auto - la largeur de l'élément doit être déterminée par la largeur intrinsèque de son contenu. |
| HEIGHT_AUTO | Attribut Height : Auto - La hauteur de l'élément doit être déterminée par la hauteur intrinsèque de son contenu. |
| BLOCK_ALIGN_BEFORE | Attribut BlockAlign : Before - Le bord avant du rectangle d'allocation du premier enfant est aligné avec celui du rectangle de contenu de la cellule du tableau. |
| BLOCK_ALIGN_MIDDLE | Attribut BlockAlign : Milieu - Enfants centrés dans la cellule du tableau. La distance entre le bord avant du rectangle d'allocation du premier enfant et celui du rectangle de contenu de la cellule du tableau doit être la même que la distance entre le bord après du rectangle d'allocation du dernier enfant et celui du rectangle de contenu de la cellule du tableau. |
| BLOCK_ALIGN_AFTER | Attribut BlockAlign : Après - Le bord après du rectangle d'allocation du dernier enfant est aligné avec celui du rectangle de contenu de la cellule du tableau. |
| BLOCK_ALIGN_JUSTIFY | Attribut BlockAlign : Justifier - Enfants alignés avec les bords avant et après du rectangle de contenu de la cellule du tableau. Le premier enfant doit être placé comme décrit pour Avant et le dernier enfant comme décrit pour Après, avec un espacement égal entre les enfants. S'il n'y a qu'un seul enfant, il doit être aligné uniquement avec le bord avant, comme pour Avant. |
| INLINE_ALIGN_START | Attribut InlineAlign : Début - Le bord de départ du rectangle d'allocation de chaque enfant est aligné avec celui du rectangle de contenu de la cellule du tableau. |
| INLINE_ALIGN_CENTER | Attribut InlineAlign : Centre - Chaque enfant est centré dans la cellule du tableau. La distance entre les bords de départ du rectangle d'allocation de l'enfant et le rectangle de contenu de la cellule du tableau doit être la même que la distance entre leurs bords de fin. |
| INLINE_ALIGN_END | Attribut InlineAlign : Fin - Le bord de fin du rectangle d'allocation de chaque enfant est aligné avec celui du rectangle de contenu de la cellule du tableau. |
| LINE_HEIGHT_NORMAL | Attribut LineHeight : Normal - Ajuster la hauteur de ligne pour inclure toute valeur non nulle spécifiée pour BaselineShift. |
| LINE_HEIGHT_AUTO | Attribut LineHeight : Auto - Aucun ajustement de la valeur de BaselineShift ne doit être effectué. |
| TEXT_DECORATION_TYPE_NONE | Attribut TextDecorationType : Aucun - Aucun décor de texte. |
| TEXT_DECORATION_TYPE_UNDERLINE | Attribut TextDecorationType : Souligné - Une ligne sous le texte. |
| TEXT_DECORATION_TYPE_OVERLINE | Attribut TextDecorationType : Surligne - Une ligne au-dessus du texte. |
| TEXT_DECORATION_TYPE_LINE_THROUGH | Attribut TextDecorationType : Barré - Une ligne traversant le milieu du texte. |
| RUBY_ALIGN_START | Attribute RubyAlign: Start - Le contenu doit être aligné sur le bord de départ dans la direction de progression en ligne. |
| RUBY_ALIGN_CENTER | Attribute RubyAlign: Center - Le contenu doit être centré dans la direction de progression en ligne. |
| RUBY_ALIGN_END | Attribute RubyAlign: End - Le contenu doit être aligné sur le bord de fin dans la direction de progression en ligne. |
| RUBY_ALIGN_JUSTIFY | Attribute RubyAlign: Justify - Le contenu doit être étendu pour remplir la largeur disponible dans la direction de progression en ligne. |
| RUBY_ALIGN_DISTRIBUTE | Attribute RubyAlign: Distribute - Le contenu doit être étendu pour remplir la largeur disponible dans la direction de progression en ligne. Cependant, un espace doit également être inséré au bord de départ et au bord de fin du texte. L'espacement doit être réparti selon un ratio de 1:2:1 (début:infixe:fin). Il doit être changé en un ratio de 0:1:1 si le ruby apparaît au début d'une ligne de texte ou en un ratio de 1:1:0 si le ruby apparaît à la fin de la ligne de texte. |
| RUBY_POSITION_BEFORE | Attribute RubyPosition: Before - Le contenu RT doit être aligné le long du bord avant de l'élément. |
| RUBY_POSITION_AFTER | Attribute RubyPosition: After - Le contenu RT doit être aligné le long du bord après de l'élément. |
| RUBY_POSITION_WARICHU | Attribute RubyPosition: Warichu - Les éléments RT et les éléments RP associés doivent être formatés comme un warichu, suivant l'élément RB. |
| RUBY_POSITION_INLINE | Attribute RubyPosition: Inline - Les éléments RT et les éléments RP associés doivent être formatés comme un commentaire entre parenthèses, suivant l'élément RB. |
| GLYPH_ORIENTATION_VERTICAL_AUTO | Attribute GlyphOrientationVertical: Auto - Spécifie une orientation par défaut pour le texte, selon qu'il est en pleine largeur (aussi large qu'il est haut). |
| LIST_NUMBERING_NONE | Attribute ListNumbering: None - Aucun auto-numérotage; les éléments Lbl (s'ils sont présents) contiennent du texte arbitraire qui n'est soumis à aucun schéma de numérotation. |
| LIST_NUMBERING_DISC | Attribute ListNumbering: Disc - Puce circulaire solide. |
| LIST_NUMBERING_CIRCLE | Attribute ListNumbering: Circle - Puce circulaire ouverte. |
| LIST_NUMBERING_SQUARE | Attribut ListNumbering: Square - Puce carrée solide. |
| LIST_NUMBERING_DECIMAL | Attribut ListNumbering: Decimal - Chiffres arabes décimaux (1-9, 10-99, ...). |
| LIST_NUMBERING_UPPER_ROMAN | Attribut ListNumbering: UpperRoman - Nombres romains majuscules (I, II, III, IV, ...). |
| LIST_NUMBERING_LOWER_ROMAN | Attribut ListNumbering: LowerRoman - Nombres romains minuscules (i, ii, iii, iv, ...). |
| LIST_NUMBERING_UPPER_ALPHA | Attribut ListNumbering: UpperAlpha - Lettres majuscules (A, B, C, ...). |
| LIST_NUMBERING_LOWER_ALPHA | Attribut ListNumbering: LowerAlpha - Lettres minuscules (a, b, c, ...). |
| ROLE_RB | Attribut Role: rb - Bouton radio. |
| ROLE_CB | Attribut Role: cb - Case à cocher. |
| ROLE_PB | Attribut Role: pb - Bouton poussoir. |
| ROLE_TV | Attribut Role: tv - Champ texte-valeur. |
| CHECKED_ON | Attribut checked: On - L'état d'un bouton radio ou d'une case à cocher. |
| CHECKED_OFF | Attribut checked: Off - L'état d'un bouton radio ou d'une case à cocher. |
| CHECKED_NEUTRAL | Attribut vérifié : Neutre - L'état d'un bouton radio ou d'une case à cocher. |
| SCOPE_ROW | Portée de l'attribut : Ligne. |
| SCOPE_COLUMN | Portée de l'attribut : Colonne. |
| SCOPE_BOTH | Portée de l'attribut : Les deux. |
## Méthodes
| Nom | Description |
| :- | :- |
| from_name_attribute_key(name, attribute_key) | Obtient le nom de l'attribut pour la clé d'attribut. |

### Voir aussi

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

