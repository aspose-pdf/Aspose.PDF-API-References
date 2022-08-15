---
title: PdfFormatConversionOptions
second_title: Aspose.PDF für .NET-API-Referenz
description: steht für eine Reihe von Optionen zum Konvertieren von PDF-Dokumenten
type: docs
weight: 6030
url: /de/net/aspose.pdf/pdfformatconversionoptions/
---
## PdfFormatConversionOptions class

steht für eine Reihe von Optionen zum Konvertieren von PDF-Dokumenten

```csharp
public class PdfFormatConversionOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor)(PdfFormat) | Konstruktor |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_1)(PdfFormat, ConvertErrorAction) | Konstruktor |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_3)(string, PdfFormat) | Konstruktor |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_2)(Stream, PdfFormat, ConvertErrorAction) | Konstruktor |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_4)(string, PdfFormat, ConvertErrorAction) | Konstruktor |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_5)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Konstruktor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [Default](../../aspose.pdf/pdfformatconversionoptions/default) { get; } | Ruft das PdfFormatConversionOptions-Objekt mit Standardparametern ab |
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext) { get; set; } | Dieses Flag steuert die Textausrichtung im konvertierten Dokument. Standardmäßig wirkt sich die Dokumentkonvertierung nicht auf die Textausrichtung aus und lässt den Text unverändert. Aber in einigen Fällen verursacht die Schriftart substitution Textüberlappungen oder zusätzliche Leerzeichen im konvertierten Dokument. Wenn dieses Flag gesetzt ist werden spezielle Ausrichtungsoperationen durchgeführt. Dieses Flag sollte nur für Dokumente gesetzt werden, die Probleme mit überlappendem Text oder zusätzlichen Textzwischenräumen haben, wodurch die Verwendung dieses Flags die Leistung verringert und in einigen Fällen Textinhalte beschädigen könnte. |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction) { get; set; } | Aktion für Bilder mit weicher Maske. |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction) { get; set; } | Aktion für nicht konvertierbare Objekte |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy) { get; set; } | Strategie(n) zum Ausschließen überflüssiger Schriftarten und zum Reduzieren der Dokumentdateigröße. Dieser Parameter hat nur Sinn, wenn Flag[`OptimizeFileSize`](./optimizefilesize) auf true gesetzt ist. Standardmäßig Kombination von StrategienSubsetFonts and RemoveDuplicatedFonts wird verwendet. |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions) { get; } | Optionen für Fälle, in denen es nicht möglich ist, einige Schriftarten in ein PDF-Dokument einzubetten. |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format) { get; set; } | PDF-Format. |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename) { get; set; } | Holt oder setzt den Dateinamen des ICC-Profilnamens. Im Falle von null wird das Standard-ICC-Profil verwendet. |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode) { get; set; } | Ruft/legt die Ausführung von Bildströmen im asynchronen Modus ab. |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode) { get; set; } | Ist der Umwandlungsmodus für wenig Arbeitsspeicher aktiviert |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo) { get; set; } | Ruft ab oder legt fest, ob Daten von Info an Metadaten übergeben werden, wenn sie in PDF 2.0 konvertiert werden. Standardmäßig wahr. |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename) { get; set; } | Pfad zur Datei, in der Kommentare gespeichert werden. |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream) { get; set; } | Stream, in dem Kommentare gespeichert werden. |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases) { get; } | Enthält Flags zur Steuerung des PDF/A-Konvertierungsprozesses für Fälle, in denen das Quelldokument nicht der PDF/A-Spezifikation entspricht. |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts) { get; } | Diese Eigenschaft ist Out-Property. Es enthält alle Schriftarten (Schriftartnamen), die auf dem Computer bei der letzten PDF/A-Konvertierung nicht gefunden wurden. |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize) { get; set; } | Ruft oder setzt ein Flag, das den speziellen Konvertierungsmodus aktiviert/deaktiviert, um ein PDF/A-Dokument mit reduzierter Dateigröße zu erhalten. Jetzt wirkt sich dieses Flag auf die Optimierung von Schriftarten aus, die in PDF-Dokumenten verwendet werden, möglicherweise wird dieses Flag in Zukunft ebenfalls verwendet um die Optimierung für andere Datenstrukturen, wie z. B. Grafik, einzuschalten. Das Setzen dieses Flags und Modus könnte die Dateigröße erheblich reduzieren, aber gleichzeitig die Konvertierungsleistung erheblich verringern. |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy) { get; set; } | Strategie zur Verarbeitung von Symbolen aus Unicode Private Use Area (PUA). |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy) { get; set; } | Strategie zum Kopieren von Codierungsdaten für symbolische Schriftarten, wenn die symbolische TrueType-Schriftart mehr als eine untergeordnete Codierungstabelle hat. |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction) { get; set; } | Aktion für bildmaskierte Objekte |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules) { get; set; } | Regeln zur Lösung von Problemen mit Unicode-Mapping. Kann null sein. |

## Felder

| Name | Beschreibung |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy) | Strategie zum Ausrichten von Text. Dieser Parameter hat nur Sinn, wenn Flag[`AlignText`](./aligntext) auf true gesetzt ist. |

### Siehe auch

* namensraum [Aspose.Pdf](../../aspose.pdf)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
