---
title: Class PdfAConvertOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfAConvertOptions-Klasse. Stellt Optionen für die Konvertierung von PDF-Dokumenten in das PDF/A-Format mit dem PdfAConverter-Plugin dar
type: docs
weight: 8990
url: /de/net/aspose.pdf.plugins/pdfaconvertoptions/
---
## PdfAConvertOptions-Klasse

Stellt Optionen für die Konvertierung von PDF-Dokumenten in das PDF/A-Format mit dem [`PdfAConverter`](../pdfaconverter/) Plugin dar.

```csharp
public sealed class PdfAConvertOptions : PdfAOptionsBase
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfAConvertOptions](pdfaconvertoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlignText](../../aspose.pdf.plugins/pdfaoptionsbase/aligntext/) { get; set; } | Ruft einen Wert ab oder legt ihn fest, der angibt, ob zusätzliche Mittel erforderlich sind, um die Textausrichtung während des PDF/A-Konvertierungsprozesses beizubehalten. |
| [ErrorAction](../../aspose.pdf.plugins/pdfaoptionsbase/erroraction/) { get; set; } | Ruft die Aktion ab oder legt sie fest, die für Objekte zu ergreifen ist, die nicht konvertiert werden können. |
| [ExcludeFontsStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/) { get; set; } | Ruft die Strategie zum Entfernen von Schriftarten ab oder legt sie fest, um die Dateigröße während des PDF/A-Konvertierungsprozesses zu minimieren. |
| [FontEmbeddingOptions](../../aspose.pdf.plugins/pdfaoptionsbase/fontembeddingoptions/) { get; } | Ruft die Optionen zum Verarbeiten von Schriftarten ab, die nicht in das Dokument eingebettet werden können. |
| [IccProfileFileName](../../aspose.pdf.plugins/pdfaoptionsbase/iccprofilefilename/) { get; set; } | Ruft den Dateinamen des ICC (International Color Consortium) Profils ab oder legt ihn fest, der für die PDF/A-Konvertierung anstelle des Standardprofils verwendet werden soll. |
| [Inputs](../../aspose.pdf.plugins/pdfaoptionsbase/inputs/) { get; } | Ruft die Sammlung von Datenquellen ab |
| [IsLowMemoryMode](../../aspose.pdf.plugins/pdfaoptionsbase/islowmemorymode/) { get; set; } | Ruft einen Wert ab oder legt ihn fest, der angibt, ob der Low-Memory-Modus während des PDF/A-Konvertierungsprozesses aktiviert ist. |
| [LogOutputSource](../../aspose.pdf.plugins/pdfaoptionsbase/logoutputsource/) { get; set; } | Ruft die Datenquelle für die Protokollausgabe ab oder legt sie fest. |
| [NonSpecificationFlags](../../aspose.pdf.plugins/pdfaoptionsbase/nonspecificationflags/) { get; } | Ruft die Flags ab, die die PDF/A-Konvertierung für Fälle steuern, in denen das Quell-PDF-Dokument nicht der PDF-Spezifikation entspricht. |
| [OptimizeFileSize](../../aspose.pdf.plugins/pdfaoptionsbase/optimizefilesize/) { get; set; } | Ruft einen Wert ab oder legt ihn fest, der angibt, ob versucht werden soll, die Dateigröße während des PDF/A-Konvertierungsprozesses zu reduzieren. |
| [Outputs](../../aspose.pdf.plugins/pdfaconvertoptions/outputs/) { get; } | Ruft die Sammlung der hinzugefügten Ziele (Datei- oder Stream-Datenquellen) für die Speicherung der Operationsergebnisse ab. |
| [PdfAVersion](../../aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/) { get; set; } | Ruft die Version des PDF/A-Standards ab oder legt sie fest, die für die Validierung oder Konvertierung verwendet werden soll. |
| [PuaSymbolsProcessingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/puasymbolsprocessingstrategy/) { get; set; } | Ruft die Strategie zum Verarbeiten von Symbolen im Private Use Area (PUA) im PDF-Dokument ab oder legt sie fest. |
| [SoftMaskAction](../../aspose.pdf.plugins/pdfaoptionsbase/softmaskaction/) { get; set; } | Ruft die Aktion ab oder legt sie fest, die während der Konvertierung von Bildern mit Soft-Masken ergriffen werden soll. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/symbolicfontencodingstrategy/) { get; set; } | Ruft die Strategie zum Kodieren von symbolischen Schriftarten beim Konvertieren in das PDF/A-Format ab oder legt sie fest. |
| [UnicodeProcessingRules](../../aspose.pdf.plugins/pdfaoptionsbase/unicodeprocessingrules/) { get; set; } | Ruft die Regeln für die Verarbeitung von ToUnicode CMap-Tabellen ab und nicht mit Unicode-Symbolen verknüpft während des PDF/A-Konvertierungsprozesses. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfaoptionsbase/addinput/)(IDataSource) | Fügt der Sammlung eine neue Datenquelle hinzu |
| [AddOutput](../../aspose.pdf.plugins/pdfaconvertoptions/addoutput/)(IDataSource) | Fügt ein neues Ziel zum Speichern des Ergebnisses hinzu. |

### Siehe auch

* Klasse [PdfAOptionsBase](../pdfaoptionsbase/)
* Namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* Assembly [Aspose.PDF](../../)