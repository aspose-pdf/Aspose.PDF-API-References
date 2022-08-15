---
title: AttributeName
second_title: Référence de l'API Aspose.PDF pour .NET
description: Représente la classe pour les valeurs de nom dattribut.
type: docs
weight: 4050
url: /fr/net/aspose.pdf.logicalstructure/attributename/
---
## AttributeName class

Représente la classe pour les valeurs de nom d'attribut.

```csharp
public sealed class AttributeName
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AttributeKey](../../aspose.pdf.logicalstructure/attributename/attributekey) { get; } | Obtient la clé d'attribut. |
| [Name](../../aspose.pdf.logicalstructure/attributename/name) { get; } | Obtient la valeur du nom de l'attribut. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [FromNameAttributeKey](../../aspose.pdf.logicalstructure/attributename/fromnameattributekey)(string, AttributeKey) | Obtient le nom d'attribut pour la clé d'attribut. |
| override [ToString](../../aspose.pdf.logicalstructure/attributename/tostring)() | Renvoie une chaîne qui représente l'objet actuel. |

## Des champs

| Nom | La description |
| --- | --- |
| static readonly [BlockAlign_After](../../aspose.pdf.logicalstructure/attributename/blockalign_after) | Attribute BlockAlign : After - Après le bord du rectangle d'allocation du dernier enfant aligné avec celui du rectangle de contenu de la cellule du tableau. |
| static readonly [BlockAlign_Before](../../aspose.pdf.logicalstructure/attributename/blockalign_before) | Attribute BlockAlign : Avant - Bord avant du rectangle d'allocation du premier enfant aligné avec celui du rectangle de contenu de la cellule du tableau. |
| static readonly [BlockAlign_Justify](../../aspose.pdf.logicalstructure/attributename/blockalign_justify) | Attribut BlockAlign : Justify - Enfants alignés avec les bords avant et après du rectangle de contenu de la cellule du tableau. Le premier enfant doit être placé comme décrit pour Avant et le dernier enfant comme décrit pour Après, avec un espacement égal entre les enfants. S'il n'y a qu'un seul enfant, il doit être aligné avec le bord avant uniquement, comme pour Before. |
| static readonly [BlockAlign_Middle](../../aspose.pdf.logicalstructure/attributename/blockalign_middle) | Attribut BlockAlign : Middle- Children centré dans la cellule du tableau. La distance entre le bord avant du rectangle d'allocation du premier enfant et celui du rectangle de contenu de la cellule du tableau doit être la même que la distance entre le bord après du rectangle d'allocation du dernier enfant et celui du rectangle de contenu de la cellule du tableau. |
| static readonly [BorderStyle_Dashed](../../aspose.pdf.logicalstructure/attributename/borderstyle_dashed) | Attribute BorderStyle : Dashed - La bordure est une série de segments de ligne courts. |
| static readonly [BorderStyle_Dotted](../../aspose.pdf.logicalstructure/attributename/borderstyle_dotted) | Attribute BorderStyle : Dotted - La bordure est une série de points. |
| static readonly [BorderStyle_Double](../../aspose.pdf.logicalstructure/attributename/borderstyle_double) | Attribute BorderStyle : Double - La bordure est constituée de deux lignes pleines. La somme des deux lignes et de l'espace entre elles est égale à la valeur de BorderThickness. |
| static readonly [BorderStyle_Groove](../../aspose.pdf.logicalstructure/attributename/borderstyle_groove) | Attribute BorderStyle : Groove - La bordure semble avoir été sculptée dans le canevas. |
| static readonly [BorderStyle_Hidden](../../aspose.pdf.logicalstructure/attributename/borderstyle_hidden) | Attribute BorderStyle : Masqué - Identique à Aucun, sauf en termes de résolution des conflits de bordure pour les éléments de tableau. |
| static readonly [BorderStyle_Inset](../../aspose.pdf.logicalstructure/attributename/borderstyle_inset) | Attribute BorderStyle : Inset - La bordure donne l'impression que la boîte entière est intégrée dans le canevas. |
| static readonly [BorderStyle_None](../../aspose.pdf.logicalstructure/attributename/borderstyle_none) | Attribut BorderStyle : Aucun - Pas de bordure. Force la valeur calculée de BorderThickness à 0. |
| static readonly [BorderStyle_Outset](../../aspose.pdf.logicalstructure/attributename/borderstyle_outset) | Attribute BorderStyle : Outset - La bordure donne l'impression que la boîte entière sortait du canevas (à l'opposé de Inset). |
| static readonly [BorderStyle_Ridge](../../aspose.pdf.logicalstructure/attributename/borderstyle_ridge) | Attribute BorderStyle : Ridge - La bordure semble sortir du canevas (à l'opposé de Groove). |
| static readonly [BorderStyle_Solid](../../aspose.pdf.logicalstructure/attributename/borderstyle_solid) | Attribute BorderStyle : Solid - La bordure est un segment de ligne unique. |
| static readonly [Checked_neutral](../../aspose.pdf.logicalstructure/attributename/checked_neutral) | Attribut coché : Neutre - L'état d'un bouton radio ou d'un champ de case à cocher. |
| static readonly [Checked_off](../../aspose.pdf.logicalstructure/attributename/checked_off) | Attribut coché : désactivé - L'état d'un bouton radio ou d'un champ de case à cocher. |
| static readonly [Checked_on](../../aspose.pdf.logicalstructure/attributename/checked_on) | Attribut coché : Activé - L'état d'un bouton radio ou d'un champ de case à cocher. |
| static readonly [GlyphOrientationVertical_Auto](../../aspose.pdf.logicalstructure/attributename/glyphorientationvertical_auto) | Attribut GlyphOrientationVertical : Auto - Spécifie une orientation par défaut pour le texte, selon qu'il est pleine largeur (aussi large que haut). |
| static readonly [Height_Auto](../../aspose.pdf.logicalstructure/attributename/height_auto) | Hauteur d'attribut : Auto - La hauteur de l'élément doit être déterminée par la hauteur intrinsèque de son contenu. |
| static readonly [InlineAlign_Center](../../aspose.pdf.logicalstructure/attributename/inlinealign_center) | Attribut InlineAlign : Center - Chaque enfant est centré dans la cellule du tableau. La distance entre les bords de départ du rectangle d'allocation de l'enfant et le rectangle de contenu de la cellule du tableau doit être la même que la distance entre leurs bords de fin. |
| static readonly [InlineAlign_End](../../aspose.pdf.logicalstructure/attributename/inlinealign_end) | Attribute InlineAlign : End - Bord de fin du rectangle d'allocation de chaque enfant aligné avec celui du rectangle de contenu de la cellule du tableau. |
| static readonly [InlineAlign_Start](../../aspose.pdf.logicalstructure/attributename/inlinealign_start) | Attribute InlineAlign : Start - Bord de départ du rectangle d'allocation de chaque enfant aligné avec celui du rectangle de contenu de la cellule du tableau. |
| static readonly [LineHeight_Auto](../../aspose.pdf.logicalstructure/attributename/lineheight_auto) | Attribut LineHeight : Auto - Aucun ajustement de la valeur de BaselineShift ne doit être effectué. |
| static readonly [LineHeight_Normal](../../aspose.pdf.logicalstructure/attributename/lineheight_normal) | Attribut LineHeight : Normal - Ajustez la hauteur de la ligne pour inclure toute valeur différente de zéro spécifiée pour BaselineShift. |
| static readonly [ListNumbering_Circle](../../aspose.pdf.logicalstructure/attributename/listnumbering_circle) | Numérotation de la liste d'attributs : Cercle - Puce circulaire ouverte. |
| static readonly [ListNumbering_Decimal](../../aspose.pdf.logicalstructure/attributename/listnumbering_decimal) | Attribute ListNumbering : Decimal - Chiffres arabes décimaux (1-9, 10-99, ...). |
| static readonly [ListNumbering_Disc](../../aspose.pdf.logicalstructure/attributename/listnumbering_disc) | Numérotation de la liste d'attributs : Disque - Puce circulaire pleine. |
| static readonly [ListNumbering_LowerAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_loweralpha) | Attribute ListNumbering : LowerAlpha - Lettres minuscules (a, b, c, ...). |
| static readonly [ListNumbering_LowerRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_lowerroman) | Attribute ListNumbering : LowerRoman - Chiffres romains minuscules (i, ii, iii, iv, ...). |
| static readonly [ListNumbering_None](../../aspose.pdf.logicalstructure/attributename/listnumbering_none) | Attribute ListNumbering : Aucun - Pas de numérotation automatique ; Les éléments Lbl (le cas échéant) contiennent du texte arbitraire non soumis à un schéma de numérotation. |
| static readonly [ListNumbering_Square](../../aspose.pdf.logicalstructure/attributename/listnumbering_square) | Numérotation de la liste d'attributs : Carré - Puce carrée pleine. |
| static readonly [ListNumbering_UpperAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperalpha) | Attribute ListNumbering : UpperAlpha - Lettres majuscules (A, B, C, ...). |
| static readonly [ListNumbering_UpperRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperroman) | Attribute ListNumbering : UpperRoman - Chiffres romains majuscules (I, II, III, IV, ...). |
| static readonly [Placement_Before](../../aspose.pdf.logicalstructure/attributename/placement_before) | Emplacement de l'attribut : Avant - Placé de manière à ce que le bord avant du rectangle d'allocation de l'élément coïncide avec celui de la zone de référence englobante la plus proche. |
| static readonly [Placement_Block](../../aspose.pdf.logicalstructure/attributename/placement_block) | Placement des attributs : Bloc - Empilé dans le sens de la progression du bloc dans une zone de référence englobante ou un BLSE parent. |
| static readonly [Placement_End](../../aspose.pdf.logicalstructure/attributename/placement_end) | Emplacement de l'attribut : Fin - Placé de sorte que le bord d'extrémité du rectangle d'allocation de l'élément coïncide avec celui de la zone de référence englobante la plus proche. |
| static readonly [Placement_Inline](../../aspose.pdf.logicalstructure/attributename/placement_inline) | Placement d'attribut : Inline - Regroupé dans le sens de la progression en ligne dans un BLSE englobant. |
| static readonly [Placement_Start](../../aspose.pdf.logicalstructure/attributename/placement_start) | Emplacement de l'attribut : Début - Placé de manière à ce que le bord de départ du rectangle d'allocation de l'élément coïncide avec celui de la zone de référence englobante la plus proche. |
| static readonly [Role_cb](../../aspose.pdf.logicalstructure/attributename/role_cb) | Rôle d'attribut : cb - Case à cocher. |
| static readonly [Role_pb](../../aspose.pdf.logicalstructure/attributename/role_pb) | Rôle d'attribut : pb - Bouton poussoir. |
| static readonly [Role_rb](../../aspose.pdf.logicalstructure/attributename/role_rb) | Rôle d'attribut : rb - Bouton radio. |
| static readonly [Role_tv](../../aspose.pdf.logicalstructure/attributename/role_tv) | Rôle d'attribut : tv - Champ de valeur textuelle. |
| static readonly [RubyAlign_Center](../../aspose.pdf.logicalstructure/attributename/rubyalign_center) | Attribut RubyAlign : Center - Le contenu doit être centré dans le sens de la progression en ligne. |
| static readonly [RubyAlign_Distribute](../../aspose.pdf.logicalstructure/attributename/rubyalign_distribute) | Attribut RubyAlign : Distribuer - Le contenu doit être développé pour remplir la largeur disponible dans le sens de la progression en ligne. Cependant, un espace doit également être inséré au début et à la fin du texte. L'espacement doit être distribué selon un rapport 1:2:1 (début:infixe:fin). Il doit être changé en un rapport 0:1:1 si le rubis apparaît au début d'une ligne de texte ou en un rapport 1:1:0 si le rubis apparaît à la fin de la ligne de texte. |
| static readonly [RubyAlign_End](../../aspose.pdf.logicalstructure/attributename/rubyalign_end) | Attribut RubyAlign : End - Le contenu doit être aligné sur le bord de fin dans le sens de la progression en ligne. |
| static readonly [RubyAlign_Justify](../../aspose.pdf.logicalstructure/attributename/rubyalign_justify) | Attribut RubyAlign : Justifier - Le contenu doit être développé pour remplir la largeur disponible dans le sens de progression en ligne. |
| static readonly [RubyAlign_Start](../../aspose.pdf.logicalstructure/attributename/rubyalign_start) | Attribut RubyAlign : Début - Le contenu doit être aligné sur le bord de départ dans le sens de la progression en ligne. |
| static readonly [RubyPosition_After](../../aspose.pdf.logicalstructure/attributename/rubyposition_after) | Attribut RubyPosition : After - Le contenu RT doit être aligné le long du bord après de l'élément. |
| static readonly [RubyPosition_Before](../../aspose.pdf.logicalstructure/attributename/rubyposition_before) | Attribut RubyPosition : Avant - Le contenu RT doit être aligné le long du bord avant de l'élément. |
| static readonly [RubyPosition_Inline](../../aspose.pdf.logicalstructure/attributename/rubyposition_inline) | Attribut RubyPosition : Inline - Les éléments RT et RP associés doivent être mis en forme sous la forme d'un commentaire entre parenthèses, après l'élément RB. |
| static readonly [RubyPosition_Warichu](../../aspose.pdf.logicalstructure/attributename/rubyposition_warichu) | Attribut RubyPosition : Warichu - Les éléments RT et RP associés doivent être formatés en tant que warichu, après l'élément RB. |
| static readonly [Scope_Both](../../aspose.pdf.logicalstructure/attributename/scope_both) | Portée de l'attribut : les deux. |
| static readonly [Scope_Column](../../aspose.pdf.logicalstructure/attributename/scope_column) | Portée de l'attribut : Colonne. |
| static readonly [Scope_Row](../../aspose.pdf.logicalstructure/attributename/scope_row) | Portée de l'attribut : Ligne. |
| static readonly [TextAlign_Center](../../aspose.pdf.logicalstructure/attributename/textalign_center) | Attribute TextAlign : Center - Centré entre les bords de début et de fin. |
| static readonly [TextAlign_End](../../aspose.pdf.logicalstructure/attributename/textalign_end) | Attribut TextAlign : End - Aligné avec le bord de fin. |
| static readonly [TextAlign_Justify](../../aspose.pdf.logicalstructure/attributename/textalign_justify) | Attribut TextAlign : Justify - Aligné avec les bords de début et de fin, avec un espacement interne dans chaque ligne étendu, si nécessaire, pour obtenir un tel alignement. La dernière (ou la seule) ligne doit être alignée avec le bord de départ uniquement. |
| static readonly [TextAlign_Start](../../aspose.pdf.logicalstructure/attributename/textalign_start) | Attribut TextAlign : Start - Aligné avec le bord de départ. |
| static readonly [TextDecorationType_LineThrough](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_linethrough) | Attribute TextDecorationType : LineThrough - Une ligne au milieu du texte. |
| static readonly [TextDecorationType_None](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_none) | Attribut TextDecorationType : Aucun - Aucune décoration de texte. |
| static readonly [TextDecorationType_Overline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_overline) | Attribute TextDecorationType : Overline - Une ligne au-dessus du texte. |
| static readonly [TextDecorationType_Underline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_underline) | Attribute TextDecorationType : Underline - Une ligne sous le texte. |
| static readonly [Width_Auto](../../aspose.pdf.logicalstructure/attributename/width_auto) | Attribute Width : Auto - la largeur de l'élément doit être déterminée par la largeur intrinsèque de son contenu. |
| static readonly [WritingMode_LrTb](../../aspose.pdf.logicalstructure/attributename/writingmode_lrtb) | Attribute WritingMode : LrTb - Progression en ligne de gauche à droite ; bloquer la progression de haut en bas. C'est le mode d'écriture typique des systèmes d'écriture occidentaux. |
| static readonly [WritingMode_RlTb](../../aspose.pdf.logicalstructure/attributename/writingmode_rltb) | Attribute WritingMode : RlTb - Progression en ligne de droite à gauche ; bloquer la progression de haut en bas. C'est le mode d'écriture typique pour les systèmes d'écriture arabe et hébreu. |
| static readonly [WritingMode_TbRl](../../aspose.pdf.logicalstructure/attributename/writingmode_tbrl) | Attribute WritingMode : TbRl - Progression en ligne de haut en bas ; bloquer la progression de droite à gauche. C'est le mode d'écriture typique pour les systèmes d'écriture chinois et japonais. |

### Voir également

* espace de noms [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
