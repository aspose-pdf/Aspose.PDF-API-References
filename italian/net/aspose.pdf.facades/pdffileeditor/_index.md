---
title: PdfFileEditor
second_title: Aspose.PDF per .NET API Reference
description: Esegue operazioni con file PDF concatenazione divisione estrazione pagine creazione libretto ecc.
type: docs
weight: 2470
url: /it/net/aspose.pdf.facades/pdffileeditor/
---
## PdfFileEditor class

Esegue operazioni con file PDF: concatenazione, divisione, estrazione pagine, creazione libretto, ecc.

```csharp
public sealed class PdfFileEditor
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfFileEditor](pdffileeditor)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/pdffileeditor/attachmentname) { get; set; } | Ottiene o imposta il nome dell'allegato quando il risultato dell'operazione viene archiviato negli oggetti HttpResponse come allegato. |
| [CloseConcatenatedStreams](../../aspose.pdf.facades/pdffileeditor/closeconcatenatedstreams) { get; set; } | Se impostato su true, i flussi vengono chiusi dopo l'operazione. |
| [ConcatenationPacketSize](../../aspose.pdf.facades/pdffileeditor/concatenationpacketsize) { get; set; } | Numero di documenti concatenati prima che fosse effettuato un nuovo aggiornamento incrementale durante la concatenazione quando UseDiskBuffer è impostato su true. |
| [ContentDisposition](../../aspose.pdf.facades/pdffileeditor/contentdisposition) { get; set; } | Ottiene o imposta la modalità di archiviazione del contenuto quando il risultato dell'operazione viene archiviato nell'oggetto HttpResponse. Valore possibile: inline/allegato. Predefinito: inline. |
| [ConversionLog](../../aspose.pdf.facades/pdffileeditor/conversionlog) { get; } | Ottiene il registro del processo di conversione. |
| [ConvertTo](../../aspose.pdf.facades/pdffileeditor/convertto) { set; } | Imposta il formato del file PDF. Il file dei risultati verrà salvato nel formato file specificato. Se questa proprietà non è specificata, il file verrà salvato nel formato PDF predefinito senza conversione. |
| [CopyLogicalStructure](../../aspose.pdf.facades/pdffileeditor/copylogicalstructure) { get; set; } | Se true, la struttura logica del file viene copiata quando viene eseguita la concatenazione. |
| [CopyOutlines](../../aspose.pdf.facades/pdffileeditor/copyoutlines) { get; set; } | Se true, i contorni verranno copiati. |
| [CorruptedFileAction](../../aspose.pdf.facades/pdffileeditor/corruptedfileaction) { get; set; } | Questa proprietà definisce il comportamento durante la concatenazione del processo e del file danneggiato. I valori possibili sono: StopWithError e ConcatenateIgnoringCorrupted. |
| [CorruptedItems](../../aspose.pdf.facades/pdffileeditor/corrupteditems) { get; } | Matrice di problemi riscontrati durante l'esecuzione della concatenazione. Per ogni documento danneggiato passato alla funzione Concatenate() viene creata una nuova voce CorruptedItem. Questa proprietà può essere utilizzata solo quando CorruptedFileAction è ConcatenateIgnoringCorrupted. |
| [IncrementalUpdates](../../aspose.pdf.facades/pdffileeditor/incrementalupdates) { get; set; } | Se true, gli aggiornamenti incrementali vengono effettuati durante la concatenazione. |
| [KeepActions](../../aspose.pdf.facades/pdffileeditor/keepactions) { get; set; } | Se le azioni vere verranno copiate dai documenti di origine. Valore predefinito: true. |
| [KeepFieldsUnique](../../aspose.pdf.facades/pdffileeditor/keepfieldsunique) { get; set; } | Se true, i nomi dei campi verranno resi univoci quando i moduli vengono concatenati. I suffissi verranno aggiunti ai nomi dei campi, il modello di suffisso può essere specificato nella proprietà UniqueSuffix. |
| [LastException](../../aspose.pdf.facades/pdffileeditor/lastexception) { get; } | Ottiene l'ultima eccezione verificatasi. Può essere utilizzato per verificare il motivo dell'errore. |
| [MergeDuplicateLayers](../../aspose.pdf.facades/pdffileeditor/mergeduplicatelayers) { get; set; } | I contenuti facoltativi di documenti concatenati con nomi uguali verranno uniti in un livello nel documento risultante se questa proprietà è vera. Altrimenti, i livelli con nomi uguali verranno salvati come livelli diversi nel documento risultante. |
| [MergeDuplicateOutlines](../../aspose.pdf.facades/pdffileeditor/mergeduplicateoutlines) { get; set; } | Se true, i contorni duplicati vengono uniti. |
| [OptimizeSize](../../aspose.pdf.facades/pdffileeditor/optimizesize) { get; set; } | Ottiene o imposta il flag di ottimizzazione. Flussi di risorse uguali nel file risultante vengono uniti in un oggetto PDF se questo flag è impostato. Ciò consente di ridurre la dimensione del file risultante ma può causare un'esecuzione più lenta e maggiori requisiti di memoria. Valore predefinito: false. |
| [OwnerPassword](../../aspose.pdf.facades/pdffileeditor/ownerpassword) { get; set; } | Imposta la password del proprietario se il file Pdf di input di origine è crittografato. Questa proprietà non è ancora implementata. |
| [PreserveUserRights](../../aspose.pdf.facades/pdffileeditor/preserveuserrights) { get; set; } | Se true, i diritti utente del primo documento vengono applicati al documento concatenato. I diritti utente di tutti gli altri documenti vengono ignorati. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffileeditor/removesignatures) { get; set; } | Se true, tutte le firme verranno rimosse dai campi (i campi rimarranno); in caso contrario, puoi ottenere firme non valide. |
| [SaveOptions](../../aspose.pdf.facades/pdffileeditor/saveoptions) { get; set; } | Ottiene o imposta le opzioni di salvataggio quando il risultato viene archiviato come HttpResponse. Valore predefinito: PdfSaveOptions. |
| [UniqueSuffix](../../aspose.pdf.facades/pdffileeditor/uniquesuffix) { get; set; } | Formato del suffisso che viene aggiunto al nome del campo per renderlo univoco quando i moduli vengono concatenati. Questa stringa deve contenere %NUM% sottostringa che verrà sostituita con numeri. Ad esempio se UniqueSuffix = "ABC%NUM%" allora per i nomi dei campi "fieldName" saranno: fieldNameABC1, fieldNameABC2, fieldNameABC3 ecc. |
| [UseDiskBuffer](../../aspose.pdf.facades/pdffileeditor/usediskbuffer) { get; set; } | Se questa opzione viene utilizzata, il documento di destinazione verrà salvato periodicamente su disco e verrà applicata un'ulteriore concatenazione come aggiornamenti incrementali. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins#addmargins)(Stream, Stream, int[], double, double, double, double) | Ridimensiona il contenuto della pagina e aggiunge i margini specificati. I margini sono specificati in unità di spazio predefinite. |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins#addmargins_1)(string, string, int[], double, double, double, double) | Ridimensiona il contenuto della pagina e aggiunge i margini specificati. I margini sono specificati in unità di spazio predefinite. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct#addmarginspct)(Stream, Stream, int[], double, double, double, double) | Ridimensiona il contenuto della pagina e aggiunge i margini specificati. I margini sono specificati in percentuali della dimensione iniziale della pagina. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct#addmarginspct_1)(string, string, int[], double, double, double, double) | Ridimensiona il contenuto della pagina e aggiunge i margini specificati. I margini sono specificati in percentuali della dimensione iniziale della pagina. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak#addpagebreak)(Document, Document, PageBreak[]) | Aggiunge interruzioni di pagina alle pagine del documento. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak#addpagebreak_1)(Stream, Stream, PageBreak[]) | Aggiunge interruzioni di pagina alle pagine del documento. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak#addpagebreak_2)(string, string, PageBreak[]) | Aggiunge interruzioni di pagina alle pagine del documento. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append)(Stream, Stream, int, int, Stream) | Aggiunge le pagine, che sono scelte da portStream nell'intervallo da startPage a endPage, in portStream alla fine di firstInputStream. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_2)(Stream, Stream[], int, int, HttpResponse) | Aggiunge i documenti al documento di origine e salva il risultato nell'oggetto di risposta. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_1)(Stream, Stream[], int, int, Stream) | Aggiunge le pagine, che sono scelte dall'array di documenti in portStreams. Il documento risultante include firstInputFile e tutte le pagine dei documenti portStreams nell'intervallo da startPage a endPage. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_3)(string, string, int, int, string) | Aggiunge le pagine, scelte da portFile nell'intervallo da startPage a endPage, in portFile alla fine di firstInputFile. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_5)(string, string[], int, int, HttpResponse) | Aggiunge i documenti al documento di origine e salva il risultato nell'oggetto HttpResponse. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_4)(string, string[], int, int, string) | Aggiunge le pagine scelte dai documenti portFiles. Il documento risultato include firstInputFile e tutte le pagine dei documenti portFiles nell'intervallo da startPage a endPage. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate)(Document[], Document) | Concatena i documenti. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_4)(Stream[], HttpResponse) | Concatena i file e memorizza i risultati nell'oggetto HttpResponse. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_3)(Stream[], Stream) | Concatena i file |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_8)(string[], HttpResponse) | Concatena i file e salva il risultato nell'oggetto HttpResposnse. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_7)(string[], string) | Concatena i file in un unico file. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_1)(Stream, Stream, Stream) | Concatena due file. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_5)(string, string, string) | Concatena due file. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_2)(Stream, Stream, Stream, Stream) | Unisce due documenti Pdf in un nuovo documento Pdf con pagine in modi alternativi e riempie gli spazi vuoti con pagine vuote. es: il documento1 ha 5 pagine: p1, p2, p3, p4, p5. document2 ha 3 pagine: p1', p2', p3'. L'unione dei due documenti Pdf produrrà il documento risultante con le pagine: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage . |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_6)(string, string, string, string) | Unisce due documenti Pdf in un nuovo documento Pdf con pagine in modi alternativi e riempie gli spazi vuoti con pagine vuote. es: il documento1 ha 5 pagine: p1, p2, p3, p4, p5. document2 ha 3 pagine: p1', p2', p3'. L'unione dei due documenti Pdf produrrà il documento risultante con le pagine: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage . |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete_1)(Stream, int[], HttpResponse) | Elimina le pagine specificate dal documento e salva il risultato nell'oggetto HttpResponse. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete)(Stream, int[], Stream) | Elimina le pagine specificate dall'array di numeri dal file di input, salva come un nuovo file Pdf. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete_3)(string, int[], HttpResponse) | Elimina le pagine specificate dal documento e memorizza il risultato nell'oggetto HttpResponse. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete_2)(string, int[], string) | Elimina le pagine specificate dall'array di numeri dal file di input, salva come un nuovo file Pdf. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_2)(Stream, int[], HttpResponse) | Estrae le pagine specificate dal file di origine e memorizza il risultato nell'oggetto HttpResponse. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_1)(Stream, int[], Stream) | Estrae le pagine specificate dall'array di numeri, le salva come un nuovo file Pdf. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_5)(string, int[], HttpResponse) | Estrae le pagine specificate dal file di origine e memorizza il risultato nell'oggetto HttpResponse. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_4)(string, int[], string) | Estrae le pagine specificate dall'array di numeri, le salva come un nuovo file PDF. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract)(Stream, int, int, Stream) | Estrae le pagine dal file di input, salva come nuovo file Pdf. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_3)(string, int, int, string) | Estrae le pagine dal file di input, salva come nuovo file Pdf. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_2)(Stream, int, Stream, int[], HttpResponse) | Inserisce il documento in un altro documento e memorizza il risultato nell'oggetto risposta. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_1)(Stream, int, Stream, int[], Stream) | Inserisce le pagine da un altro file nel file Pdf di input. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_5)(string, int, string, int[], HttpResponse) | Inserisce il contenuto del file nel file di origine e memorizza il risultato nell'oggetto HttpResponse. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_4)(string, int, string, int[], string) | Inserisce le pagine da un altro file nel file Pdf di input. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert)(Stream, int, Stream, int, int, Stream) | Inserisce le pagine da un altro file nel file Pdf di input. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_3)(string, int, string, int, int, string) | Inserisce le pagine da un altro file nel file Pdf in una posizione. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_2)(Stream, Stream) | Crea opuscolo da InputStream a outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_8)(string, string) | Crea opuscolo dal file di input al file di output. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_1)(Stream, PageSize, HttpResponse) | Crea opuscolo dal file sorgente e memorizza il risultato in HttpResponse. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_3)(Stream, Stream, PageSize) | Crea opuscolo dal flusso di input e salva il risultato nel flusso di output. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_7)(string, PageSize, HttpResponse) | Crea opuscolo dal file di origine e memorizza il risultato in oggetti HttpResponse. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_9)(string, string, PageSize) | Crea opuscolo da inputFile a outputFile. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_5)(Stream, Stream, int[], int[]) | Crea opuscoli personalizzati dal primo InputStream a outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_11)(string, string, int[], int[]) | Crea opuscolo personalizzato dal firstInputFile a outputFile. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet)(Stream, PageSize, int[], int[], HttpResponse) | Crea un opuscolo da un file PDF e lo memorizza in HttpResponse. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_4)(Stream, Stream, PageSize, int[], int[]) | Crea opuscolo dal primo InputStream a outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_6)(string, PageSize, int[], int[], HttpResponse) | Crea opuscolo dal file sorgente e memorizza il risultato in oggetti HttpResponse. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_10)(string, string, PageSize, int[], int[]) | Crea opuscolo personalizzato dal firstInputFile a outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_4)(Stream, Stream, Stream) | Crea un documento N-Up dai due flussi PDF di input a outputStream. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_5)(Stream[], Stream, bool) | Crea un documento N su 1 dai flussi PDF multi input a outputStream. Ogni pagina di outputStream conterrà più pagine, che sono una combinazione con le pagine nei flussi di input con lo stesso numero di pagina. Le pagine multiple impilate orizzontalmente se isSidewise è vero e impilate verticalmente se isSidewise è false. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_10)(string, string, string) | Crea un documento N-Up dai due file PDF di input in outputFile. Ogni pagina di outputFile conterrà due pagine, una pagina proviene dal primo file di input e un'altra dal secondo file di input. Le due pagine sono impilate orizzontalmente. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_11)(string[], string, bool) | Crea un documento N-Up dai file PDF multi input a outputFile. Ogni pagina di outputFile conterrà più pagine, che sono una combinazione con le pagine nei file di input con lo stesso numero di pagina. Le pagine multiple impilate orizzontalmente se isSidewise è true e impilate verticalmente se isSidewise è false. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_1)(Stream, int, int, HttpResponse) | Crea un documento N-up e memorizza il risultato in HttpResponse. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_2)(Stream, Stream, int, int) | Crea un documento N su 1 dal flusso di input e salva il risultato nel flusso di output. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_7)(string, int, int, HttpResponse) | Crea un documento N-up e memorizza il risultato in HttpResponse. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_8)(string, string, int, int) | Crea un documento N su 1 dal firstInputFile a outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup)(Stream, int, int, PageSize, HttpResponse) | Crea un documento N-up e memorizza il risultato nell'oggetto HttpResponse. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_3)(Stream, Stream, int, int, PageSize) | Crea un documento N su 1 dal primo flusso di input al flusso di output. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_6)(string, int, int, PageSize, HttpResponse) | Crea un documento N-up e memorizza il risultato nell'oggetto HttpResponse. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_9)(string, string, int, int, PageSize) | Crea un documento N su 1 dal file di input a outputFile. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_6)(Document, ContentsResizeParameters) | Ridimensiona le pagine del documento. I margini vuoti vengono aggiunti intorno alla pagina ridotta. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_7)(Document, int[], ContentsResizeParameters) | Ridimensiona le pagine del documento. I margini vuoti vengono aggiunti intorno alla pagina ridotta. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents)(Stream, int[], ContentsResizeParameters, HttpResponse) | Ridimensiona il contenuto delle pagine nel documento. Se la pagina viene ridotta, vengono aggiunti margini vuoti intorno alla pagina. Il risultato viene archiviato nell'oggetto HttpResponse. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_1)(Stream, Stream, int[], ContentsResizeParameters) | Ridimensiona il contenuto delle pagine del documento. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_3)(string, int[], ContentsResizeParameters, HttpResponse) | Ridimensiona il contenuto delle pagine nel documento. Se la pagina viene ridotta, vengono aggiunti margini vuoti intorno alla pagina. Il risultato viene archiviato nell'oggetto HttpResponse. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_4)(string, string, int[], ContentsResizeParameters) | Ridimensiona il contenuto delle pagine nel documento. Se la pagina viene ridotta, vengono aggiunti margini vuoti intorno alla pagina. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_2)(Stream, Stream, int[], double, double) | Ridimensiona il contenuto delle pagine del documento. Rimpicciolisce il contenuto della pagina e aggiunge margini. La nuova dimensione del contenuto è specificata in unità di spazio predefinite. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_5)(string, string, int[], double, double) | Ridimensiona il contenuto delle pagine del documento. Rimpicciolisce il contenuto della pagina e aggiunge margini. La nuova dimensione del contenuto è specificata in unità di spazio predefinite. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct#resizecontentspct)(Stream, Stream, int[], double, double) | Ridimensiona il contenuto delle pagine del documento. Rimpicciolisce il contenuto della pagina e aggiunge margini. La nuova dimensione del contenuto è specificata in percentuali. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct#resizecontentspct_1)(string, string, int[], double, double) | Ridimensiona il contenuto delle pagine del documento. Rimpicciolisce il contenuto della pagina e aggiunge margini. La nuova dimensione del contenuto è specificata in percentuali. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst_1)(Stream, int, HttpResponse) | Divide il documento dall'inizio alla posizione specificata e memorizza il risultato nell'oggetto HttpResponse. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst)(Stream, int, Stream) | Divide dall'inizio alla posizione specificata e salva la parte anteriore nel flusso di output. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst_3)(string, int, HttpResponse) | Divide il documento dalla prima pagina alla posizione e salva il risultato in oggetti HttpResponse. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst_2)(string, int, string) | Divide il file Pdf dalla prima pagina alla posizione specificata e salva la parte anteriore come un nuovo file. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks#splittobulks)(Stream, int[][]) | Suddivide il file Pdf in più documenti. I documenti possono essere a pagina singola oa più pagine. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks#splittobulks_1)(string, int[][]) | Suddivide il file Pdf in più documenti. I documenti possono essere a pagina singola oa più pagine. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend_1)(Stream, int, HttpResponse) | Divide dalla posizione specificata e salva la parte posteriore nell'oggetto HttpResponse. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend)(Stream, int, Stream) | Divide dalla posizione specificata e salva la parte posteriore come nuovo file Stream. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend_3)(string, int, HttpResponse) | Divide dalla posizione specificata e salva la parte posteriore nell'oggetto HttpResponse. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend_2)(string, int, string) | Divide dalla posizione e salva la parte posteriore come un nuovo file. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages)(Stream) | Divide il file Pdf in documenti a pagina singola. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages_1)(string) | Divide il file PDF in documenti a pagina singola. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages_2)(Stream, string) | Dividi il file Pdf in documenti a pagina singola e lo salva nel percorso specificato. Il percorso è specificato dal nome del campo temaplate. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages_3)(string, string) | Dividi il file Pdf in documenti a pagina singola e lo salva nel percorso specificato. Il percorso è specificato dal nome del campo temaplate. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend_1)(Stream, Stream[], int, int, HttpResponse) | Aggiunge i documenti al documento di origine e salva il risultato nell'oggetto di risposta. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend)(Stream, Stream[], int, int, Stream) | Aggiunge le pagine, che sono scelte dall'array di documenti in portStreams. Il documento risultante include firstInputFile e tutte le pagine dei documenti portStreams nell'intervallo da startPage a endPage. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend_3)(string, string[], int, int, HttpResponse) | Aggiunge i documenti al documento di origine e salva il risultato nell'oggetto HttpResponse. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend_2)(string, string[], int, int, string) | Aggiunge le pagine scelte dai documenti portFiles. Il documento risultato include firstInputFile e tutte le pagine dei documenti portFiles nell'intervallo da startPage a endPage. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate)(Document[], Document) | Concatena i documenti. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_3)(Stream[], HttpResponse) | Concatena i file e memorizza i risultati nell'oggetto HttpResponse. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_2)(Stream[], Stream) | Concatena i file |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_7)(string[], HttpResponse) | Concatena i file e salva il risultato nell'oggetto HttpResposnse. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_6)(string[], string) | Concatena i file in un unico file. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_4)(string, string, string) | Concatena due file. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_1)(Stream, Stream, Stream, Stream) | Unisce due documenti Pdf in un nuovo documento Pdf con pagine in modi alternativi e riempie gli spazi vuoti con pagine vuote. es: il documento1 ha 5 pagine: p1, p2, p3, p4, p5. document2 ha 3 pagine: p1', p2', p3'. L'unione dei due documenti Pdf produrrà il documento risultante con le pagine: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage . |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_5)(string, string, string, string) | Unisce due documenti Pdf in un nuovo documento Pdf con pagine in modi alternativi e riempie gli spazi vuoti con pagine vuote. es: il documento1 ha 5 pagine: p1, p2, p3, p4, p5. document2 ha 3 pagine: p1', p2', p3'. L'unione dei due documenti Pdf produrrà il documento risultante con le pagine: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage . |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete_1)(Stream, int[], HttpResponse) | Elimina le pagine specificate dal documento e salva il risultato nell'oggetto HttpResponse. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete)(Stream, int[], Stream) | Elimina le pagine specificate dall'array di numeri dal file di input, salva come un nuovo file Pdf. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete_3)(string, int[], HttpResponse) | Elimina le pagine specificate dal documento e memorizza il risultato nell'oggetto HttpResponse. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete_2)(string, int[], string) | Elimina le pagine specificate dall'array di numeri dal file di input, salva come un nuovo file Pdf. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_1)(Stream, int[], HttpResponse) | Estrae le pagine specificate dal file di origine e memorizza il risultato nell'oggetto HttpResponse. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract)(Stream, int[], Stream) | Estrae le pagine specificate dall'array di numeri, le salva come un nuovo file Pdf. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_4)(string, int[], HttpResponse) | Estrae le pagine specificate dal file di origine e memorizza il risultato nell'oggetto HttpResponse. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_3)(string, int[], string) | Estrae le pagine specificate dall'array di numeri, le salva come un nuovo file PDF. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_2)(string, int, int, string) | Estrae le pagine dal file di input, salva come nuovo file Pdf. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert_1)(Stream, int, Stream, int[], HttpResponse) | Inserisce il documento in un altro documento e memorizza il risultato nell'oggetto risposta. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert)(Stream, int, Stream, int[], Stream) | Inserisce le pagine da un altro file nel file Pdf di input. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert_3)(string, int, string, int[], HttpResponse) | Inserisce il contenuto del file nel file di origine e memorizza il risultato nell'oggetto HttpResponse. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert_2)(string, int, string, int[], string) | Inserisce le pagine da un altro file nel file Pdf di input. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_2)(Stream, Stream) | Crea opuscolo da InputStream a outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_8)(string, string) | Crea opuscolo dal file di input al file di output. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_1)(Stream, PageSize, HttpResponse) | Crea opuscolo dal file sorgente e memorizza il risultato in HttpResponse. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_3)(Stream, Stream, PageSize) | Crea opuscolo dal flusso di input e salva il risultato nel flusso di output. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_7)(string, PageSize, HttpResponse) | Crea opuscolo dal file di origine e memorizza il risultato in oggetti HttpResponse. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_9)(string, string, PageSize) | Crea opuscolo da inputFile a outputFile. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_5)(Stream, Stream, int[], int[]) | Crea opuscoli personalizzati dal primo InputStream a outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_11)(string, string, int[], int[]) | Crea opuscolo personalizzato dal firstInputFile a outputFile. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet)(Stream, PageSize, int[], int[], HttpResponse) | Crea un opuscolo da un file PDF e lo memorizza in HttpResponse. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_4)(Stream, Stream, PageSize, int[], int[]) | Crea opuscolo dal primo InputStream a outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_6)(string, PageSize, int[], int[], HttpResponse) | Crea opuscolo dal file sorgente e memorizza il risultato in oggetti HttpResponse. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_10)(string, string, PageSize, int[], int[]) | Crea opuscolo personalizzato dal firstInputFile a outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_4)(Stream, Stream, Stream) | Crea un documento N-Up dai due flussi PDF di input a outputStream. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_5)(Stream[], Stream, bool) | Crea un documento N su 1 dai flussi PDF multi input a outputStream. Ogni pagina di outputStream conterrà più pagine, che sono una combinazione con le pagine nei flussi di input con lo stesso numero di pagina. Le pagine multiple impilate orizzontalmente se isSidewise è vero e impilate verticalmente se isSidewise è false. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_10)(string, string, string) | Crea un documento N-Up dai due file PDF di input in outputFile. Ogni pagina di outputFile conterrà due pagine, una pagina proviene dal primo file di input e un'altra dal secondo file di input. Le due pagine sono impilate orizzontalmente. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_11)(string[], string, bool) | Crea un documento N-Up dai file PDF multi input a outputFile. Ogni pagina di outputFile conterrà più pagine, che sono una combinazione con le pagine nei file di input con lo stesso numero di pagina. Le pagine multiple impilate orizzontalmente se isSidewise è true e impilate verticalmente se isSidewise è false. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_1)(Stream, int, int, HttpResponse) | Crea un documento N-up e memorizza il risultato in HttpResponse. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_2)(Stream, Stream, int, int) | Crea un documento N su 1 dal flusso di input e salva il risultato nel flusso di output. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_7)(string, int, int, HttpResponse) | Crea un documento N-up e memorizza il risultato in HttpResponse. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_8)(string, string, int, int) | Crea un documento N su 1 dal firstInputFile a outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup)(Stream, int, int, PageSize, HttpResponse) | Crea un documento N-up e memorizza il risultato nell'oggetto HttpResponse. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_3)(Stream, Stream, int, int, PageSize) | Crea un documento N su 1 dal primo flusso di input al flusso di output. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_6)(string, int, int, PageSize, HttpResponse) | Crea un documento N-up e memorizza il risultato nell'oggetto HttpResponse. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_9)(string, string, int, int, PageSize) | Crea un documento N su 1 dal file di input a outputFile. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents)(Stream, int[], ContentsResizeParameters, HttpResponse) | Ridimensiona il contenuto delle pagine nel documento. Se la pagina viene ridotta, vengono aggiunti margini vuoti intorno alla pagina. Il risultato viene archiviato nell'oggetto HttpResponse. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_1)(Stream, Stream, int[], ContentsResizeParameters) | Ridimensiona il contenuto delle pagine del documento. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_3)(string, int[], ContentsResizeParameters, HttpResponse) | Ridimensiona il contenuto delle pagine nel documento. Se la pagina viene ridotta, vengono aggiunti margini vuoti intorno alla pagina. Il risultato viene archiviato nell'oggetto HttpResponse. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_4)(string, string, int[], ContentsResizeParameters) | Ridimensiona il contenuto delle pagine nel documento. Se la pagina viene ridotta, vengono aggiunti margini vuoti intorno alla pagina. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_2)(Stream, Stream, int[], double, double) | Ridimensiona il contenuto delle pagine del documento. Rimpicciolisce il contenuto della pagina e aggiunge margini. La nuova dimensione del contenuto è specificata in unità di spazio predefinite. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst_1)(Stream, int, HttpResponse) | Divide il documento dall'inizio alla posizione specificata e memorizza il risultato nell'oggetto HttpResponse. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst)(Stream, int, Stream) | Divide dall'inizio alla posizione specificata e salva la parte anteriore nel flusso di output. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst_3)(string, int, HttpResponse) | Divide il documento dalla prima pagina alla posizione e salva il risultato in oggetti HttpResponse. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst_2)(string, int, string) | Divide il file Pdf dalla prima pagina alla posizione specificata e salva la parte anteriore come un nuovo file. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend_1)(Stream, int, HttpResponse) | Divide dalla posizione specificata e salva la parte posteriore nell'oggetto HttpResponse. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend)(Stream, int, Stream) | Divide dalla posizione specificata e salva la parte posteriore come nuovo file Stream. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend_3)(string, int, HttpResponse) | Divide dalla posizione specificata e salva la parte posteriore nell'oggetto HttpResponse. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend_2)(string, int, string) | Divide dalla posizione e salva la parte posteriore come un nuovo file. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| enum [ConcatenateCorruptedFileAction](pdffileeditor.concatenatecorruptedfileaction) | Azione eseguita quando il file danneggiato è stato soddisfatto nel processo di concatenazione. |
| class [ContentsResizeParameters](pdffileeditor.contentsresizeparameters) | Classe per specificare i parametri di ridimensionamento della pagina. Consente di impostare i seguenti parametri: Dimensioni della pagina dei risultati (larghezza, altezza) in unità di spazio predefinite o in percentuali della dimensione iniziale delle pagine; Margini sinistro, superiore, inferiore e destro in unità di spazio predefinite o in percentuali delle dimensioni della pagina iniziale; Alcuni valori possono essere lasciati nulli per il calcolo automatico. Questi valori verranno calcolati dal resto della dimensione della pagina dopo il calcolo dei valori specificati in modo esplicito. Ad esempio: se la larghezza della pagina = 100 e la nuova larghezza della pagina specificata 60 unità, i margini sinistro e destro vengono calcolati automaticamente: (100 - 60) / 2 = 15. Questa classe viene utilizzata nel metodo ResizeContents. |
| class [ContentsResizeValue](pdffileeditor.contentsresizevalue) | Valore del margine o della dimensione del contenuto specificato in percentuali delle unità di spazio predefinite. Questa classe viene utilizzata in ContentsResizeParameters. |
| class [CorruptedItem](pdffileeditor.corrupteditem) | Classe che fornisce informazioni sui file danneggiati al momento della concatenazione. |
| class [PageBreak](pdffileeditor.pagebreak) | Dati della posizione dell'interruzione di pagina. |

### Guarda anche

* spazio dei nomi [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
