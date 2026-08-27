---
title: "PdfFormatConversionOptions.RemoveFontsStrategy"
linktitle: "PdfFormatConversionOptions.RemoveFontsStrategy"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Einige Dokumente haben nach der Konvertierung in das PDF/A-Format eine große Dateigröße. Um die Dateigröße für diese Dokumente zu reduzieren, ist es notwendig, eine Strategie zum Entfernen von Schriften zu definieren. Diese Aufzählung."
type: docs
weight: 3760
url: /de/java/com.aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy

```
public static class PdfFormatConversionOptions.RemoveFontsStrategy extends com.aspose.ms.System.Enum
```

Einige Dokumente haben nach der Konvertierung in das PDF/A-Format eine große Dateigröße. Um die Dateigröße für diese Dokumente zu reduzieren, ist es notwendig, eine Strategie zum Entfernen von Schriftarten zu definieren. Diese Aufzählung deklariert Strategien, die zur Optimierung der Schriftartennutzung verwendet werden können. Jede Strategie dieser Aufzählung ist nur sinnvoll, wenn das Flag {@code OptimizeFileSize} gesetzt ist.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [RemoveDuplicatedFonts](#RemoveDuplicatedFonts) | Diese Strategie entfernt alle Schriften, die im Dokument Duplikate haben. Wenn das Dokument eine Gruppe von duplizierten Schriften enthält, wird nur eine Schrift aus dieser Gruppe im Dokument eingebettet. Alle anderen Schriften aus dieser Gruppe werden aus dem Dokument entfernt, jede entfernte Schrift wird durch das bereits eingebettete Analog ersetzt. |
| [RemoveSimilarFontsWithDifferentWidths](#RemoveSimilarFontsWithDifferentWidths) | Diese Strategie ähnelt {@code RemoveDuplicatedFonts}, entfernt jedoch nicht vollständig duplizierte Schriften, sondern Schriften, die einander ähnlich sind und sich nur im Parameter "Widths" unterscheiden. Dieser Parameter enthält eine Menge von Breiten für bestimmte Symbole der Schrift. Jeder Breitenwert aus dieser "Widths"-Menge ist nicht die reale Breite eines Symbols (Glyph), die reale Breite dieses Symbols ist bereits in den Binärdaten der Schrift definiert. Der Breitenwert aus der "Widths"-Menge bedeutet die visuelle Breite dieses Symbols – die Breite, die die PDF‑Betrachtungssoftware beim Anzeigen des Symbols anstelle der real definierten Breite in der Schrift setzen muss. Genauer gesagt besagt die Spezifikation: Acrobat‑Viewer ab Version 5.0 und später verwenden die in dem Schrift‑Dictionary gespeicherten Glyph‑Breiten, um die Breiten der Glyphen im eigentlichen Schrift‑Programm zu überschreiben, was die Konsistenz der Anzeige und des Drucks des Dokuments verbessert. Diese Strategie ist effektiver als {@code RemoveDuplicatedFonts}, aber die Verwendung dieser Strategie kann in einigen Fällen theoretisch die visuelle Darstellung des konvertierten Dokuments beschädigen. Dieser Defekt ist möglich, weil die deklarierten Breiten von Schriften für dasselbe Symbol unterschiedlich sein können und in diesem Fall die Breite dieses Symbols nach einer Schrift‑Substitution auf einen neuen Wert geändert wird – wenn die entfernte Schrift im Dokument durch eine bereits eingebettete ersetzt wird. Und wenn die visuelle Breite des Symbols geändert wird, wird es falsch angezeigt und diese Unterscheidung kann visuelle Defekte wie Textüberlappungen oder andere Probleme verursachen. Der beschriebene visuelle Defekt ist jedoch ein sehr seltener Fall und diese Strategie reduziert die Dokumentgröße effektiver. |
| [SubsetFonts](#SubsetFonts) | Dies ist die effektivste Strategie, um die Größe des Dokuments zu reduzieren. Sie verwendet vollständig eingebettete Schriftartensätze und reduziert sie auf nur die verwendeten Teilmengen. Es wird empfohlen, diese Strategie in Kombination mit {@code RemoveDuplicatedFonts} oder {@code RemoveSimilarFontsWithDifferentWidths} zu verwenden, um mehrere Kompressionseffekte für die Dateigröße zu erzielen. Die gleichzeitige Verwendung aller drei Strategien hat keinen Sinn und die Strategie {@code RemoveSimilarFontsWithDifferentWidths} wird in diesem Fall nicht verwendet. |

### RemoveDuplicatedFonts {#RemoveDuplicatedFonts}
```
public static final byte RemoveDuplicatedFonts
```

Diese Strategie entfernt alle Schriften, die im Dokument Duplikate haben. Wenn das Dokument eine Gruppe von duplizierten Schriften enthält, wird nur eine Schrift aus dieser Gruppe im Dokument eingebettet. Alle anderen Schriften aus dieser Gruppe werden aus dem Dokument entfernt, jede entfernte Schrift wird durch das bereits eingebettete Analog ersetzt.

### RemoveSimilarFontsWithDifferentWidths {#RemoveSimilarFontsWithDifferentWidths}
```
public static final byte RemoveSimilarFontsWithDifferentWidths
```

Diese Strategie ähnelt {@code RemoveDuplicatedFonts}, entfernt jedoch nicht vollständig duplizierte Schriften, sondern Schriften, die einander ähnlich sind und sich nur im Parameter "Widths" unterscheiden. Dieser Parameter enthält eine Menge von Breiten für bestimmte Symbole der Schrift. Jeder Breitenwert aus dieser "Widths"-Menge ist nicht die reale Breite eines Symbols (Glyph), die reale Breite dieses Symbols ist bereits in den Binärdaten der Schrift definiert. Der Breitenwert aus der "Widths"-Menge bedeutet die visuelle Breite dieses Symbols – die Breite, die die PDF‑Betrachtungssoftware beim Anzeigen des Symbols anstelle der real definierten Breite in der Schrift setzen muss. Genauer gesagt besagt die Spezifikation: Acrobat‑Viewer ab Version 5.0 und später verwenden die in dem Schrift‑Dictionary gespeicherten Glyph‑Breiten, um die Breiten der Glyphen im eigentlichen Schrift‑Programm zu überschreiben, was die Konsistenz der Anzeige und des Drucks des Dokuments verbessert. Diese Strategie ist effektiver als {@code RemoveDuplicatedFonts}, aber die Verwendung dieser Strategie kann in einigen Fällen theoretisch die visuelle Darstellung des konvertierten Dokuments beschädigen. Dieser Defekt ist möglich, weil die deklarierten Breiten von Schriften für dasselbe Symbol unterschiedlich sein können und in diesem Fall die Breite dieses Symbols nach einer Schrift‑Substitution auf einen neuen Wert geändert wird – wenn die entfernte Schrift im Dokument durch eine bereits eingebettete ersetzt wird. Und wenn die visuelle Breite des Symbols geändert wird, wird es falsch angezeigt und diese Unterscheidung kann visuelle Defekte wie Textüberlappungen oder andere Probleme verursachen. Der beschriebene visuelle Defekt ist jedoch ein sehr seltener Fall und diese Strategie reduziert die Dokumentgröße effektiver.

### SubsetFonts {#SubsetFonts}
```
public static final byte SubsetFonts
```

Dies ist die effektivste Strategie, um die Größe des Dokuments zu reduzieren. Sie verwendet vollständig eingebettete Schriftartensätze und reduziert sie auf nur die verwendeten Teilmengen. Es wird empfohlen, diese Strategie in Kombination mit {@code RemoveDuplicatedFonts} oder {@code RemoveSimilarFontsWithDifferentWidths} zu verwenden, um mehrere Kompressionseffekte für die Dateigröße zu erzielen. Die gleichzeitige Verwendung aller drei Strategien hat keinen Sinn und die Strategie {@code RemoveSimilarFontsWithDifferentWidths} wird in diesem Fall nicht verwendet.
