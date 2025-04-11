---
title: Class PdfAOptionsBase
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfAOptionsBase-Klasse. Stellt die Basisklasse für die Optionen des PdfAConverter-Plugins dar. Diese Klasse bietet Eigenschaften und Methoden zur Konfiguration des PDF/A-Konvertierungs- und Validierungsprozesses.
type: docs
weight: 9010
url: /de/net/aspose.pdf.plugins/pdfaoptionsbase/
---
## PdfAOptionsBase-Klasse

Stellt die Basisklasse für die [`PdfAConverter`](../pdfaconverter/) Plugin-Optionen dar. Diese Klasse bietet Eigenschaften und Methoden zur Konfiguration des PDF/A-Konvertierungs- und Validierungsprozesses.

```csharp
public abstract class PdfAOptionsBase : IPluginOptions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlignText](../../aspose.pdf.plugins/pdfaoptionsbase/aligntext/) { get; set; } | Ruft einen Wert ab oder legt einen fest, der angibt, ob zusätzliche Mittel erforderlich sind, um die Textausrichtung während des PDF/A-Konvertierungsprozesses beizubehalten. |
| [ErrorAction](../../aspose.pdf.plugins/pdfaoptionsbase/erroraction/) { get; set; } | Ruft die Aktion ab oder legt die Aktion fest, die für Objekte durchgeführt werden soll, die nicht konvertiert werden können. |
| [ExcludeFontsStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/) { get; set; } | Ruft die Strategie zum Entfernen von Schriftarten ab oder legt sie fest, um die Dateigröße während des PDF/A-Konvertierungsprozesses zu minimieren. |
| [FontEmbeddingOptions](../../aspose.pdf.plugins/pdfaoptionsbase/fontembeddingoptions/) { get; } | Ruft die Optionen zum Verarbeiten von Schriftarten ab, die nicht in das Dokument eingebettet werden können. |
| [IccProfileFileName](../../aspose.pdf.plugins/pdfaoptionsbase/iccprofilefilename/) { get; set; } | Ruft den Dateinamen des ICC (International Color Consortium)-Profils ab oder legt ihn fest, der für die PDF/A-Konvertierung anstelle des Standardprofils verwendet werden soll. |
| [Inputs](../../aspose.pdf.plugins/pdfaoptionsbase/inputs/) { get; } | Ruft die Sammlung von Datenquellen ab |
| [IsLowMemoryMode](../../aspose.pdf.plugins/pdfaoptionsbase/islowmemorymode/) { get; set; } | Ruft einen Wert ab oder legt einen fest, der angibt, ob der Low-Memory-Modus während des PDF/A-Konvertierungsprozesses aktiviert ist. |
| [LogOutputSource](../../aspose.pdf.plugins/pdfaoptionsbase/logoutputsource/) { get; set; } | Ruft die Datenquelle für die Protokollausgabe ab oder legt sie fest. |
| [NonSpecificationFlags](../../aspose.pdf.plugins/pdfaoptionsbase/nonspecificationflags/) { get; } | Ruft die Flags ab, die die PDF/A-Konvertierung für Fälle steuern, in denen das Quell-PDF-Dokument nicht der PDF-Spezifikation entspricht. |
| [OptimizeFileSize](../../aspose.pdf.plugins/pdfaoptionsbase/optimizefilesize/) { get; set; } | Ruft einen Wert ab oder legt einen fest, der angibt, ob versucht werden soll, die Dateigröße während des PDF/A-Konvertierungsprozesses zu reduzieren. |
| [PdfAVersion](../../aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/) { get; set; } | Ruft die Version des PDF/A-Standards ab oder legt sie fest, die für die Validierung oder Konvertierung verwendet werden soll. |
| [PuaSymbolsProcessingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/puasymbolsprocessingstrategy/) { get; set; } | Ruft die Strategie zum Verarbeiten von Symbolen im Bereich für private Nutzung (PUA) im PDF-Dokument ab oder legt sie fest. |
| [SoftMaskAction](../../aspose.pdf.plugins/pdfaoptionsbase/softmaskaction/) { get; set; } | Ruft die Aktion ab oder legt die Aktion fest, die während der Konvertierung von Bildern mit Soft-Masken durchgeführt werden soll. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/symbolicfontencodingstrategy/) { get; set; } | Ruft die Strategie zum Kodieren von symbolischen Schriftarten beim Konvertieren in das PDF/A-Format ab oder legt sie fest. |
| [UnicodeProcessingRules](../../aspose.pdf.plugins/pdfaoptionsbase/unicodeprocessingrules/) { get; set; } | Ruft die Regeln zum Verarbeiten von ToUnicode CMap-Tabellen ab oder legt sie fest, die nicht mit Unicode-Symbolen während des PDF/A-Konvertierungsprozesses verknüpft sind. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfaoptionsbase/addinput/)(IDataSource) | Fügt der Sammlung eine neue Datenquelle hinzu |

### Siehe auch

* Schnittstelle [IPluginOptions](../ipluginoptions/)
* Namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* Assembly [Aspose.PDF](../../)