---
title: Class PdfFormatConversionOptions
second_title: Aspose.PDF for .NET API Reference
description: Die Klasse Aspose.Pdf.PdfFormatConversionOptions stellt eine Reihe von Optionen zur Konvertierung von PDF-Dokumenten dar.
type: docs
weight: 8380
url: /de/net/aspose.pdf/pdfformatconversionoptions/
---
## Klasse PdfFormatConversionOptions

stellt eine Reihe von Optionen zur Konvertierung von PDF-Dokumenten dar

```csharp
public class PdfFormatConversionOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor)(PdfFormat) | Konstruktor |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_1)(PdfFormat, ConvertErrorAction) | Konstruktor |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_3)(string, PdfFormat) | Konstruktor |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_2)(Stream, PdfFormat, ConvertErrorAction) | Konstruktor |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_4)(string, PdfFormat, ConvertErrorAction) | Konstruktor |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_5)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Konstruktor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [Default](../../aspose.pdf/pdfformatconversionoptions/default/) { get; } | Gibt das PdfFormatConversionOptions-Objekt mit den Standardparametern zurück |
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext/) { get; set; } | Dieses Flag steuert die Textausrichtung im konvertierten Dokument. Standardmäßig hat die Dokumentenkonvertierung keinen Einfluss auf die Textausrichtung und lässt den Text unverändert. In einigen Fällen kann die Schriftartsubstitution jedoch zu überlappendem Text oder zusätzlichen Abständen im konvertierten Dokument führen. Wenn dieses Flag gesetzt ist, werden spezielle Ausrichtungsoperationen durchgeführt. Dieses Flag sollte nur für Dokumente gesetzt werden, die Probleme mit überlappendem Text oder zusätzlichen Textabständen haben, da die Verwendung dieses Flags die Leistung verringern und in einigen Fällen den Textinhalt beschädigen könnte. |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction/) { get; set; } | Aktion für Bilder mit weichem Masken. |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction/) { get; set; } | Aktion für Objekte, die nicht konvertiert werden können |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy/) { get; set; } | Strategie(n) zum Ausschluss überflüssiger Schriftarten und zur Reduzierung der Dateigröße des Dokuments. Dieser Parameter hat nur dann Bedeutung, wenn das Flag [`OptimizeFileSize`](./optimizefilesize/) auf true gesetzt ist. Standardmäßig wird eine Kombination der Strategien SubsetFonts und RemoveDuplicatedFonts verwendet. |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions/) { get; } | Optionen für Fälle, in denen es nicht möglich ist, einige Schriftarten in das PDF-Dokument einzubetten. |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format/) { get; set; } | PDF-Format. |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename/) { get; set; } | Gibt den Dateinamen des ICC-Profils zurück oder setzt ihn. Im Falle von null wird das Standard-ICC-Profil verwendet. |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode/) { get; set; } | Gibt an, ob Bildströme im asynchronen Modus ausgeführt werden. |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode/) { get; set; } | Ist der Modus für die Konvertierung mit geringem Speicher aktiviert |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo/) { get; set; } | Gibt an, ob Daten von Info zu Metadaten beim Konvertieren in PDF 2.0 übergeben werden sollen. Standardmäßig true. |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename/) { get; set; } | Pfad zur Datei, in der Kommentare gespeichert werden. |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream/) { get; set; } | Stream, in dem Kommentare gespeichert werden. |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases/) { get; } | Enthält Flags zur Steuerung des PDF/A-Konvertierungsprozesses für Fälle, in denen das Quelldokument nicht der PDF/A-Spezifikation entspricht. |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts/) { get; } | Diese Eigenschaft ist eine Ausgabeeigenschaft. Sie enthält alle Schriftarten (Schriftartnamen), die bei der letzten PDF/A-Konvertierung nicht auf dem Computer gefunden wurden. |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize/) { get; set; } | Gibt ein Flag zurück oder setzt es, das den speziellen Konvertierungsmodus aktiviert/deaktiviert, um ein PDF/A-Dokument mit reduzierter Dateigröße zu erhalten. Dieses Flag hat jetzt Einfluss auf die Optimierung der in PDF-Dokumenten verwendeten Schriftarten. Möglicherweise wird dieses Flag in Zukunft auch verwendet, um die Optimierung für andere Datenstrukturen, wie Grafiken, zu aktivieren. Das Setzen dieses Flags und Modus kann die Dateigröße erheblich reduzieren, aber gleichzeitig die Leistung der Konvertierung erheblich verringern. |
| [OutputIntent](../../aspose.pdf/pdfformatconversionoptions/outputintent/) { get; set; } | Gibt das [`OutputIntent`](../outputintent/) für die PDF-Formatkonvertierung zurück oder setzt es. |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy/) { get; set; } | Strategie zur Verarbeitung von Symbolen aus dem Unicode-Bereich für private Nutzung (PUA). |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy/) { get; set; } | Strategie zum Kopieren von Kodierungsdaten für symbolische Schriftarten, wenn die symbolische TrueType-Schriftart mehr als eine Kodierungstabelle hat. |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction/) { get; set; } | Aktion für bildmaskierte Objekte |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules/) { get; set; } | Regeln zur Lösung von Problemen mit der Unicode-Zuordnung. Kann null sein. |

## Felder

| Name | Beschreibung |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy/) | Strategie zur Ausrichtung von Text. Dieser Parameter hat nur dann Bedeutung, wenn das Flag [`AlignText`](./aligntext/) auf true gesetzt ist. |

### Siehe auch

* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)