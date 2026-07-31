---
title: "Classe PdfAConvertOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Plugins.PdfAConvertOptions. Rappresenta le opzioni per la conversione di documenti PDF in formato PDF/A con il plugin PdfAConverter"
type: docs
weight: 9140
url: /it/net/aspose.pdf.plugins/pdfaconvertoptions/
---
## PdfAConvertOptions class

Rappresenta le opzioni per la conversione di documenti PDF in formato PDF/A con il plugin [`PdfAConverter`](../pdfaconverter/).

```csharp
public sealed class PdfAConvertOptions : PdfAOptionsBase
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfAConvertOptions](pdfaconvertoptions/)() | Il costruttore predefinito. |

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
| [Outputs](../../aspose.pdf.plugins/pdfaconvertoptions/outputs/) { get; } | Ottiene la collezione di destinazioni aggiunte (file o sorgenti dati stream) per i risultati dell'operazione di salvataggio. |
| [PdfAVersion](../../aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/) { get; set; } | Ottiene o imposta la versione dello standard PDF/A da utilizzare per la convalida o la conversione. |
| [PuaSymbolsProcessingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/puasymbolsprocessingstrategy/) { get; set; } | Ottiene o imposta la strategia per l'elaborazione dei simboli Private Use Area (PUA) nel documento PDF. |
| [SoftMaskAction](../../aspose.pdf.plugins/pdfaoptionsbase/softmaskaction/) { get; set; } | Ottiene o imposta l'azione da eseguire durante la conversione delle immagini con maschere morbide. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/symbolicfontencodingstrategy/) { get; set; } | Ottiene o imposta la strategia per la codifica dei font simbolici durante la conversione al formato PDF/A. |
| [UnicodeProcessingRules](../../aspose.pdf.plugins/pdfaoptionsbase/unicodeprocessingrules/) { get; set; } | Ottiene o imposta le regole per l'elaborazione delle tabelle ToUnicode CMap e non collegate ai simboli Unicode durante il processo di conversione PDF/A. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfaoptionsbase/addinput/)(IDataSource) | Aggiunge una nuova origine dati alla raccolta |
| [AddOutput](../../aspose.pdf.plugins/pdfaconvertoptions/addoutput/)(IDataSource) | Aggiunge una nuova destinazione di salvataggio del risultato. |

### Vedi anche

* class [PdfAOptionsBase](../pdfaoptionsbase/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


