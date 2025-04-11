---
title: Class PdfFormatConversionOptions
second_title: Aspose.PDF for .NET API Reference
description: La classe Aspose.Pdf.PdfFormatConversionOptions rappresenta un insieme di opzioni per convertire documenti PDF
type: docs
weight: 8380
url: /it/net/aspose.pdf/pdfformatconversionoptions/
---
## PdfFormatConversionOptions class

rappresenta un insieme di opzioni per convertire documenti PDF

```csharp
public class PdfFormatConversionOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor)(PdfFormat) | Costruttore |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_1)(PdfFormat, ConvertErrorAction) | Costruttore |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_3)(string, PdfFormat) | Costruttore |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_2)(Stream, PdfFormat, ConvertErrorAction) | Costruttore |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_4)(string, PdfFormat, ConvertErrorAction) | Costruttore |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_5)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Costruttore |

## Properties

| Name | Description |
| --- | --- |
| static [Default](../../aspose.pdf/pdfformatconversionoptions/default/) { get; } | Ottiene l'oggetto PdfFormatConversionOptions con parametri predefiniti |
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext/) { get; set; } | Questo flag controlla l'allineamento del testo nel documento convertito. Per impostazione predefinita, la conversione del documento non influisce sull'allineamento del testo e lascia il testo così com'è. Ma in alcuni casi, la sostituzione del font causa sovrapposizioni di testo o spazi extra nel documento convertito. Quando questo flag è impostato, verranno eseguite operazioni di allineamento speciali. Questo flag dovrebbe essere impostato solo per documenti che presentano problemi con il testo sovrapposto o spazi di testo extra, poiché l'uso di questo flag riduce le prestazioni e in alcuni casi potrebbe corrompere il contenuto del testo. |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction/) { get; set; } | Azione per immagini con maschera morbida. |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction/) { get; set; } | Azione per oggetti che non possono essere convertiti |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy/) { get; set; } | Strategia(e) per escludere font superflui e ridurre la dimensione del file del documento. Questo parametro ha senso solo quando il flag [`OptimizeFileSize`](./optimizefilesize/) è impostato su true. Per impostazione predefinita, viene utilizzata una combinazione di strategie SubsetFonts e RemoveDuplicatedFonts. |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions/) { get; } | Opzioni per i casi in cui non è possibile incorporare alcuni font nel documento PDF. |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format/) { get; set; } | Formato PDF. |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename/) { get; set; } | Ottiene o imposta il nome del file del profilo icc. In caso di null, viene utilizzato il profilo icc predefinito. |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode/) { get; set; } | Ottiene/imposta l'esecuzione dei flussi di immagini in modalità asincrona. |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode/) { get; set; } | Modalità di conversione a bassa memoria abilitata |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo/) { get; set; } | Ottiene o imposta se passare i dati da Info a Metadata quando convertito in PDF 2.0. True per impostazione predefinita. |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename/) { get; set; } | Percorso del file in cui verranno memorizzati i commenti. |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream/) { get; set; } | Stream in cui verranno memorizzati i commenti. |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases/) { get; } | Contiene flag per controllare il processo di conversione PDF/A per i casi in cui il documento sorgente non corrisponde alla specifica PDF/A. |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts/) { get; } | Questa proprietà è una proprietà esterna. Contiene tutti i font (nomi dei font) che non sono stati trovati sul computer durante l'ultima conversione PDF/A. |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize/) { get; set; } | Ottiene o imposta un flag che abilita/disabilita una modalità di conversione speciale per ottenere un documento PDF/A con dimensioni di file ridotte. Ora questo flag influisce sull'ottimizzazione dei font utilizzati nel documento PDF; possibilmente, in futuro, questo flag sarà utilizzato anche per attivare l'ottimizzazione per altre strutture dati, come la grafica. L'impostazione di questo flag e della modalità potrebbe ridurre significativamente la dimensione del file, ma allo stesso tempo potrebbe ridurre significativamente le prestazioni della conversione. |
| [OutputIntent](../../aspose.pdf/pdfformatconversionoptions/outputintent/) { get; set; } | Ottiene o imposta l'[`OutputIntent`](../outputintent/) per la conversione del formato PDF. |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy/) { get; set; } | Strategia per elaborare simboli dall'area di utilizzo privato Unicode (PUA). |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy/) { get; set; } | Strategia per copiare i dati di codifica per font simbolici se il font TrueType simbolico ha più di una sottotabella di codifica. |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction/) { get; set; } | Azione per oggetti mascherati da immagini |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules/) { get; set; } | Regole per risolvere problemi con la mappatura unicode. Può essere null. |

## Fields

| Name | Description |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy/) | Strategia per allineare il testo. Questo parametro ha senso solo quando il flag [`AlignText`](./aligntext/) è impostato su true. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)