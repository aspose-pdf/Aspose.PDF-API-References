---
title: TextSearchOptions
second_title: Aspose.PDF für .NET-API-Referenz
description: Repräsentiert Textsuchoptionen
type: docs
weight: 7200
url: /de/net/aspose.pdf.text/textsearchoptions/
---
## TextSearchOptions class

Repräsentiert Textsuchoptionen

```csharp
public sealed class TextSearchOptions : TextOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [TextSearchOptions](textsearchoptions#constructor_2)(bool) | Initialisiert eine neue Instanz von[`TextSearchOptions`](../textsearchoptions) object. Gibt den Verwendungsmodus für reguläre Ausdrücke an. |
| [TextSearchOptions](textsearchoptions#constructor)(Rectangle) | Initialisiert eine neue Instanz von[`TextSearchOptions`](../textsearchoptions)object. Gibt ein Rechteck an, das den gesuchten Text begrenzt. |
| [TextSearchOptions](textsearchoptions#constructor_1)(Rectangle, bool) | Initialisiert eine neue Instanz von[`TextSearchOptions`](../textsearchoptions) object. Gibt ein Rechteck an, das den gesuchten Text und den Verwendungsmodus für reguläre Ausdrücke begrenzt. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [IgnoreResourceFontErrors](../../aspose.pdf.text/textsearchoptions/ignoreresourcefonterrors) { get; set; } | Erhält oder setzt die Angabe, dass Fehler im Zusammenhang mit dem Fehlen einer Schriftart vom Text-(Fragment-)Absorber ignoriert werden. true - bedeutet, dass Fehler aufgrund des Fehlens einer Schriftart ignoriert werden. Textsegmente, die auf falsche Ressourcen verweisen, werden während der Verarbeitung übersprungen. false (Standard) - Fehlen eines Schriftartfehlers beendet die Verarbeitung durch Auslösen einer Ausnahme. |
| [IgnoreShadowText](../../aspose.pdf.text/textsearchoptions/ignoreshadowtext) { get; set; } | Erhält oder setzt die Angabe, dass Textfragmente, die Schatten von normalem Text darstellen, während der Suche ignoriert werden. wahr – bedeutet, dass Schattentext nicht gefunden wird (versuchen Sie dies, wenn die Textsuche doppelte Fragmente an den nahen Positionen zurückgibt) falsch – bedeutet, dass Schatten Text wird ebenso gefunden wie normaler Text (Standardwert) |
| [IsRegularExpressionUsed](../../aspose.pdf.text/textsearchoptions/isregularexpressionused) { get; set; } | Ruft ab oder legt fest, dass ein regulärer Ausdruck verwendet wird. |
| [LimitToPageBounds](../../aspose.pdf.text/textsearchoptions/limittopagebounds) { get; set; } | Ruft ab oder legt fest, dass Text innerhalb der Seitengrenzen gesucht wird. |
| [LogTextExtractionErrors](../../aspose.pdf.text/textsearchoptions/logtextextractionerrors) { get; set; } | Erhält oder setzt die Angabe, dass Fehler bei der Textextraktion (Decodierung) im Text-(Fragment-)Absorber protokolliert werden. true – bedeutet, dass Fehler bei der Textextraktion (Decodierung) protokolliert werden. Dies kann die Leistung beeinträchtigen. false (Standard) – keine Fehlerprotokollierung. |
| [Rectangle](../../aspose.pdf.text/textsearchoptions/rectangle) { get; set; } | Ruft ein Rechteck ab oder legt es fest, das den gesuchten Text umschließt. |
| [SearchForTextRelatedGraphics](../../aspose.pdf.text/textsearchoptions/searchfortextrelatedgraphics) { get; set; } | Ermittelt oder setzt einen Wert, der die Suche nach textbezogenen Grafiken (Unterstreichungen, Hintergrund usw.) während der Textsuche ermöglicht. true – Es wird nach textbezogenen Grafiken gesucht (Standardwert). false – Grafikelemente, die im Quelldokument vorhanden sein können wird ignoriert. Stellen Sie dies ein, wenn Leistungsprobleme auftreten oder Unterstreichungen, Hintergrund oder Clipping nicht verarbeitet werden müssen. |
| [StoredGraphicElementsMaxCount](../../aspose.pdf.text/textsearchoptions/storedgraphicelementsmaxcount) { get; set; } | Ermittelt oder setzt einen Wert, der die Suche nach textbezogenen Grafiken (Unterstreichungen, Hintergrund usw.) auf einer Seite für die angegebene Anzahl von Elementen einschränkt. Der Standardwert ist 250. Stellen Sie einen niedrigeren Wert im Fall von Leistungsproblemen ein, versuchen Sie einen größeren Wert in der Falls einige Grafikelemente nicht gefunden wurden. |
| [UseFontEngineEncoding](../../aspose.pdf.text/textsearchoptions/usefontengineencoding) { get; set; } | Erhält oder setzt die Angabe, dass Text mit der Zeichensatz-Engine-Codierung gesucht wird. true – bedeutet, dass die Zeichensatz-Engine-Codierung verwendet wird (versuchen Sie dies, wenn die Textsuche aufgrund einer unvollständigen Codierung im Dokument fehlschlägt) false – bedeutet, dass die Zeichensatz-Codierung des Dokuments verwendet wird verwendet werden (Standardwert) |

### Siehe auch

* class [TextOptions](../textoptions)
* namensraum [Aspose.Pdf.Text](../../aspose.pdf.text)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
