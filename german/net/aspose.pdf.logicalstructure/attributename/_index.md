---
title: Class AttributeName
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.AttributeName Klasse. Stellt die Klasse für Attributnamenwerte dar
type: docs
weight: 6220
url: /de/net/aspose.pdf.logicalstructure/attributename/
---
## AttributName Klasse

Stellt die Klasse für Attributnamenwerte dar.

```csharp
public sealed class AttributeName
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AttributSchlüssel](../../aspose.pdf.logicalstructure/attributename/attributekey/) { get; } | Gibt den Attributschlüssel zurück. |
| [Name](../../aspose.pdf.logicalstructure/attributename/name/) { get; } | Gibt den Namen des Attributs zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [VonNameAttributSchlüssel](../../aspose.pdf.logicalstructure/attributename/fromnameattributekey/)(string, AttributSchlüssel) | Gibt den Attributnamen für den Attributschlüssel zurück. |
| override [ToString](../../aspose.pdf.logicalstructure/attributename/tostring/)() | Gibt eine Zeichenfolge zurück, die das aktuelle Objekt darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [BlockAusrichtung_Nach](../../aspose.pdf.logicalstructure/attributename/blockalign_after/) | Attribut BlockAusrichtung: Nach - Nachkante des Zuweisungsrechtecks des letzten Kindes, ausgerichtet mit dem Rechteck des Inhalts der Tabellenzelle. |
| static readonly [BlockAusrichtung_Vor](../../aspose.pdf.logicalstructure/attributename/blockalign_before/) | Attribut BlockAusrichtung: Vor - Vorkante des Zuweisungsrechtecks des ersten Kindes, ausgerichtet mit dem Rechteck des Inhalts der Tabellenzelle. |
| static readonly [BlockAusrichtung_Justify](../../aspose.pdf.logicalstructure/attributename/blockalign_justify/) | Attribut BlockAusrichtung: Justify - Kinder, die sowohl mit der Vor- als auch mit der Nachkante des Inhaltsrechtecks der Tabellenzelle ausgerichtet sind. Das erste Kind wird wie für Vor beschrieben platziert und das letzte Kind wie für Nach beschrieben, mit gleichmäßigem Abstand zwischen den Kindern. Wenn es nur ein Kind gibt, wird es nur mit der Vorkante ausgerichtet, wie für Vor. |
| static readonly [BlockAusrichtung_Mitte](../../aspose.pdf.logicalstructure/attributename/blockalign_middle/) | Attribut BlockAusrichtung: Mitte - Kinder, die innerhalb der Tabellenzelle zentriert sind. Der Abstand zwischen der Vorkante des Zuweisungsrechtecks des ersten Kindes und dem Rechteck des Inhalts der Tabellenzelle muss dem Abstand zwischen der Nachkante des Zuweisungsrechtecks des letzten Kindes und dem Rechteck des Inhalts der Tabellenzelle entsprechen. |
| static readonly [Randstil_Gestrichelt](../../aspose.pdf.logicalstructure/attributename/borderstyle_dashed/) | Attribut Randstil: Gestrichelt - Der Rand besteht aus einer Reihe kurzer Liniensegmente. |
| static readonly [Randstil_Punktiert](../../aspose.pdf.logicalstructure/attributename/borderstyle_dotted/) | Attribut Randstil: Punktiert - Der Rand besteht aus einer Reihe von Punkten. |
| static readonly [Randstil_Doppelt](../../aspose.pdf.logicalstructure/attributename/borderstyle_double/) | Attribut Randstil: Doppelt - Der Rand besteht aus zwei durchgehenden Linien. Die Summe der beiden Linien und der Abstand zwischen ihnen entspricht dem Wert von Randdicke. |
| static readonly [Randstil_Rille](../../aspose.pdf.logicalstructure/attributename/borderstyle_groove/) | Attribut Randstil: Rille - Der Rand sieht aus, als wäre er in die Leinwand eingraviert. |
| static readonly [Randstil_Verlöscht](../../aspose.pdf.logicalstructure/attributename/borderstyle_hidden/) | Attribut Randstil: Versteckt - Dasselbe wie Keine, außer in Bezug auf die Konfliktlösung für Tabellen-Elemente. |
| static readonly [Randstil_Eingefügt](../../aspose.pdf.logicalstructure/attributename/borderstyle_inset/) | Attribut Randstil: Eingefügt - Der Rand lässt die gesamte Box so aussehen, als wäre sie in die Leinwand eingebettet. |
| static readonly [Randstil_Keine](../../aspose.pdf.logicalstructure/attributename/borderstyle_none/) | Attribut Randstil: Keine - Kein Rand. Erzwingt den berechneten Wert der Randdicke auf 0. |
| static readonly [Randstil_Ausgestoßen](../../aspose.pdf.logicalstructure/attributename/borderstyle_outset/) | Attribut Randstil: Ausgestoßen - Der Rand lässt die gesamte Box so aussehen, als käme sie aus der Leinwand (das Gegenteil von Eingefügt). |
| static readonly [Randstil_Kante](../../aspose.pdf.logicalstructure/attributename/borderstyle_ridge/) | Attribut Randstil: Kante - Der Rand sieht aus, als käme er aus der Leinwand (das Gegenteil von Rille). |
| static readonly [Randstil_Durchgehend](../../aspose.pdf.logicalstructure/attributename/borderstyle_solid/) | Attribut Randstil: Durchgehend - Der Rand ist ein einzelnes Liniensegment. |
| static readonly [Überprüft_neutral](../../aspose.pdf.logicalstructure/attributename/checked_neutral/) | Attribut überprüft: Neutral - Der Zustand eines Optionsfeldes oder Kontrollkästchenfeldes. |
| static readonly [Überprüft_aus](../../aspose.pdf.logicalstructure/attributename/checked_off/) | Attribut überprüft: Aus - Der Zustand eines Optionsfeldes oder Kontrollkästchenfeldes. |
| static readonly [Überprüft_ein](../../aspose.pdf.logicalstructure/attributename/checked_on/) | Attribut überprüft: Ein - Der Zustand eines Optionsfeldes oder Kontrollkästchenfeldes. |
| static readonly [GlyphenOrientierungVertikal_Auto](../../aspose.pdf.logicalstructure/attributename/glyphorientationvertical_auto/) | Attribut GlyphenOrientierungVertikal: Auto - Gibt eine Standardorientierung für Text an, abhängig davon, ob er vollbreit (so breit wie hoch) ist. |
| static readonly [Höhe_Auto](../../aspose.pdf.logicalstructure/attributename/height_auto/) | Attribut Höhe: Auto - Die Höhe des Elements wird durch die intrinsische Höhe seines Inhalts bestimmt. |
| static readonly [InlineAusrichtung_Zentrum](../../aspose.pdf.logicalstructure/attributename/inlinealign_center/) | Attribut InlineAusrichtung: Zentrum - Jedes Kind wird innerhalb der Tabellenzelle zentriert. Der Abstand zwischen den Startkanten des Zuweisungsrechtecks des Kindes und dem Inhaltsrechteck der Tabellenzelle muss dem Abstand zwischen ihren Endkanten entsprechen. |
| static readonly [InlineAusrichtung_Ende](../../aspose.pdf.logicalstructure/attributename/inlinealign_end/) | Attribut InlineAusrichtung: Ende - Endkante des Zuweisungsrechtecks jedes Kindes, ausgerichtet mit dem Rechteck des Inhalts der Tabellenzelle. |
| static readonly [InlineAusrichtung_Start](../../aspose.pdf.logicalstructure/attributename/inlinealign_start/) | Attribut InlineAusrichtung: Start - Startkante des Zuweisungsrechtecks jedes Kindes, ausgerichtet mit dem Rechteck des Inhalts der Tabellenzelle. |
| static readonly [Zeilenhöhe_Auto](../../aspose.pdf.logicalstructure/attributename/lineheight_auto/) | Attribut Zeilenhöhe: Auto - Anpassungen für den Wert von BaselineShift werden nicht vorgenommen. |
| static readonly [Zeilenhöhe_Normal](../../aspose.pdf.logicalstructure/attributename/lineheight_normal/) | Attribut Zeilenhöhe: Normal - Passt die Zeilenhöhe an, um jeden nicht nullen Wert für BaselineShift einzuschließen. |
| static readonly [ListenNummerierung_Kreis](../../aspose.pdf.logicalstructure/attributename/listnumbering_circle/) | Attribut ListenNummerierung: Kreis - Offene kreisförmige Aufzählung. |
| static readonly [ListenNummerierung_Dezimal](../../aspose.pdf.logicalstructure/attributename/listnumbering_decimal/) | Attribut ListenNummerierung: Dezimal - Dezimale arabische Ziffern (1-9, 10-99, ...). |
| static readonly [ListenNummerierung_Scheibe](../../aspose.pdf.logicalstructure/attributename/listnumbering_disc/) | Attribut ListenNummerierung: Scheibe - Solide kreisförmige Aufzählung. |
| static readonly [ListenNummerierung_Kleinbuchstaben](../../aspose.pdf.logicalstructure/attributename/listnumbering_loweralpha/) | Attribut ListenNummerierung: Kleinbuchstaben - Kleinbuchstaben (a, b, c, ...). |
| static readonly [ListenNummerierung_Kleinrömisch](../../aspose.pdf.logicalstructure/attributename/listnumbering_lowerroman/) | Attribut ListenNummerierung: Kleinrömisch - Kleinrömische Ziffern (i, ii, iii, iv, ...). |
| static readonly [ListenNummerierung_Keine](../../aspose.pdf.logicalstructure/attributename/listnumbering_none/) | Attribut ListenNummerierung: Keine - Keine automatische Nummerierung; Lbl-Elemente (falls vorhanden) enthalten beliebigen Text, der keinem Nummerierungsschema unterliegt. |
| static readonly [ListenNummerierung_Quadrat](../../aspose.pdf.logicalstructure/attributename/listnumbering_square/) | Attribut ListenNummerierung: Quadrat - Solide quadratische Aufzählung. |
| static readonly [ListenNummerierung_Großbuchstaben](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperalpha/) | Attribut ListenNummerierung: Großbuchstaben - Großbuchstaben (A, B, C, ...). |
| static readonly [ListenNummerierung_Großrömisch](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperroman/) | Attribut ListenNummerierung: Großrömisch - Großrömische Ziffern (I, II, III, IV, ...). |
| static readonly [Platzierung_Vor](../../aspose.pdf.logicalstructure/attributename/placement_before/) | Attribut Platzierung: Vor - So platziert, dass die Vorkante des Zuweisungsrechtecks des Elements mit der des nächstgelegenen umschließenden Referenzbereichs übereinstimmt. |
| static readonly [Platzierung_Block](../../aspose.pdf.logicalstructure/attributename/placement_block/) | Attribut Platzierung: Block - In der Blockfortschrittsrichtung innerhalb eines umschließenden Referenzbereichs oder übergeordneten BLSE gestapelt. |
| static readonly [Platzierung_Ende](../../aspose.pdf.logicalstructure/attributename/placement_end/) | Attribut Platzierung: Ende - So platziert, dass die Endkante des Zuweisungsrechtecks des Elements mit der des nächstgelegenen umschließenden Referenzbereichs übereinstimmt. |
| static readonly [Platzierung_Inline](../../aspose.pdf.logicalstructure/attributename/placement_inline/) | Attribut Platzierung: Inline - In der Inline-Fortschrittsrichtung innerhalb eines umschließenden BLSE gepackt. |
| static readonly [Platzierung_Start](../../aspose.pdf.logicalstructure/attributename/placement_start/) | Attribut Platzierung: Start - So platziert, dass die Startkante des Zuweisungsrechtecks des Elements mit der des nächstgelegenen umschließenden Referenzbereichs übereinstimmt. |
| static readonly [Rolle_cb](../../aspose.pdf.logicalstructure/attributename/role_cb/) | Attribut Rolle: cb - Kontrollkästchen. |
| static readonly [Rolle_pb](../../aspose.pdf.logicalstructure/attributename/role_pb/) | Attribut Rolle: pb - Druckknopf. |
| static readonly [Rolle_rb](../../aspose.pdf.logicalstructure/attributename/role_rb/) | Attribut Rolle: rb - Optionsfeld. |
| static readonly [Rolle_tv](../../aspose.pdf.logicalstructure/attributename/role_tv/) | Attribut Rolle: tv - Text-Wert-Feld. |
| static readonly [RubyAusrichtung_Zentrum](../../aspose.pdf.logicalstructure/attributename/rubyalign_center/) | Attribut RubyAusrichtung: Zentrum - Der Inhalt wird in der Inline-Fortschrittsrichtung zentriert. |
| static readonly [RubyAusrichtung_Verteilen](../../aspose.pdf.logicalstructure/attributename/rubyalign_distribute/) | Attribut RubyAusrichtung: Verteilen - Der Inhalt wird erweitert, um die verfügbare Breite in der Inline-Fortschrittsrichtung auszufüllen. Es wird jedoch auch Platz an der Start- und Endkante des Textes eingefügt. Der Abstand wird im Verhältnis 1:2:1 (Start:Infix:Ende) verteilt. Er wird auf ein Verhältnis von 0:1:1 geändert, wenn der Ruby am Anfang einer Textzeile erscheint, oder auf ein Verhältnis von 1:1:0, wenn der Ruby am Ende der Textzeile erscheint. |
| static readonly [RubyAusrichtung_Ende](../../aspose.pdf.logicalstructure/attributename/rubyalign_end/) | Attribut RubyAusrichtung: Ende - Der Inhalt wird an der Endkante in der Inline-Fortschrittsrichtung ausgerichtet. |
| static readonly [RubyAusrichtung_Justify](../../aspose.pdf.logicalstructure/attributename/rubyalign_justify/) | Attribut RubyAusrichtung: Justify - Der Inhalt wird erweitert, um die verfügbare Breite in der Inline-Fortschrittsrichtung auszufüllen. |
| static readonly [RubyAusrichtung_Start](../../aspose.pdf.logicalstructure/attributename/rubyalign_start/) | Attribut RubyAusrichtung: Start - Der Inhalt wird an der Startkante in der Inline-Fortschrittsrichtung ausgerichtet. |
| static readonly [RubyPosition_Nach](../../aspose.pdf.logicalstructure/attributename/rubyposition_after/) | Attribut RubyPosition: Nach - Der RT-Inhalt wird entlang der Nachkante des Elements ausgerichtet. |
| static readonly [RubyPosition_Vor](../../aspose.pdf.logicalstructure/attributename/rubyposition_before/) | Attribut RubyPosition: Vor - Der RT-Inhalt wird entlang der Vorkante des Elements ausgerichtet. |
| static readonly [RubyPosition_Inline](../../aspose.pdf.logicalstructure/attributename/rubyposition_inline/) | Attribut RubyPosition: Inline - Der RT- und die zugehörigen RP-Elemente werden als Klammerkommentar formatiert, der dem RB-Element folgt. |
| static readonly [RubyPosition_Warichu](../../aspose.pdf.logicalstructure/attributename/rubyposition_warichu/) | Attribut RubyPosition: Warichu - Der RT- und die zugehörigen RP-Elemente werden als Warichu formatiert, die dem RB-Element folgt. |
| static readonly [Umfang_Beide](../../aspose.pdf.logicalstructure/attributename/scope_both/) | Attribut Umfang: Beide. |
| static readonly [Umfang_Spalte](../../aspose.pdf.logicalstructure/attributename/scope_column/) | Attribut Umfang: Spalte. |
| static readonly [Umfang_Reihe](../../aspose.pdf.logicalstructure/attributename/scope_row/) | Attribut Umfang: Reihe. |
| static readonly [TextAusrichtung_Zentrum](../../aspose.pdf.logicalstructure/attributename/textalign_center/) | Attribut TextAusrichtung: Zentrum - Zentriert zwischen den Start- und Endkanten. |
| static readonly [TextAusrichtung_Ende](../../aspose.pdf.logicalstructure/attributename/textalign_end/) | Attribut TextAusrichtung: Ende - Ausgerichtet mit der Endkante. |
| static readonly [TextAusrichtung_Justify](../../aspose.pdf.logicalstructure/attributename/textalign_justify/) | Attribut TextAusrichtung: Justify - Ausgerichtet mit sowohl der Start- als auch der Endkante, wobei der interne Abstand innerhalb jeder Zeile bei Bedarf erweitert wird, um eine solche Ausrichtung zu erreichen. Die letzte (oder einzige) Zeile wird nur mit der Startkante ausgerichtet. |
| static readonly [TextAusrichtung_Start](../../aspose.pdf.logicalstructure/attributename/textalign_start/) | Attribut TextAusrichtung: Start - Ausgerichtet mit der Startkante. |
| static readonly [TextDekorationstyp_Durchgestrichen](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_linethrough/) | Attribut TextDekorationstyp: Durchgestrichen - Eine Linie durch die Mitte des Textes. |
| static readonly [TextDekorationstyp_Keine](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_none/) | Attribut TextDekorationstyp: Keine - Keine Textdekoration. |
| static readonly [TextDekorationstyp_Überlinie](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_overline/) | Attribut TextDekorationstyp: Überlinie - Eine Linie über dem Text. |
| static readonly [TextDekorationstyp_Underline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_underline/) | Attribut TextDekorationstyp: Unterstrichen - Eine Linie unter dem Text. |
| static readonly [Breite_Auto](../../aspose.pdf.logicalstructure/attributename/width_auto/) | Attribut Breite: Auto - Die Breite des Elements wird durch die intrinsische Breite seines Inhalts bestimmt. |
| static readonly [Schreibmodus_LrTb](../../aspose.pdf.logicalstructure/attributename/writingmode_lrtb/) | Attribut Schreibmodus: LrTb - Inline-Fortschritt von links nach rechts; Blockfortschritt von oben nach unten. Dies ist der typische Schreibmodus für westliche Schriftsysteme. |
| static readonly [Schreibmodus_RlTb](../../aspose.pdf.logicalstructure/attributename/writingmode_rltb/) | Attribut Schreibmodus: RlTb - Inline-Fortschritt von rechts nach links; Blockfortschritt von oben nach unten. Dies ist der typische Schreibmodus für arabische und hebräische Schriftsysteme. |
| static readonly [Schreibmodus_TbRl](../../aspose.pdf.logicalstructure/attributename/writingmode_tbrl/) | Attribut Schreibmodus: TbRl - Inline-Fortschritt von oben nach unten; Blockfortschritt von rechts nach links. Dies ist der typische Schreibmodus für chinesische und japanische Schriftsysteme. |

### Siehe auch

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)