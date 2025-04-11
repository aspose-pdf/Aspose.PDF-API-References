---
title: Class RenderingOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.RenderingOptions-Klasse. Stellt Rendering-Optionen dar
type: docs
weight: 9760
url: /de/net/aspose.pdf/renderingoptions/
---
## RenderingOptions-Klasse

Stellt Rendering-Optionen dar.

```csharp
public sealed class RenderingOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [RenderingOptions](renderingoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AnalyzeFonts](../../aspose.pdf/renderingoptions/analyzefonts/) { get; set; } | Ersetzt Schriftarten nach Bedarf, um sicherzustellen, dass alle Zeichen im Text angezeigt werden können. Der Algorithmus zur Schriftartsubstitution folgt diesen Schritten: 1. Wenn der Benutzer die Eigenschaft DefaultFontName ausdrücklich festlegt, überprüfen Sie, ob die angegebene Schriftart die gewünschten Zeichen anzeigen kann. 2. Wenn keine benutzerdefinierte Schriftart festgelegt ist, suchen Sie nach Schriftarten, die über die !:FontRepository.Sources hinzugefügt wurden. 3. Analysieren Sie den Text, um sein Alphabet oder seine Schrift zu identifizieren und schlagen Sie entsprechende Schriftartnamen vor. Versuchen Sie, diese Schriftarten im System zu finden und zu verwenden. 4. Als Fallback suchen Sie im System nach einer Schriftart, die in der Lage ist, die erforderlichen Zeichen anzuzeigen. |
| [BarcodeOptimization](../../aspose.pdf/renderingoptions/barcodeoptimization/) { get; set; } | Ruft den Barcode-Optimierungsmodus ab oder legt ihn fest. |
| [ConvertFontsToUnicodeTTF](../../aspose.pdf/renderingoptions/convertfontstounicodettf/) { get; set; } | Gibt an, dass alle Schriftarten in TTF-Unicode-Versionen konvertiert werden. Dies ist aus Kompatibilitätsgründen nützlich und optimiert die Verwendung von Schriftarten, da jede neue TTF-Schriftart nicht alle Symbole der Quellschriftart enthält, sondern nur die Symbole, die im Text verwendet werden. |
| [DefaultFontName](../../aspose.pdf/renderingoptions/defaultfontname/) { get; set; } | Ruft den Standardnamen der Schriftart ab oder legt ihn fest, die zur Substitution fehlender Schriftarten verwendet wird. |
| [HeightExtraUnits](../../aspose.pdf/renderingoptions/heightextraunits/) { get; set; } | Ruft einen Wert ab oder legt ihn fest, der verwendet wird, um die Breite des Rechtecks für den AppendRectangle-Operator zu erhöhen oder zu verringern. |
| [IgnoreResourceFontErrors](../../aspose.pdf/renderingoptions/ignoreresourcefonterrors/) { get; set; } | Ruft die Angabe ab oder legt sie fest, dass Fehler im Zusammenhang mit dem Fehlen von Schriftarten ignoriert werden. true - bedeutet, dass Fehler aufgrund des Fehlens von Schriftarten ignoriert werden. Textsegmente, die auf falsche Ressourcen verweisen, werden während der Verarbeitung übersprungen. false ist standardmäßig. |
| [InterpolationHighQuality](../../aspose.pdf/renderingoptions/interpolationhighquality/) { get; set; } | Ruft den Hochqualitätsmodus für die Interpolation ab oder legt ihn fest. |
| [MaxFontsCacheSize](../../aspose.pdf/renderingoptions/maxfontscachesize/) { get; set; } | Maximale Anzahl von Schriftarten im Schriftarten-Cache. Der Standardwert beträgt 10. |
| [MaxSymbolsCacheSize](../../aspose.pdf/renderingoptions/maxsymbolscachesize/) { get; set; } | Maximale Anzahl von Symbolen im Symbol-Cache. Der Standardwert beträgt 100. |
| [OptimizeDimensions](../../aspose.pdf/renderingoptions/optimizedimensions/) { get; set; } | Ruft den Optimierungsmodus für Dimensionen ab oder legt ihn fest. |
| [SystemFontsNativeRendering](../../aspose.pdf/renderingoptions/systemfontsnativerendering/) { get; set; } | Ruft einen Modus ab oder legt ihn fest, in dem Systemschriftarten nativ gerendert werden. |
| [UseFontHinting](../../aspose.pdf/renderingoptions/usefonthinting/) { get; set; } | Die Verwendung dieses Flags aktiviert den Schriftart-Hinting-Mechanismus. Schriftart-Hinting ist die Verwendung mathematischer Anweisungen zur Anpassung der Anzeige einer Outline-Schriftart. In einigen Fällen kann das Aktivieren dieses Flags Probleme mit der Lesbarkeit des Textes lösen. Momentan hat die Verwendung dieses Flags nur Auswirkungen auf TTF-Schriftarten, wenn diese Schriftarten im Quelldokument verwendet werden. |
| [WidthExtraUnits](../../aspose.pdf/renderingoptions/widthextraunits/) { get; set; } | Ruft einen Wert ab oder legt ihn fest, der verwendet wird, um die Breite des Rechtecks für den AppendRectangle-Operator zu erhöhen oder zu verringern. |

### Siehe auch

* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)