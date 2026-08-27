---
title: "PdfFileEditorWeb"
linktitle: "PdfFileEditorWeb"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta la classe PdfFileEditorWeb. Implementa operazioni con file PDF: concatenazione, divisione, estrazione di pagine, creazione di opuscoli, ecc."
type: docs
weight: 480
url: /it/java/com.aspose.pdf.facades/pdffileeditorweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfFileEditorWeb

**All Implemented Interfaces:**
IPdfFileEditor

```
public final class PdfFileEditorWeb extends Object implements IPdfFileEditor
```

Rappresenta la classe PdfFileEditorWeb. Implementa operazioni con file PDF: concatenazione, divisione, estrazione di pagine, creazione di opuscoli, ecc.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfFileEditorWeb](#PdfFileEditorWeb--) | Costruttore di PdfFileEditorWeb. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Ridimensiona il contenuto della pagina e aggiunge i margini specificati. |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Ridimensiona il contenuto della pagina e aggiunge i margini specificati. |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Ridimensiona il contenuto della pagina e aggiunge i margini specificati. |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Ridimensiona il contenuto della pagina e aggiunge i margini specificati. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Aggiunge interruzioni di pagina nelle pagine del documento. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Aggiunge interruzioni di pagina nelle pagine del documento. |
| [addPageBreak](#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Aggiunge interruzioni di pagina nelle pagine del documento. |
| [addPageBreak](#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Aggiunge interruzioni di pagina nelle pagine del documento. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-javax.servlet.http.HttpServletResponse-) | Aggiunge documenti al documento di origine e salva il risultato nell'oggetto response. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | Aggiunge pagine, scelte dall'array di documenti in portStreams. |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | Aggiunge pagine, scelte da portStream nell'intervallo da startPage a endPage, in portStream alla fine di firstInputStream. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-javax.servlet.http.HttpServletResponse-) | Aggiunge documenti al documento di origine e salva il risultato nell'oggetto HttpServletResponse. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | Aggiunge pagine, scelte dai documenti di portFiles. |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | Aggiunge pagine, scelte da portFile nell'intervallo da startPage a endPage, in portFile alla fine di firstInputFile. |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | Concatena documenti. |
| [concatenate](#concatenate-java.io.InputStream:A-javax.servlet.http.HttpServletResponse-) | Concatena i file e memorizza il risultato nell'oggetto HttpServletResponse. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | Concatena file |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Unisce due documenti Pdf in un nuovo documento Pdf con le pagine alternate e riempie gli spazi vuoti con pagine bianche. |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Concatena due file. |
| [concatenate](#concatenate-java.lang.String:A-javax.servlet.http.HttpServletResponse-) | Concatena i file e salva il risultato nell'oggetto HttpResposnse. |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | Concatena file in un unico file. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | Concatena due file. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Unisce due documenti Pdf in un nuovo documento Pdf con le pagine alternate e riempie gli spazi vuoti con pagine bianche. |
| [createArrayWithExclusion](#createArrayWithExclusion-int-int-) |  |
| [delete](#delete-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | Elimina le pagine specificate dal documento e salva il risultato nell'oggetto HttpServletResponse. |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | Elimina le pagine specificate da un array di numeri dal file di input, salvandole in un nuovo file Pdf. |
| [delete](#delete-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | Elimina le pagine specificate dal documento e memorizza il risultato nell'oggetto HttpServletResponse. |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | Elimina le pagine specificate da un array di numeri dal file di input, salvandole in un nuovo file Pdf. |
| [extract](#extract-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | Estrae le pagine specificate dal file di origine e memorizza il risultato nell'oggetto HttpServletResponse. |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | Estrae le pagine specificate da un array di numeri, salvandole in un nuovo file Pdf. |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | Estrae le pagine dal file di input, salvandole in un nuovo file Pdf. |
| [extract](#extract-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | Estrae le pagine specificate dal file di origine e memorizza il risultato nell'oggetto HttpServletResponse. |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | Estrae le pagine specificate da un array di numeri, salvandole in un nuovo file PDF. |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | Estrae le pagine dal file di input, salvandole in un nuovo file Pdf. |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | Obsoleto. Questa proprietà è obsoleta e non può essere utilizzata per consentire il lancio di eccezioni. |
| [getAttachmentName](#getAttachmentName--) | Ottiene il nome dell'allegato quando il risultato dell'operazione è memorizzato negli oggetti HttpServletResponse come allegato. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | Se impostato su true, i flussi vengono chiusi dopo l'operazione. |
| [getConcatenationPacketSize](#getConcatenationPacketSize--) | Numero di documenti concatenati prima che venga effettuato un nuovo aggiornamento incrementale durante la concatenazione quando UseDiskBuffer è impostato su true. |
| [getContentDisposition](#getContentDisposition--) | Ottiene come verrà memorizzato il contenuto quando il risultato dell'operazione viene memorizzato nell'oggetto HttpServletResponse. |
| [getConversionLog](#getConversionLog--) | Ottiene il log del processo di conversione. |
| [getCopyLogicalStructure](#getCopyLogicalStructure--) | Se true, la struttura logica del file viene copiata quando viene eseguita la concatenazione. |
| [getCopyOutlines](#getCopyOutlines--) | Se true, i contorni (outlines) verranno copiati. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | Questa proprietà definisce il comportamento quando il processo di concatenazione incontra un file corrotto. |
| [getCorruptedItems](#getCorruptedItems--) | Array dei problemi riscontrati durante l'esecuzione della concatenazione. |
| [getCustomProgressConcatenationHandler](#getCustomProgressConcatenationHandler--) | Rappresentazione del processore interno di eventi di avanzamento che funziona durante la concatenazione e traduce gli eventi di concatenazione delle fasi interne in codice del cliente esterno. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | Se true, gli aggiornamenti incrementali vengono eseguiti durante la concatenazione. |
| [getKeepActions](#getKeepActions--) | Se true, le azioni verranno copiate dai documenti di origine. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | Se true, i nomi dei campi saranno resi unici quando i moduli vengono concatenati. |
| [getLastException](#getLastException--) | Ottiene l'ultima eccezione verificatasi. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | I contenuti opzionali dei documenti concatenati con nomi uguali saranno uniti in un unico livello nel documento risultante se questa proprietà è true. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | Se true, i contorni duplicati vengono uniti. |
| [getOptimizeSize](#getOptimizeSize--) | Ottiene o imposta il flag di ottimizzazione. |
| [getOwnerPassword](#getOwnerPassword--) | Ottiene la password del proprietario se il file PDF di input di origine è crittografato. |
| [getPreserveUserRights](#getPreserveUserRights--) | Se vero, i diritti utente del primo documento vengono applicati al documento concatenato. |
| [getRemoveSignatures](#getRemoveSignatures--) | Se vero, tutte le firme saranno rimosse dai campi (i campi rimarranno); altrimenti, potresti ottenere firme non valide. |
| [getSaveOptions](#getSaveOptions--) | Ottiene o imposta le opzioni di salvataggio quando il risultato viene memorizzato come HttpServletResponse. |
| [getUniqueSuffix](#getUniqueSuffix--) | Ottiene il formato del suffisso che viene aggiunto al nome del campo per renderlo unico quando i moduli sono concatenati. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | Inserisce il documento in un altro documento e memorizza il risultato nell'oggetto risposta. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | Inserisce pagine da un altro file nel file PDF di input. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | Inserisce pagine da un altro file nel file PDF di input. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | Inserisce il contenuto del file nel file di origine e memorizza il risultato nell'oggetto HttpServletResponse. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | Inserisce pagine da un altro file nel file PDF di input. |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | Inserisce pagine da un altro file nel file PDF in una posizione. |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella) costruite da diverse immagini di sfondo a piastrelle identiche posizionate una accanto all'altra. |
| [isUseDiskBuffer](#isUseDiskBuffer--) | Se questa opzione è utilizzata, il documento di destinazione verrà salvato su disco periodicamente e le successive concatenazioni verranno applicate come aggiornamenti incrementali. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | Crea un libretto dallo InputStream verso outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | Crea un libretto personalizzato dal firstInputStream verso outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | Crea un libretto dallo stream di input e salva il risultato nello stream di output. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | Crea un libretto dal firstInputStream verso outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Crea un opuscolo dal file di origine e memorizza il risultato nell'HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-) | Crea un opuscolo dal file PDF e lo memorizza nell'HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Crea un opuscolo dal file di origine e memorizza il risultato negli oggetti HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-) | Crea un opuscolo dal file di origine e memorizza il risultato negli oggetti HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | Crea un libretto dal file di input verso file di output. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | Crea un libretto personalizzato dal firstInputFile verso outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | Crea un libretto dal inputFile verso outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | Crea un libretto personalizzato dal firstInputFile verso outputFile. |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | Crea un documento N-Up dai più stream PDF di input verso outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Crea un documento N-Up dai due stream PDF di input verso outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-) | Crea un documento N-up e memorizza il risultato nell'HttpServletResponse. |
| [makeNUp](#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Crea un documento N-up e memorizza il risultato nell'oggetto HttpServletResponse. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | Crea un documento N-Up dallo stream di input e salva il risultato nello stream di output. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | Crea un documento N-Up dal primo stream di input verso stream di output. |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | Crea un documento N-Up dai più file PDF di input verso outputFile. |
| [makeNUp](#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-) | Crea un documento N-up e memorizza il risultato nell'HttpServletResponse. |
| [makeNUp](#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Crea un documento N-up e memorizza il risultato nell'oggetto HttpServletResponse. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | Crea un documento N-Up dal firstInputFile verso outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | Crea un documento N-Up dal file di input verso outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | Crea un documento N-Up dai due file PDF di input verso outputFile. |
| [resizeContents](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ridimensiona le pagine del documento. |
| [resizeContents](#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ridimensiona le pagine del documento. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Ridimensiona i contenuti delle pagine del documento. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ridimensiona il contenuto delle pagine del documento. |
| [resizeContents](#resizeContents-com.aspose.ms.System.IO.Stream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | Ridimensiona il contenuto delle pagine nel documento. |
| [resizeContents](#resizeContents-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | Ridimensiona il contenuto delle pagine nel documento. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | Ridimensiona i contenuti delle pagine del documento. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ridimensiona il contenuto delle pagine nel documento. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Ridimensiona i contenuti delle pagine del documento. |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | Ridimensiona i contenuti delle pagine del documento. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ridimensiona le pagine del documento. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ridimensiona le pagine del documento. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | Obsoleto. Questa proprietà è obsoleta e non può essere utilizzata per consentire il lancio di eccezioni. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Imposta il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpServletResponse come allegato. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | Se impostato su true, i flussi vengono chiusi dopo l'operazione. |
| [setConcatenationPacketSize](#setConcatenationPacketSize-int-) | Numero di documenti concatenati prima che venga effettuato un nuovo aggiornamento incrementale durante la concatenazione quando UseDiskBuffer è impostato su true. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Imposta come verrà memorizzato il contenuto quando il risultato dell'operazione viene memorizzato nell'oggetto HttpServletResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Imposta il formato del file PDF. |
| [setCopyLogicalStructure](#setCopyLogicalStructure-boolean-) | Se true, la struttura logica del file viene copiata quando viene eseguita la concatenazione. |
| [setCopyOutlines](#setCopyOutlines-boolean-) | Se true, i contorni (outlines) verranno copiati. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | Questa proprietà definisce il comportamento quando il processo di concatenazione incontra un file corrotto. |
| [setCustomProgressConcatenationHandler](#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-) | Rappresentazione del processore interno di eventi di avanzamento che funziona durante la concatenazione e traduce gli eventi di concatenazione delle fasi interne in codice del cliente esterno. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | Se true, gli aggiornamenti incrementali vengono eseguiti durante la concatenazione. |
| [setKeepActions](#setKeepActions-boolean-) | Se true, le azioni verranno copiate dai documenti di origine. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | Se true, i nomi dei campi saranno resi unici quando i moduli vengono concatenati. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | I contenuti opzionali dei documenti concatenati con nomi uguali saranno uniti in un unico livello nel documento risultante se questa proprietà è true. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | Se true, i contorni duplicati vengono uniti. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Ottiene o imposta il flag di ottimizzazione. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | Imposta la password del proprietario se il file PDF di input di origine è crittografato. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | Se vero, i diritti utente del primo documento vengono applicati al documento concatenato. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | Se vero, tutte le firme saranno rimosse dai campi (i campi rimarranno); altrimenti, potresti ottenere firme non valide. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Imposta le opzioni di salvataggio quando il risultato viene memorizzato come HttpServletResponse. |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella) costruite da diverse immagini di sfondo a piastrelle identiche posizionate una accanto all'altra. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | Imposta il formato del suffisso che viene aggiunto al nome del campo per renderlo univoco quando i moduli sono concatenati. |
| [setUseDiskBuffer](#setUseDiskBuffer-boolean-) | Se questa opzione è utilizzata, il documento di destinazione verrà salvato su disco periodicamente e le successive concatenazioni verranno applicate come aggiornamenti incrementali. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | Divide il documento dall'inizio fino alla posizione specificata e memorizza il risultato nell'oggetto HttpServletResponse. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | Dividi dall'inizio fino alla posizione specificata e salva la parte anteriore nello Stream di output. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | Divide il documento dalla prima pagina fino alla posizione e salva il risultato negli oggetti HttpServletResponse. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | Dividi il file PDF dalla prima pagina fino alla posizione specificata e salva la parte anteriore come nuovo file. |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | Divide il file Pdf in diversi documenti. I documenti possono essere a pagina singola o multi-pagina. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | Divide il file Pdf in diversi documenti. I documenti possono essere a pagina singola o multi-pagina. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | Divide dalla posizione specificata e salva la parte finale nell'oggetto HttpServletResponse. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | Dividi dalla posizione specificata e salva la parte posteriore come nuovo Stream di file. |
| [splitToEnd](#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | Divide dalla posizione specificata e salva la parte finale nell'oggetto HttpServletResponse. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | Dividi dalla posizione e salva la parte posteriore come nuovo file. |
| [splitToPages](#splitToPages-java.io.InputStream-) | Divide il file Pdf in documenti a pagina singola. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | Dividi il file Pdf in documenti a pagina singola e salvalo nel percorso specificato. |
| [splitToPages](#splitToPages-java.lang.String-) | Dividi il file PDF in documenti a pagina singola. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | Dividi il file Pdf in documenti a pagina singola e salvalo nel percorso specificato. |

### PdfFileEditorWeb {#PdfFileEditorWeb--}
```
public PdfFileEditorWeb()
```

Costruttore di PdfFileEditorWeb.

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Ridimensiona il contenuto della pagina e aggiunge i margini specificati.

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Ridimensiona il contenuto della pagina e aggiunge i margini specificati.

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Ridimensiona il contenuto della pagina e aggiunge i margini specificati.

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Ridimensiona il contenuto della pagina e aggiunge i margini specificati.

### addPageBreak {#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Aggiunge interruzioni di pagina nelle pagine del documento.

### addPageBreak {#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Aggiunge interruzioni di pagina nelle pagine del documento.

### addPageBreak {#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Aggiunge interruzioni di pagina nelle pagine del documento.

### addPageBreak {#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Aggiunge interruzioni di pagina nelle pagine del documento.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-javax.servlet.http.HttpServletResponse-}
Aggiunge documenti al documento di origine e salva il risultato nell'oggetto response.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
Aggiunge pagine, scelte dall'array di documenti in portStreams.

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
Aggiunge pagine, scelte da portStream nell'intervallo da startPage a endPage, in portStream alla fine di firstInputStream.

### append {#append-java.lang.String-java.lang.String:A-int-int-javax.servlet.http.HttpServletResponse-}
Aggiunge documenti al documento di origine e salva il risultato nell'oggetto HttpServletResponse.

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
Aggiunge pagine, scelte dai documenti di portFiles.

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
Aggiunge pagine, scelte da portFile nell'intervallo da startPage a endPage, in portFile alla fine di firstInputFile.

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
Concatena documenti.

### concatenate {#concatenate-java.io.InputStream:A-javax.servlet.http.HttpServletResponse-}
Concatena i file e memorizza il risultato nell'oggetto HttpServletResponse.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
Concatena file

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Unisce due documenti Pdf in un nuovo documento Pdf con le pagine alternate e riempie gli spazi vuoti con pagine bianche.

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Concatena due file.

### concatenate {#concatenate-java.lang.String:A-javax.servlet.http.HttpServletResponse-}
Concatena i file e salva il risultato nell'oggetto HttpResposnse.

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
Concatena file in un unico file.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
Concatena due file.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Unisce due documenti Pdf in un nuovo documento Pdf con le pagine alternate e riempie gli spazi vuoti con pagine bianche.

### createArrayWithExclusion {#createArrayWithExclusion-int-int-}
```
public static Integer [] createArrayWithExclusion(int n, int y)
```



### delete {#delete-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
Elimina le pagine specificate dal documento e salva il risultato nell'oggetto HttpServletResponse.

### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
Elimina le pagine specificate da un array di numeri dal file di input, salvandole in un nuovo file Pdf.

### delete {#delete-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
Elimina le pagine specificate dal documento e memorizza il risultato nell'oggetto HttpServletResponse.

### delete {#delete-java.lang.String-int:A-java.lang.String-}
Elimina le pagine specificate da un array di numeri dal file di input, salvandole in un nuovo file Pdf.

### extract {#extract-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
Estrae le pagine specificate dal file di origine e memorizza il risultato nell'oggetto HttpServletResponse.

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
Estrae le pagine specificate da un array di numeri, salvandole in un nuovo file Pdf.

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
Estrae le pagine dal file di input, salvandole in un nuovo file Pdf.

### extract {#extract-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
Estrae le pagine specificate dal file di origine e memorizza il risultato nell'oggetto HttpServletResponse.

### extract {#extract-java.lang.String-int:A-java.lang.String-}
Estrae le pagine specificate da un array di numeri, salvandole in un nuovo file PDF.

### extract {#extract-java.lang.String-int-int-java.lang.String-}
Estrae le pagine dal file di input, salvandole in un nuovo file Pdf.

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
@Deprecated public boolean getAllowConcatenateExceptions()
```

Obsoleto. Questa proprietà è obsoleta e non può essere utilizzata per consentire il lancio di eccezioni.

**Returns:**
Valore booleano

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Ottiene il nome dell'allegato quando il risultato dell'operazione è memorizzato negli oggetti HttpServletResponse come allegato.

**Returns:**
valore stringa

### getCloseConcatenatedStreams {#getCloseConcatenatedStreams--}
```
public boolean getCloseConcatenatedStreams()
```

Se impostato su true, i flussi vengono chiusi dopo l'operazione.

**Returns:**
valore booleano

### getConcatenationPacketSize {#getConcatenationPacketSize--}
```
public final int getConcatenationPacketSize()
```

Numero di documenti concatenati prima che venga effettuato un nuovo aggiornamento incrementale durante la concatenazione quando UseDiskBuffer è impostato su true.

**Returns:**
valore int

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Ottiene come verrà memorizzato il contenuto quando il risultato dell'operazione viene memorizzato nell'oggetto HttpServletResponse.

**Returns:**
Elemento ContentDisposition

### getConversionLog {#getConversionLog--}
```
public String getConversionLog()
```

Ottiene il log del processo di conversione.

**Returns:**
valore stringa

### getCopyLogicalStructure {#getCopyLogicalStructure--}
```
public boolean getCopyLogicalStructure()
```

Se true, la struttura logica del file viene copiata quando viene eseguita la concatenazione.

**Returns:**
valore booleano

### getCopyOutlines {#getCopyOutlines--}
```
public boolean getCopyOutlines()
```

Se true, i contorni (outlines) verranno copiati.

**Returns:**
valore booleano

### getCorruptedFileAction {#getCorruptedFileAction--}
```
public int getCorruptedFileAction()
```

Questa proprietà definisce il comportamento quando il processo di concatenazione incontra un file corrotto.

**Returns:**
Elemento ConcatenateCorruptedFileAction

### getCorruptedItems {#getCorruptedItems--}
```
public PdfFileEditor.CorruptedItem [] getCorruptedItems()
```

Array dei problemi riscontrati durante l'esecuzione della concatenazione.

**Returns:**
Array di PdfFileEditor.CorruptedItem

### getCustomProgressConcatenationHandler {#getCustomProgressConcatenationHandler--}
```
public PdfFileEditor.ConcatenationProgressHandler getCustomProgressConcatenationHandler()
```

Rappresentazione del processore interno di eventi di avanzamento che funziona durante la concatenazione e traduce gli eventi di concatenazione delle fasi interne in codice del cliente esterno.

**Returns:**
istanza di ConcatenationProgressHandler

### getIncrementalUpdates {#getIncrementalUpdates--}
```
public boolean getIncrementalUpdates()
```

Se true, gli aggiornamenti incrementali vengono eseguiti durante la concatenazione.

**Returns:**
valore booleano

### getKeepActions {#getKeepActions--}
```
public final boolean getKeepActions()
```

Se true, le azioni verranno copiate dai documenti di origine.

**Returns:**
valore booleano

### getKeepFieldsUnique {#getKeepFieldsUnique--}
```
public boolean getKeepFieldsUnique()
```

Se true, i nomi dei campi saranno resi unici quando i moduli vengono concatenati.

**Returns:**
valore booleano

### getLastException {#getLastException--}
```
public final RuntimeException getLastException()
```

Ottiene l'ultima eccezione verificatasi.

**Returns:**
oggetto java.lang.Exception

### getMergeDuplicateLayers {#getMergeDuplicateLayers--}
```
public boolean getMergeDuplicateLayers()
```

I contenuti opzionali dei documenti concatenati con nomi uguali saranno uniti in un unico livello nel documento risultante se questa proprietà è true.

**Returns:**
valore booleano

### getMergeDuplicateOutlines {#getMergeDuplicateOutlines--}
```
public boolean getMergeDuplicateOutlines()
```

Se true, i contorni duplicati vengono uniti.

**Returns:**
valore booleano

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Ottiene o imposta il flag di ottimizzazione.

**Returns:**
valore booleano

### getOwnerPassword {#getOwnerPassword--}
```
public String getOwnerPassword()
```

Ottiene la password del proprietario se il file PDF di input di origine è crittografato.

**Returns:**
Oggetto stringa

### getPreserveUserRights {#getPreserveUserRights--}
```
public boolean getPreserveUserRights()
```

Se vero, i diritti utente del primo documento vengono applicati al documento concatenato.

**Returns:**
valore booleano

### getRemoveSignatures {#getRemoveSignatures--}
```
public boolean getRemoveSignatures()
```

Se vero, tutte le firme saranno rimosse dai campi (i campi rimarranno); altrimenti, potresti ottenere firme non valide.

**Returns:**
valore booleano

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Ottiene o imposta le opzioni di salvataggio quando il risultato viene memorizzato come HttpServletResponse.

**Returns:**
oggetto SaveOptions

### getUniqueSuffix {#getUniqueSuffix--}
```
public String getUniqueSuffix()
```

Ottiene il formato del suffisso che viene aggiunto al nome del campo per renderlo unico quando i moduli sono concatenati.

**Returns:**
Oggetto stringa

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
Inserisce il documento in un altro documento e memorizza il risultato nell'oggetto risposta.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
Inserisce pagine da un altro file nel file PDF di input.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
Inserisce pagine da un altro file nel file PDF di input.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
Inserisce il contenuto del file nel file di origine e memorizza il risultato nell'oggetto HttpServletResponse.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
Inserisce pagine da un altro file nel file PDF di input.

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
Inserisce pagine da un altro file nel file PDF in una posizione.

### isTryMergeAdjacentSameBackgroundImages {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```

A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella) costruite da diverse immagini di sfondo a piastrelle identiche posizionate una accanto all'altra.

**Returns:**
valore booleano

### isUseDiskBuffer {#isUseDiskBuffer--}
```
public final boolean isUseDiskBuffer()
```

Se questa opzione è utilizzata, il documento di destinazione verrà salvato su disco periodicamente e le successive concatenazioni verranno applicate come aggiornamenti incrementali.

**Returns:**
valore booleano

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
Crea un libretto dallo InputStream verso outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
Crea un libretto personalizzato dal firstInputStream verso outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
Crea un libretto dallo stream di input e salva il risultato nello stream di output.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
Crea un libretto dal firstInputStream verso outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Crea un opuscolo dal file di origine e memorizza il risultato nell'HttpServletResponse.

### makeBooklet {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-}
Crea un opuscolo dal file PDF e lo memorizza nell'HttpServletResponse.

### makeBooklet {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Crea un opuscolo dal file di origine e memorizza il risultato negli oggetti HttpServletResponse.

### makeBooklet {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-}
Crea un opuscolo dal file di origine e memorizza il risultato negli oggetti HttpServletResponse.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-}
Crea un libretto dal file di input verso file di output.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-}
Crea un libretto personalizzato dal firstInputFile verso outputFile.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
Crea un libretto dal inputFile verso outputFile.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-}
Crea un libretto personalizzato dal firstInputFile verso outputFile.

### makeNUp {#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-}
Crea un documento N-Up dai più stream PDF di input verso outputStream.

### makeNUp {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Crea un documento N-Up dai due stream PDF di input verso outputStream.

### makeNUp {#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-}
Crea un documento N-up e memorizza il risultato nell'HttpServletResponse.

### makeNUp {#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Crea un documento N-up e memorizza il risultato nell'oggetto HttpServletResponse.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
Crea un documento N-Up dallo stream di input e salva il risultato nello stream di output.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
Crea un documento N-Up dal primo stream di input verso stream di output.

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
Crea un documento N-Up dai più file PDF di input verso outputFile.

### makeNUp {#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-}
Crea un documento N-up e memorizza il risultato nell'HttpServletResponse.

### makeNUp {#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Crea un documento N-up e memorizza il risultato nell'oggetto HttpServletResponse.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
Crea un documento N-Up dal firstInputFile verso outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
Crea un documento N-Up dal file di input verso outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
Crea un documento N-Up dai due file PDF di input verso outputFile.

### resizeContents {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ridimensiona le pagine del documento.

### resizeContents {#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ridimensiona le pagine del documento.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Ridimensiona i contenuti delle pagine del documento.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ridimensiona il contenuto delle pagine del documento.

### resizeContents {#resizeContents-com.aspose.ms.System.IO.Stream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
Ridimensiona il contenuto delle pagine nel documento.

### resizeContents {#resizeContents-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
Ridimensiona il contenuto delle pagine nel documento.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
Ridimensiona i contenuti delle pagine del documento.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ridimensiona il contenuto delle pagine nel documento.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Ridimensiona i contenuti delle pagine del documento.

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
Ridimensiona i contenuti delle pagine del documento.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ridimensiona le pagine del documento.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ridimensiona le pagine del documento.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
@Deprecated public void setAllowConcatenateExceptions(boolean value)
```

Obsoleto. Questa proprietà è obsoleta e non può essere utilizzata per consentire il lancio di eccezioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Valore booleano |

### setAttachmentName {#setAttachmentName-java.lang.String-}
Imposta il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpServletResponse come allegato.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams(boolean value)
```

Se impostato su true, i flussi vengono chiusi dopo l'operazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setConcatenationPacketSize {#setConcatenationPacketSize-int-}
```
public final void setConcatenationPacketSize(int value)
```

Numero di documenti concatenati prima che venga effettuato un nuovo aggiornamento incrementale durante la concatenazione quando UseDiskBuffer è impostato su true.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Imposta come verrà memorizzato il contenuto quando il risultato dell'operazione viene memorizzato nell'oggetto HttpServletResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Imposta il formato del file PDF.

### setCopyLogicalStructure {#setCopyLogicalStructure-boolean-}
```
public void setCopyLogicalStructure(boolean value)
```

Se true, la struttura logica del file viene copiata quando viene eseguita la concatenazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setCopyOutlines {#setCopyOutlines-boolean-}
```
public void setCopyOutlines(boolean value)
```

Se true, i contorni (outlines) verranno copiati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setCorruptedFileAction {#setCorruptedFileAction-int-}
```
public void setCorruptedFileAction(int value)
```

Questa proprietà definisce il comportamento quando il processo di concatenazione incontra un file corrotto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento ConcatenateCorruptedFileAction |

### setCustomProgressConcatenationHandler {#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-}
Rappresentazione del processore interno di eventi di avanzamento che funziona durante la concatenazione e traduce gli eventi di concatenazione delle fasi interne in codice del cliente esterno.

### setIncrementalUpdates {#setIncrementalUpdates-boolean-}
```
public void setIncrementalUpdates(boolean value)
```

Se true, gli aggiornamenti incrementali vengono eseguiti durante la concatenazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setKeepActions {#setKeepActions-boolean-}
```
public final void setKeepActions(boolean value)
```

Se true, le azioni verranno copiate dai documenti di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setKeepFieldsUnique {#setKeepFieldsUnique-boolean-}
```
public void setKeepFieldsUnique(boolean value)
```

Se true, i nomi dei campi saranno resi unici quando i moduli vengono concatenati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setMergeDuplicateLayers {#setMergeDuplicateLayers-boolean-}
```
public void setMergeDuplicateLayers(boolean value)
```

I contenuti opzionali dei documenti concatenati con nomi uguali saranno uniti in un unico livello nel documento risultante se questa proprietà è true.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setMergeDuplicateOutlines {#setMergeDuplicateOutlines-boolean-}
```
public void setMergeDuplicateOutlines(boolean value)
```

Se true, i contorni duplicati vengono uniti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Ottiene o imposta il flag di ottimizzazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setOwnerPassword {#setOwnerPassword-java.lang.String-}
Imposta la password del proprietario se il file PDF di input di origine è crittografato.

### setPreserveUserRights {#setPreserveUserRights-boolean-}
```
public void setPreserveUserRights(boolean value)
```

Se vero, i diritti utente del primo documento vengono applicati al documento concatenato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setRemoveSignatures {#setRemoveSignatures-boolean-}
```
public void setRemoveSignatures(boolean value)
```

Se vero, tutte le firme saranno rimosse dai campi (i campi rimarranno); altrimenti, potresti ottenere firme non valide.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Imposta le opzioni di salvataggio quando il risultato viene memorizzato come HttpServletResponse.

### setTryMergeAdjacentSameBackgroundImages {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```

A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella) costruite da diverse immagini di sfondo a piastrelle identiche posizionate una accanto all'altra.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages |  | valore booleano |

### setUniqueSuffix {#setUniqueSuffix-java.lang.String-}
Imposta il formato del suffisso che viene aggiunto al nome del campo per renderlo univoco quando i moduli sono concatenati.

### setUseDiskBuffer {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer(boolean value)
```

Se questa opzione è utilizzata, il documento di destinazione verrà salvato su disco periodicamente e le successive concatenazioni verranno applicate come aggiornamenti incrementali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
Divide il documento dall'inizio fino alla posizione specificata e memorizza il risultato nell'oggetto HttpServletResponse.

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
Dividi dall'inizio fino alla posizione specificata e salva la parte anteriore nello Stream di output.

### splitFromFirst {#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
Divide il documento dalla prima pagina fino alla posizione e salva il risultato negli oggetti HttpServletResponse.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
Dividi il file PDF dalla prima pagina fino alla posizione specificata e salva la parte anteriore come nuovo file.

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
Divide il file Pdf in diversi documenti. I documenti possono essere a pagina singola o multi-pagina.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
Divide il file Pdf in diversi documenti. I documenti possono essere a pagina singola o multi-pagina.

### splitToEnd {#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
Divide dalla posizione specificata e salva la parte finale nell'oggetto HttpServletResponse.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
Dividi dalla posizione specificata e salva la parte posteriore come nuovo Stream di file.

### splitToEnd {#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
Divide dalla posizione specificata e salva la parte finale nell'oggetto HttpServletResponse.

### splitToEnd {#splitToEnd-java.lang.String-int-java.lang.String-}
Dividi dalla posizione e salva la parte posteriore come nuovo file.

### splitToPages {#splitToPages-java.io.InputStream-}
Divide il file Pdf in documenti a pagina singola.

### splitToPages {#splitToPages-java.io.InputStream-java.lang.String-}
Dividi il file Pdf in documenti a pagina singola e salvalo nel percorso specificato.

### splitToPages {#splitToPages-java.lang.String-}
Dividi il file PDF in documenti a pagina singola.

### splitToPages {#splitToPages-java.lang.String-java.lang.String-}
Dividi il file Pdf in documenti a pagina singola e salvalo nel percorso specificato.
