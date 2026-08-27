---
title: "AttributeName"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt eine Klasse für Attributnamenwerte dar."
type: docs
weight: 50
url: /de/python-net/aspose.pdf.logicalstructure/attributename/
---

## AttributeName class

Stellt eine Klasse für Attributnamenwerte dar.

Der AttributeName-Typ stellt die folgenden Member bereit:
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| Name | Liefert den Namenswert des Attributs. |
| attribute_key | Gibt den Attributschlüssel zurück. |
| PLACEMENT_BLOCK | Attributplatzierung: Block – Gestapelt in Richtung der Blockfortschrittsrichtung innerhalb eines umschließenden Referenzbereichs oder übergeordneten BLSE. |
| PLACEMENT_INLINE | Attributplatzierung: Inline – Angeordnet in Richtung des Inline-Fortschritts innerhalb eines umschließenden BLSE. |
| PLACEMENT_BEFORE | Attributplatzierung: Before – Platziert, sodass die vordere Kante des Zuweisungsrechtecks des Elements mit der des nächstgelegenen umschließenden Referenzbereichs übereinstimmt. |
| PLACEMENT_START | Attributplatzierung: Start – Platziert, sodass die Startkante des Zuweisungsrechtecks des Elements mit der des nächstgelegenen umschließenden Referenzbereichs übereinstimmt. |
| PLACEMENT_END | Attributplatzierung: End – Platziert, sodass die Endkante des Zuweisungsrechtecks des Elements mit der des nächstgelegenen umschließenden Referenzbereichs übereinstimmt. |
| WRITING_MODE_LR_TB | Schreibmodus-Attribut: LrTb – Inline-Fortschritt von links nach rechts; Block-Fortschritt von oben nach unten. Dies ist der typische Schreibmodus für westliche Schriftsysteme. |
| WRITING_MODE_RL_TB | Schreibmodus-Attribut: RlTb – Inline-Fortschritt von rechts nach links; Block-Fortschritt von oben nach unten. Dies ist der typische Schreibmodus für arabische und hebräische Schriftsysteme. |
| WRITING_MODE_TB_RL | Schreibmodus-Attribut: TbRl – Inline-Fortschritt von oben nach unten; Block-Fortschritt von rechts nach links. Dies ist der typische Schreibmodus für chinesische und japanische Schriftsysteme. |
| BORDER_STYLE_NONE | BorderStyle-Attribut: None – Kein Rahmen. Erzwingt, dass der berechnete Wert von BorderThicknessto 0 ist. |
| BORDER_STYLE_HIDDEN | BorderStyle-Attribut: Hidden – Gleich wie None, jedoch hinsichtlich der Konfliktlösung von Rahmen für Tabellenelemente. |
| BORDER_STYLE_DOTTED | Attribut BorderStyle: Dotted - Der Rand ist eine Reihe von Punkten. |
| BORDER_STYLE_DASHED | Attribut BorderStyle: Dashed - Der Rand ist eine Reihe kurzer Liniensegmente. |
| BORDER_STYLE_SOLID | Attribut BorderStyle: Solid - Der Rand ist ein einzelnes Liniensegment. |
| BORDER_STYLE_DOUBLE | Attribut BorderStyle: Double - Der Rand besteht aus zwei durchgezogenen Linien. Die Summe der beiden Linien und des dazwischen liegenden Abstands entspricht dem Wert von BorderThickness. |
| BORDER_STYLE_GROOVE | Attribut BorderStyle: Groove - Der Rand sieht so aus, als wäre er in die Leinwand eingraviert. |
| BORDER_STYLE_RIDGE | Attribut BorderStyle: Ridge - Der Rand sieht so aus, als käme er aus der Leinwand heraus (das Gegenteil von Groove). |
| BORDER_STYLE_INSET | Attribut BorderStyle: Inset - Der Rand lässt die gesamte Box so aussehen, als wäre sie in die Leinwand eingebettet. |
| BORDER_STYLE_OUTSET | Attribut BorderStyle: Outset - Der Rand lässt die gesamte Box so aussehen, als käme sie aus der Leinwand heraus (das Gegenteil von Inset). |
| TEXT_ALIGN_START | Attribut TextAlign: Start - Ausgerichtet an der Startkante. |
| TEXT_ALIGN_CENTER | Attribut TextAlign: Center - Zentriert zwischen der Start- und Endkante. |
| TEXT_ALIGN_END | Attribut TextAlign: End - Ausgerichtet an der Endkante. |
| TEXT_ALIGN_JUSTIFY | Attribut TextAlign: Justify - Ausgerichtet an sowohl der Start- als auch der Endkante, wobei der innere Abstand jeder Zeile bei Bedarf erweitert wird, um diese Ausrichtung zu erreichen. Die letzte (oder einzige) Zeile wird nur an der Startkante ausgerichtet. |
| WIDTH_AUTO | Attribut Width: Auto - Die Breite des Elements wird durch die intrinsische Breite seines Inhalts bestimmt. |
| HEIGHT_AUTO | Attribut Height: Auto - Die Höhe des Elements wird durch die intrinsische Höhe seines Inhalts bestimmt. |
| BLOCK_ALIGN_BEFORE | Attribut BlockAlign: Before - Die Vorderkante des Zuweisungsrechtecks des ersten Kindes ist mit der des Inhaltsrechtecks der Tabellenzelle ausgerichtet. |
| BLOCK_ALIGN_MIDDLE | Attribut BlockAlign: Middle - Kinder sind innerhalb der Tabellenzelle zentriert. Der Abstand zwischen der Vorderkante des Zuweisungsrechtecks des ersten Kindes und der des Inhaltsrechtecks der Tabellenzelle muss derselbe sein wie der Abstand zwischen der Hinterkante des Zuweisungsrechtecks des letzten Kindes und der des Inhaltsrechtecks der Tabellenzelle. |
| BLOCK_ALIGN_AFTER | Attribut BlockAlign: After - Die Hinterkante des Zuweisungsrechtecks des letzten Kindes ist mit der des Inhaltsrechtecks der Tabellenzelle ausgerichtet. |
| BLOCK_ALIGN_JUSTIFY | Attribut BlockAlign: Justify - Kinder sind sowohl an der Vorder- als auch an der Hinterkante des Inhaltsrechtecks der Tabellenzelle ausgerichtet. Das erste Kind wird wie bei Before platziert und das letzte Kind wie bei After, mit gleichem Abstand zwischen den Kindern. Gibt es nur ein Kind, wird es nur an der Vorderkante ausgerichtet, wie bei Before. |
| INLINE_ALIGN_START | Attribut InlineAlign: Start - Die Startkante des Zuweisungsrechtecks jedes Kindes ist mit der des Inhaltsrechtecks der Tabellenzelle ausgerichtet. |
| INLINE_ALIGN_CENTER | Attribut InlineAlign: Center - Jedes Kind ist innerhalb der Tabellenzelle zentriert. Der Abstand zwischen den Startkanten des Zuweisungsrechtecks des Kindes und des Inhaltsrechtecks der Tabellenzelle muss derselbe sein wie der Abstand zwischen deren Endkanten. |
| INLINE_ALIGN_END | Attribut InlineAlign: End - Die Endkante des Zuweisungsrechtecks jedes Kindes ist mit der des Inhaltsrechtecks der Tabellenzelle ausgerichtet. |
| LINE_HEIGHT_NORMAL | Attribut LineHeight: Normal - Die Zeilenhöhe wird angepasst, um einen beliebigen von BaselineShift angegebenen von Null verschiedenen Wert einzuschließen. |
| LINE_HEIGHT_AUTO | Attribut LineHeight: Auto - Es wird keine Anpassung des Wertes von BaselineShift vorgenommen. |
| TEXT_DECORATION_TYPE_NONE | Attribut TextDecorationType: None - Keine Textdekoration. |
| TEXT_DECORATION_TYPE_UNDERLINE | Attribut TextDecorationType: Underline - Eine Linie unter dem Text. |
| TEXT_DECORATION_TYPE_OVERLINE | Attribut TextDecorationType: Overline - Eine Linie über dem Text. |
| TEXT_DECORATION_TYPE_LINE_THROUGH | Attribut TextDecorationType: LineThrough - Eine Linie durch die Mitte des Textes. |
| RUBY_ALIGN_START | Attribut RubyAlign: Start - Der Inhalt soll am Startkantenrand in der Inline‑Fortschrittsrichtung ausgerichtet werden. |
| RUBY_ALIGN_CENTER | Attribut RubyAlign: Center - Der Inhalt soll in der Inline‑Fortschrittsrichtung zentriert werden. |
| RUBY_ALIGN_END | Attribut RubyAlign: End - Der Inhalt soll am Endkantenrand in der Inline‑Fortschrittsrichtung ausgerichtet werden. |
| RUBY_ALIGN_JUSTIFY | Attribut RubyAlign: Justify - Der Inhalt soll erweitert werden, um die verfügbare Breite in der Inline‑Fortschrittsrichtung zu füllen. |
| RUBY_ALIGN_DISTRIBUTE | Attribut RubyAlign: Distribute - Der Inhalt soll erweitert werden, um die verfügbare Breite in der Inline‑Fortschrittsrichtung zu füllen. Allerdings soll am Startkantenrand und Endkantenrand des Textes ebenfalls Platz eingefügt werden. Der Abstand soll im Verhältnis 1:2:1 (Start:Infix:Ende) verteilt werden. Er wird zu einem Verhältnis 0:1:1 geändert, wenn das Ruby am Anfang einer Textzeile erscheint, oder zu einem Verhältnis 1:1:0, wenn das Ruby am Ende der Textzeile erscheint. |
| RUBY_POSITION_BEFORE | Attribut RubyPosition: Before - Der RT‑Inhalt soll entlang der Vorderkante des Elements ausgerichtet werden. |
| RUBY_POSITION_AFTER | Attribut RubyPosition: After - Der RT‑Inhalt soll entlang der Nachkante des Elements ausgerichtet werden. |
| RUBY_POSITION_WARICHU | Attribut RubyPosition: Warichu - Der RT‑ und die zugehörigen RP‑Elemente sollen als Warichu formatiert werden, nach dem RB‑Element. |
| RUBY_POSITION_INLINE | Attribut RubyPosition: Inline - Der RT‑ und die zugehörigen RP‑Elemente sollen als Klammerkommentar formatiert werden, nach dem RB‑Element. |
| GLYPH_ORIENTATION_VERTICAL_AUTO | Attribut GlyphOrientationVertical: Auto - Gibt eine Standardorientierung für Text an, abhängig davon, ob er vollbreit (so breit wie hoch) ist. |
| LIST_NUMBERING_NONE | Attribut ListNumbering: None - Keine automatische Nummerierung; Lbl‑Elemente (falls vorhanden) enthalten beliebigen Text, der nicht einem Nummerierungsschema unterliegt. |
| LIST_NUMBERING_DISC | Attribut ListNumbering: Disc - Solider kreisförmiger Aufzählungspunkt. |
| LIST_NUMBERING_CIRCLE | Attribut ListNumbering: Circle - Offener kreisförmiger Aufzählungszeichen. |
| LIST_NUMBERING_SQUARE | Attribut ListNumbering: Square - Solides quadratisches Aufzählungszeichen. |
| LIST_NUMBERING_DECIMAL | Attribut ListNumbering: Decimal - Dezimale arabische Ziffern (1-9, 10-99, ...). |
| LIST_NUMBERING_UPPER_ROMAN | Attribut ListNumbering: UpperRoman - Großbuchstaben‑römische Ziffern (I, II, III, IV, ...). |
| LIST_NUMBERING_LOWER_ROMAN | Attribut ListNumbering: LowerRoman - Kleinbuchstaben‑römische Ziffern (i, ii, iii, iv, ...). |
| LIST_NUMBERING_UPPER_ALPHA | Attribut ListNumbering: UpperAlpha - Großbuchstaben (A, B, C, ...). |
| LIST_NUMBERING_LOWER_ALPHA | Attribut ListNumbering: LowerAlpha - Kleinbuchstaben (a, b, c, ...). |
| ROLE_RB | Attribut Role: rb - Optionsfeld. |
| ROLE_CB | Attribut Role: cb - Kontrollkästchen. |
| ROLE_PB | Attribut Role: pb - Schaltfläche. |
| ROLE_TV | Attribut Role: tv - Textwertfeld. |
| CHECKED_ON | Attribut checked: On - Der Zustand eines Optionsfelds oder Kontrollkästchens. |
| CHECKED_OFF | Attribut checked: Off - Der Zustand eines Optionsfelds oder Kontrollkästchens. |
| CHECKED_NEUTRAL | Attribut geprüft: Neutral - Der Zustand eines Optionsschalters oder Kontrollkästchenfeldes. |
| SCOPE_ROW | Attributbereich: Zeile. |
| SCOPE_COLUMN | Attributbereich: Spalte. |
| SCOPE_BOTH | Attributbereich: Beide. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| from_name_attribute_key(name, attribute_key) | Ermittelt den Attributnamen für den Attributschlüssel. |

### Siehe auch

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

