---
title: Class TextSearchOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextSearchOptions-Klasse. Stellt Textsuchoptionen dar
type: docs
weight: 11040
url: /de/net/aspose.pdf.text/textsearchoptions/
---
## TextSearchOptions-Klasse

Stellt Textsuchoptionen dar

```csharp
public sealed class TextSearchOptions : TextOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TextSearchOptions](textsearchoptions/#constructor_2)(bool) | Initialisiert eine neue Instanz des `TextSearchOptions`-Objekts. Gibt den Modus für die Verwendung regulärer Ausdrücke an. |
| [TextSearchOptions](textsearchoptions/#constructor)(Rectangle) | Initialisiert eine neue Instanz des `TextSearchOptions`-Objekts. Gibt das Rechteck an, das den gesuchten Text begrenzt. |
| [TextSearchOptions](textsearchoptions/#constructor_1)(Rectangle, bool) | Initialisiert eine neue Instanz des `TextSearchOptions`-Objekts. Gibt das Rechteck an, das den gesuchten Text begrenzt, und den Modus für die Verwendung regulärer Ausdrücke. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [IgnoreResourceFontErrors](../../aspose.pdf.text/textsearchoptions/ignoreresourcefonterrors/) { get; set; } | Ruft an oder setzt die Angabe, dass Fehler im Zusammenhang mit dem Fehlen von Schriftarten vom Text (Fragment) Absorber ignoriert werden. true - bedeutet, dass Fehler aufgrund fehlender Schriftarten ignoriert werden. Textsegmente, die auf falsche Ressourcen verweisen, werden während der Verarbeitung übersprungen. false (Standard) - Fehler aufgrund fehlender Schriftarten beenden die Verarbeitung durch Auslösen einer Ausnahme. |
| [IgnoreShadowText](../../aspose.pdf.text/textsearchoptions/ignoreshadowtext/) { get; set; } | Ruft an oder setzt die Angabe, dass Textfragmente, die den Schatten von normalem Text darstellen, während der Suche ignoriert werden. true - bedeutet, dass Schattentext nicht gefunden wird (versuchen Sie dies, wenn die Textsuche doppelte Fragmente an nahen Positionen zurückgibt) false - bedeutet, dass Schattentext sowie normaler Text gefunden wird (Standardwert) |
| [IsRegularExpressionUsed](../../aspose.pdf.text/textsearchoptions/isregularexpressionused/) { get; set; } | Ruft an oder setzt die Angabe, dass ein regulärer Ausdruck verwendet wird. |
| [LimitToPageBounds](../../aspose.pdf.text/textsearchoptions/limittopagebounds/) { get; set; } | Ruft an oder setzt die Angabe, dass der Text innerhalb der Seitenränder gesucht wird. |
| [LogTextExtractionErrors](../../aspose.pdf.text/textsearchoptions/logtextextractionerrors/) { get; set; } | Ruft an oder setzt die Angabe, dass Fehler bei der Textextraktion (Dekodierung) im Text (Fragment) Absorber protokolliert werden. true - bedeutet, dass Fehler bei der Textextraktion (Dekodierung) protokolliert werden. Dies kann die Leistung verringern. false (Standard) - kein Fehlerprotokoll. |
| [Rectangle](../../aspose.pdf.text/textsearchoptions/rectangle/) { get; set; } | Ruft an oder setzt das Rechteck, das den gesuchten Text begrenzt. |
| [SearchForTextRelatedGraphics](../../aspose.pdf.text/textsearchoptions/searchfortextrelatedgraphics/) { get; set; } | Ruft an oder setzt den Wert, der das Suchen nach textbezogenen Grafiken (Unterstreichungen, Hintergründe usw.) während der Textsuche erlaubt. true - die Suche nach textbezogenen Grafiken wird durchgeführt (Standardwert). false - grafische Elemente, die im Quelldokument vorhanden sein könnten, werden ignoriert. Setzen Sie dies im Falle von Leistungsproblemen oder wenn keine Unterstreichungen, Hintergründe oder Zuschnitte behandelt werden müssen. |
| [SearchInAnnotations](../../aspose.pdf.text/textsearchoptions/searchinannotations/) { get; set; } | Ruft an oder setzt den Wert, der das Suchen nach Text in Anmerkungen erlaubt. true - Text wird in Anmerkungen gesucht. false - Text in Anmerkungen wird nicht vom TextFragmentAbsorber analysiert. |
| [StoredGraphicElementsMaxCount](../../aspose.pdf.text/textsearchoptions/storedgraphicelementsmaxcount/) { get; set; } | Ruft an oder setzt den Wert, der die Suche nach textbezogenen Grafiken (Unterstreichungen, Hintergründe usw.) auf einer Seite für die angegebene Anzahl von Elementen begrenzt. Der Standardwert beträgt 250. Setzen Sie einen niedrigeren Wert im Falle von Leistungsproblemen, versuchen Sie einen höheren Wert, wenn einige grafische Elemente nicht gefunden wurden. |
| [UseFontEngineEncoding](../../aspose.pdf.text/textsearchoptions/usefontengineencoding/) { get; set; } | Ruft an oder setzt die Angabe, dass der Text unter Verwendung der Schriftart-Engine-Codierung gesucht wird. true - bedeutet, dass die Schriftart-Engine-Codierung verwendet wird (versuchen Sie dies, wenn die Textsuche aufgrund unvollkommener Codierung im Dokument fehlschlägt) false - bedeutet, dass die Dokumentenschriftcodierung verwendet wird (Standardwert) |

### Siehe auch

* Klasse [TextOptions](../textoptions/)
* Namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../)