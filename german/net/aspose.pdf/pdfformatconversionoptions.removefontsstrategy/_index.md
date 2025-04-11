---
title: Enum PdfFormatConversionOptions.RemoveFontsStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfFormatConversionOptionsRemoveFontsStrategy Enum. Einige Dokumente haben nach der Konvertierung in das PDF/A-Format eine große Dateigröße. Um die Dateigröße für diese Dokumente zu reduzieren, ist es notwendig, eine Strategie zum Entfernen von Schriftarten zu definieren. Diese Enumeration erklärt Strategien, die verwendet werden können, um die Nutzung von Schriftarten zu optimieren. Jede Strategie aus dieser Enumeration hat nur dann Sinn, wenn das Flag [`OptimizeFileSize`](../pdfformatconversionoptions/optimizefilesize/) gesetzt ist.
type: docs
weight: 8400
url: /de/net/aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
## PdfFormatConversionOptions.RemoveFontsStrategy Enumeration

Einige Dokumente haben nach der Konvertierung in das PDF/A-Format eine große Dateigröße. Um die Dateigröße für diese Dokumente zu reduzieren, ist es notwendig, eine Strategie zum Entfernen von Schriftarten zu definieren. Diese Enumeration erklärt Strategien, die verwendet werden können, um die Nutzung von Schriftarten zu optimieren. Jede Strategie aus dieser Enumeration hat nur dann Sinn, wenn das Flag [`OptimizeFileSize`](../pdfformatconversionoptions/optimizefilesize/) gesetzt ist.

```csharp
[Flags]
public enum RemoveFontsStrategy : byte
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| RemoveDuplicatedFonts | `4` | Diese Strategie entfernt alle Schriftarten, die Duplikate im Dokument haben. Wenn das Dokument eine Gruppe von duplizierten Schriftarten enthält, wird nur eine Schriftart aus dieser Gruppe im Dokument eingebettet. Alle anderen Schriftarten aus dieser Gruppe werden aus dem Dokument entfernt, jede entfernte Schriftart wird durch das bereits eingebettete Pendant ersetzt. |
| RemoveSimilarFontsWithDifferentWidths | `1` | Diese Strategie ähnelt RemoveDuplicatedFonts, entfernt jedoch keine vollständig duplizierten Schriftarten, sondern Schriftarten, die einander ähnlich sind und sich nur durch den Parameter "Widths" unterscheiden. Dieser Parameter enthält eine Menge von bestimmten Breiten für die angegebenen Symbole der Schriftart. Jeder Wert der Breite aus dieser "Widths"-Menge ist nicht die tatsächliche Breite des Symbols (Glyphen), die tatsächliche Breite für dieses Symbol ist bereits in den binären Daten der Schriftart definiert. Der Wert der Breite aus der "Widths"-Menge bedeutet die visuelle Breite für dieses Symbol - die Breite, die die PDF-Viewer-Software beim Anzeigen des Symbols anstelle der tatsächlichen Breite, die in der Schriftart definiert ist, einstellen muss. Genauer gesagt sagt die Spezifikation: Acrobat 5.0 und spätere Viewer verwenden die Glyphenbreiten, die im Schriftartenwörterbuch gespeichert sind, um die Breiten der Glyphen im Schriftartenprogramm selbst zu überschreiben, was die Konsistenz der Anzeige und des Drucks des Dokuments verbessert. Diese Strategie ist effektiver als RemoveDuplicatedFonts, aber die Verwendung dieser Strategie könnte in einigen Fällen theoretisch die visuelle Präsentation des konvertierten Dokuments beschädigen. Dieser Defekt ist möglich, da die deklarierten Breiten der Schriftarten für dasselbe Symbol unterschiedlich sein könnten und in diesem Fall die Breite dieses Symbols nach der Schriftartsubstitution auf eine neue geändert wird - wenn die entfernte Schriftart im Dokument durch die bereits eingebettete ersetzt wird. Und wenn sich die visuelle Breite des Symbols ändert, wird es falsch angezeigt, und diese Unterscheidung könnte visuelle Defekte wie Textüberlappungen oder andere Probleme verursachen. Aber der beschriebene visuelle Defekt ist ein sehr seltener Fall, und diese Strategie reduziert die Größe des Dokuments effektiver. |
| SubsetFonts | `2` | Dies ist die effektivste Strategie zur Reduzierung der Dateigröße des Dokuments. Sie nimmt vollständig eingebettete Schriftsätze und kürzt sie auf nur die verwendeten Teilmengen. Es wird empfohlen, diese Strategie in Kombination mit RemoveDuplicatedFonts oder RemoveSimilarFontsWithDifferentWidths zu verwenden, um einen mehrfachen Kompressionseffekt für die Dateigröße zu erzielen. Die gleichzeitige Verwendung aller drei Strategien hat keinen Sinn, und die Strategie RemoveSimilarFontsWithDifferentWidths wird in diesem Fall nicht verwendet. |

### Siehe auch

* Klasse [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)