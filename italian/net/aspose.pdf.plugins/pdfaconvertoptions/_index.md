---
title: Class PdfAConvertOptions
second_title: Aspose.PDF for .NET API Reference
description: La classe Aspose.Pdf.Plugins.PdfAConvertOptions. Rappresenta le opzioni per convertire documenti PDF in formato PDF/A con il plugin PdfAConverter
type: docs
weight: 8990
url: /it/net/aspose.pdf.plugins/pdfaconvertoptions/
---
## PdfAConvertOptions class

Rappresenta le opzioni per convertire documenti PDF in formato PDF/A con il plugin [`PdfAConverter`](../pdfaconverter/).

```csharp
public sealed class PdfAConvertOptions : PdfAOptionsBase
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfAConvertOptions](pdfaconvertoptions/)() | Il costruttore predefinito. |

## Properties

| Name | Description |
| --- | --- |
| [AlignText](../../aspose.pdf.plugins/pdfaoptionsbase/aligntext/) { get; set; } | Ottiene o imposta un valore che indica se sono necessari mezzi aggiuntivi per preservare l'allineamento del testo durante il processo di conversione PDF/A. |
| [ErrorAction](../../aspose.pdf.plugins/pdfaoptionsbase/erroraction/) { get; set; } | Ottiene o imposta l'azione da intraprendere per gli oggetti che non possono essere convertiti. |
| [ExcludeFontsStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/) { get; set; } | Ottiene o imposta la strategia per rimuovere i font per minimizzare la dimensione del file di output durante il processo di conversione PDF/A. |
| [FontEmbeddingOptions](../../aspose.pdf.plugins/pdfaoptionsbase/fontembeddingoptions/) { get; } | Ottiene le opzioni per elaborare i font che non possono essere incorporati nel documento. |
| [IccProfileFileName](../../aspose.pdf.plugins/pdfaoptionsbase/iccprofilefilename/) { get; set; } | Ottiene o imposta il nome del file del profilo ICC (International Color Consortium) da utilizzare per la conversione PDF/A al posto di quello predefinito. |
| [Inputs](../../aspose.pdf.plugins/pdfaoptionsbase/inputs/) { get; } | Ottiene la collezione di fonti di dati |
| [IsLowMemoryMode](../../aspose.pdf.plugins/pdfaoptionsbase/islowmemorymode/) { get; set; } | Ottiene o imposta un valore che indica se la modalità a bassa memoria è abilitata durante il processo di conversione PDF/A. |
| [LogOutputSource](../../aspose.pdf.plugins/pdfaoptionsbase/logoutputsource/) { get; set; } | Ottiene o imposta la fonte di dati per l'output del log. |
| [NonSpecificationFlags](../../aspose.pdf.plugins/pdfaoptionsbase/nonspecificationflags/) { get; } | Ottiene i flag che controllano la conversione PDF/A per i casi in cui il documento PDF sorgente non corrisponde alla specifica PDF. |
| [OptimizeFileSize](../../aspose.pdf.plugins/pdfaoptionsbase/optimizefilesize/) { get; set; } | Ottiene o imposta un valore che indica se tentare di ridurre la dimensione del file durante il processo di conversione PDF/A. |
| [Outputs](../../aspose.pdf.plugins/pdfaconvertoptions/outputs/) { get; } | Ottiene la collezione di destinazioni aggiunte (file o fonti di dati stream) per i risultati dell'operazione di salvataggio. |
| [PdfAVersion](../../aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/) { get; set; } | Ottiene o imposta la versione dello standard PDF/A da utilizzare per la validazione o la conversione. |
| [PuaSymbolsProcessingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/puasymbolsprocessingstrategy/) { get; set; } | Ottiene o imposta la strategia per elaborare i simboli dell'Area di Uso Privato (PUA) nel documento PDF. |
| [SoftMaskAction](../../aspose.pdf.plugins/pdfaoptionsbase/softmaskaction/) { get; set; } | Ottiene o imposta l'azione da intraprendere durante la conversione di immagini con maschere morbide. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/symbolicfontencodingstrategy/) { get; set; } | Ottiene o imposta la strategia per la codifica dei font simbolici durante la conversione in formato PDF/A. |
| [UnicodeProcessingRules](../../aspose.pdf.plugins/pdfaoptionsbase/unicodeprocessingrules/) { get; set; } | Ottiene o imposta le regole per l'elaborazione delle tabelle CMap ToUnicode e non collegate ai simboli Unicode durante il processo di conversione PDF/A. |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfaoptionsbase/addinput/)(IDataSource) | Aggiunge una nuova fonte di dati alla collezione |
| [AddOutput](../../aspose.pdf.plugins/pdfaconvertoptions/addoutput/)(IDataSource) | Aggiunge un nuovo obiettivo di salvataggio dei risultati. |

### See Also

* class [PdfAOptionsBase](../pdfaoptionsbase/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)