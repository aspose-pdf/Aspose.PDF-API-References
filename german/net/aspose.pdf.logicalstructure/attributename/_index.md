---
title: AttributeName
second_title: Aspose.PDF für .NET-API-Referenz
description: Stellt die Klasse für Attributnamenswerte dar.
type: docs
weight: 4050
url: /de/net/aspose.pdf.logicalstructure/attributename/
---
## AttributeName class

Stellt die Klasse für Attributnamenswerte dar.

```csharp
public sealed class AttributeName
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AttributeKey](../../aspose.pdf.logicalstructure/attributename/attributekey) { get; } | Ruft den Attributschlüssel ab. |
| [Name](../../aspose.pdf.logicalstructure/attributename/name) { get; } | Ruft den Namenswert des Attributs ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromNameAttributeKey](../../aspose.pdf.logicalstructure/attributename/fromnameattributekey)(string, AttributeKey) | Ruft den Attributnamen für den Attributschlüssel ab. |
| override [ToString](../../aspose.pdf.logicalstructure/attributename/tostring)() | Gibt eine Zeichenfolge zurück, die das aktuelle Objekt darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [BlockAlign_After](../../aspose.pdf.logicalstructure/attributename/blockalign_after) | Attribut BlockAlign: After - Nachdem die Kante des Zuordnungsrechtecks des letzten untergeordneten Elements an der des Inhaltsrechtecks der Tabellenzelle ausgerichtet ist. |
| static readonly [BlockAlign_Before](../../aspose.pdf.logicalstructure/attributename/blockalign_before) | Attribut BlockAlign: Before – Vor dem Rand des Zuweisungsrechtecks des ersten untergeordneten Elements, ausgerichtet an dem des Inhaltsrechtecks der Tabellenzelle. |
| static readonly [BlockAlign_Justify](../../aspose.pdf.logicalstructure/attributename/blockalign_justify) | Attribut BlockAlign: Justify – Untergeordnete Elemente werden sowohl an den Kanten davor als auch danach des Inhaltsrechtecks der Tabellenzelle ausgerichtet. Das erste Kind wird wie unter „Vorher“ beschrieben und das letzte Kind wie unter „Nachher“ beschrieben platziert, mit gleichem Abstand zwischen den Kindern. Wenn es nur ein untergeordnetes Element gibt, wird es nur an der Before-Kante ausgerichtet, wie bei Before. |
| static readonly [BlockAlign_Middle](../../aspose.pdf.logicalstructure/attributename/blockalign_middle) | Attribut BlockAlign: Middle- Children zentriert innerhalb der Tabellenzelle. Der Abstand zwischen der Vorkante des Zuordnungsrechtecks des ersten untergeordneten Elements und dem Inhaltsrechteck der Tabellenzelle muss gleich sein wie der Abstand zwischen der Nachkante des Zuordnungsrechtecks des letzten untergeordneten Elements und dem Inhaltsrechteck der Tabellenzelle. |
| static readonly [BorderStyle_Dashed](../../aspose.pdf.logicalstructure/attributename/borderstyle_dashed) | Attribut BorderStyle: Dashed – Der Rahmen besteht aus einer Reihe kurzer Liniensegmente. |
| static readonly [BorderStyle_Dotted](../../aspose.pdf.logicalstructure/attributename/borderstyle_dotted) | Attribut BorderStyle: Dotted - Der Rahmen besteht aus einer Reihe von Punkten. |
| static readonly [BorderStyle_Double](../../aspose.pdf.logicalstructure/attributename/borderstyle_double) | Attribut BorderStyle: Double - Der Rahmen besteht aus zwei durchgezogenen Linien. Die Summe der beiden Linien und des Abstands zwischen ihnen entspricht dem Wert von BorderThickness. |
| static readonly [BorderStyle_Groove](../../aspose.pdf.logicalstructure/attributename/borderstyle_groove) | Attribut BorderStyle: Groove - Der Rand sieht aus, als wäre er in die Leinwand geschnitzt. |
| static readonly [BorderStyle_Hidden](../../aspose.pdf.logicalstructure/attributename/borderstyle_hidden) | Attribut BorderStyle: Hidden – Dasselbe wie None, außer in Bezug auf die Auflösung von Rahmenkonflikten für Tabellenelemente. |
| static readonly [BorderStyle_Inset](../../aspose.pdf.logicalstructure/attributename/borderstyle_inset) | Attribut BorderStyle: Inset – Der Rahmen lässt die gesamte Box so aussehen, als wäre sie in die Leinwand eingebettet. |
| static readonly [BorderStyle_None](../../aspose.pdf.logicalstructure/attributename/borderstyle_none) | Attribut BorderStyle: None - Kein Rahmen. Erzwingt den berechneten Wert von BorderThickness auf 0. |
| static readonly [BorderStyle_Outset](../../aspose.pdf.logicalstructure/attributename/borderstyle_outset) | Attribut BorderStyle: Outset – Der Rahmen lässt die gesamte Box so aussehen, als käme sie aus der Leinwand (das Gegenteil von Inset). |
| static readonly [BorderStyle_Ridge](../../aspose.pdf.logicalstructure/attributename/borderstyle_ridge) | Attribut BorderStyle: Ridge – Der Rand sieht aus, als käme er aus der Leinwand (das Gegenteil von Groove). |
| static readonly [BorderStyle_Solid](../../aspose.pdf.logicalstructure/attributename/borderstyle_solid) | Attribute BorderStyle: Solid - Der Rahmen ist ein einzelnes Liniensegment. |
| static readonly [Checked_neutral](../../aspose.pdf.logicalstructure/attributename/checked_neutral) | Attribut überprüft: Neutral – Der Status eines Optionsfelds oder Kontrollkästchenfelds. |
| static readonly [Checked_off](../../aspose.pdf.logicalstructure/attributename/checked_off) | Attribut geprüft: Aus – Der Status eines Optionsfelds oder Kontrollkästchenfelds. |
| static readonly [Checked_on](../../aspose.pdf.logicalstructure/attributename/checked_on) | Attribut geprüft: Ein – Der Status eines Optionsfelds oder Kontrollkästchenfelds. |
| static readonly [GlyphOrientationVertical_Auto](../../aspose.pdf.logicalstructure/attributename/glyphorientationvertical_auto) | Attribut GlyphOrientationVertical: Auto – Gibt eine Standardausrichtung für Text an, abhängig davon, ob er die volle Breite hat (so breit wie hoch). |
| static readonly [Height_Auto](../../aspose.pdf.logicalstructure/attributename/height_auto) | Attribut Höhe: Auto - Die Höhe des Elements wird durch die intrinsische Höhe seines Inhalts bestimmt. |
| static readonly [InlineAlign_Center](../../aspose.pdf.logicalstructure/attributename/inlinealign_center) | Attribut InlineAlign: Center - Jedes untergeordnete Element wird innerhalb der Tabellenzelle zentriert. Der Abstand zwischen den Anfangskanten des Zuordnungsrechtecks des untergeordneten Elements und dem Inhaltsrechteck der Tabellenzelle muss gleich dem Abstand zwischen ihren Endkanten sein. |
| static readonly [InlineAlign_End](../../aspose.pdf.logicalstructure/attributename/inlinealign_end) | Attribut InlineAlign: End – Endkante des Zuordnungsrechtecks jedes untergeordneten Elements, ausgerichtet an der des Inhaltsrechtecks der Tabellenzelle. |
| static readonly [InlineAlign_Start](../../aspose.pdf.logicalstructure/attributename/inlinealign_start) | Attribut InlineAlign: Start – Anfangskante des Zuordnungsrechtecks jedes untergeordneten Elements ausgerichtet mit der des Inhaltsrechtecks der Tabellenzelle. |
| static readonly [LineHeight_Auto](../../aspose.pdf.logicalstructure/attributename/lineheight_auto) | Attribut LineHeight: Auto - Anpassung für den Wert von BaselineShift soll nicht vorgenommen werden. |
| static readonly [LineHeight_Normal](../../aspose.pdf.logicalstructure/attributename/lineheight_normal) | Attribut LineHeight: Normal – Passen Sie die Zeilenhöhe so an, dass alle für BaselineShift angegebenen Werte ungleich Null enthalten sind. |
| static readonly [ListNumbering_Circle](../../aspose.pdf.logicalstructure/attributename/listnumbering_circle) | Attribut ListNumbering: Circle - Kreisförmiges Aufzählungszeichen öffnen. |
| static readonly [ListNumbering_Decimal](../../aspose.pdf.logicalstructure/attributename/listnumbering_decimal) | Attribute ListNumbering: Decimal - Arabische Dezimalzahlen (1-9, 10-99, ...). |
| static readonly [ListNumbering_Disc](../../aspose.pdf.logicalstructure/attributename/listnumbering_disc) | Attribut ListNumbering: Disc - Vollständiges kreisförmiges Aufzählungszeichen. |
| static readonly [ListNumbering_LowerAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_loweralpha) | Attribut ListNumbering: LowerAlpha - Kleinbuchstaben (a, b, c, ...). |
| static readonly [ListNumbering_LowerRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_lowerroman) | Attribut ListNumbering: LowerRoman - römische Ziffern in Kleinbuchstaben (i, ii, iii, iv, ...). |
| static readonly [ListNumbering_None](../../aspose.pdf.logicalstructure/attributename/listnumbering_none) | Attribut ListNumbering: None - Keine automatische Nummerierung; Lbl-Elemente (falls vorhanden) enthalten beliebigen Text, der keinem Nummerierungsschema unterliegt. |
| static readonly [ListNumbering_Square](../../aspose.pdf.logicalstructure/attributename/listnumbering_square) | Attribut ListNumbering: Square - Vollständiges quadratisches Aufzählungszeichen. |
| static readonly [ListNumbering_UpperAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperalpha) | Attribut ListNumbering: UpperAlpha - Großbuchstaben (A, B, C, ...). |
| static readonly [ListNumbering_UpperRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperroman) | Attribute ListNumbering: UpperRoman - Römische Ziffern in Großbuchstaben (I, II, III, IV, ...). |
| static readonly [Placement_Before](../../aspose.pdf.logicalstructure/attributename/placement_before) | Attributplatzierung: Vorher - Wird so platziert, dass die Vorher-Kante des Zuordnungsrechtecks des Elements mit der des nächsten umschließenden Referenzbereichs zusammenfällt. |
| static readonly [Placement_Block](../../aspose.pdf.logicalstructure/attributename/placement_block) | Attributplatzierung: Block – Gestapelt in Blockfortschrittsrichtung innerhalb eines umschließenden Referenzbereichs oder übergeordneten BLSE. |
| static readonly [Placement_End](../../aspose.pdf.logicalstructure/attributename/placement_end) | Attributplatzierung: Ende - Wird so platziert, dass die Endkante des Zuordnungsrechtecks des Elements mit der des nächsten umschließenden Referenzbereichs zusammenfällt. |
| static readonly [Placement_Inline](../../aspose.pdf.logicalstructure/attributename/placement_inline) | Attributplatzierung: Inline – Gepackt in der Inline-Progressionsrichtung innerhalb einer umschließenden BLSE. |
| static readonly [Placement_Start](../../aspose.pdf.logicalstructure/attributename/placement_start) | Attributplatzierung: Start - Wird so platziert, dass die Startkante des Zuordnungsrechtecks des Elements mit der des nächsten umschließenden Referenzbereichs zusammenfällt. |
| static readonly [Role_cb](../../aspose.pdf.logicalstructure/attributename/role_cb) | Attribut Rolle: cb - Kontrollkästchen. |
| static readonly [Role_pb](../../aspose.pdf.logicalstructure/attributename/role_pb) | Attribut Rolle: pb - Taster. |
| static readonly [Role_rb](../../aspose.pdf.logicalstructure/attributename/role_rb) | Attributrolle: rb - Optionsfeld. |
| static readonly [Role_tv](../../aspose.pdf.logicalstructure/attributename/role_tv) | Attributrolle: tv - Textwertfeld. |
| static readonly [RubyAlign_Center](../../aspose.pdf.logicalstructure/attributename/rubyalign_center) | Attribut RubyAlign: Center - Der Inhalt soll in der Inline-Fortschrittsrichtung zentriert werden. |
| static readonly [RubyAlign_Distribute](../../aspose.pdf.logicalstructure/attributename/rubyalign_distribute) | Attribut RubyAlign: Distribute - Der Inhalt soll erweitert werden, um die verfügbare Breite in der Inline-Progressionsrichtung auszufüllen. Allerdings soll auch am Anfangs- und Endrand des Textes ein Leerzeichen eingefügt werden. Die Abstände müssen im Verhältnis 1:2:1 (Start:Infix:Ende) verteilt werden. Es soll auf ein Verhältnis von 0:1:1 geändert werden, wenn der Rubin am Anfang einer Textzeile erscheint, oder auf ein Verhältnis von 1:1:0, wenn der Rubin am Ende der Textzeile erscheint. |
| static readonly [RubyAlign_End](../../aspose.pdf.logicalstructure/attributename/rubyalign_end) | Attribut RubyAlign: End - Der Inhalt soll an der Endkante in der Inline-Fortschrittsrichtung ausgerichtet werden. |
| static readonly [RubyAlign_Justify](../../aspose.pdf.logicalstructure/attributename/rubyalign_justify) | Attribut RubyAlign: Justify – Der Inhalt soll erweitert werden, um die verfügbare Breite in der Inline-Progressionsrichtung auszufüllen. |
| static readonly [RubyAlign_Start](../../aspose.pdf.logicalstructure/attributename/rubyalign_start) | Attribut RubyAlign: Start - Der Inhalt soll an der Startkante in Inline-Fortschrittsrichtung ausgerichtet werden. |
| static readonly [RubyPosition_After](../../aspose.pdf.logicalstructure/attributename/rubyposition_after) | Attribut RubyPosition: After – Der RT-Inhalt soll entlang der hinteren Kante des Elements ausgerichtet werden. |
| static readonly [RubyPosition_Before](../../aspose.pdf.logicalstructure/attributename/rubyposition_before) | Attribut RubyPosition: Before - Der RT-Inhalt soll entlang der Before-Kante des Elements ausgerichtet werden. |
| static readonly [RubyPosition_Inline](../../aspose.pdf.logicalstructure/attributename/rubyposition_inline) | Attribut RubyPosition: Inline – Die RT- und zugehörigen RP-Elemente müssen als Kommentar in Klammern nach dem RB-Element formatiert werden. |
| static readonly [RubyPosition_Warichu](../../aspose.pdf.logicalstructure/attributename/rubyposition_warichu) | Attribut RubyPosition: Warichu – Das RT und die zugehörigen RP-Elemente werden als Warichu formatiert, nach dem RB-Element. |
| static readonly [Scope_Both](../../aspose.pdf.logicalstructure/attributename/scope_both) | Attributbereich: Beides. |
| static readonly [Scope_Column](../../aspose.pdf.logicalstructure/attributename/scope_column) | Attributbereich: Spalte. |
| static readonly [Scope_Row](../../aspose.pdf.logicalstructure/attributename/scope_row) | Attributbereich: Zeile. |
| static readonly [TextAlign_Center](../../aspose.pdf.logicalstructure/attributename/textalign_center) | Attribut TextAlign: Center – Zentriert zwischen Start- und Endkante. |
| static readonly [TextAlign_End](../../aspose.pdf.logicalstructure/attributename/textalign_end) | Attribut TextAlign: End - An der Endkante ausgerichtet. |
| static readonly [TextAlign_Justify](../../aspose.pdf.logicalstructure/attributename/textalign_justify) | Attribut TextAlign: Justify – Ausgerichtet sowohl an den Start- als auch an den Endkanten, wobei der interne Abstand innerhalb jeder Zeile erweitert wird, falls erforderlich, um eine solche Ausrichtung zu erreichen. Die letzte (oder einzige) Linie soll nur an der Startkante ausgerichtet werden. |
| static readonly [TextAlign_Start](../../aspose.pdf.logicalstructure/attributename/textalign_start) | Attribut TextAlign: Start - Ausgerichtet an der Startkante. |
| static readonly [TextDecorationType_LineThrough](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_linethrough) | Attribut TextDecorationType: LineThrough - Eine Linie durch die Mitte des Textes. |
| static readonly [TextDecorationType_None](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_none) | Attribut TextDecorationType: None - Keine Textdekoration. |
| static readonly [TextDecorationType_Overline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_overline) | Attribut TextDecorationType: Overline - Eine Linie über dem Text. |
| static readonly [TextDecorationType_Underline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_underline) | Attribut TextDecorationType: Underline - Eine Linie unter dem Text. |
| static readonly [Width_Auto](../../aspose.pdf.logicalstructure/attributename/width_auto) | Attribut Breite: Auto - die Breite des Elements wird durch die intrinsische Breite seines Inhalts bestimmt. |
| static readonly [WritingMode_LrTb](../../aspose.pdf.logicalstructure/attributename/writingmode_lrtb) | Attribut WritingMode: LrTb - Inline-Fortschritt von links nach rechts; Blockierung von oben nach unten. Dies ist der typische Schreibmodus für westliche Schriftsysteme. |
| static readonly [WritingMode_RlTb](../../aspose.pdf.logicalstructure/attributename/writingmode_rltb) | Attribut WritingMode: RlTb - Inline-Fortschritt von rechts nach links; Blockierung von oben nach unten. Dies ist der typische Schreibmodus für arabische und hebräische Schriftsysteme. |
| static readonly [WritingMode_TbRl](../../aspose.pdf.logicalstructure/attributename/writingmode_tbrl) | Attribut WritingMode: TbRl - Inline-Progression von oben nach unten; Blockierung von rechts nach links. Dies ist der typische Schreibmodus für chinesische und japanische Schriftsysteme. |

### Siehe auch

* namensraum [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
