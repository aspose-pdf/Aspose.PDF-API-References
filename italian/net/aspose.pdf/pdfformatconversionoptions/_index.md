---
title: "Classe PdfFormatConversionOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.PdfFormatConversionOptions. Rappresenta un insieme di opzioni per convertire un documento PDF"
type: docs
weight: 8520
url: /it/net/aspose.pdf/pdfformatconversionoptions/
---
## PdfFormatConversionOptions class

rappresenta un insieme di opzioni per convertire il documento PDF

```csharp
public class PdfFormatConversionOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor)(PdfFormat) | Costruttore |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_1)(PdfFormat, ConvertErrorAction) | Costruttore |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_3)(string, PdfFormat) | Costruttore |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_2)(Stream, PdfFormat, ConvertErrorAction) | Costruttore |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_4)(string, PdfFormat, ConvertErrorAction) | Costruttore |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_5)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [Default](../../aspose.pdf/pdfformatconversionoptions/default/) { get; } | Ottiene l'oggetto PdfFormatConversionOptions con i parametri predefiniti |
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext/) { get; set; } | Questa opzione controlla l'allineamento del testo nel documento convertito. Per impostazione predefinita la conversione del documento non influisce sull'allineamento del testo e lo lascia invariato. Tuttavia, in alcuni casi la sostituzione dei caratteri provoca sovrapposizioni di testo o spazi aggiuntivi nel documento convertito. Quando questa opzione è impostata, verranno eseguite operazioni speciali di allineamento. Questa opzione dovrebbe essere impostata solo per i documenti che presentano problemi di testo sovrapposto o spazi extra, poiché l'uso di questa opzione diminuisce le prestazioni e in alcuni casi potrebbe corrompere il contenuto del testo. |
| [AutoTaggingSettings](../../aspose.pdf/pdfformatconversionoptions/autotaggingsettings/) { get; set; } | Ottiene o imposta le impostazioni per il tagging automatico durante la conversione del formato PDF. |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction/) { get; set; } | Azione per le immagini con maschera morbida. |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction/) { get; set; } | Azione per gli oggetti che non possono essere convertiti |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy/) { get; set; } | Strategia(e) per escludere i font superflui e ridurre la dimensione del file del documento. Questo parametro ha senso solo quando l'opzione [`OptimizeFileSize`](./optimizefilesize/) è impostata su true. Per impostazione predefinita viene utilizzata la combinazione delle strategie SubsetFonts e RemoveDuplicatedFonts. |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions/) { get; } | Opzioni per i casi in cui non è possibile incorporare alcuni font nel documento PDF. |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format/) { get; set; } | Formato PDF. |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename/) { get; set; } | Ottiene o imposta il nome file del profilo ICC. In caso di null viene utilizzato il profilo ICC predefinito. |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode/) { get; set; } | Ottiene/imposta l'esecuzione dei flussi di immagini in modalità asincrona. |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode/) { get; set; } | È abilitata la modalità di conversione a bassa memoria |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo/) { get; set; } | Ottiene o imposta se trasferire i dati da Info a Metadata quando convertito in PDF 2.0. True per impostazione predefinita. |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename/) { get; set; } | Percorso del file in cui verranno memorizzati i commenti. |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream/) { get; set; } | Stream in cui verranno memorizzati i commenti. |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases/) { get; } | Contiene le opzioni per controllare il processo di conversione PDF/A nei casi in cui il documento di origine non corrisponda alla specifica PDF/A. |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts/) { get; } | Questa proprietà è una proprietà di output. Contiene tutti i font (nomi dei font) che non sono stati trovati sul computer nell'ultima conversione PDF/A. |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize/) { get; set; } | Ottiene o imposta un'opzione che abilita/disabilita la modalità di conversione speciale per ottenere un documento PDF/A con dimensione ridotta. Attualmente questa opzione influisce sull'ottimizzazione dei font utilizzati nel documento PDF e, possibilmente in futuro, sarà usata anche per attivare l'ottimizzazione di altre strutture dati, come la grafica. L'insieme di questa opzione e della modalità può ridurre significativamente la dimensione del file, ma allo stesso tempo può diminuire notevolmente le prestazioni della conversione. |
| [OutputIntent](../../aspose.pdf/pdfformatconversionoptions/outputintent/) { get; set; } | Ottiene o imposta il [`OutputIntent`](../outputintent/) per la conversione del formato PDF. |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy/) { get; set; } | Strategia per elaborare i simboli dall'area di uso privato Unicode (PUA). |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy/) { get; set; } | Strategia per copiare i dati di codifica per i caratteri simbolici se il font TrueType simbolico ha più di una sottotabella di codifica. |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction/) { get; set; } | Azione per oggetti mascherati di immagine |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules/) { get; set; } | Regole per risolvere i problemi di mappatura Unicode. Può essere nullo. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy/) | Strategia per allineare il testo. Questo parametro ha senso solo quando il flag [`AlignText`](./aligntext/) è impostato su true. |

### Vedi anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


