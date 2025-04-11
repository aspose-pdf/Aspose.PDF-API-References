---
title: Class PdfFileEditor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfFileEditor. Implementa operazioni con concatenazione di file PDF, suddivisione, estrazione di pagine, creazione di opuscoli, ecc.
type: docs
weight: 4460
url: /it/net/aspose.pdf.facades/pdffileeditor/
---
## Classe PdfFileEditor

Implementa operazioni con file PDF: concatenazione, suddivisione, estrazione di pagine, creazione di opuscoli, ecc.

```csharp
public sealed class PdfFileEditor
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfFileEditor](pdffileeditor/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CloseConcatenatedStreams](../../aspose.pdf.facades/pdffileeditor/closeconcatenatedstreams/) { get; set; } | Se impostato su true, gli stream vengono chiusi dopo l'operazione. |
| [ConcatenationPacketSize](../../aspose.pdf.facades/pdffileeditor/concatenationpacketsize/) { get; set; } | Numero di documenti concatenati prima che venga effettuato un nuovo aggiornamento incrementale durante la concatenazione quando UseDiskBuffer è impostato su true. |
| [ConversionLog](../../aspose.pdf.facades/pdffileeditor/conversionlog/) { get; } | Ottiene il log del processo di conversione. |
| [ConvertTo](../../aspose.pdf.facades/pdffileeditor/convertto/) { set; } | Imposta il formato del file PDF. Il file risultante sarà salvato nel formato di file specificato. Se questa proprietà non è specificata, il file sarà salvato nel formato PDF predefinito senza conversione. |
| [CopyLogicalStructure](../../aspose.pdf.facades/pdffileeditor/copylogicalstructure/) { get; set; } | Se true, la struttura logica del file viene copiata quando viene eseguita la concatenazione. |
| [CopyOutlines](../../aspose.pdf.facades/pdffileeditor/copyoutlines/) { get; set; } | Se true, le outline verranno copiate. |
| [CorruptedFileAction](../../aspose.pdf.facades/pdffileeditor/corruptedfileaction/) { get; set; } | Questa proprietà definisce il comportamento quando il processo di concatenazione incontra un file corrotto. I valori possibili sono: StopWithError e ConcatenateIgnoringCorrupted. |
| [CorruptedItems](../../aspose.pdf.facades/pdffileeditor/corrupteditems/) { get; } | Array di problemi riscontrati quando è stata eseguita la concatenazione. Per ogni documento corrotto passato alla funzione Concatenate() viene creata una nuova voce CorruptedItem. Questa proprietà può essere utilizzata solo quando CorruptedFileAction è ConcatenateIgnoringCorrupted. |
| [IncrementalUpdates](../../aspose.pdf.facades/pdffileeditor/incrementalupdates/) { get; set; } | Se true, vengono effettuati aggiornamenti incrementali durante la concatenazione. |
| [KeepActions](../../aspose.pdf.facades/pdffileeditor/keepactions/) { get; set; } | Se true, le azioni verranno copiate dai documenti sorgente. Valore predefinito: true. |
| [KeepFieldsUnique](../../aspose.pdf.facades/pdffileeditor/keepfieldsunique/) { get; set; } | Se true, i nomi dei campi saranno resi unici quando i moduli vengono concatenati. I suffissi verranno aggiunti ai nomi dei campi, il modello di suffisso può essere specificato nella proprietà UniqueSuffix. |
| [LastException](../../aspose.pdf.facades/pdffileeditor/lastexception/) { get; } | Ottiene l'ultima eccezione verificatasi. Può essere utilizzato per controllare il motivo del fallimento. |
| [MergeDuplicateLayers](../../aspose.pdf.facades/pdffileeditor/mergeduplicatelayers/) { get; set; } | I contenuti opzionali dei documenti concatenati con nomi uguali verranno uniti in un unico livello nel documento risultante se questa proprietà è true. Altrimenti, i livelli con nomi uguali verranno salvati come livelli diversi nel documento risultante. |
| [MergeDuplicateOutlines](../../aspose.pdf.facades/pdffileeditor/mergeduplicateoutlines/) { get; set; } | Se true, le outline duplicate vengono unite. |
| [OptimizeSize](../../aspose.pdf.facades/pdffileeditor/optimizesize/) { get; set; } | Ottiene o imposta il flag di ottimizzazione. Gli stream di risorse uguali nel file risultante vengono uniti in un unico oggetto PDF se questo flag è impostato. Questo consente di ridurre la dimensione del file risultante, ma può causare un'esecuzione più lenta e maggiori requisiti di memoria. Valore predefinito: false. |
| [OwnerPassword](../../aspose.pdf.facades/pdffileeditor/ownerpassword/) { get; set; } | Imposta la password del proprietario se il file PDF di input sorgente è crittografato. Questa proprietà non è ancora implementata. |
| [PreserveUserRights](../../aspose.pdf.facades/pdffileeditor/preserveuserrights/) { get; set; } | Se true, i diritti utente del primo documento vengono applicati al documento concatenato. I diritti utente di tutti gli altri documenti vengono ignorati. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffileeditor/removesignatures/) { get; set; } | Se true, tutte le firme verranno rimosse dai campi (i campi rimarranno); altrimenti, si possono ottenere firme non valide. |
| [UniqueSuffix](../../aspose.pdf.facades/pdffileeditor/uniquesuffix/) { get; set; } | Formato del suffisso che viene aggiunto al nome del campo per renderlo unico quando i moduli vengono concatenati. Questa stringa deve contenere la sottostringa %NUM% che verrà sostituita con numeri. Ad esempio, se UniqueSuffix = "ABC%NUM%", allora per il campo "fieldName" i nomi saranno: fieldNameABC1, fieldNameABC2, fieldNameABC3, ecc. |
| [UseDiskBuffer](../../aspose.pdf.facades/pdffileeditor/usediskbuffer/) { get; set; } | Se questa opzione è utilizzata, il documento di destinazione verrà salvato su disco periodicamente e la successiva concatenazione verrà applicata ad esso come aggiornamenti incrementali. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins)(Stream, Stream, int[], double, double, double, double) | Ridimensiona i contenuti della pagina e aggiunge margini specificati. I margini sono specificati in unità di spazio predefinite. |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins_1)(string, string, int[], double, double, double, double) | Ridimensiona i contenuti della pagina e aggiunge margini specificati. I margini sono specificati in unità di spazio predefinite. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct)(Stream, Stream, int[], double, double, double, double) | Ridimensiona i contenuti della pagina e aggiunge margini specificati. I margini sono specificati in percentuale della dimensione iniziale della pagina. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct_1)(string, string, int[], double, double, double, double) | Ridimensiona i contenuti della pagina e aggiunge margini specificati. I margini sono specificati in percentuale della dimensione iniziale della pagina. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak)(Document, Document, PageBreak[]) | Aggiunge interruzioni di pagina nelle pagine del documento. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_1)(Stream, Stream, PageBreak[]) | Aggiunge interruzioni di pagina nelle pagine del documento. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_2)(string, string, PageBreak[]) | Aggiunge interruzioni di pagina nelle pagine del documento. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append)(Stream, Stream, int, int, Stream) | Aggiunge pagine, scelte da portStream nell'intervallo da startPage a endPage, in portStream alla fine di firstInputStream. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_1)(Stream, Stream[], int, int, Stream) | Aggiunge pagine, scelte da un array di documenti in portStreams. Il documento risultante include firstInputFile e tutte le pagine dei documenti portStreams nell'intervallo startPage a endPage. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_2)(string, string, int, int, string) | Aggiunge pagine, scelte da portFile nell'intervallo da startPage a endPage, in portFile alla fine di firstInputFile. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_3)(string, string[], int, int, string) | Aggiunge pagine, scelte da documenti portFiles. Il documento risultante include firstInputFile e tutte le pagine dei documenti portFiles nell'intervallo startPage a endPage. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate)(Document[], Document) | Concatenates documents. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_3)(Stream[], Stream) | Concatenates files |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_6)(string[], string) | Concatenates files into one file. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_1)(Stream, Stream, Stream) | Concatenates two files. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_4)(string, string, string) | Concatenates two files. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_2)(Stream, Stream, Stream, Stream) | Unisce due documenti Pdf in un nuovo documento Pdf con pagine in modi alternativi e riempie i posti vuoti con pagine vuote. ad esempio: document1 ha 5 pagine: p1, p2, p3, p4, p5. document2 ha 3 pagine: p1', p2', p3'. Unendo i due documenti Pdf si otterrà il documento risultante con pagine: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_5)(string, string, string, string) | Unisce due documenti Pdf in un nuovo documento Pdf con pagine in modi alternativi e riempie i posti vuoti con pagine vuote. ad esempio: document1 ha 5 pagine: p1, p2, p3, p4, p5. document2 ha 3 pagine: p1', p2', p3'. Unendo i due documenti Pdf si otterrà il documento risultante con pagine: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete)(Stream, int[], Stream) | Elimina le pagine specificate dall'array di numeri dal file di input, salvando come un nuovo file Pdf. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete_1)(string, int[], string) | Elimina le pagine specificate dall'array di numeri dal file di input, salvando come un nuovo file Pdf. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_1)(Stream, int[], Stream) | Estrae le pagine specificate dall'array di numeri, salvando come un nuovo file Pdf. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_3)(string, int[], string) | Estrae le pagine specificate dall'array di numeri, salvando come un nuovo file PDF. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract)(Stream, int, int, Stream) | Estrae le pagine dal file di input, salvando come un nuovo file Pdf. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_2)(string, int, int, string) | Estrae le pagine dal file di input, salvando come un nuovo file Pdf. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_1)(Stream, int, Stream, int[], Stream) | Inserisce pagine da un altro file nel file Pdf di input. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_3)(string, int, string, int[], string) | Inserisce pagine da un altro file nel file Pdf di input. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert)(Stream, int, Stream, int, int, Stream) | Inserisce pagine da un altro file nel file Pdf di input. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_2)(string, int, string, int, int, string) | Inserisce pagine da un altro file nel file Pdf in una posizione. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet)(Stream, Stream) | Crea un opuscolo da InputStream a outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_4)(string, string) | Crea un opuscolo dal file di input al file di output. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_1)(Stream, Stream, PageSize) | Crea un opuscolo dallo stream di input e salva il risultato nello stream di output. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_5)(string, string, PageSize) | Crea un opuscolo dal file di inputFile al file di outputFile. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_3)(Stream, Stream, int[], int[]) | Crea un opuscolo personalizzato da firstInputStream a outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_7)(string, string, int[], int[]) | Crea un opuscolo personalizzato da firstInputFile a outputFile. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_2)(Stream, Stream, PageSize, int[], int[]) | Crea un opuscolo da firstInputStream a outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_6)(string, string, PageSize, int[], int[]) | Crea un opuscolo personalizzato da firstInputFile a outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_2)(Stream, Stream, Stream) | Crea un documento N-Up dai due stream PDF di input a outputStream. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_3)(Stream[], Stream, bool) | Crea un documento N-Up dai multi stream PDF di input a outputStream. Ogni pagina di outputStream conterrà più pagine, che sono una combinazione delle pagine negli stream di input dello stesso numero di pagina. Le pagine multiple si sovrappongono orizzontalmente se isSidewise è true e si sovrappongono verticalmente se isSidewise è false. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_6)(string, string, string) | Crea un documento N-Up dai due file PDF di input a outputFile. Ogni pagina di outputFile conterrà due pagine, una pagina è dal primo file di input e l'altra è dal secondo file di input. Le due pagine si sovrappongono orizzontalmente. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_7)(string[], string, bool) | Crea un documento N-Up dai multi file PDF di input a outputFile. Ogni pagina di outputFile conterrà più pagine, che sono una combinazione delle pagine nei file di input dello stesso numero di pagina. Le pagine multiple si sovrappongono orizzontalmente se isSidewise è true e si sovrappongono verticalmente se isSidewise è false. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup)(Stream, Stream, int, int) | Crea un documento N-Up dallo stream di input e salva il risultato nello stream di output. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_4)(string, string, int, int) | Crea un documento N-Up dal firstInputFile a outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_1)(Stream, Stream, int, int, PageSize) | Crea un documento N-Up dal primo stream di input allo stream di output. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_5)(string, string, int, int, PageSize) | Crea un documento N-Up dal file di input a outputFile. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_4)(Document, ContentsResizeParameters) | Ridimensiona le pagine del documento. Vengono aggiunti margini vuoti attorno alla pagina ridotta. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_5)(Document, int[], ContentsResizeParameters) | Ridimensiona le pagine del documento. Vengono aggiunti margini vuoti attorno alla pagina ridotta. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents)(Stream, Stream, int[], ContentsResizeParameters) | Ridimensiona i contenuti delle pagine del documento. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_2)(string, string, int[], ContentsResizeParameters) | Ridimensiona i contenuti delle pagine nel documento. Se la pagina è ridotta, vengono aggiunti margini vuoti attorno alla pagina. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_1)(Stream, Stream, int[], double, double) | Ridimensiona i contenuti delle pagine del documento. Riduce i contenuti della pagina e aggiunge margini. La nuova dimensione dei contenuti è specificata in unità di spazio predefinite. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_3)(string, string, int[], double, double) | Ridimensiona i contenuti delle pagine del documento. Riduce i contenuti della pagina e aggiunge margini. La nuova dimensione dei contenuti è specificata in unità di spazio predefinite. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct)(Stream, Stream, int[], double, double) | Ridimensiona i contenuti delle pagine del documento. Riduce i contenuti della pagina e aggiunge margini. La nuova dimensione dei contenuti è specificata in percentuale. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct_1)(string, string, int[], double, double) | Ridimensiona i contenuti delle pagine del documento. Riduce i contenuti della pagina e aggiunge margini. La nuova dimensione dei contenuti è specificata in percentuale. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst)(Stream, int, Stream) | Divide dall'inizio fino alla posizione specificata e salva la parte anteriore nello stream di output. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst_1)(string, int, string) | Divide il file Pdf dalla prima pagina fino alla posizione specificata e salva la parte anteriore come un nuovo file. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks)(Stream, int[][]) | Divide il file Pdf in diversi documenti. I documenti possono essere a pagina singola o multipagina. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks_1)(string, int[][]) | Divide il file Pdf in diversi documenti. I documenti possono essere a pagina singola o multipagina. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend)(Stream, int, Stream) | Divide dalla posizione specificata e salva la parte posteriore come un nuovo file Stream. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend_1)(string, int, string) | Divide dalla posizione e salva la parte posteriore come un nuovo file. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages)(Stream) | Divide il file Pdf in documenti a pagina singola. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_1)(string) | Divide il file PDF in documenti a pagina singola. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_2)(Stream, string) | Divide il file Pdf in documenti a pagina singola e lo salva nel percorso specificato. Il percorso è specificato dal modello del nome del campo. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_3)(string, string) | Divide il file Pdf in documenti a pagina singola e lo salva nel percorso specificato. Il percorso è specificato dal modello del nome del campo. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend)(Stream, Stream[], int, int, Stream) | Aggiunge pagine, scelte da un array di documenti in portStreams. Il documento risultante include firstInputFile e tutte le pagine dei documenti portStreams nell'intervallo startPage a endPage. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend_1)(string, string[], int, int, string) | Aggiunge pagine, scelte da documenti portFiles. Il documento risultante include firstInputFile e tutte le pagine dei documenti portFiles nell'intervallo startPage a endPage. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate)(Document[], Document) | Concatenates documents. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_2)(Stream[], Stream) | Concatenates files |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_5)(string[], string) | Concatenates files into one file. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_3)(string, string, string) | Concatenates two files. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_1)(Stream, Stream, Stream, Stream) | Unisce due documenti Pdf in un nuovo documento Pdf con pagine in modi alternativi e riempie i posti vuoti con pagine vuote. ad esempio: document1 ha 5 pagine: p1, p2, p3, p4, p5. document2 ha 3 pagine: p1', p2', p3'. Unendo i due documenti Pdf si otterrà il documento risultante con pagine: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_4)(string, string, string, string) | Unisce due documenti Pdf in un nuovo documento Pdf con pagine in modi alternativi e riempie i posti vuoti con pagine vuote. ad esempio: document1 ha 5 pagine: p1, p2, p3, p4, p5. document2 ha 3 pagine: p1', p2', p3'. Unendo i due documenti Pdf si otterrà il documento risultante con pagine: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete)(Stream, int[], Stream) | Elimina le pagine specificate dall'array di numeri dal file di input, salvando come un nuovo file Pdf. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete_1)(string, int[], string) | Elimina le pagine specificate dall'array di numeri dal file di input, salvando come un nuovo file Pdf. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract)(Stream, int[], Stream) | Estrae le pagine specificate dall'array di numeri, salvando come un nuovo file Pdf. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_2)(string, int[], string) | Estrae le pagine specificate dall'array di numeri, salvando come un nuovo file PDF. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_1)(string, int, int, string) | Estrae le pagine dal file di input, salvando come un nuovo file Pdf. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert)(Stream, int, Stream, int[], Stream) | Inserisce pagine da un altro file nel file Pdf di input. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert_1)(string, int, string, int[], string) | Inserisce pagine da un altro file nel file Pdf di input. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet)(Stream, Stream) | Crea un opuscolo da InputStream a outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_4)(string, string) | Crea un opuscolo dal file di input al file di output. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_1)(Stream, Stream, PageSize) | Crea un opuscolo dallo stream di input e salva il risultato nello stream di output. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_5)(string, string, PageSize) | Crea un opuscolo dal file di inputFile al file di outputFile. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_3)(Stream, Stream, int[], int[]) | Crea un opuscolo personalizzato da firstInputStream a outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_7)(string, string, int[], int[]) | Crea un opuscolo personalizzato da firstInputFile a outputFile. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_2)(Stream, Stream, PageSize, int[], int[]) | Crea un opuscolo da firstInputStream a outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_6)(string, string, PageSize, int[], int[]) | Crea un opuscolo personalizzato da firstInputFile a outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_2)(Stream, Stream, Stream) | Crea un documento N-Up dai due input PDF streams a outputStream. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_3)(Stream[], Stream, bool) | Crea un documento N-Up dai multi input PDF streams a outputStream. Ogni pagina di outputStream conterrà multi pagine, che sono combinazioni delle pagine negli input streams dello stesso numero di pagina. Le multi-pagine si sovrappongono orizzontalmente se isSidewise è true e si sovrappongono verticalmente se isSidewise è false. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_6)(string, string, string) | Crea un documento N-Up dai due file PDF di input a outputFile. Ogni pagina di outputFile conterrà due pagine, una pagina è dal primo file di input e l'altra è dal secondo file di input. Le due pagine si sovrappongono orizzontalmente. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_7)(string[], string, bool) | Crea un documento N-Up dai multi file PDF di input a outputFile. Ogni pagina di outputFile conterrà multi pagine, che sono combinazioni delle pagine nei file di input dello stesso numero di pagina. Le multi pagine si sovrappongono orizzontalmente se isSidewise è true e si sovrappongono verticalmente se isSidewise è false. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup)(Stream, Stream, int, int) | Crea un documento N-Up dallo stream di input e salva il risultato nello stream di output. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_4)(string, string, int, int) | Crea un documento N-Up dal firstInputFile a outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_1)(Stream, Stream, int, int, PageSize) | Crea un documento N-Up dal primo stream di input allo stream di output. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_5)(string, string, int, int, PageSize) | Crea un documento N-Up dal file di input a outputFile. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents)(Stream, Stream, int[], ContentsResizeParameters) | Ridimensiona i contenuti delle pagine del documento. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_2)(string, string, int[], ContentsResizeParameters) | Ridimensiona i contenuti delle pagine nel documento. Se la pagina è ridotta, vengono aggiunti margini vuoti attorno alla pagina. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_1)(Stream, Stream, int[], double, double) | Ridimensiona i contenuti delle pagine del documento. Riduce i contenuti della pagina e aggiunge margini. La nuova dimensione dei contenuti è specificata in unità di spazio predefinite. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst)(Stream, int, Stream) | Divide dall'inizio fino alla posizione specificata e salva la parte anteriore nello stream di output. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst_1)(string, int, string) | Divide il file Pdf dalla prima pagina fino alla posizione specificata e salva la parte anteriore come un nuovo file. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend)(Stream, int, Stream) | Divide dalla posizione specificata e salva la parte posteriore come un nuovo file Stream. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend_1)(string, int, string) | Divide dalla posizione e salva la parte posteriore come un nuovo file. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| enum [ConcatenateCorruptedFileAction](../../aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction) | Azione eseguita quando si incontra un file corrotto nel processo di concatenazione. |
| class [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters) | Classe per specificare i parametri di ridimensionamento della pagina. Consente di impostare i seguenti parametri: Dimensione della pagina risultante (larghezza, altezza) in unità di spazio predefinite o in percentuale della dimensione delle pagine iniziali; Margini sinistro, superiore, inferiore e destro in unità di spazio predefinite o in percentuale della dimensione della pagina iniziale; Alcuni valori possono essere lasciati null per il calcolo automatico. Questi valori verranno calcolati dal resto della dimensione della pagina dopo il calcolo dei valori esplicitamente specificati. Ad esempio: se la larghezza della pagina = 100 e la nuova larghezza della pagina specificata è di 60 unità, allora i margini sinistro e destro vengono calcolati automaticamente: (100 - 60) / 2 = 15. Questa classe è utilizzata nel metodo ResizeContents. |
| class [ContentsResizeValue](../../aspose.pdf.facades/pdffileeditor.contentsresizevalue) | Valore del margine o della dimensione del contenuto specificato in percentuale delle unità di spazio predefinite. Questa classe è utilizzata in ContentsResizeParameters. |
| class [CorruptedItem](../../aspose.pdf.facades/pdffileeditor.corrupteditem) | Classe che fornisce informazioni sui file corrotti durante la concatenazione. |
| class [PageBreak](../../aspose.pdf.facades/pdffileeditor.pagebreak) | Dati sulla posizione dell'interruzione di pagina. |

### Vedi anche

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)