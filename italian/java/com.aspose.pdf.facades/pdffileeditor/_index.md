---
title: "PdfFileEditor"
linktitle: "PdfFileEditor"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Implementa operazioni sui file PDF: concatenazione, divisione, estrazione di pagine, creazione di opuscoli, ecc."
type: docs
weight: 410
url: /it/java/com.aspose.pdf.facades/pdffileeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfFileEditor

**All Implemented Interfaces:**
IPdfFileEditor

```
public final class PdfFileEditor extends Object implements IPdfFileEditor
```

Implementa operazioni sui file PDF: concatenazione, divisione, estrazione di pagine, creazione di opuscoli, ecc.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfFileEditor](#PdfFileEditor--) | Costruttore di PdfFileEditor. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | <p> Ridimensiona il contenuto della pagina e aggiunge i margini specificati. I margini sono specificati in unità di spazio predefinite. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileInputStream("output.pdf"); fileEditor.addMargins(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); dest.Close(); </pre> |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | <p> Ridimensiona il contenuto della pagina e aggiunge i margini specificati. I margini sono specificati in unità di spazio predefinite. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMargins("input.pdf", "output.pdf", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); </pre> |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | <p> Ridimensiona il contenuto della pagina e aggiunge i margini specificati. I margini sono specificati in percentuale della dimensione iniziale della pagina. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileInputStream("output.pdf"); fileEditor.addMarginsPct(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); dest.close(); </pre> |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | <p> Ridimensiona il contenuto della pagina e aggiunge i margini specificati. I margini sono specificati in percentuale della dimensione iniziale della pagina. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMarginsPct("input.pdf", "output.pdf", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); </pre> |
| [addPageBreak](#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Aggiunge interruzioni di pagina nelle pagine del documento. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Aggiunge interruzioni di pagina nelle pagine del documento. |
| [addPageBreak](#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Aggiunge interruzioni di pagina nelle pagine del documento. |
| [addPageBreak](#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Aggiunge interruzioni di pagina nelle pagine del documento. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | <p> Aggiunge pagine, scelte da un array di documenti in portStreams. Il documento risultante include firstInputFile e tutte le pagine dei documenti portStreams nell'intervallo da startPage a endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream(\"input.pdf\"); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OtputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.append(instream, new InputStream[] { stream1, stream2}, 3, 5, outstream); </pre> |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | <p> Aggiunge pagine, scelte da portStream entro l'intervallo da startPage a endPage, in portStream alla fine di firstInputStream. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream(\"input.pdf\"); InputStream stream1 = new FileInputStream(\"file1.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.append(instream, stream1, 3, 5, outstream); </pre> |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | <p> Aggiunge pagine, scelte dai documenti portFiles. Il documento risultante include firstInputFile e tutte le pagine dei documenti portFiles nell'intervallo da startPage a endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append(\"input.pdf\", new string[] { \"file1.pdf\", \"file2.pdf\"}, 3, 5, \"outfile.pdf\"); </pre> |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | <p> Aggiunge pagine, scelte da portFile entro l'intervallo da startPage a endPage, in portFile alla fine di firstInputFile. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append(\"input.pdf\", \"file1.pdf\", 3, 5, \"outfile.pdf\"); </pre> |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | Concatena documenti. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | <p> Concatena file </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(new Stream[] { stream1, stream2 } , outstream); </pre> |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> Unisce due documenti Pdf in un nuovo documento Pdf con le pagine alternate e riempie gli spazi vuoti con pagine bianche. ad es.: document1 ha 5 pagine: p1, p2, p3, p4, p5. document2 ha 3 pagine: p1', p2', p3'. L'unione dei due documenti Pdf produrrà il documento risultante con le pagine: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); InputStream blank = new FileInputStream(\"blank.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(new Stream[] { stream1, stream2, blank } , outstream); </pre> |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> Concatena due file. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(stream1, stream2, outstream); </pre> |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | <p> Concatena file in un unico file. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(new String[] { \"src1.pdf\", \"src2.pdf\" }, \"dest.pdf\"); </pre> |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | <p> Concatena due file. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.concatenate(\"file1.pdf\", \"file2.pdf\", \"outfile.pdf\"); </pre> |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | <p> Unisce due documenti Pdf in un nuovo documento Pdf con le pagine alternate e riempie gli spazi vuoti con pagine bianche. ad es.: document1 ha 5 pagine: p1, p2, p3, p4, p5. document2 ha 3 pagine: p1', p2', p3'. L'unione dei due documenti Pdf produrrà il documento risultante con le pagine: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(\"src1.pdf\", \"src2.pdf\", \"blank.pdf\", \"dest.pdf\"); </pre> |
| [createArrayWithExclusion](#createArrayWithExclusion-int-int-) |  |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | <p> Elimina le pagine specificate da un array di numeri dal file di input, salvandole come un nuovo file Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream intputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileInputStream(\"output.pdf\"); pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream); </pre> |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | <p> Elimina le pagine specificate da un array di numeri dal file di input, salvandole come un nuovo file Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.delete(\"input.pdf\", new int[] { 2, 3 }, \"out.pdf\"); </pre> |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | <p> Estrae le pagine specificate da un array di numeri, salvandole come un nuovo file Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream(\"file1.pdf\"); OutputStream outStream = new FileInputStream(\"out.pdf\"); pfe.extract(sourceStream, new int[] { 3, 5, 8 }, outStream); </pre> |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | <p> Estrae le pagine dal file di input, salvandole come un nuovo file Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream(\"file1.pdf\"); OutputStream outStream = new FileOutputStream(\"out.pdf\"); pfe.extract(sourceStream, 1, 3, 6, outStream); </pre> |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | <p> Estrae le pagine specificate da un array di numeri, salvandole come un nuovo file PDF. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.extract(\"input.pdf\", new int[] { 3, 5, 7 }, \"output.pdf\"); </pre> |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | <p> Estrae le pagine dal file di input, salvandole come un nuovo file Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.Extract(\"input.pdf\", 3, 7, \"output.pdf\"); </pre> |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | <p> Se impostato su true, le eccezioni vengono sollevate se si verifica un errore. Altrimenti le eccezioni non vengono sollevate e i metodi restituiscono false in caso di fallimento. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre> |
| [getAttachmentName](#getAttachmentName--) | Ottiene il nome dell'allegato quando il risultato dell'operazione è memorizzato negli oggetti HttpServletResponse come allegato. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | Se impostato su true, i flussi vengono chiusi dopo l'operazione. |
| [getConcatenationPacketSize](#getConcatenationPacketSize--) | Numero di documenti concatenati prima che venga effettuato un nuovo aggiornamento incrementale durante la concatenazione quando UseDiskBuffer è impostato su true. |
| [getContentDisposition](#getContentDisposition--) | Ottiene come il contenuto sarà memorizzato quando il risultato dell'operazione è memorizzato nell'oggetto HttpServletResponse. Valori possibili: inline / attachment. Predefinito: inline. |
| [getConversionLog](#getConversionLog--) | Ottiene il log del processo di conversione. |
| [getCopyLogicalStructure](#getCopyLogicalStructure--) | Se true, la struttura logica del file viene copiata quando viene eseguita la concatenazione. |
| [getCopyOutlines](#getCopyOutlines--) | Se true, i contorni (outlines) verranno copiati. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | Questa proprietà definisce il comportamento quando il processo di concatenazione incontra un file corrotto. I valori possibili sono: StopWithError e ConcatenateIgnoringCorrupted. |
| [getCorruptedItems](#getCorruptedItems--) | <p> Array di problemi riscontrati quando è stata eseguita la concatenazione. Per ogni documento corrotto passato alla funzione Concatenate() viene creata una nuova voce CorruptedItem. Questa proprietà può essere usata solo quando CorruptedFileAction è ConcatenateIgnoringCorrupted. </p> <hr> <pre> //concatenate documents and show information about corrupted documents PdfFileEditor pfe = new PdfFileEditor(); pfe.setCorruptedFileAction(PdfFileEditor.ConcatenateCorruptedFileAction.ConcatenateIgnoringCorrupted); {@code if (pfe.getCorruptedItems().length >0)} { for(PdfFileEditor.CorruptedItem item : pfe.getCorruptedItems()) { System.out.println(item.getIndex()+ \" reason: \" + item.getException()); } } </pre> |
| [getCustomProgressConcatenationHandler](#getCustomProgressConcatenationHandler--) | Rappresentazione del processore interno di eventi di avanzamento che funziona durante la concatenazione e traduce gli eventi di concatenazione delle fasi interne in codice del cliente esterno. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | Se true, gli aggiornamenti incrementali vengono eseguiti durante la concatenazione. |
| [getKeepActions](#getKeepActions--) | Se true, le azioni verranno copiate dai documenti di origine. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | Se true, i nomi dei campi verranno resi unici quando i moduli sono concatenati. Verranno aggiunti suffissi ai nomi dei campi; il modello di suffisso può essere specificato nella proprietà UniqueSuffix. |
| [getLastException](#getLastException--) | Ottiene l'ultima eccezione verificatasi. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | I contenuti opzionali dei documenti concatenati con nomi uguali saranno uniti in un unico livello nel documento risultante se questa proprietà è true. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | Se true, i contorni duplicati vengono uniti. |
| [getOptimizeSize](#getOptimizeSize--) | Ottiene o imposta il flag di ottimizzazione. |
| [getOwnerPassword](#getOwnerPassword--) | Ottiene la password del proprietario se il file Pdf di input di origine è crittografato. Questa proprietà non è ancora implementata. |
| [getPreserveUserRights](#getPreserveUserRights--) | Se vero, i diritti utente del primo documento vengono applicati al documento concatenato. |
| [getRemoveSignatures](#getRemoveSignatures--) | Se vero, tutte le firme saranno rimosse dai campi (i campi rimarranno); altrimenti, potresti ottenere firme non valide. |
| [getSaveOptions](#getSaveOptions--) | Ottiene o imposta le opzioni di salvataggio quando il risultato è memorizzato come HttpServletResponse. Valore predefinito: PdfSaveOptions. |
| [getUniqueSuffix](#getUniqueSuffix--) | Ottieni il formato del suffisso che viene aggiunto al nome del campo per renderlo univoco quando i moduli sono concatenati. Questa stringa deve contenere la sottostringa %NUM% che sarà sostituita con numeri. Per esempio, se UniqueSuffix = "ABC%NUM%" allora per il campo "fieldName" i nomi saranno: fieldNameABC1, fieldNameABC2, fieldNameABC3 ecc. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | <p> Inserisce pagine da un altro file nel file Pdf di input. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileoutputStream("out.pdf"); pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream); </pre> |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | <p> Inserisce pagine da un altro file nel file Pdf di input. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre> |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | <p> Inserisce pagine da un altro file nel file Pdf di input. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre> |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | <p> Inserisce pagine da un altro file nel file Pdf in una posizione. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf"); </pre> |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella) costruite da diverse immagini di sfondo a piastrelle identiche posizionate una accanto all'altra. |
| [isUseDiskBuffer](#isUseDiskBuffer--) | Se questa opzione è utilizzata, il documento di destinazione verrà salvato su disco periodicamente e le successive concatenazioni verranno applicate come aggiornamenti incrementali. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | <p> Crea un libretto dallo InputStream allo outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | <p> Crea un libretto personalizzato dal firstInputStream allo outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | <p> Crea un libretto dallo stream di input e salva il risultato nello stream di output. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | <p> Crea un libretto dal firstInputStream allo outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | <p> Crea un libretto dal file di input al file di output. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf"); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | <p> Crea un libretto personalizzato dal firstInputFile al outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | <p> Crea un opuscolo dal inputFile al outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", PageSize.A4); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | <p> Crea un opuscolo personalizzato dal firstInputFile al outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | <p> Crea un documento N‑Up dai flussi PDF di input multipli a outputStream. Ogni pagina di outputStream conterrà più pagine, che sono una combinazione delle pagine nei flussi di input con lo stesso numero di pagina. Le pagine multiple sono impilate orizzontalmente se isSidewise è true e verticalmente se isSidewise è false. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"input1.pdf\"); InputStream stream2 = new FileInputStream(\"input2.pdf\"); InputStream stream3 = new FileInputStream(\"input3.pdf\"); OutputStream output = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(new InputStream[] { stream1, stream2, stream3 }, output, false); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> Crea un documento N‑Up dai due flussi PDF di input a outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream input1 = new FileInputStream(\"input1.pdf\"); InputStream input2 = new FileInputStream(\"input2.pdf\"); OutputStream output = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(input1, input2, output); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | <p> Crea un documento N‑Up dal flusso di input e salva il risultato nel flusso di output. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(inputStream, outputStream, 3, 3); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | <p> Crea un documento N‑Up dal primo flusso di input al flusso di output. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4); </pre> |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | <p> Crea un documento N‑Up dai file PDF di input multipli a outputFile. Ogni pagina di outputFile conterrà più pagine, che sono una combinazione delle pagine nei file di input con lo stesso numero di pagina. Le pagine multiple sono impilate orizzontalmente se isSidewise è true e verticalmente se isSidewise è false. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(new String[] { \"input1.pdf\", \"input2.pdf\", \"input3.pdf\" }, \"output.pdf\", false); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | <p> Crea un documento N‑Up dal firstInputFile al outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input.pdf\", \"output.pdf\", 3, 3); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | <p> Crea un documento N‑Up dal file di input al outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input.pdf\", \"output.pdf\", 3, 3, PageSize.A4); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | <p> Crea un documento N‑Up dai due file PDF di input a outputFile. Ogni pagina di outputFile conterrà due pagine, una proveniente dal primo file di input e l'altra dal secondo file di input. Le due pagine sono impilate orizzontalmente. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input1.pdf\", \"input2.pdf\", \"output.pdf\"); </pre> |
| [resizeContents](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ridimensiona le pagine del documento. |
| [resizeContents](#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ridimensiona le pagine del documento. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | <p> Ridimensiona il contenuto delle pagine del documento. Riduce il contenuto della pagina e aggiunge margini. La nuova dimensione del contenuto è specificata nelle unità di spazio predefinite. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileOutputStream(\"output.pdf\"); fileEditor.resizeContents(src, dest, //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre> |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ridimensiona il contenuto delle pagine del documento. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | <p> Ridimensiona il contenuto delle pagine del documento. Riduce il contenuto della pagina e aggiunge i margini. La nuova dimensione del contenuto è specificata nelle unità di spazio predefinite. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizeContents("input.pdf", "output.pdf", //ridimensiona tutte le pagine del documento null, //nuova larghezza del contenuto = 200 200, //nuova altezza del contenuto = 300 300); // l'area restante della pagina sarà vuota </pre> |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ridimensiona il contenuto delle pagine nel documento. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | <p> Ridimensiona il contenuto delle pagine del documento. Riduce il contenuto della pagina e aggiunge i margini. La nuova dimensione del contenuto è specificata in percentuale. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileOutputStream("output.pdf"); fileEditor.resizePct(src, dest, //ridimensiona tutte le pagine del documento null, //nuova larghezza del contenuto = 60% della dimensione iniziale 60, //nuova altezza del contenuto = 60% della dimensione iniziale 60); // L'area restante della pagina sarà vuota (margini della pagina). // Lo stesso per i margini superiore e inferiore. </pre> |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | <p> Ridimensiona il contenuto delle pagine del documento. Riduce il contenuto della pagina e aggiunge i margini. La nuova dimensione del contenuto è specificata in percentuale. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizePct("input.pdf", "output.pdf", //ridimensiona tutte le pagine del documento null, //nuova larghezza del contenuto = 60% della dimensione iniziale 60, //nuova altezza del contenuto = 60% della dimensione iniziale 60); // L'area restante della pagina sarà vuota (margini della pagina). // Lo stesso per i margini superiore e inferiore. </pre> |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ridimensiona le pagine del documento. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ridimensiona le pagine del documento. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | <p> Se impostato su true, le eccezioni vengono sollevate se si verifica un errore. Altrimenti le eccezioni non vengono sollevate e i metodi restituiscono false in caso di fallimento. </p> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Imposta il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpServletResponse come allegato. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | <p> Se impostato su true, i flussi vengono chiusi dopo l'operazione. </p> |
| [setConcatenationPacketSize](#setConcatenationPacketSize-int-) | Numero di documenti concatenati prima che venga effettuato un nuovo aggiornamento incrementale durante la concatenazione quando UseDiskBuffer è impostato su true. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Imposta come verrà memorizzato il contenuto quando il risultato dell'operazione viene salvato nell'oggetto HttpServletResponse. Valori possibili: inline / attachment. Predefinito: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Imposta il formato del file PDF. Il file risultante verrà salvato nel formato specificato. Se questa proprietà non è specificata, il file verrà salvato nel formato PDF predefinito senza conversione. |
| [setCopyLogicalStructure](#setCopyLogicalStructure-boolean-) | Se true, la struttura logica del file viene copiata quando viene eseguita la concatenazione. |
| [setCopyOutlines](#setCopyOutlines-boolean-) | Se true, i contorni (outlines) verranno copiati. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | Questa proprietà definisce il comportamento quando il processo di concatenazione incontra un file corrotto. I valori possibili sono: StopWithError e ConcatenateIgnoringCorrupted. |
| [setCustomProgressConcatenationHandler](#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-) | Rappresentazione del processore interno di eventi di avanzamento che funziona durante la concatenazione e traduce gli eventi di concatenazione delle fasi interne in codice del cliente esterno. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | Se true, gli aggiornamenti incrementali vengono eseguiti durante la concatenazione. |
| [setKeepActions](#setKeepActions-boolean-) | Se true, le azioni verranno copiate dai documenti di origine. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | Se true, i nomi dei campi verranno resi unici quando i moduli sono concatenati. Verranno aggiunti suffissi ai nomi dei campi; il modello di suffisso può essere specificato nella proprietà UniqueSuffix. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | I contenuti opzionali dei documenti concatenati con nomi uguali saranno uniti in un unico livello nel documento risultante se questa proprietà è true. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | Se true, i contorni duplicati vengono uniti. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Ottiene o imposta il flag di ottimizzazione. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | Imposta la password del proprietario se il file Pdf di input è crittografato. Questa proprietà non è ancora implementata. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | Se vero, i diritti utente del primo documento vengono applicati al documento concatenato. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | Se vero, tutte le firme saranno rimosse dai campi (i campi rimarranno); altrimenti, potresti ottenere firme non valide. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Imposta le opzioni di salvataggio quando il risultato viene memorizzato come HttpServletResponse. Valore predefinito: PdfSaveOptions. |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella) costruite da diverse immagini di sfondo a piastrelle identiche posizionate una accanto all'altra. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | <p> Imposta il formato del suffisso che viene aggiunto al nome del campo per renderlo univoco quando i moduli sono concatenati. Questa stringa deve contenere la sottostringa %NUM% che verrà sostituita con numeri. Ad esempio, se UniqueSuffix = "ABC%NUM%" allora per il campo "fieldName" i nomi saranno: fieldNameABC1, fieldNameABC2, fieldNameABC3 ecc. </p> <hr> <pre> PdfFileEditor ed = new PdfFileEditor(); ed.setUniqueSuffix ( "_%NUM%"); </pre> |
| [setUseDiskBuffer](#setUseDiskBuffer-boolean-) | Se questa opzione è utilizzata, il documento di destinazione verrà salvato su disco periodicamente e le successive concatenazioni verranno applicate come aggiornamenti incrementali. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | <p> Divide dall'inizio fino alla posizione specificata e salva la parte anteriore nello Stream di output. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.splitFromFirst(sourceStream, 5, outStream); </pre> <hr> I flussi NON vengono chiusi dopo questa operazione. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | <p> Divide il file Pdf dalla prima pagina fino alla posizione specificata e salva la parte anteriore come nuovo file. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitFromFirst("input.pdf", 5, "out.pdf"); </pre> |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | Divide il file Pdf in diversi documenti. I documenti possono essere a pagina singola o multi-pagina. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | Divide il file Pdf in diversi documenti. I documenti possono essere a pagina singola o multi-pagina. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | <p> Divide dalla posizione specificata e salva la parte finale come nuovo Stream di file. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.splitToEnd(sourceStream, 5, outStream); </pre> <hr> I flussi NON vengono chiusi dopo questa operazione a meno che non sia specificato CloseConcatedStreams. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | <p> Divide dalla posizione e salva la parte finale come nuovo file. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitToEnd("input.pdf", 5, "out.pdf"); </pre> |
| [splitToPages](#splitToPages-java.io.InputStream-) | Divide il file Pdf in documenti a pagina singola. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | Dividi il file Pdf in documenti a pagina singola e salvalo nel percorso specificato. |
| [splitToPages](#splitToPages-java.lang.String-) | Dividi il file PDF in documenti a pagina singola. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | Dividi il file Pdf in documenti a pagina singola e salvalo nel percorso specificato. |

### PdfFileEditor {#PdfFileEditor--}
```
public PdfFileEditor()
```

Costruttore di PdfFileEditor.

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
<p> Ridimensiona il contenuto della pagina e aggiunge i margini specificati. I margini sono specificati in unità di spazio predefinite. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileInputStream("output.pdf"); fileEditor.addMargins(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); dest.Close(); </pre>

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
<p> Ridimensiona il contenuto della pagina e aggiunge i margini specificati. I margini sono specificati in unità di spazio predefinite. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMargins("input.pdf", "output.pdf", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); </pre>

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
<p> Ridimensiona il contenuto della pagina e aggiunge i margini specificati. I margini sono specificati in percentuale della dimensione iniziale della pagina. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileInputStream("output.pdf"); fileEditor.addMarginsPct(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); dest.close(); </pre>

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
<p> Ridimensiona il contenuto della pagina e aggiunge i margini specificati. I margini sono specificati in percentuale della dimensione iniziale della pagina. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMarginsPct("input.pdf", "output.pdf", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); </pre>

### addPageBreak {#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Aggiunge interruzioni di pagina nelle pagine del documento.

### addPageBreak {#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Aggiunge interruzioni di pagina nelle pagine del documento.

### addPageBreak {#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Aggiunge interruzioni di pagina nelle pagine del documento.

### addPageBreak {#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Aggiunge interruzioni di pagina nelle pagine del documento.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
<p> Aggiunge pagine, scelte da un array di documenti in portStreams. Il documento risultante include firstInputFile e tutte le pagine dei documenti portStreams nell'intervallo da startPage a endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream(\"input.pdf\"); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OtputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.append(instream, new InputStream[] { stream1, stream2}, 3, 5, outstream); </pre>

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
<p> Aggiunge pagine, scelte da portStream entro l'intervallo da startPage a endPage, in portStream alla fine di firstInputStream. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream(\"input.pdf\"); InputStream stream1 = new FileInputStream(\"file1.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.append(instream, stream1, 3, 5, outstream); </pre>

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
<p> Aggiunge pagine, scelte dai documenti portFiles. Il documento risultante include firstInputFile e tutte le pagine dei documenti portFiles nell'intervallo da startPage a endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append(\"input.pdf\", new string[] { \"file1.pdf\", \"file2.pdf\"}, 3, 5, \"outfile.pdf\"); </pre>

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
<p> Aggiunge pagine, scelte da portFile entro l'intervallo da startPage a endPage, in portFile alla fine di firstInputFile. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append(\"input.pdf\", \"file1.pdf\", 3, 5, \"outfile.pdf\"); </pre>

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
Concatena documenti.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
<p> Concatena file </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(new Stream[] { stream1, stream2 } , outstream); </pre>

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> Unisce due documenti Pdf in un nuovo documento Pdf con le pagine alternate e riempie gli spazi vuoti con pagine bianche. ad es.: document1 ha 5 pagine: p1, p2, p3, p4, p5. document2 ha 3 pagine: p1', p2', p3'. L'unione dei due documenti Pdf produrrà il documento risultante con le pagine: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); InputStream blank = new FileInputStream(\"blank.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(new Stream[] { stream1, stream2, blank } , outstream); </pre>

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> Concatena due file. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(stream1, stream2, outstream); </pre>

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
<p> Concatena file in un unico file. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(new String[] { \"src1.pdf\", \"src2.pdf\" }, \"dest.pdf\"); </pre>

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
<p> Concatena due file. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.concatenate(\"file1.pdf\", \"file2.pdf\", \"outfile.pdf\"); </pre>

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
<p> Unisce due documenti Pdf in un nuovo documento Pdf con le pagine alternate e riempie gli spazi vuoti con pagine bianche. ad es.: document1 ha 5 pagine: p1, p2, p3, p4, p5. document2 ha 3 pagine: p1', p2', p3'. L'unione dei due documenti Pdf produrrà il documento risultante con le pagine: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(\"src1.pdf\", \"src2.pdf\", \"blank.pdf\", \"dest.pdf\"); </pre>

### createArrayWithExclusion {#createArrayWithExclusion-int-int-}
```
public static Integer [] createArrayWithExclusion(int n, int y)
```



### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
<p> Elimina le pagine specificate da un array di numeri dal file di input, salvandole come un nuovo file Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream intputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileInputStream(\"output.pdf\"); pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream); </pre>

### delete {#delete-java.lang.String-int:A-java.lang.String-}
<p> Elimina le pagine specificate da un array di numeri dal file di input, salvandole come un nuovo file Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.delete(\"input.pdf\", new int[] { 2, 3 }, \"out.pdf\"); </pre>

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
<p> Estrae le pagine specificate da un array di numeri, salvandole come un nuovo file Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream(\"file1.pdf\"); OutputStream outStream = new FileInputStream(\"out.pdf\"); pfe.extract(sourceStream, new int[] { 3, 5, 8 }, outStream); </pre>

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
<p> Estrae le pagine dal file di input, salvandole come un nuovo file Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream(\"file1.pdf\"); OutputStream outStream = new FileOutputStream(\"out.pdf\"); pfe.extract(sourceStream, 1, 3, 6, outStream); </pre>

### extract {#extract-java.lang.String-int:A-java.lang.String-}
<p> Estrae le pagine specificate da un array di numeri, salvandole come un nuovo file PDF. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.extract(\"input.pdf\", new int[] { 3, 5, 7 }, \"output.pdf\"); </pre>

### extract {#extract-java.lang.String-int-int-java.lang.String-}
<p> Estrae le pagine dal file di input, salvandole come un nuovo file Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.Extract(\"input.pdf\", 3, 7, \"output.pdf\"); </pre>

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
@Deprecated public boolean getAllowConcatenateExceptions()
```

<p> Se impostato su true, le eccezioni vengono sollevate se si verifica un errore. Altrimenti le eccezioni non vengono sollevate e i metodi restituiscono false in caso di fallimento. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre>

**Returns:**
valore booleano @deprecated Questa proprietà è deprecata e non può essere utilizzata per consentire il lancio di eccezioni.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Ottiene il nome dell'allegato quando il risultato dell'operazione è memorizzato negli oggetti HttpServletResponse come allegato.

**Returns:**
valore String

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

Ottiene come il contenuto sarà memorizzato quando il risultato dell'operazione è memorizzato nell'oggetto HttpServletResponse. Valori possibili: inline / attachment. Predefinito: inline.

**Returns:**
Elemento ContentDisposition @see ContentDisposition

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

Questa proprietà definisce il comportamento quando il processo di concatenazione incontra un file corrotto. I valori possibili sono: StopWithError e ConcatenateIgnoringCorrupted.

**Returns:**
Elemento ConcatenateCorruptedFileAction @see ConcatenateCorruptedFileAction

### getCorruptedItems {#getCorruptedItems--}
```
public PdfFileEditor.CorruptedItem [] getCorruptedItems()
```

<p> Array di problemi riscontrati quando è stata eseguita la concatenazione. Per ogni documento corrotto passato alla funzione Concatenate() viene creata una nuova voce CorruptedItem. Questa proprietà può essere usata solo quando CorruptedFileAction è ConcatenateIgnoringCorrupted. </p> <hr> <pre> //concatenate documents and show information about corrupted documents PdfFileEditor pfe = new PdfFileEditor(); pfe.setCorruptedFileAction(PdfFileEditor.ConcatenateCorruptedFileAction.ConcatenateIgnoringCorrupted); {@code if (pfe.getCorruptedItems().length >0)} { for(PdfFileEditor.CorruptedItem item : pfe.getCorruptedItems()) { System.out.println(item.getIndex()+ \" reason: \" + item.getException()); } } </pre>

**Returns:**
array di PdfFileEditor.CorruptedItem

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

Se true, i nomi dei campi verranno resi unici quando i moduli sono concatenati. Verranno aggiunti suffissi ai nomi dei campi; il modello di suffisso può essere specificato nella proprietà UniqueSuffix.

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

Ottiene la password del proprietario se il file Pdf di input di origine è crittografato. Questa proprietà non è ancora implementata.

**Returns:**
valore String

### getPreserveUserRights {#getPreserveUserRights--}
```
public boolean getPreserveUserRights()
```

Se vero, i diritti utente del primo documento vengono applicati al documento concatenato.

**Returns:**
valore booleano

### getRemoveSignatures {#getRemoveSignatures--}
```
public final boolean getRemoveSignatures()
```

Se vero, tutte le firme saranno rimosse dai campi (i campi rimarranno); altrimenti, potresti ottenere firme non valide.

**Returns:**
valore booleano

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Ottiene o imposta le opzioni di salvataggio quando il risultato è memorizzato come HttpServletResponse. Valore predefinito: PdfSaveOptions.

**Returns:**
oggetto SaveOptions

### getUniqueSuffix {#getUniqueSuffix--}
```
public String getUniqueSuffix()
```

Ottieni il formato del suffisso che viene aggiunto al nome del campo per renderlo univoco quando i moduli sono concatenati. Questa stringa deve contenere la sottostringa %NUM% che sarà sostituita con numeri. Per esempio, se UniqueSuffix = "ABC%NUM%" allora per il campo "fieldName" i nomi saranno: fieldNameABC1, fieldNameABC2, fieldNameABC3 ecc.

**Returns:**
valore String

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
<p> Inserisce pagine da un altro file nel file Pdf di input. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileoutputStream("out.pdf"); pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream); </pre>

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
<p> Inserisce pagine da un altro file nel file Pdf di input. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre>

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
<p> Inserisce pagine da un altro file nel file Pdf di input. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre>

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
<p> Inserisce pagine da un altro file nel file Pdf in una posizione. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf"); </pre>

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
<p> Crea un libretto dallo InputStream allo outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
<p> Crea un libretto personalizzato dal firstInputStream allo outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
<p> Crea un libretto dallo stream di input e salva il risultato nello stream di output. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
<p> Crea un libretto dal firstInputStream allo outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-}
<p> Crea un libretto dal file di input al file di output. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf"); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-}
<p> Crea un libretto personalizzato dal firstInputFile al outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
<p> Crea un opuscolo dal inputFile al outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", PageSize.A4); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-}
<p> Crea un opuscolo personalizzato dal firstInputFile al outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeNUp {#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-}
<p> Crea un documento N‑Up dai flussi PDF di input multipli a outputStream. Ogni pagina di outputStream conterrà più pagine, che sono una combinazione delle pagine nei flussi di input con lo stesso numero di pagina. Le pagine multiple sono impilate orizzontalmente se isSidewise è true e verticalmente se isSidewise è false. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"input1.pdf\"); InputStream stream2 = new FileInputStream(\"input2.pdf\"); InputStream stream3 = new FileInputStream(\"input3.pdf\"); OutputStream output = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(new InputStream[] { stream1, stream2, stream3 }, output, false); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> Crea un documento N‑Up dai due flussi PDF di input a outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream input1 = new FileInputStream(\"input1.pdf\"); InputStream input2 = new FileInputStream(\"input2.pdf\"); OutputStream output = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(input1, input2, output); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
<p> Crea un documento N‑Up dal flusso di input e salva il risultato nel flusso di output. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(inputStream, outputStream, 3, 3); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
<p> Crea un documento N‑Up dal primo flusso di input al flusso di output. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4); </pre>

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
<p> Crea un documento N‑Up dai file PDF di input multipli a outputFile. Ogni pagina di outputFile conterrà più pagine, che sono una combinazione delle pagine nei file di input con lo stesso numero di pagina. Le pagine multiple sono impilate orizzontalmente se isSidewise è true e verticalmente se isSidewise è false. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(new String[] { \"input1.pdf\", \"input2.pdf\", \"input3.pdf\" }, \"output.pdf\", false); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
<p> Crea un documento N‑Up dal firstInputFile al outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input.pdf\", \"output.pdf\", 3, 3); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
<p> Crea un documento N‑Up dal file di input al outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input.pdf\", \"output.pdf\", 3, 3, PageSize.A4); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
<p> Crea un documento N‑Up dai due file PDF di input a outputFile. Ogni pagina di outputFile conterrà due pagine, una proveniente dal primo file di input e l'altra dal secondo file di input. Le due pagine sono impilate orizzontalmente. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input1.pdf\", \"input2.pdf\", \"output.pdf\"); </pre>

### resizeContents {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ridimensiona le pagine del documento.

### resizeContents {#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ridimensiona le pagine del documento.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
<p> Ridimensiona il contenuto delle pagine del documento. Riduce il contenuto della pagina e aggiunge margini. La nuova dimensione del contenuto è specificata nelle unità di spazio predefinite. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileOutputStream(\"output.pdf\"); fileEditor.resizeContents(src, dest, //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre>

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ridimensiona il contenuto delle pagine del documento.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
<p> Ridimensiona il contenuto delle pagine del documento. Riduce il contenuto della pagina e aggiunge i margini. La nuova dimensione del contenuto è specificata nelle unità di spazio predefinite. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizeContents("input.pdf", "output.pdf", //ridimensiona tutte le pagine del documento null, //nuova larghezza del contenuto = 200 200, //nuova altezza del contenuto = 300 300); // l'area restante della pagina sarà vuota </pre>

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ridimensiona il contenuto delle pagine nel documento.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
<p> Ridimensiona il contenuto delle pagine del documento. Riduce il contenuto della pagina e aggiunge i margini. La nuova dimensione del contenuto è specificata in percentuale. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileOutputStream("output.pdf"); fileEditor.resizePct(src, dest, //ridimensiona tutte le pagine del documento null, //nuova larghezza del contenuto = 60% della dimensione iniziale 60, //nuova altezza del contenuto = 60% della dimensione iniziale 60); // L'area restante della pagina sarà vuota (margini della pagina). // Lo stesso per i margini superiore e inferiore. </pre>

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
<p> Ridimensiona il contenuto delle pagine del documento. Riduce il contenuto della pagina e aggiunge i margini. La nuova dimensione del contenuto è specificata in percentuale. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizePct("input.pdf", "output.pdf", //ridimensiona tutte le pagine del documento null, //nuova larghezza del contenuto = 60% della dimensione iniziale 60, //nuova altezza del contenuto = 60% della dimensione iniziale 60); // L'area restante della pagina sarà vuota (margini della pagina). // Lo stesso per i margini superiore e inferiore. </pre>

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ridimensiona le pagine del documento.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ridimensiona le pagine del documento.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
@Deprecated public void setAllowConcatenateExceptions(boolean value)
```

<p> Se impostato su true, le eccezioni vengono sollevate se si verifica un errore. Altrimenti le eccezioni non vengono sollevate e i metodi restituiscono false in caso di fallimento. </p>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre> @deprecated Questa proprietà è deprecata e non può essere usata per consentire il lancio di eccezioni. |

### setAttachmentName {#setAttachmentName-java.lang.String-}
Imposta il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpServletResponse come allegato.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams(boolean value)
```

<p> Se impostato su true, i flussi vengono chiusi dopo l'operazione. </p>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setCloseConcatenatedStreams (true); </pre> |

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
Imposta come verrà memorizzato il contenuto quando il risultato dell'operazione viene salvato nell'oggetto HttpServletResponse. Valori possibili: inline / attachment. Predefinito: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Imposta il formato del file PDF. Il file risultante verrà salvato nel formato specificato. Se questa proprietà non è specificata, il file verrà salvato nel formato PDF predefinito senza conversione.

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

Questa proprietà definisce il comportamento quando il processo di concatenazione incontra un file corrotto. I valori possibili sono: StopWithError e ConcatenateIgnoringCorrupted.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int @see ConcatenateCorruptedFileAction |

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

Se true, i nomi dei campi verranno resi unici quando i moduli sono concatenati. Verranno aggiunti suffissi ai nomi dei campi; il modello di suffisso può essere specificato nella proprietà UniqueSuffix.

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
Imposta la password del proprietario se il file Pdf di input è crittografato. Questa proprietà non è ancora implementata.

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
public final void setRemoveSignatures(boolean value)
```

Se vero, tutte le firme saranno rimosse dai campi (i campi rimarranno); altrimenti, potresti ottenere firme non valide.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Imposta le opzioni di salvataggio quando il risultato viene memorizzato come HttpServletResponse. Valore predefinito: PdfSaveOptions.

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
<p> Imposta il formato del suffisso che viene aggiunto al nome del campo per renderlo univoco quando i moduli sono concatenati. Questa stringa deve contenere la sottostringa %NUM% che verrà sostituita con numeri. Ad esempio, se UniqueSuffix = "ABC%NUM%" allora per il campo "fieldName" i nomi saranno: fieldNameABC1, fieldNameABC2, fieldNameABC3 ecc. </p> <hr> <pre> PdfFileEditor ed = new PdfFileEditor(); ed.setUniqueSuffix ( "_%NUM%"); </pre>

### setUseDiskBuffer {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer(boolean value)
```

Se questa opzione è utilizzata, il documento di destinazione verrà salvato su disco periodicamente e le successive concatenazioni verranno applicate come aggiornamenti incrementali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
<p> Divide dall'inizio fino alla posizione specificata e salva la parte anteriore nello Stream di output. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.splitFromFirst(sourceStream, 5, outStream); </pre> <hr> I flussi NON vengono chiusi dopo questa operazione.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
<p> Divide il file Pdf dalla prima pagina fino alla posizione specificata e salva la parte anteriore come nuovo file. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitFromFirst("input.pdf", 5, "out.pdf"); </pre>

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
Divide il file Pdf in diversi documenti. I documenti possono essere a pagina singola o multi-pagina.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
Divide il file Pdf in diversi documenti. I documenti possono essere a pagina singola o multi-pagina.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
<p> Divide dalla posizione specificata e salva la parte finale come nuovo Stream di file. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.splitToEnd(sourceStream, 5, outStream); </pre> <hr> I flussi NON vengono chiusi dopo questa operazione a meno che non sia specificato CloseConcatedStreams.

### splitToEnd {#splitToEnd-java.lang.String-int-java.lang.String-}
<p> Divide dalla posizione e salva la parte finale come nuovo file. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitToEnd("input.pdf", 5, "out.pdf"); </pre>

### splitToPages {#splitToPages-java.io.InputStream-}
Divide il file Pdf in documenti a pagina singola.

### splitToPages {#splitToPages-java.io.InputStream-java.lang.String-}
Dividi il file Pdf in documenti a pagina singola e salvalo nel percorso specificato.

### splitToPages {#splitToPages-java.lang.String-}
Dividi il file PDF in documenti a pagina singola.

### splitToPages {#splitToPages-java.lang.String-java.lang.String-}
Dividi il file Pdf in documenti a pagina singola e salvalo nel percorso specificato.
