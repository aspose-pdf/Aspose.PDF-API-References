---
title: "AttributeName"
linktitle: "AttributeName"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe pour les valeurs de nom d'attribut."
type: docs
weight: 20
url: /fr/java/com.aspose.pdf.tagged.logicalstructure/attributename/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.AttributeName

```
public final class AttributeName extends Object
```

Représente une classe pour les valeurs de nom d'attribut.

## Champs

| Champ | Description |
| --- | --- |
| [BlockAlign_After](#BlockAlign_After) | Attribut BlockAlign: After - Bord après du rectangle d'allocation du dernier enfant aligné avec celui du rectangle de contenu de la cellule du tableau. |
| [BlockAlign_Before](#BlockAlign_Before) | Attribut BlockAlign: Before - Bord avant du rectangle d'allocation du premier enfant aligné avec celui du rectangle de contenu de la cellule du tableau. |
| [BlockAlign_Justify](#BlockAlign_Justify) | Attribut BlockAlign: Justify - Enfants alignés avec les bords avant et après du rectangle de contenu de la cellule du tableau. Le premier enfant doit être placé comme décrit pour Before et le dernier enfant comme décrit pour After, avec un espacement égal entre les enfants. S'il n'y a qu'un seul enfant, il doit être aligné uniquement avec le bord avant, comme pour Before. |
| [BlockAlign_Middle](#BlockAlign_Middle) | Attribut BlockAlign: Middle- Enfants centrés dans la cellule du tableau. La distance entre le bord avant du rectangle d'allocation du premier enfant et celui du rectangle de contenu de la cellule du tableau doit être identique à la distance entre le bord après du rectangle d'allocation du dernier enfant et celui du rectangle de contenu de la cellule du tableau. |
| [BorderStyle_Dashed](#BorderStyle_Dashed) | Attribut BorderStyle: Dashed - La bordure est une série de courts segments de ligne. |
| [BorderStyle_Dotted](#BorderStyle_Dotted) | Attribut BorderStyle: Dotted - La bordure est une série de points. |
| [BorderStyle_Double](#BorderStyle_Double) | Attribut BorderStyle: Double - La bordure est composée de deux lignes pleines. La somme des deux lignes et de l'espace entre elles est égale à la valeur de BorderThickness. |
| [BorderStyle_Groove](#BorderStyle_Groove) | Attribut BorderStyle: Groove - La bordure semble être sculptée dans le canevas. |
| [BorderStyle_Hidden](#BorderStyle_Hidden) | Attribut BorderStyle: Hidden - Identique à None, sauf en ce qui concerne la résolution des conflits de bordure pour les éléments de tableau. |
| [BorderStyle_Inset](#BorderStyle_Inset) | Attribut BorderStyle: Inset - La bordure donne l'impression que la boîte entière est incrustée dans le canevas. |
| [BorderStyle_None](#BorderStyle_None) | Attribut BorderStyle: None - Pas de bordure. Force la valeur calculée de BorderThicknessto à 0. |
| [BorderStyle_Outset](#BorderStyle_Outset) | Attribut BorderStyle: Outset - La bordure donne l'impression que la boîte entière sort du canevas (l'opposé de Inset). |
| [BorderStyle_Ridge](#BorderStyle_Ridge) | Attribut BorderStyle: Ridge - La bordure semble sortir du canevas (l'opposé de Groove). |
| [BorderStyle_Solid](#BorderStyle_Solid) | Attribut BorderStyle: Solid - La bordure est un segment de ligne unique. |
| [Checked_neutral](#Checked_neutral) | Attribut checked: Neutral - L'état d'un champ bouton radio ou case à cocher. |
| [Checked_off](#Checked_off) | Attribut checked: Off - L'état d'un bouton radio ou d'une case à cocher. |
| [Checked_on](#Checked_on) | Attribut checked: On - L'état d'un bouton radio ou d'une case à cocher. |
| [GlyphOrientationVertical_Auto](#GlyphOrientationVertical_Auto) | Attribut GlyphOrientationVertical: Auto - Spécifie une orientation par défaut pour le texte, selon qu'il est pleine largeur (aussi large que haut). |
| [Height_Auto](#Height_Auto) | Attribut Height: Auto - La hauteur de l'élément doit être déterminée par la hauteur intrinsèque de son contenu. |
| [InlineAlign_Center](#InlineAlign_Center) | Attribut InlineAlign: Center - Chaque enfant centré à l'intérieur de la cellule du tableau. La distance entre les bords de départ du rectangle d'allocation de l'enfant et le rectangle de contenu de la cellule du tableau doit être identique à la distance entre leurs bords de fin. |
| [InlineAlign_End](#InlineAlign_End) | Attribut InlineAlign: End - Le bord de fin du rectangle d'allocation de chaque enfant est aligné avec celui du rectangle de contenu de la cellule du tableau. |
| [InlineAlign_Start](#InlineAlign_Start) | Attribut InlineAlign: Start - Le bord de départ du rectangle d'allocation de chaque enfant est aligné avec celui du rectangle de contenu de la cellule du tableau. |
| [LineHeight_Auto](#LineHeight_Auto) | Attribut LineHeight: Auto - Aucun ajustement de la valeur de BaselineShift ne sera effectué. |
| [LineHeight_Normal](#LineHeight_Normal) | Attribut LineHeight: Normal - Ajuster la hauteur de ligne pour inclure toute valeur non nulle spécifiée pour BaselineShift. |
| [ListNumbering_Circle](#ListNumbering_Circle) | Attribut ListNumbering: Circle - Puce circulaire ouverte. |
| [ListNumbering_Decimal](#ListNumbering_Decimal) | Attribut ListNumbering: Decimal - Chiffres arabes décimaux (1-9, 10-99, ...). |
| [ListNumbering_Disc](#ListNumbering_Disc) | Attribut ListNumbering: Disc - Puce circulaire pleine. |
| [ListNumbering_LowerAlpha](#ListNumbering_LowerAlpha) | Attribut ListNumbering: LowerAlpha - Lettres minuscules (a, b, c, ...). |
| [ListNumbering_LowerRoman](#ListNumbering_LowerRoman) | Attribut ListNumbering: LowerRoman - Chiffres romains minuscules (i, ii, iii, iv, ...). |
| [ListNumbering_None](#ListNumbering_None) | Attribut ListNumbering: None - Aucun auto‑numérotage ; les éléments Lbl (le cas échéant) contiennent du texte arbitraire qui n'est soumis à aucun schéma de numérotation. |
| [ListNumbering_Square](#ListNumbering_Square) | Attribut ListNumbering: Square - Puce carrée pleine. |
| [ListNumbering_UpperAlpha](#ListNumbering_UpperAlpha) | Attribut ListNumbering: UpperAlpha - Lettres majuscules (A, B, C, ...). |
| [ListNumbering_UpperRoman](#ListNumbering_UpperRoman) | Attribut ListNumbering: UpperRoman - Chiffres romains majuscules (I, II, III, IV, ...). |
| [Placement_Before](#Placement_Before) | Attribut Placement: Before - Placé de sorte que le bord avant du rectangle d'allocation de l'élément coïncide avec celui de la zone de référence la plus proche. |
| [Placement_Block](#Placement_Block) | Attribut Placement: Block - Empilé dans la direction de progression du bloc à l'intérieur d'une zone de référence englobante ou du BLSE parent. |
| [Placement_End](#Placement_End) | Attribut Placement: End - Placé de sorte que le bord de fin du rectangle d'allocation de l'élément coïncide avec celui de la zone de référence la plus proche. |
| [Placement_Inline](#Placement_Inline) | Attribut Placement: Inline - Compacté dans la direction de progression en ligne à l'intérieur d'un BLSE englobant. |
| [Placement_Start](#Placement_Start) | Attribut Placement: Start - Placé de sorte que le bord de départ du rectangle d'allocation de l'élément coïncide avec celui de la zone de référence la plus proche. |
| [Role_cb](#Role_cb) | Attribut Role: cb - Case à cocher. |
| [Role_pb](#Role_pb) | Attribut Role: pb - Bouton poussoir. |
| [Role_rb](#Role_rb) | Attribut Rôle: rb - Bouton radio. |
| [Role_tv](#Role_tv) | Attribut Rôle: tv - Champ texte-valeur. |
| [RubyAlign_Center](#RubyAlign_Center) | Attribut RubyAlign: Center - Le contenu doit être centré dans la direction de progression en ligne. |
| [RubyAlign_Distribute](#RubyAlign_Distribute) | Attribut RubyAlign: Distribute - Le contenu doit être étendu pour remplir la largeur disponible dans la direction de progression en ligne. Cependant, un espace doit également être inséré aux bords de début et de fin du texte. L'espacement doit être réparti selon un ratio 1:2:1 (début:intermédiaire:fin). Il doit être changé en un ratio 0:1:1 si le ruby apparaît au début d'une ligne de texte ou en un ratio 1:1:0 si le ruby apparaît à la fin d'une ligne de texte. |
| [RubyAlign_End](#RubyAlign_End) | Attribut RubyAlign: End - Le contenu doit être aligné sur le bord de fin dans la direction de progression en ligne. |
| [RubyAlign_Justify](#RubyAlign_Justify) | Attribut RubyAlign: Justify - Le contenu doit être étendu pour remplir la largeur disponible dans la direction de progression en ligne. |
| [RubyAlign_Start](#RubyAlign_Start) | Attribut RubyAlign: Start - Le contenu doit être aligné sur le bord de début dans la direction de progression en ligne. |
| [RubyPosition_After](#RubyPosition_After) | Attribut RubyPosition: After - Le contenu RT doit être aligné le long du bord après de l'élément. |
| [RubyPosition_Before](#RubyPosition_Before) | Attribut RubyPosition: Before - Le contenu RT doit être aligné le long du bord avant de l'élément. |
| [RubyPosition_Inline](#RubyPosition_Inline) | Attribut RubyPosition: Inline - Les éléments RT et les RP associés doivent être formatés comme un commentaire entre parenthèses, suivant l'élément RB. |
| [RubyPosition_Warichu](#RubyPosition_Warichu) | Attribut RubyPosition: Warichu - Les éléments RT et les RP associés doivent être formatés comme un warichu, suivant l'élément RB. |
| [Scope_Both](#Scope_Both) | Attribut Portée: Both. |
| [Scope_Column](#Scope_Column) | Attribut Portée: Column. |
| [Scope_Row](#Scope_Row) | Attribut Portée: Row. |
| [TextAlign_Center](#TextAlign_Center) | Attribut TextAlign: Center - Centré entre les bords de début et de fin. |
| [TextAlign_End](#TextAlign_End) | Attribut TextAlign: End - Aligné avec le bord de fin. |
| [TextAlign_Justify](#TextAlign_Justify) | Attribut TextAlign: Justify - Aligné avec les bords de début et de fin, l'espacement interne de chaque ligne étant étendu, si nécessaire, pour obtenir cet alignement. La dernière (ou unique) ligne doit être alignée uniquement avec le bord de début. |
| [TextAlign_Start](#TextAlign_Start) | Attribut TextAlign: Start - Aligné avec le bord de début. |
| [TextDecorationType_LineThrough](#TextDecorationType_LineThrough) | Attribut TextDecorationType: LineThrough - Une ligne traversant le milieu du texte. |
| [TextDecorationType_None](#TextDecorationType_None) | Attribut TextDecorationType: None - Aucun décor de texte. |
| [TextDecorationType_Overline](#TextDecorationType_Overline) | Attribut TextDecorationType: Overline - Une ligne au-dessus du texte. |
| [TextDecorationType_Underline](#TextDecorationType_Underline) | Attribut TextDecorationType: Underline - Une ligne sous le texte. |
| [Width_Auto](#Width_Auto) | Attribut Width: Auto - la largeur de l'élément doit être déterminée par la largeur intrinsèque de son contenu. |
| [WritingMode_LrTb](#WritingMode_LrTb) | Attribut WritingMode: LrTb - Progression en ligne de gauche à droite; progression de bloc de haut en bas. C'est le mode d'écriture typique pour les systèmes d'écriture occidentaux. |
| [WritingMode_RlTb](#WritingMode_RlTb) | Attribut WritingMode: RlTb - Progression en ligne de droite à gauche; progression de bloc de haut en bas. C'est le mode d'écriture typique pour les systèmes d'écriture arabes et hébreux. |
| [WritingMode_TbRl](#WritingMode_TbRl) | Attribut WritingMode : TbRl - Progression en ligne de haut en bas ; progression de bloc de droite à gauche. C’est le mode d’écriture typique pour les systèmes d’écriture chinois et japonais. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [fromNameAttributeKey](#fromNameAttributeKey-java.lang.String-com.aspose.pdf.tagged.logicalstructure.AttributeKey-) | Obtient le nom de l’attribut pour la clé d’attribut. |
| [getAttributeKey](#getAttributeKey--) | Obtient la clé d’attribut. |
| [getName](#getName--) | Obtient la valeur du nom de l’attribut. |
| [toString](#toString--) | Renvoie une chaîne qui représente l'objet actuel. |

### BlockAlign_After {#BlockAlign_After}
```
public static final AttributeName BlockAlign_After
```

Attribut BlockAlign: After - Bord après du rectangle d'allocation du dernier enfant aligné avec celui du rectangle de contenu de la cellule du tableau.

### BlockAlign_Before {#BlockAlign_Before}
```
public static final AttributeName BlockAlign_Before
```

Attribut BlockAlign: Before - Bord avant du rectangle d'allocation du premier enfant aligné avec celui du rectangle de contenu de la cellule du tableau.

### BlockAlign_Justify {#BlockAlign_Justify}
```
public static final AttributeName BlockAlign_Justify
```

Attribut BlockAlign: Justify - Enfants alignés avec les bords avant et après du rectangle de contenu de la cellule du tableau. Le premier enfant doit être placé comme décrit pour Before et le dernier enfant comme décrit pour After, avec un espacement égal entre les enfants. S'il n'y a qu'un seul enfant, il doit être aligné uniquement avec le bord avant, comme pour Before.

### BlockAlign_Middle {#BlockAlign_Middle}
```
public static final AttributeName BlockAlign_Middle
```

Attribut BlockAlign: Middle- Enfants centrés dans la cellule du tableau. La distance entre le bord avant du rectangle d'allocation du premier enfant et celui du rectangle de contenu de la cellule du tableau doit être identique à la distance entre le bord après du rectangle d'allocation du dernier enfant et celui du rectangle de contenu de la cellule du tableau.

### BorderStyle_Dashed {#BorderStyle_Dashed}
```
public static final AttributeName BorderStyle_Dashed
```

Attribut BorderStyle: Dashed - La bordure est une série de courts segments de ligne.

### BorderStyle_Dotted {#BorderStyle_Dotted}
```
public static final AttributeName BorderStyle_Dotted
```

Attribut BorderStyle: Dotted - La bordure est une série de points.

### BorderStyle_Double {#BorderStyle_Double}
```
public static final AttributeName BorderStyle_Double
```

Attribut BorderStyle: Double - La bordure est composée de deux lignes pleines. La somme des deux lignes et de l'espace entre elles est égale à la valeur de BorderThickness.

### BorderStyle_Groove {#BorderStyle_Groove}
```
public static final AttributeName BorderStyle_Groove
```

Attribut BorderStyle: Groove - La bordure semble être sculptée dans le canevas.

### BorderStyle_Hidden {#BorderStyle_Hidden}
```
public static final AttributeName BorderStyle_Hidden
```

Attribut BorderStyle: Hidden - Identique à None, sauf en ce qui concerne la résolution des conflits de bordure pour les éléments de tableau.

### BorderStyle_Inset {#BorderStyle_Inset}
```
public static final AttributeName BorderStyle_Inset
```

Attribut BorderStyle: Inset - La bordure donne l'impression que la boîte entière est incrustée dans le canevas.

### BorderStyle_None {#BorderStyle_None}
```
public static final AttributeName BorderStyle_None
```

Attribut BorderStyle: None - Pas de bordure. Force la valeur calculée de BorderThicknessto à 0.

### BorderStyle_Outset {#BorderStyle_Outset}
```
public static final AttributeName BorderStyle_Outset
```

Attribut BorderStyle: Outset - La bordure donne l'impression que la boîte entière sort du canevas (l'opposé de Inset).

### BorderStyle_Ridge {#BorderStyle_Ridge}
```
public static final AttributeName BorderStyle_Ridge
```

Attribut BorderStyle: Ridge - La bordure semble sortir du canevas (l'opposé de Groove).

### BorderStyle_Solid {#BorderStyle_Solid}
```
public static final AttributeName BorderStyle_Solid
```

Attribut BorderStyle: Solid - La bordure est un segment de ligne unique.

### Checked_neutral {#Checked_neutral}
```
public static final AttributeName Checked_neutral
```

Attribut checked: Neutral - L'état d'un champ bouton radio ou case à cocher.

### Checked_off {#Checked_off}
```
public static final AttributeName Checked_off
```

Attribut checked: Off - L'état d'un bouton radio ou d'une case à cocher.

### Checked_on {#Checked_on}
```
public static final AttributeName Checked_on
```

Attribut checked: On - L'état d'un bouton radio ou d'une case à cocher.

### GlyphOrientationVertical_Auto {#GlyphOrientationVertical_Auto}
```
public static final AttributeName GlyphOrientationVertical_Auto
```

Attribut GlyphOrientationVertical: Auto - Spécifie une orientation par défaut pour le texte, selon qu'il est pleine largeur (aussi large que haut).

### Height_Auto {#Height_Auto}
```
public static final AttributeName Height_Auto
```

Attribut Height: Auto - La hauteur de l'élément doit être déterminée par la hauteur intrinsèque de son contenu.

### InlineAlign_Center {#InlineAlign_Center}
```
public static final AttributeName InlineAlign_Center
```

Attribut InlineAlign: Center - Chaque enfant centré à l'intérieur de la cellule du tableau. La distance entre les bords de départ du rectangle d'allocation de l'enfant et le rectangle de contenu de la cellule du tableau doit être identique à la distance entre leurs bords de fin.

### InlineAlign_End {#InlineAlign_End}
```
public static final AttributeName InlineAlign_End
```

Attribut InlineAlign: End - Le bord de fin du rectangle d'allocation de chaque enfant est aligné avec celui du rectangle de contenu de la cellule du tableau.

### InlineAlign_Start {#InlineAlign_Start}
```
public static final AttributeName InlineAlign_Start
```

Attribut InlineAlign: Start - Le bord de départ du rectangle d'allocation de chaque enfant est aligné avec celui du rectangle de contenu de la cellule du tableau.

### LineHeight_Auto {#LineHeight_Auto}
```
public static final AttributeName LineHeight_Auto
```

Attribut LineHeight: Auto - Aucun ajustement de la valeur de BaselineShift ne sera effectué.

### LineHeight_Normal {#LineHeight_Normal}
```
public static final AttributeName LineHeight_Normal
```

Attribut LineHeight: Normal - Ajuster la hauteur de ligne pour inclure toute valeur non nulle spécifiée pour BaselineShift.

### ListNumbering_Circle {#ListNumbering_Circle}
```
public static final AttributeName ListNumbering_Circle
```

Attribut ListNumbering: Circle - Puce circulaire ouverte.

### ListNumbering_Decimal {#ListNumbering_Decimal}
```
public static final AttributeName ListNumbering_Decimal
```

Attribut ListNumbering: Decimal - Chiffres arabes décimaux (1-9, 10-99, ...).

### ListNumbering_Disc {#ListNumbering_Disc}
```
public static final AttributeName ListNumbering_Disc
```

Attribut ListNumbering: Disc - Puce circulaire pleine.

### ListNumbering_LowerAlpha {#ListNumbering_LowerAlpha}
```
public static final AttributeName ListNumbering_LowerAlpha
```

Attribut ListNumbering: LowerAlpha - Lettres minuscules (a, b, c, ...).

### ListNumbering_LowerRoman {#ListNumbering_LowerRoman}
```
public static final AttributeName ListNumbering_LowerRoman
```

Attribut ListNumbering: LowerRoman - Chiffres romains minuscules (i, ii, iii, iv, ...).

### ListNumbering_None {#ListNumbering_None}
```
public static final AttributeName ListNumbering_None
```

Attribut ListNumbering: None - Aucun auto‑numérotage ; les éléments Lbl (le cas échéant) contiennent du texte arbitraire qui n'est soumis à aucun schéma de numérotation.

### ListNumbering_Square {#ListNumbering_Square}
```
public static final AttributeName ListNumbering_Square
```

Attribut ListNumbering: Square - Puce carrée pleine.

### ListNumbering_UpperAlpha {#ListNumbering_UpperAlpha}
```
public static final AttributeName ListNumbering_UpperAlpha
```

Attribut ListNumbering: UpperAlpha - Lettres majuscules (A, B, C, ...).

### ListNumbering_UpperRoman {#ListNumbering_UpperRoman}
```
public static final AttributeName ListNumbering_UpperRoman
```

Attribut ListNumbering: UpperRoman - Chiffres romains majuscules (I, II, III, IV, ...).

### Placement_Before {#Placement_Before}
```
public static final AttributeName Placement_Before
```

Attribut Placement: Before - Placé de sorte que le bord avant du rectangle d'allocation de l'élément coïncide avec celui de la zone de référence la plus proche.

### Placement_Block {#Placement_Block}
```
public static final AttributeName Placement_Block
```

Attribut Placement: Block - Empilé dans la direction de progression du bloc à l'intérieur d'une zone de référence englobante ou du BLSE parent.

### Placement_End {#Placement_End}
```
public static final AttributeName Placement_End
```

Attribut Placement: End - Placé de sorte que le bord de fin du rectangle d'allocation de l'élément coïncide avec celui de la zone de référence la plus proche.

### Placement_Inline {#Placement_Inline}
```
public static final AttributeName Placement_Inline
```

Attribut Placement: Inline - Compacté dans la direction de progression en ligne à l'intérieur d'un BLSE englobant.

### Placement_Start {#Placement_Start}
```
public static final AttributeName Placement_Start
```

Attribut Placement: Start - Placé de sorte que le bord de départ du rectangle d'allocation de l'élément coïncide avec celui de la zone de référence la plus proche.

### Role_cb {#Role_cb}
```
public static final AttributeName Role_cb
```

Attribut Role: cb - Case à cocher.

### Role_pb {#Role_pb}
```
public static final AttributeName Role_pb
```

Attribut Role: pb - Bouton poussoir.

### Role_rb {#Role_rb}
```
public static final AttributeName Role_rb
```

Attribut Rôle: rb - Bouton radio.

### Role_tv {#Role_tv}
```
public static final AttributeName Role_tv
```

Attribut Rôle: tv - Champ texte-valeur.

### RubyAlign_Center {#RubyAlign_Center}
```
public static final AttributeName RubyAlign_Center
```

Attribut RubyAlign: Center - Le contenu doit être centré dans la direction de progression en ligne.

### RubyAlign_Distribute {#RubyAlign_Distribute}
```
public static final AttributeName RubyAlign_Distribute
```

Attribut RubyAlign: Distribute - Le contenu doit être étendu pour remplir la largeur disponible dans la direction de progression en ligne. Cependant, un espace doit également être inséré aux bords de début et de fin du texte. L'espacement doit être réparti selon un ratio 1:2:1 (début:intermédiaire:fin). Il doit être changé en un ratio 0:1:1 si le ruby apparaît au début d'une ligne de texte ou en un ratio 1:1:0 si le ruby apparaît à la fin d'une ligne de texte.

### RubyAlign_End {#RubyAlign_End}
```
public static final AttributeName RubyAlign_End
```

Attribut RubyAlign: End - Le contenu doit être aligné sur le bord de fin dans la direction de progression en ligne.

### RubyAlign_Justify {#RubyAlign_Justify}
```
public static final AttributeName RubyAlign_Justify
```

Attribut RubyAlign: Justify - Le contenu doit être étendu pour remplir la largeur disponible dans la direction de progression en ligne.

### RubyAlign_Start {#RubyAlign_Start}
```
public static final AttributeName RubyAlign_Start
```

Attribut RubyAlign: Start - Le contenu doit être aligné sur le bord de début dans la direction de progression en ligne.

### RubyPosition_After {#RubyPosition_After}
```
public static final AttributeName RubyPosition_After
```

Attribut RubyPosition: After - Le contenu RT doit être aligné le long du bord après de l'élément.

### RubyPosition_Before {#RubyPosition_Before}
```
public static final AttributeName RubyPosition_Before
```

Attribut RubyPosition: Before - Le contenu RT doit être aligné le long du bord avant de l'élément.

### RubyPosition_Inline {#RubyPosition_Inline}
```
public static final AttributeName RubyPosition_Inline
```

Attribut RubyPosition: Inline - Les éléments RT et les RP associés doivent être formatés comme un commentaire entre parenthèses, suivant l'élément RB.

### RubyPosition_Warichu {#RubyPosition_Warichu}
```
public static final AttributeName RubyPosition_Warichu
```

Attribut RubyPosition: Warichu - Les éléments RT et les RP associés doivent être formatés comme un warichu, suivant l'élément RB.

### Scope_Both {#Scope_Both}
```
public static final AttributeName Scope_Both
```

Attribut Portée: Both.

### Scope_Column {#Scope_Column}
```
public static final AttributeName Scope_Column
```

Attribut Portée: Column.

### Scope_Row {#Scope_Row}
```
public static final AttributeName Scope_Row
```

Attribut Portée: Row.

### TextAlign_Center {#TextAlign_Center}
```
public static final AttributeName TextAlign_Center
```

Attribut TextAlign: Center - Centré entre les bords de début et de fin.

### TextAlign_End {#TextAlign_End}
```
public static final AttributeName TextAlign_End
```

Attribut TextAlign: End - Aligné avec le bord de fin.

### TextAlign_Justify {#TextAlign_Justify}
```
public static final AttributeName TextAlign_Justify
```

Attribut TextAlign: Justify - Aligné avec les bords de début et de fin, l'espacement interne de chaque ligne étant étendu, si nécessaire, pour obtenir cet alignement. La dernière (ou unique) ligne doit être alignée uniquement avec le bord de début.

### TextAlign_Start {#TextAlign_Start}
```
public static final AttributeName TextAlign_Start
```

Attribut TextAlign: Start - Aligné avec le bord de début.

### TextDecorationType_LineThrough {#TextDecorationType_LineThrough}
```
public static final AttributeName TextDecorationType_LineThrough
```

Attribut TextDecorationType: LineThrough - Une ligne traversant le milieu du texte.

### TextDecorationType_None {#TextDecorationType_None}
```
public static final AttributeName TextDecorationType_None
```

Attribut TextDecorationType: None - Aucun décor de texte.

### TextDecorationType_Overline {#TextDecorationType_Overline}
```
public static final AttributeName TextDecorationType_Overline
```

Attribut TextDecorationType: Overline - Une ligne au-dessus du texte.

### TextDecorationType_Underline {#TextDecorationType_Underline}
```
public static final AttributeName TextDecorationType_Underline
```

Attribut TextDecorationType: Underline - Une ligne sous le texte.

### Width_Auto {#Width_Auto}
```
public static final AttributeName Width_Auto
```

Attribut Width: Auto - la largeur de l'élément doit être déterminée par la largeur intrinsèque de son contenu.

### WritingMode_LrTb {#WritingMode_LrTb}
```
public static final AttributeName WritingMode_LrTb
```

Attribut WritingMode: LrTb - Progression en ligne de gauche à droite; progression de bloc de haut en bas. C'est le mode d'écriture typique pour les systèmes d'écriture occidentaux.

### WritingMode_RlTb {#WritingMode_RlTb}
```
public static final AttributeName WritingMode_RlTb
```

Attribut WritingMode: RlTb - Progression en ligne de droite à gauche; progression de bloc de haut en bas. C'est le mode d'écriture typique pour les systèmes d'écriture arabes et hébreux.

### WritingMode_TbRl {#WritingMode_TbRl}
```
public static final AttributeName WritingMode_TbRl
```

Attribut WritingMode : TbRl - Progression en ligne de haut en bas ; progression de bloc de droite à gauche. C’est le mode d’écriture typique pour les systèmes d’écriture chinois et japonais.

### fromNameAttributeKey {#fromNameAttributeKey-java.lang.String-com.aspose.pdf.tagged.logicalstructure.AttributeKey-}
Obtient le nom de l’attribut pour la clé d’attribut.

### getAttributeKey {#getAttributeKey--}
```
public final AttributeKey getAttributeKey()
```

Obtient la clé d’attribut.

**Returns:**
Instance d'AttributeKey

### getName {#getName--}
```
public final String getName()
```

Obtient la valeur du nom de l’attribut.

**Returns:**
valeur String

### toString {#toString--}
```
public String toString()
```

Renvoie une chaîne qui représente l'objet actuel.

**Returns:**
Chaîne qui représente l'objet actuel.
