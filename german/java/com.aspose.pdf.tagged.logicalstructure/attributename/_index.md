---
title: "AttributeName"
linktitle: "AttributeName"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Klasse für Attributnamenwerte dar."
type: docs
weight: 20
url: /de/java/com.aspose.pdf.tagged.logicalstructure/attributename/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.AttributeName

```
public final class AttributeName extends Object
```

Stellt eine Klasse für Attributnamenwerte dar.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [BlockAlign_After](#BlockAlign_After) | Attribute BlockAlign: After - Nachkante des Zuweisungsrechtecks des letzten Kindes, ausgerichtet an der des Inhaltsrechtecks der Tabellenzelle. |
| [BlockAlign_Before](#BlockAlign_Before) | Attribute BlockAlign: Before - Vorkante des Zuweisungsrechtecks des ersten Kindes, ausgerichtet an der des Inhaltsrechtecks der Tabellenzelle. |
| [BlockAlign_Justify](#BlockAlign_Justify) | Attribute BlockAlign: Justify - Kinder werden sowohl an der Vor- als auch an der Nachkante des Inhaltsrechtecks der Tabellenzelle ausgerichtet. Das erste Kind wird wie bei Before platziert und das letzte Kind wie bei After, wobei der Abstand zwischen den Kindern gleich ist. Gibt es nur ein Kind, wird es nur an der Vorkante ausgerichtet, wie bei Before. |
| [BlockAlign_Middle](#BlockAlign_Middle) | Attribute BlockAlign: Middle - Kinder werden innerhalb der Tabellenzelle zentriert. Der Abstand zwischen der Vorkante des Zuweisungsrechtecks des ersten Kindes und dem Inhaltsrechteck der Tabellenzelle ist derselbe wie der Abstand zwischen der Nachkante des Zuweisungsrechtecks des letzten Kindes und dem Inhaltsrechteck der Tabellenzelle. |
| [BorderStyle_Dashed](#BorderStyle_Dashed) | Attribute BorderStyle: Dashed - Der Rand besteht aus einer Reihe kurzer Liniensegmente. |
| [BorderStyle_Dotted](#BorderStyle_Dotted) | Attribute BorderStyle: Dotted - Der Rand besteht aus einer Reihe von Punkten. |
| [BorderStyle_Double](#BorderStyle_Double) | Attribute BorderStyle: Double - Der Rand besteht aus zwei durchgezogenen Linien. Die Summe der beiden Linien und des dazwischen liegenden Abstands entspricht dem Wert von BorderThickness. |
| [BorderStyle_Groove](#BorderStyle_Groove) | Attribute BorderStyle: Groove - Der Rand sieht aus, als wäre er in die Leinwand eingraviert. |
| [BorderStyle_Hidden](#BorderStyle_Hidden) | Attribute BorderStyle: Hidden - Wie None, jedoch im Hinblick auf die Konfliktlösung von Rändern bei Tabellenelementen. |
| [BorderStyle_Inset](#BorderStyle_Inset) | Attribute BorderStyle: Inset - Der Rand lässt die gesamte Box erscheinen, als wäre sie in die Leinwand eingebettet. |
| [BorderStyle_None](#BorderStyle_None) | Attribute BorderStyle: None - Kein Rand. Erzwingt, dass der berechnete Wert von BorderThickness 0 ist. |
| [BorderStyle_Outset](#BorderStyle_Outset) | Attribute BorderStyle: Outset - Der Rand lässt die gesamte Box erscheinen, als käme sie aus der Leinwand heraus (das Gegenteil von Inset). |
| [BorderStyle_Ridge](#BorderStyle_Ridge) | Attribute BorderStyle: Ridge - Der Rand sieht aus, als käme er aus der Leinwand heraus (das Gegenteil von Groove). |
| [BorderStyle_Solid](#BorderStyle_Solid) | Attribute BorderStyle: Solid - Der Rand ist ein einzelnes Liniensegment. |
| [Checked_neutral](#Checked_neutral) | Attribute checked: Neutral - Der Zustand eines Optionsfelds oder Kontrollkästchenfeldes. |
| [Checked_off](#Checked_off) | Attribut checked: Off - Der Zustand eines Optionsfelds oder eines Kontrollkästchenfeldes. |
| [Checked_on](#Checked_on) | Attribut checked: On - Der Zustand eines Optionsfelds oder eines Kontrollkästchenfeldes. |
| [GlyphOrientationVertical_Auto](#GlyphOrientationVertical_Auto) | Attribut GlyphOrientationVertical: Auto - Gibt eine Standardausrichtung für Text an, abhängig davon, ob er vollbreit (so breit wie hoch) ist. |
| [Height_Auto](#Height_Auto) | Attribut Height: Auto - Die Höhe des Elements wird durch die intrinsische Höhe seines Inhalts bestimmt. |
| [InlineAlign_Center](#InlineAlign_Center) | Attribut InlineAlign: Center - Jedes Kind wird innerhalb der Tabellenzelle zentriert. Der Abstand zwischen den Startkanten des Zuweisungsrechtecks des Kindes und dem Inhaltsrechteck der Tabellenzelle ist derselbe wie der Abstand zwischen ihren Endkanten. |
| [InlineAlign_End](#InlineAlign_End) | Attribut InlineAlign: End - Die Endkante des Zuweisungsrechtecks jedes Kindes ist mit der des Inhaltsrechtecks der Tabellenzelle ausgerichtet. |
| [InlineAlign_Start](#InlineAlign_Start) | Attribut InlineAlign: Start - Die Startkante des Zuweisungsrechtecks jedes Kindes ist mit der des Inhaltsrechtecks der Tabellenzelle ausgerichtet. |
| [LineHeight_Auto](#LineHeight_Auto) | Attribut LineHeight: Auto - Es wird keine Anpassung des Wertes von BaselineShift vorgenommen. |
| [LineHeight_Normal](#LineHeight_Normal) | Attribut LineHeight: Normal - Die Zeilenhöhe wird angepasst, um einen angegebenen von Null verschiedenen Wert für BaselineShift zu berücksichtigen. |
| [ListNumbering_Circle](#ListNumbering_Circle) | Attribut ListNumbering: Circle - Offener kreisförmiger Aufzählungspunkt. |
| [ListNumbering_Decimal](#ListNumbering_Decimal) | Attribut ListNumbering: Decimal - Dezimale arabische Ziffern (1-9, 10-99, ...). |
| [ListNumbering_Disc](#ListNumbering_Disc) | Attribut ListNumbering: Disc - Füllender kreisförmiger Aufzählungspunkt. |
| [ListNumbering_LowerAlpha](#ListNumbering_LowerAlpha) | Attribut ListNumbering: LowerAlpha - Kleinbuchstaben (a, b, c, ...). |
| [ListNumbering_LowerRoman](#ListNumbering_LowerRoman) | Attribut ListNumbering: LowerRoman - Kleinbuchstaben römische Zahlen (i, ii, iii, iv, ...). |
| [ListNumbering_None](#ListNumbering_None) | Attribut ListNumbering: None - Keine automatische Nummerierung; Lbl-Elemente (falls vorhanden) enthalten beliebigen Text, der nicht einem Nummerierungsschema unterliegt. |
| [ListNumbering_Square](#ListNumbering_Square) | Attribut ListNumbering: Square - Füllender quadratischer Aufzählungspunkt. |
| [ListNumbering_UpperAlpha](#ListNumbering_UpperAlpha) | Attribut ListNumbering: UpperAlpha - Großbuchstaben (A, B, C, ...). |
| [ListNumbering_UpperRoman](#ListNumbering_UpperRoman) | Attribut ListNumbering: UpperRoman - Großbuchstaben römische Zahlen (I, II, III, IV, ...). |
| [Placement_Before](#Placement_Before) | Attribut Placement: Before - Platziert, sodass die Vorderkante des Zuweisungsrechtecks des Elements mit der der nächstgelegenen umgebenden Referenzfläche übereinstimmt. |
| [Placement_Block](#Placement_Block) | Attribut Placement: Block - Gestapelt in Blockfortschrittsrichtung innerhalb einer umgebenden Referenzfläche oder übergeordneten BLSE. |
| [Placement_End](#Placement_End) | Attribut Placement: End - Platziert, sodass die Endkante des Zuweisungsrechtecks des Elements mit der der nächstgelegenen umgebenden Referenzfläche übereinstimmt. |
| [Placement_Inline](#Placement_Inline) | Attribut Placement: Inline - Angeordnet in Inline-Fortschrittsrichtung innerhalb einer umgebenden BLSE. |
| [Placement_Start](#Placement_Start) | Attribut Placement: Start - Platziert, sodass die Startkante des Zuweisungsrechtecks des Elements mit der der nächstgelegenen umgebenden Referenzfläche übereinstimmt. |
| [Role_cb](#Role_cb) | Attribut Role: cb - Kontrollkästchen. |
| [Role_pb](#Role_pb) | Attribut Role: pb - Drucktaste. |
| [Role_rb](#Role_rb) | Attribut Rolle: rb - Radio-Button. |
| [Role_tv](#Role_tv) | Attribut Rolle: tv - Textwertfeld. |
| [RubyAlign_Center](#RubyAlign_Center) | Attribut RubyAlign: Center - Der Inhalt soll in der Inline‑Fortschritts‑Richtung zentriert werden. |
| [RubyAlign_Distribute](#RubyAlign_Distribute) | Attribut RubyAlign: Distribute - Der Inhalt soll in der Inline‑Fortschritts‑Richtung ausgedehnt werden, um die verfügbare Breite zu füllen. Allerdings soll am Anfangs‑ und Endrand des Textes ebenfalls Platz eingefügt werden. Der Abstand soll mit einem Verhältnis von 1:2:1 (Anfang:Zwischenteil:Ende) verteilt werden. Er wird zu einem Verhältnis von 0:1:1 geändert, wenn das ruby am Anfang einer Textzeile erscheint, oder zu einem Verhältnis von 1:1:0, wenn das ruby am Ende der Textzeile erscheint. |
| [RubyAlign_End](#RubyAlign_End) | Attribut RubyAlign: End - Der Inhalt soll am Endrand in der Inline‑Fortschritts‑Richtung ausgerichtet werden. |
| [RubyAlign_Justify](#RubyAlign_Justify) | Attribut RubyAlign: Justify - Der Inhalt soll in der Inline‑Fortschritts‑Richtung ausgedehnt werden, um die verfügbare Breite zu füllen. |
| [RubyAlign_Start](#RubyAlign_Start) | Attribut RubyAlign: Start - Der Inhalt soll am Anfangsrande in der Inline‑Fortschritts‑Richtung ausgerichtet werden. |
| [RubyPosition_After](#RubyPosition_After) | Attribut RubyPosition: After - Der RT‑Inhalt soll entlang des Nach‑Randes des Elements ausgerichtet werden. |
| [RubyPosition_Before](#RubyPosition_Before) | Attribut RubyPosition: Before - Der RT‑Inhalt soll entlang des Vor‑Randes des Elements ausgerichtet werden. |
| [RubyPosition_Inline](#RubyPosition_Inline) | Attribut RubyPosition: Inline - Der RT‑ und die zugehörigen RP‑Elemente sollen als Klammerkommentar formatiert werden, der dem RB‑Element folgt. |
| [RubyPosition_Warichu](#RubyPosition_Warichu) | Attribut RubyPosition: Warichu - Der RT‑ und die zugehörigen RP‑Elemente sollen als Warichu formatiert werden, der dem RB‑Element folgt. |
| [Scope_Both](#Scope_Both) | Attribut Scope: Beide. |
| [Scope_Column](#Scope_Column) | Attribut Scope: Spalte. |
| [Scope_Row](#Scope_Row) | Attribut Scope: Zeile. |
| [TextAlign_Center](#TextAlign_Center) | Attribut TextAlign: Center - Zentriert zwischen dem Anfangs‑ und Endrand. |
| [TextAlign_End](#TextAlign_End) | Attribut TextAlign: End - Am Endrand ausgerichtet. |
| [TextAlign_Justify](#TextAlign_Justify) | Attribut TextAlign: Justify - An beiden Rändern ausgerichtet, wobei der innere Abstand jeder Zeile bei Bedarf erweitert wird, um diese Ausrichtung zu erreichen. Die letzte (oder einzige) Zeile wird nur am Anfangsrande ausgerichtet. |
| [TextAlign_Start](#TextAlign_Start) | Attribut TextAlign: Start - Am Anfangsrande ausgerichtet. |
| [TextDecorationType_LineThrough](#TextDecorationType_LineThrough) | Attribut TextDecorationType: LineThrough - Eine Linie durch die Mitte des Textes. |
| [TextDecorationType_None](#TextDecorationType_None) | Attribut TextDecorationType: None - Keine Textdekoration. |
| [TextDecorationType_Overline](#TextDecorationType_Overline) | Attribut TextDecorationType: Overline - Eine Linie über dem Text. |
| [TextDecorationType_Underline](#TextDecorationType_Underline) | Attribut TextDecorationType: Underline - Eine Linie unter dem Text. |
| [Width_Auto](#Width_Auto) | Attribut Width: Auto - Die Breite des Elements wird durch die intrinsische Breite seines Inhalts bestimmt. |
| [WritingMode_LrTb](#WritingMode_LrTb) | Attribut WritingMode: LrTb - Inline‑Fortschritt von links nach rechts; Block‑Fortschritt von oben nach unten. Dies ist der typische Schreibmodus für westliche Schriftsysteme. |
| [WritingMode_RlTb](#WritingMode_RlTb) | Attribut WritingMode: RlTb - Inline‑Fortschritt von rechts nach links; Block‑Fortschritt von oben nach unten. Dies ist der typische Schreibmodus für arabische und hebräische Schriftsysteme. |
| [WritingMode_TbRl](#WritingMode_TbRl) | Attribut WritingMode: TbRl - Inline-Fortschritt von oben nach unten; Block-Fortschritt von rechts nach links. Dies ist der typische Schreibmodus für chinesische und japanische Schriftsysteme. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [fromNameAttributeKey](#fromNameAttributeKey-java.lang.String-com.aspose.pdf.tagged.logicalstructure.AttributeKey-) | Liefert den Attributnamen für den Attributschlüssel. |
| [getAttributeKey](#getAttributeKey--) | Liefert den Attributschlüssel. |
| [getName](#getName--) | Liefert den Namenswert des Attributs. |
| [toString](#toString--) | Gibt einen String zurück, der das aktuelle Objekt darstellt. |

### BlockAlign_After {#BlockAlign_After}
```
public static final AttributeName BlockAlign_After
```

Attribute BlockAlign: After - Nachkante des Zuweisungsrechtecks des letzten Kindes, ausgerichtet an der des Inhaltsrechtecks der Tabellenzelle.

### BlockAlign_Before {#BlockAlign_Before}
```
public static final AttributeName BlockAlign_Before
```

Attribute BlockAlign: Before - Vorkante des Zuweisungsrechtecks des ersten Kindes, ausgerichtet an der des Inhaltsrechtecks der Tabellenzelle.

### BlockAlign_Justify {#BlockAlign_Justify}
```
public static final AttributeName BlockAlign_Justify
```

Attribute BlockAlign: Justify - Kinder werden sowohl an der Vor- als auch an der Nachkante des Inhaltsrechtecks der Tabellenzelle ausgerichtet. Das erste Kind wird wie bei Before platziert und das letzte Kind wie bei After, wobei der Abstand zwischen den Kindern gleich ist. Gibt es nur ein Kind, wird es nur an der Vorkante ausgerichtet, wie bei Before.

### BlockAlign_Middle {#BlockAlign_Middle}
```
public static final AttributeName BlockAlign_Middle
```

Attribute BlockAlign: Middle - Kinder werden innerhalb der Tabellenzelle zentriert. Der Abstand zwischen der Vorkante des Zuweisungsrechtecks des ersten Kindes und dem Inhaltsrechteck der Tabellenzelle ist derselbe wie der Abstand zwischen der Nachkante des Zuweisungsrechtecks des letzten Kindes und dem Inhaltsrechteck der Tabellenzelle.

### BorderStyle_Dashed {#BorderStyle_Dashed}
```
public static final AttributeName BorderStyle_Dashed
```

Attribute BorderStyle: Dashed - Der Rand besteht aus einer Reihe kurzer Liniensegmente.

### BorderStyle_Dotted {#BorderStyle_Dotted}
```
public static final AttributeName BorderStyle_Dotted
```

Attribute BorderStyle: Dotted - Der Rand besteht aus einer Reihe von Punkten.

### BorderStyle_Double {#BorderStyle_Double}
```
public static final AttributeName BorderStyle_Double
```

Attribute BorderStyle: Double - Der Rand besteht aus zwei durchgezogenen Linien. Die Summe der beiden Linien und des dazwischen liegenden Abstands entspricht dem Wert von BorderThickness.

### BorderStyle_Groove {#BorderStyle_Groove}
```
public static final AttributeName BorderStyle_Groove
```

Attribute BorderStyle: Groove - Der Rand sieht aus, als wäre er in die Leinwand eingraviert.

### BorderStyle_Hidden {#BorderStyle_Hidden}
```
public static final AttributeName BorderStyle_Hidden
```

Attribute BorderStyle: Hidden - Wie None, jedoch im Hinblick auf die Konfliktlösung von Rändern bei Tabellenelementen.

### BorderStyle_Inset {#BorderStyle_Inset}
```
public static final AttributeName BorderStyle_Inset
```

Attribute BorderStyle: Inset - Der Rand lässt die gesamte Box erscheinen, als wäre sie in die Leinwand eingebettet.

### BorderStyle_None {#BorderStyle_None}
```
public static final AttributeName BorderStyle_None
```

Attribute BorderStyle: None - Kein Rand. Erzwingt, dass der berechnete Wert von BorderThickness 0 ist.

### BorderStyle_Outset {#BorderStyle_Outset}
```
public static final AttributeName BorderStyle_Outset
```

Attribute BorderStyle: Outset - Der Rand lässt die gesamte Box erscheinen, als käme sie aus der Leinwand heraus (das Gegenteil von Inset).

### BorderStyle_Ridge {#BorderStyle_Ridge}
```
public static final AttributeName BorderStyle_Ridge
```

Attribute BorderStyle: Ridge - Der Rand sieht aus, als käme er aus der Leinwand heraus (das Gegenteil von Groove).

### BorderStyle_Solid {#BorderStyle_Solid}
```
public static final AttributeName BorderStyle_Solid
```

Attribute BorderStyle: Solid - Der Rand ist ein einzelnes Liniensegment.

### Checked_neutral {#Checked_neutral}
```
public static final AttributeName Checked_neutral
```

Attribute checked: Neutral - Der Zustand eines Optionsfelds oder Kontrollkästchenfeldes.

### Checked_off {#Checked_off}
```
public static final AttributeName Checked_off
```

Attribut checked: Off - Der Zustand eines Optionsfelds oder eines Kontrollkästchenfeldes.

### Checked_on {#Checked_on}
```
public static final AttributeName Checked_on
```

Attribut checked: On - Der Zustand eines Optionsfelds oder eines Kontrollkästchenfeldes.

### GlyphOrientationVertical_Auto {#GlyphOrientationVertical_Auto}
```
public static final AttributeName GlyphOrientationVertical_Auto
```

Attribut GlyphOrientationVertical: Auto - Gibt eine Standardausrichtung für Text an, abhängig davon, ob er vollbreit (so breit wie hoch) ist.

### Height_Auto {#Height_Auto}
```
public static final AttributeName Height_Auto
```

Attribut Height: Auto - Die Höhe des Elements wird durch die intrinsische Höhe seines Inhalts bestimmt.

### InlineAlign_Center {#InlineAlign_Center}
```
public static final AttributeName InlineAlign_Center
```

Attribut InlineAlign: Center - Jedes Kind wird innerhalb der Tabellenzelle zentriert. Der Abstand zwischen den Startkanten des Zuweisungsrechtecks des Kindes und dem Inhaltsrechteck der Tabellenzelle ist derselbe wie der Abstand zwischen ihren Endkanten.

### InlineAlign_End {#InlineAlign_End}
```
public static final AttributeName InlineAlign_End
```

Attribut InlineAlign: End - Die Endkante des Zuweisungsrechtecks jedes Kindes ist mit der des Inhaltsrechtecks der Tabellenzelle ausgerichtet.

### InlineAlign_Start {#InlineAlign_Start}
```
public static final AttributeName InlineAlign_Start
```

Attribut InlineAlign: Start - Die Startkante des Zuweisungsrechtecks jedes Kindes ist mit der des Inhaltsrechtecks der Tabellenzelle ausgerichtet.

### LineHeight_Auto {#LineHeight_Auto}
```
public static final AttributeName LineHeight_Auto
```

Attribut LineHeight: Auto - Es wird keine Anpassung des Wertes von BaselineShift vorgenommen.

### LineHeight_Normal {#LineHeight_Normal}
```
public static final AttributeName LineHeight_Normal
```

Attribut LineHeight: Normal - Die Zeilenhöhe wird angepasst, um einen angegebenen von Null verschiedenen Wert für BaselineShift zu berücksichtigen.

### ListNumbering_Circle {#ListNumbering_Circle}
```
public static final AttributeName ListNumbering_Circle
```

Attribut ListNumbering: Circle - Offener kreisförmiger Aufzählungspunkt.

### ListNumbering_Decimal {#ListNumbering_Decimal}
```
public static final AttributeName ListNumbering_Decimal
```

Attribut ListNumbering: Decimal - Dezimale arabische Ziffern (1-9, 10-99, ...).

### ListNumbering_Disc {#ListNumbering_Disc}
```
public static final AttributeName ListNumbering_Disc
```

Attribut ListNumbering: Disc - Füllender kreisförmiger Aufzählungspunkt.

### ListNumbering_LowerAlpha {#ListNumbering_LowerAlpha}
```
public static final AttributeName ListNumbering_LowerAlpha
```

Attribut ListNumbering: LowerAlpha - Kleinbuchstaben (a, b, c, ...).

### ListNumbering_LowerRoman {#ListNumbering_LowerRoman}
```
public static final AttributeName ListNumbering_LowerRoman
```

Attribut ListNumbering: LowerRoman - Kleinbuchstaben römische Zahlen (i, ii, iii, iv, ...).

### ListNumbering_None {#ListNumbering_None}
```
public static final AttributeName ListNumbering_None
```

Attribut ListNumbering: None - Keine automatische Nummerierung; Lbl-Elemente (falls vorhanden) enthalten beliebigen Text, der nicht einem Nummerierungsschema unterliegt.

### ListNumbering_Square {#ListNumbering_Square}
```
public static final AttributeName ListNumbering_Square
```

Attribut ListNumbering: Square - Füllender quadratischer Aufzählungspunkt.

### ListNumbering_UpperAlpha {#ListNumbering_UpperAlpha}
```
public static final AttributeName ListNumbering_UpperAlpha
```

Attribut ListNumbering: UpperAlpha - Großbuchstaben (A, B, C, ...).

### ListNumbering_UpperRoman {#ListNumbering_UpperRoman}
```
public static final AttributeName ListNumbering_UpperRoman
```

Attribut ListNumbering: UpperRoman - Großbuchstaben römische Zahlen (I, II, III, IV, ...).

### Placement_Before {#Placement_Before}
```
public static final AttributeName Placement_Before
```

Attribut Placement: Before - Platziert, sodass die Vorderkante des Zuweisungsrechtecks des Elements mit der der nächstgelegenen umgebenden Referenzfläche übereinstimmt.

### Placement_Block {#Placement_Block}
```
public static final AttributeName Placement_Block
```

Attribut Placement: Block - Gestapelt in Blockfortschrittsrichtung innerhalb einer umgebenden Referenzfläche oder übergeordneten BLSE.

### Placement_End {#Placement_End}
```
public static final AttributeName Placement_End
```

Attribut Placement: End - Platziert, sodass die Endkante des Zuweisungsrechtecks des Elements mit der der nächstgelegenen umgebenden Referenzfläche übereinstimmt.

### Placement_Inline {#Placement_Inline}
```
public static final AttributeName Placement_Inline
```

Attribut Placement: Inline - Angeordnet in Inline-Fortschrittsrichtung innerhalb einer umgebenden BLSE.

### Placement_Start {#Placement_Start}
```
public static final AttributeName Placement_Start
```

Attribut Placement: Start - Platziert, sodass die Startkante des Zuweisungsrechtecks des Elements mit der der nächstgelegenen umgebenden Referenzfläche übereinstimmt.

### Role_cb {#Role_cb}
```
public static final AttributeName Role_cb
```

Attribut Role: cb - Kontrollkästchen.

### Role_pb {#Role_pb}
```
public static final AttributeName Role_pb
```

Attribut Role: pb - Drucktaste.

### Role_rb {#Role_rb}
```
public static final AttributeName Role_rb
```

Attribut Rolle: rb - Radio-Button.

### Role_tv {#Role_tv}
```
public static final AttributeName Role_tv
```

Attribut Rolle: tv - Textwertfeld.

### RubyAlign_Center {#RubyAlign_Center}
```
public static final AttributeName RubyAlign_Center
```

Attribut RubyAlign: Center - Der Inhalt soll in der Inline‑Fortschritts‑Richtung zentriert werden.

### RubyAlign_Distribute {#RubyAlign_Distribute}
```
public static final AttributeName RubyAlign_Distribute
```

Attribut RubyAlign: Distribute - Der Inhalt soll in der Inline‑Fortschritts‑Richtung ausgedehnt werden, um die verfügbare Breite zu füllen. Allerdings soll am Anfangs‑ und Endrand des Textes ebenfalls Platz eingefügt werden. Der Abstand soll mit einem Verhältnis von 1:2:1 (Anfang:Zwischenteil:Ende) verteilt werden. Er wird zu einem Verhältnis von 0:1:1 geändert, wenn das ruby am Anfang einer Textzeile erscheint, oder zu einem Verhältnis von 1:1:0, wenn das ruby am Ende der Textzeile erscheint.

### RubyAlign_End {#RubyAlign_End}
```
public static final AttributeName RubyAlign_End
```

Attribut RubyAlign: End - Der Inhalt soll am Endrand in der Inline‑Fortschritts‑Richtung ausgerichtet werden.

### RubyAlign_Justify {#RubyAlign_Justify}
```
public static final AttributeName RubyAlign_Justify
```

Attribut RubyAlign: Justify - Der Inhalt soll in der Inline‑Fortschritts‑Richtung ausgedehnt werden, um die verfügbare Breite zu füllen.

### RubyAlign_Start {#RubyAlign_Start}
```
public static final AttributeName RubyAlign_Start
```

Attribut RubyAlign: Start - Der Inhalt soll am Anfangsrande in der Inline‑Fortschritts‑Richtung ausgerichtet werden.

### RubyPosition_After {#RubyPosition_After}
```
public static final AttributeName RubyPosition_After
```

Attribut RubyPosition: After - Der RT‑Inhalt soll entlang des Nach‑Randes des Elements ausgerichtet werden.

### RubyPosition_Before {#RubyPosition_Before}
```
public static final AttributeName RubyPosition_Before
```

Attribut RubyPosition: Before - Der RT‑Inhalt soll entlang des Vor‑Randes des Elements ausgerichtet werden.

### RubyPosition_Inline {#RubyPosition_Inline}
```
public static final AttributeName RubyPosition_Inline
```

Attribut RubyPosition: Inline - Der RT‑ und die zugehörigen RP‑Elemente sollen als Klammerkommentar formatiert werden, der dem RB‑Element folgt.

### RubyPosition_Warichu {#RubyPosition_Warichu}
```
public static final AttributeName RubyPosition_Warichu
```

Attribut RubyPosition: Warichu - Der RT‑ und die zugehörigen RP‑Elemente sollen als Warichu formatiert werden, der dem RB‑Element folgt.

### Scope_Both {#Scope_Both}
```
public static final AttributeName Scope_Both
```

Attribut Scope: Beide.

### Scope_Column {#Scope_Column}
```
public static final AttributeName Scope_Column
```

Attribut Scope: Spalte.

### Scope_Row {#Scope_Row}
```
public static final AttributeName Scope_Row
```

Attribut Scope: Zeile.

### TextAlign_Center {#TextAlign_Center}
```
public static final AttributeName TextAlign_Center
```

Attribut TextAlign: Center - Zentriert zwischen dem Anfangs‑ und Endrand.

### TextAlign_End {#TextAlign_End}
```
public static final AttributeName TextAlign_End
```

Attribut TextAlign: End - Am Endrand ausgerichtet.

### TextAlign_Justify {#TextAlign_Justify}
```
public static final AttributeName TextAlign_Justify
```

Attribut TextAlign: Justify - An beiden Rändern ausgerichtet, wobei der innere Abstand jeder Zeile bei Bedarf erweitert wird, um diese Ausrichtung zu erreichen. Die letzte (oder einzige) Zeile wird nur am Anfangsrande ausgerichtet.

### TextAlign_Start {#TextAlign_Start}
```
public static final AttributeName TextAlign_Start
```

Attribut TextAlign: Start - Am Anfangsrande ausgerichtet.

### TextDecorationType_LineThrough {#TextDecorationType_LineThrough}
```
public static final AttributeName TextDecorationType_LineThrough
```

Attribut TextDecorationType: LineThrough - Eine Linie durch die Mitte des Textes.

### TextDecorationType_None {#TextDecorationType_None}
```
public static final AttributeName TextDecorationType_None
```

Attribut TextDecorationType: None - Keine Textdekoration.

### TextDecorationType_Overline {#TextDecorationType_Overline}
```
public static final AttributeName TextDecorationType_Overline
```

Attribut TextDecorationType: Overline - Eine Linie über dem Text.

### TextDecorationType_Underline {#TextDecorationType_Underline}
```
public static final AttributeName TextDecorationType_Underline
```

Attribut TextDecorationType: Underline - Eine Linie unter dem Text.

### Width_Auto {#Width_Auto}
```
public static final AttributeName Width_Auto
```

Attribut Width: Auto - Die Breite des Elements wird durch die intrinsische Breite seines Inhalts bestimmt.

### WritingMode_LrTb {#WritingMode_LrTb}
```
public static final AttributeName WritingMode_LrTb
```

Attribut WritingMode: LrTb - Inline‑Fortschritt von links nach rechts; Block‑Fortschritt von oben nach unten. Dies ist der typische Schreibmodus für westliche Schriftsysteme.

### WritingMode_RlTb {#WritingMode_RlTb}
```
public static final AttributeName WritingMode_RlTb
```

Attribut WritingMode: RlTb - Inline‑Fortschritt von rechts nach links; Block‑Fortschritt von oben nach unten. Dies ist der typische Schreibmodus für arabische und hebräische Schriftsysteme.

### WritingMode_TbRl {#WritingMode_TbRl}
```
public static final AttributeName WritingMode_TbRl
```

Attribut WritingMode: TbRl - Inline-Fortschritt von oben nach unten; Block-Fortschritt von rechts nach links. Dies ist der typische Schreibmodus für chinesische und japanische Schriftsysteme.

### fromNameAttributeKey {#fromNameAttributeKey-java.lang.String-com.aspose.pdf.tagged.logicalstructure.AttributeKey-}
Liefert den Attributnamen für den Attributschlüssel.

### getAttributeKey {#getAttributeKey--}
```
public final AttributeKey getAttributeKey()
```

Liefert den Attributschlüssel.

**Returns:**
AttributeKey-Instanz

### getName {#getName--}
```
public final String getName()
```

Liefert den Namenswert des Attributs.

**Returns:**
String Wert

### toString {#toString--}
```
public String toString()
```

Gibt einen String zurück, der das aktuelle Objekt darstellt.

**Returns:**
String, der das aktuelle Objekt darstellt.
