---
title: PdfFormatConversionOptions
second_title: Aspose.PDF per .NET API Reference
description: rappresenta linsieme di opzioni per convertire il documento PDF
type: docs
weight: 6030
url: /it/net/aspose.pdf/pdfformatconversionoptions/
---
## PdfFormatConversionOptions class

rappresenta l'insieme di opzioni per convertire il documento PDF

```csharp
public class PdfFormatConversionOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor)(PdfFormat) | Costruttore |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_1)(PdfFormat, ConvertErrorAction) | Costruttore |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_3)(string, PdfFormat) | Costruttore |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_2)(Stream, PdfFormat, ConvertErrorAction) | Costruttore |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_4)(string, PdfFormat, ConvertErrorAction) | Costruttore |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_5)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [Default](../../aspose.pdf/pdfformatconversionoptions/default) { get; } | Ottiene l'oggetto PdfFormatConversionOptions con parametri predefiniti |
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext) { get; set; } | Questo flag controlla l'allineamento del testo nel documento convertito. Per impostazione predefinita, la conversione del documento non influisce sull'allineamento del testo e lascia il testo così com'è. Ma in alcuni casi la sostituzione del carattere provoca la sovrapposizione del testo o spazi extra nel documento convertito. Quando questo flag è impostato verranno eseguite speciali operazioni di allineamento. Questo flag dovrebbe essere impostato solo per i documenti che hanno problemi con testo sovrapposto o spazi di testo extra causano l'uso di questo flag che riduce le prestazioni e in alcuni casi potrebbe danneggiare il contenuto del testo. |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction) { get; set; } | Azione per immagini con maschera morbida. |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction) { get; set; } | Azione per oggetti che non possono essere convertiti |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy) { get; set; } | Strategie per escludere i font superflui e ridurre le dimensioni del file del documento. Questo parametro ha senso solo quando flag[`OptimizeFileSize`](./optimizefilesize) è impostato su true. Per impostazione predefinita, combinazione di strategieSubsetFonts e RemoveDuplicatedFonts viene utilizzato. |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions) { get; } | Opzioni per i casi in cui non è possibile incorporare alcuni font nel documento PDF. |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format) { get; set; } | formato PDF. |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename) { get; set; } | Ottiene o imposta il nome del file del nome del profilo icc. In caso di null viene utilizzato il profilo icc predefinito. |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode) { get; set; } | Ottiene/imposta l'esecuzione di flussi di immagini in modalità asincrona. |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode) { get; set; } | La modalità di conversione della memoria insufficiente è abilitata |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo) { get; set; } | Ottiene o imposta se passare i dati dalle informazioni ai metadati quando vengono convertiti in PDF 2.0. Vero per impostazione predefinita. |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename) { get; set; } | Percorso del file in cui verranno archiviati i commenti. |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream) { get; set; } | Stream in cui verranno archiviati i commenti. |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases) { get; } | Contiene i flag per controllare il processo di conversione PDF/A per i casi in cui il documento di origine non corrisponde alla specifica PDF/A. |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts) { get; } | Questa proprietà è fuori proprietà. Contiene tutti i caratteri (nomi dei caratteri) che non sono stati trovati sul computer all'ultima conversione PDF/A. |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize) { get; set; } | Ottiene o imposta un flag che abilita/disabilita la modalità di conversione speciale per ottenere un documento PDF/A con dimensioni del file ridotte. Ora questo flag influisce sull'ottimizzazione dei caratteri utilizzati nel documento PDF, probabilmente, in futuro, verrà utilizzato anche questo flag per attivare l'ottimizzazione per altre strutture dati, come la grafica. L'impostazione di questo flag e modalità potrebbe ridurre significativamente le dimensioni del file ma allo stesso tempo potrebbe ridurre significativamente le prestazioni di conversione. |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy) { get; set; } | Strategia per elaborare simboli da Unicode Private Use Area (PUA). |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy) { get; set; } | Strategia per copiare i dati di codifica per i font simbolici se il font TrueType simbolico ha più di una sottotabella di codifica. |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction) { get; set; } | Azione per oggetti con maschera immagine |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules) { get; set; } | Regole per risolvere problemi con la mappatura unicode. Può essere nullo. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy) | Strategia per allineare il testo. Questo parametro ha senso solo quando flag[`AlignText`](./aligntext) è impostato su true. |

### Guarda anche

* spazio dei nomi [Aspose.Pdf](../../aspose.pdf)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
