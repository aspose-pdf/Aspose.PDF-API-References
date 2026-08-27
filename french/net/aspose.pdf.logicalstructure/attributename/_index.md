---
title: "Classe AttributeName"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.LogicalStructure.AttributeName. Représente la classe pour les valeurs de noms d'attribut."
type: docs
weight: 6360
url: /fr/net/aspose.pdf.logicalstructure/attributename/
---
## AttributeName class

Représente la classe pour les valeurs de nom d'attribut.

```csharp
public sealed class AttributeName
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AttributeKey](../../aspose.pdf.logicalstructure/attributename/attributekey/) { get; } | Obtient la clé de l'attribut. |
| [Name](../../aspose.pdf.logicalstructure/attributename/name/) { get; } | Obtient la valeur du nom de l'attribut. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromNameAttributeKey](../../aspose.pdf.logicalstructure/attributename/fromnameattributekey/)(string, AttributeKey) | Obtient le nom de l'attribut pour la clé d'attribut. |
| override [ToString](../../aspose.pdf.logicalstructure/attributename/tostring/)() | Renvoie une chaîne qui représente l’objet actuel. |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [BlockAlign_After](../../aspose.pdf.logicalstructure/attributename/blockalign_after/) | Attribut BlockAlign: After - Le bord après du rectangle d'allocation du dernier enfant est aligné avec celui du rectangle de contenu de la cellule du tableau. |
| static readonly [BlockAlign_Before](../../aspose.pdf.logicalstructure/attributename/blockalign_before/) | Attribut BlockAlign: Before - Le bord avant du rectangle d'allocation du premier enfant est aligné avec celui du rectangle de contenu de la cellule du tableau. |
| static readonly [BlockAlign_Justify](../../aspose.pdf.logicalstructure/attributename/blockalign_justify/) | Attribut BlockAlign: Justify - Les enfants sont alignés avec les bords avant et après du rectangle de contenu de la cellule du tableau. Le premier enfant doit être placé comme décrit pour Before et le dernier enfant comme décrit pour After, avec un espacement égal entre les enfants. S'il n'y a qu'un seul enfant, il doit être aligné uniquement avec le bord avant, comme pour Before. |
| static readonly [BlockAlign_Middle](../../aspose.pdf.logicalstructure/attributename/blockalign_middle/) | Attribut BlockAlign: Middle- Enfants centrés à l'intérieur de la cellule du tableau. La distance entre le bord avant du rectangle d'allocation du premier enfant et celui du rectangle de contenu de la cellule du tableau doit être la même que la distance entre le bord après du rectangle d'allocation du dernier enfant et celui du rectangle de contenu de la cellule du tableau. |
| static readonly [BorderStyle_Dashed](../../aspose.pdf.logicalstructure/attributename/borderstyle_dashed/) | Attribut BorderStyle: Dashed - La bordure est une série de courts segments de ligne. |
| static readonly [BorderStyle_Dotted](../../aspose.pdf.logicalstructure/attributename/borderstyle_dotted/) | Attribut BorderStyle: Dotted - La bordure est une série de points. |
| static readonly [BorderStyle_Double](../../aspose.pdf.logicalstructure/attributename/borderstyle_double/) | Attribut BorderStyle : Double - La bordure est composée de deux lignes pleines. La somme des deux lignes et de l'espace entre elles est égale à la valeur de BorderThickness. |
| static readonly [BorderStyle_Groove](../../aspose.pdf.logicalstructure/attributename/borderstyle_groove/) | Attribut BorderStyle : Groove - La bordure semble être gravée dans le canevas. |
| static readonly [BorderStyle_Hidden](../../aspose.pdf.logicalstructure/attributename/borderstyle_hidden/) | Attribut BorderStyle : Hidden - Identique à None, sauf en ce qui concerne la résolution des conflits de bordure pour les éléments de tableau. |
| static readonly [BorderStyle_Inset](../../aspose.pdf.logicalstructure/attributename/borderstyle_inset/) | Attribut BorderStyle : Inset - La bordure donne l'impression que la boîte entière est encastrée dans le canevas. |
| static readonly [BorderStyle_None](../../aspose.pdf.logicalstructure/attributename/borderstyle_none/) | Attribut BorderStyle : None - Pas de bordure. Force la valeur calculée de BorderThicknessto à 0. |
| static readonly [BorderStyle_Outset](../../aspose.pdf.logicalstructure/attributename/borderstyle_outset/) | Attribut BorderStyle : Outset - La bordure donne l'impression que la boîte entière sort du canevas (l'opposé de Inset). |
| static readonly [BorderStyle_Ridge](../../aspose.pdf.logicalstructure/attributename/borderstyle_ridge/) | Attribut BorderStyle : Ridge - La bordure semble sortir du canevas (l'opposé de Groove). |
| static readonly [BorderStyle_Solid](../../aspose.pdf.logicalstructure/attributename/borderstyle_solid/) | Attribut BorderStyle : Solid - La bordure est un segment de ligne unique. |
| static readonly [Checked_neutral](../../aspose.pdf.logicalstructure/attributename/checked_neutral/) | Attribut checked : Neutral - L'état d'un champ bouton radio ou case à cocher. |
| static readonly [Checked_off](../../aspose.pdf.logicalstructure/attributename/checked_off/) | Attribut checked : Off - L'état d'un champ bouton radio ou case à cocher. |
| static readonly [Checked_on](../../aspose.pdf.logicalstructure/attributename/checked_on/) | Attribut checked : On - L'état d'un champ bouton radio ou case à cocher. |
| static readonly [GlyphOrientationVertical_Auto](../../aspose.pdf.logicalstructure/attributename/glyphorientationvertical_auto/) | Attribut GlyphOrientationVertical : Auto - Spécifie une orientation par défaut pour le texte, selon qu'il est pleine largeur (aussi large qu'il est haut). |
| static readonly [Height_Auto](../../aspose.pdf.logicalstructure/attributename/height_auto/) | Attribut Height : Auto - La hauteur de l'élément doit être déterminée par la hauteur intrinsèque de son contenu. |
| static readonly [InlineAlign_Center](../../aspose.pdf.logicalstructure/attributename/inlinealign_center/) | Attribut InlineAlign : Center - Chaque enfant centré dans la cellule du tableau. La distance entre les bords de départ du rectangle d'allocation de l'enfant et le rectangle de contenu de la cellule du tableau doit être identique à la distance entre leurs bords de fin. |
| static readonly [InlineAlign_End](../../aspose.pdf.logicalstructure/attributename/inlinealign_end/) | Attribut InlineAlign : End - Le bord de fin du rectangle d'allocation de chaque enfant est aligné avec celui du rectangle de contenu de la cellule du tableau. |
| static readonly [InlineAlign_Start](../../aspose.pdf.logicalstructure/attributename/inlinealign_start/) | Attribut InlineAlign : Start - Le bord de départ du rectangle d'allocation de chaque enfant est aligné avec celui du rectangle de contenu de la cellule du tableau. |
| static readonly [LineHeight_Auto](../../aspose.pdf.logicalstructure/attributename/lineheight_auto/) | Attribut LineHeight : Auto - Aucun ajustement de la valeur de BaselineShift ne doit être effectué. |
| static readonly [LineHeight_Normal](../../aspose.pdf.logicalstructure/attributename/lineheight_normal/) | Attribut LineHeight : Normal - Ajuste la hauteur de ligne pour inclure toute valeur non nulle spécifiée pour BaselineShift. |
| static readonly [ListNumbering_Circle](../../aspose.pdf.logicalstructure/attributename/listnumbering_circle/) | Attribut ListNumbering : Circle - Puce circulaire ouverte. |
| static readonly [ListNumbering_Decimal](../../aspose.pdf.logicalstructure/attributename/listnumbering_decimal/) | Attribut ListNumbering : Decimal - Chiffres arabes décimaux (1-9, 10-99, ...). |
| static readonly [ListNumbering_Disc](../../aspose.pdf.logicalstructure/attributename/listnumbering_disc/) | Attribut ListNumbering : Disc - Puce circulaire pleine. |
| static readonly [ListNumbering_LowerAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_loweralpha/) | Attribut ListNumbering : LowerAlpha - Lettres minuscules (a, b, c, ...). |
| static readonly [ListNumbering_LowerRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_lowerroman/) | Attribut ListNumbering : LowerRoman - Chiffres romains minuscules (i, ii, iii, iv, ...). |
| static readonly [ListNumbering_None](../../aspose.pdf.logicalstructure/attributename/listnumbering_none/) | Attribut ListNumbering : None - Pas d'auto-numérotation ; les éléments Lbl (le cas échéant) contiennent du texte arbitraire qui n'est soumis à aucun schéma de numérotation. |
| static readonly [ListNumbering_Square](../../aspose.pdf.logicalstructure/attributename/listnumbering_square/) | Attribut ListNumbering : Square - Puce carrée pleine. |
| static readonly [ListNumbering_UpperAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperalpha/) | Attribut ListNumbering : UpperAlpha - Lettres majuscules (A, B, C, …). |
| static readonly [ListNumbering_UpperRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperroman/) | Attribut ListNumbering : UpperRoman - Nombres romains majuscules (I, II, III, IV, …). |
| static readonly [Placement_Before](../../aspose.pdf.logicalstructure/attributename/placement_before/) | Attribut Placement : Before - Placée de façon que le bord avant du rectangle d'allocation de l'élément coïncide avec celui de la zone de référence la plus proche. |
| static readonly [Placement_Block](../../aspose.pdf.logicalstructure/attributename/placement_block/) | Attribut Placement : Block - Empilée dans la direction de progression du bloc à l'intérieur d'une zone de référence englobante ou du BLSE parent. |
| static readonly [Placement_End](../../aspose.pdf.logicalstructure/attributename/placement_end/) | Attribut Placement : End - Placée de façon que le bord final du rectangle d'allocation de l'élément coïncide avec celui de la zone de référence la plus proche. |
| static readonly [Placement_Inline](../../aspose.pdf.logicalstructure/attributename/placement_inline/) | Attribut Placement : Inline - Compactée dans la direction de progression en ligne à l'intérieur d'un BLSE englobant. |
| static readonly [Placement_Start](../../aspose.pdf.logicalstructure/attributename/placement_start/) | Attribut Placement : Start - Placée de façon que le bord de départ du rectangle d'allocation de l'élément coïncide avec celui de la zone de référence la plus proche. |
| static readonly [Role_cb](../../aspose.pdf.logicalstructure/attributename/role_cb/) | Attribut Role : cb - Case à cocher. |
| static readonly [Role_pb](../../aspose.pdf.logicalstructure/attributename/role_pb/) | Attribut Role : pb - Bouton poussoir. |
| static readonly [Role_rb](../../aspose.pdf.logicalstructure/attributename/role_rb/) | Attribut Role : rb - Bouton radio. |
| static readonly [Role_tv](../../aspose.pdf.logicalstructure/attributename/role_tv/) | Attribut Role : tv - Champ texte-valeur. |
| static readonly [RubyAlign_Center](../../aspose.pdf.logicalstructure/attributename/rubyalign_center/) | Attribut RubyAlign : Center - Le contenu doit être centré dans la direction de progression en ligne. |
| static readonly [RubyAlign_Distribute](../../aspose.pdf.logicalstructure/attributename/rubyalign_distribute/) | Attribut RubyAlign : Distribute - Le contenu doit être étendu pour remplir la largeur disponible dans la direction de progression en ligne. Cependant, un espace doit également être inséré au bord de départ et au bord de fin du texte. L'espacement doit être réparti selon un ratio 1 : 2 : 1 (début :infixe :fin). Il doit être modifié en un ratio 0 : 1 : 1 si le ruby apparaît au début d'une ligne de texte ou en un ratio 1 : 1 : 0 s'il apparaît à la fin de la ligne de texte. |
| static readonly [RubyAlign_End](../../aspose.pdf.logicalstructure/attributename/rubyalign_end/) | Attribut RubyAlign : End - Le contenu doit être aligné sur le bord final dans la direction de progression en ligne. |
| static readonly [RubyAlign_Justify](../../aspose.pdf.logicalstructure/attributename/rubyalign_justify/) | Attribut RubyAlign : Justify - Le contenu doit être étendu pour remplir la largeur disponible dans la direction de progression en ligne. |
| static readonly [RubyAlign_Start](../../aspose.pdf.logicalstructure/attributename/rubyalign_start/) | Attribut RubyAlign : Start - Le contenu doit être aligné sur le bord de départ dans la direction de progression en ligne. |
| static readonly [RubyPosition_After](../../aspose.pdf.logicalstructure/attributename/rubyposition_after/) | Attribut RubyPosition : After - Le contenu RT doit être aligné le long du bord après de l'élément. |
| static readonly [RubyPosition_Before](../../aspose.pdf.logicalstructure/attributename/rubyposition_before/) | Attribut RubyPosition : Before - Le contenu RT doit être aligné le long du bord avant de l'élément. |
| static readonly [RubyPosition_Inline](../../aspose.pdf.logicalstructure/attributename/rubyposition_inline/) | Attribut RubyPosition : Inline - Les éléments RT et les RP associés doivent être formatés comme un commentaire entre parenthèses, suivant l'élément RB. |
| static readonly [RubyPosition_Warichu](../../aspose.pdf.logicalstructure/attributename/rubyposition_warichu/) | Attribut RubyPosition : Warichu - Les éléments RT et les RP associés doivent être formatés comme un warichu, suivant l'élément RB. |
| static readonly [Scope_Both](../../aspose.pdf.logicalstructure/attributename/scope_both/) | Attribut Scope : Both. |
| static readonly [Scope_Column](../../aspose.pdf.logicalstructure/attributename/scope_column/) | Attribut Scope : Column. |
| static readonly [Scope_Row](../../aspose.pdf.logicalstructure/attributename/scope_row/) | Attribut Scope : Row. |
| static readonly [TextAlign_Center](../../aspose.pdf.logicalstructure/attributename/textalign_center/) | Attribut TextAlign : Center - Centré entre les bords de départ et de fin. |
| static readonly [TextAlign_End](../../aspose.pdf.logicalstructure/attributename/textalign_end/) | Attribut TextAlign : End - Aligné avec le bord final. |
| static readonly [TextAlign_Justify](../../aspose.pdf.logicalstructure/attributename/textalign_justify/) | Attribut TextAlign : Justify - Aligné avec les bords de début et de fin, l'espacement interne de chaque ligne étant élargi, si nécessaire, pour obtenir cet alignement. La dernière (ou unique) ligne doit être alignée uniquement avec le bord de début. |
| static readonly [TextAlign_Start](../../aspose.pdf.logicalstructure/attributename/textalign_start/) | Attribut TextAlign : Start - Aligné avec le bord de début. |
| static readonly [TextDecorationType_LineThrough](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_linethrough/) | Attribut TextDecorationType : LineThrough - Une ligne traversant le milieu du texte. |
| static readonly [TextDecorationType_None](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_none/) | Attribut TextDecorationType : None - Aucune décoration de texte. |
| static readonly [TextDecorationType_Overline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_overline/) | Attribut TextDecorationType : Overline - Une ligne au-dessus du texte. |
| static readonly [TextDecorationType_Underline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_underline/) | Attribut TextDecorationType : Underline - Une ligne sous le texte. |
| static readonly [Width_Auto](../../aspose.pdf.logicalstructure/attributename/width_auto/) | Attribut Width : Auto - la largeur de l'élément doit être déterminée par la largeur intrinsèque de son contenu. |
| static readonly [WritingMode_LrTb](../../aspose.pdf.logicalstructure/attributename/writingmode_lrtb/) | Attribut WritingMode : LrTb - Progression en ligne de gauche à droite; progression de bloc de haut en bas. C'est le mode d'écriture typique des systèmes d'écriture occidentaux. |
| static readonly [WritingMode_RlTb](../../aspose.pdf.logicalstructure/attributename/writingmode_rltb/) | Attribut WritingMode : RlTb - Progression en ligne de droite à gauche; progression de bloc de haut en bas. C'est le mode d'écriture typique des systèmes d'écriture arabes et hébreux. |
| static readonly [WritingMode_TbRl](../../aspose.pdf.logicalstructure/attributename/writingmode_tbrl/) | Attribut WritingMode : TbRl - Progression en ligne de haut en bas; progression de bloc de droite à gauche. C'est le mode d'écriture typique des systèmes d'écriture chinois et japonais. |

### Voir aussi

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


