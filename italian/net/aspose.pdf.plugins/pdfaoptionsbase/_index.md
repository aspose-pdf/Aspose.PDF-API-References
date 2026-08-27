---
title: "Classe PdfAOptionsBase"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Plugins.PdfAOptionsBase. Rappresenta la classe base per le opzioni del plugin PdfAConverter. Questa classe fornisce proprietà e metodi per configurare il processo di conversione e convalida PDF/A."
type: docs
weight: 9160
url: /it/net/aspose.pdf.plugins/pdfaoptionsbase/
---
## PdfAOptionsBase class

Rappresenta la classe base per le opzioni del plugin [`PdfAConverter`](../pdfaconverter/). Questa classe fornisce proprietà e metodi per configurare il processo di conversione e convalida PDF/A.

```csharp
public abstract class PdfAOptionsBase : IPluginOptions
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlignText](../../aspose.pdf.plugins/pdfaoptionsbase/aligntext/) { get; set; } | Ottiene o imposta un valore che indica se sono necessari mezzi aggiuntivi per preservare l'allineamento del testo durante il processo di conversione PDF/A. |
| [ErrorAction](../../aspose.pdf.plugins/pdfaoptionsbase/erroraction/) { get; set; } | Ottiene o imposta l'azione da eseguire per gli oggetti che non possono essere convertiti. |
| [ExcludeFontsStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/) { get; set; } | Ottiene o imposta la strategia per rimuovere i font al fine di ridurre al minimo la dimensione del file di output durante il processo di conversione PDF/A. |
| [FontEmbeddingOptions](../../aspose.pdf.plugins/pdfaoptionsbase/fontembeddingoptions/) { get; } | Ottiene le opzioni per elaborare i font che non possono essere incorporati nel Document. |
| [IccProfileFileName](../../aspose.pdf.plugins/pdfaoptionsbase/iccprofilefilename/) { get; set; } | Ottiene o imposta il nome file del profilo ICC (International Color Consortium) da utilizzare per la conversione PDF/A al posto di quello predefinito. |
| [Inputs](../../aspose.pdf.plugins/pdfaoptionsbase/inputs/) { get; } | Ottiene la raccolta di origini dati. |
| [IsLowMemoryMode](../../aspose.pdf.plugins/pdfaoptionsbase/islowmemorymode/) { get; set; } | Ottiene o imposta un valore che indica se la modalità a bassa memoria è abilitata durante il processo di conversione PDF/A. |
| [LogOutputSource](../../aspose.pdf.plugins/pdfaoptionsbase/logoutputsource/) { get; set; } | Ottiene o imposta la fonte dati per l'output del log. |
| [NonSpecificationFlags](../../aspose.pdf.plugins/pdfaoptionsbase/nonspecificationflags/) { get; } | Ottiene i flag che controllano la conversione PDF/A per i casi in cui il Document PDF di origine non corrisponde alla specifica PDF. |
| [OptimizeFileSize](../../aspose.pdf.plugins/pdfaoptionsbase/optimizefilesize/) { get; set; } | Ottiene o imposta un valore che indica se provare a ridurre la dimensione del file durante il processo di conversione PDF/A. |
| [PdfAVersion](../../aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/) { get; set; } | Ottiene o imposta la versione dello standard PDF/A da utilizzare per la convalida o la conversione. |
| [PuaSymbolsProcessingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/puasymbolsprocessingstrategy/) { get; set; } | Ottiene o imposta la strategia per l'elaborazione dei simboli Private Use Area (PUA) nel documento PDF. |
| [SoftMaskAction](../../aspose.pdf.plugins/pdfaoptionsbase/softmaskaction/) { get; set; } | Ottiene o imposta l'azione da eseguire durante la conversione delle immagini con maschere morbide. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/symbolicfontencodingstrategy/) { get; set; } | Ottiene o imposta la strategia per la codifica dei font simbolici durante la conversione al formato PDF/A. |
| [UnicodeProcessingRules](../../aspose.pdf.plugins/pdfaoptionsbase/unicodeprocessingrules/) { get; set; } | Ottiene o imposta le regole per l'elaborazione delle tabelle ToUnicode CMap e non collegate ai simboli Unicode durante il processo di conversione PDF/A. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfaoptionsbase/addinput/)(IDataSource) | Aggiunge una nuova origine dati alla raccolta |

### Vedi anche

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


