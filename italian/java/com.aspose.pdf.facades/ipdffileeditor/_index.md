---
title: "IPdfFileEditor"
linktitle: "IPdfFileEditor"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Implementa operazioni sui file PDF: concatenazione, divisione, estrazione di pagine, creazione di opuscoli, ecc."
type: docs
weight: 290
url: /it/java/com.aspose.pdf.facades/ipdffileeditor/
---
```
public interface IPdfFileEditor
```

Implementa operazioni sui file PDF: concatenazione, divisione, estrazione di pagine, creazione di opuscoli, ecc.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Ridimensiona il contenuto della pagina e aggiunge i margini specificati. |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Ridimensiona il contenuto della pagina e aggiunge i margini specificati. |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Ridimensiona il contenuto della pagina e aggiunge i margini specificati. |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Ridimensiona il contenuto della pagina e aggiunge i margini specificati. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | Aggiunge pagine, scelte dall'array di documenti in portStreams. |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | Aggiunge pagine, scelte da portStream nell'intervallo da startPage a endPage, in portStream alla fine di firstInputStream. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | Aggiunge pagine, scelte dai documenti di portFiles. |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | Aggiunge pagine, scelte da portFile nell'intervallo da startPage a endPage, in portFile alla fine di firstInputFile. |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | Concatena documenti. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | Concatena file |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Unisce due documenti Pdf in un nuovo documento Pdf con le pagine alternate e riempie gli spazi vuoti con pagine bianche. |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Concatena due file. |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | Concatena file in un unico file. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | Concatena due file. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Unisce due documenti Pdf in un nuovo documento Pdf con le pagine alternate e riempie gli spazi vuoti con pagine bianche. |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | Elimina le pagine specificate da un array di numeri dal file di input, salvandole in un nuovo file Pdf. |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | Elimina le pagine specificate da un array di numeri dal file di input, salvandole in un nuovo file Pdf. |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | Estrae le pagine specificate da un array di numeri, salvandole in un nuovo file Pdf. |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | Estrae le pagine dal file di input, salvandole in un nuovo file Pdf. |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | Estrae le pagine specificate da un array di numeri, salvandole in un nuovo file PDF. |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | Estrae le pagine dal file di input, salvandole in un nuovo file Pdf. |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | è Consenti Concatenazione Eccezioni |
| [getAttachmentName](#getAttachmentName--) | Ottiene il nome dell'allegato quando il risultato dell'operazione è memorizzato negli oggetti HttpServletResponse come allegato. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | Se impostato su true, i flussi vengono chiusi dopo l'operazione. |
| [getContentDisposition](#getContentDisposition--) | Ottiene come verrà memorizzato il contenuto quando il risultato dell'operazione viene memorizzato nell'oggetto HttpServletResponse. |
| [getConversionLog](#getConversionLog--) | Ottiene il log del processo di conversione. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | Questa proprietà definisce il comportamento quando il processo di concatenazione incontra un file corrotto. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | Se true, gli aggiornamenti incrementali vengono eseguiti durante la concatenazione. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | Se true, i nomi dei campi saranno resi unici quando i moduli vengono concatenati. |
| [getLastException](#getLastException--) | Ottiene l'ultima eccezione verificatasi. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | I contenuti opzionali dei documenti concatenati con nomi uguali saranno uniti in un unico livello nel documento risultante se questa proprietà è true. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | Se true, i contorni duplicati vengono uniti. |
| [getOwnerPassword](#getOwnerPassword--) | Ottiene la password del proprietario se il file PDF di input di origine è crittografato. |
| [getPreserveUserRights](#getPreserveUserRights--) | Se vero, i diritti utente del primo documento vengono applicati al documento concatenato. |
| [getRemoveSignatures](#getRemoveSignatures--) | Se vero, tutte le firme saranno rimosse dai campi (i campi rimarranno); altrimenti, potresti ottenere firme non valide. |
| [getSaveOptions](#getSaveOptions--) | Ottiene o imposta le opzioni di salvataggio quando il risultato viene memorizzato come HttpServletResponse. |
| [getUniqueSuffix](#getUniqueSuffix--) | Ottiene il formato del suffisso che viene aggiunto al nome del campo per renderlo unico quando i moduli sono concatenati. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | Inserisce pagine da un altro file nel file PDF di input. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | Inserisce pagine da un altro file nel file PDF di input. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | Inserisce pagine da un altro file nel file PDF di input. |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | Inserisce pagine da un altro file nel file PDF in una posizione. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | Crea un libretto dallo InputStream verso outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | Crea un libretto personalizzato dal firstInputStream verso outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | Crea un libretto dallo stream di input e salva il risultato nello stream di output. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | Crea un libretto dal firstInputStream verso outputStream. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | Crea un libretto dal file di input verso file di output. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | Crea un libretto personalizzato dal firstInputFile verso outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | Crea un libretto dal inputFile verso outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | Crea un libretto personalizzato dal firstInputFile verso outputFile. |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | Crea un documento N-Up dai più stream PDF di input verso outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Crea un documento N-Up dai due stream PDF di input verso outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | Crea un documento N-Up dallo stream di input e salva il risultato nello stream di output. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | Crea un documento N-Up dal primo stream di input verso stream di output. |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | Crea un documento N-Up dai più file PDF di input verso outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | Crea un documento N-Up dal firstInputFile verso outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | Crea un documento N-Up dal file di input verso outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | Crea un documento N-Up dai due file PDF di input verso outputFile. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Ridimensiona i contenuti delle pagine del documento. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | Ridimensiona i contenuti delle pagine del documento. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Ridimensiona i contenuti delle pagine del documento. |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | Ridimensiona i contenuti delle pagine del documento. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | Se impostato su true, vengono generate eccezioni se si verifica un errore. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Imposta il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpServletResponse come allegato. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | Se impostato su true, i flussi vengono chiusi dopo l'operazione. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Imposta come verrà memorizzato il contenuto quando il risultato dell'operazione viene memorizzato nell'oggetto HttpServletResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Imposta il formato del file PDF. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | Questa proprietà definisce il comportamento quando il processo di concatenazione incontra un file corrotto. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | Se true, gli aggiornamenti incrementali vengono eseguiti durante la concatenazione. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | Se true, i nomi dei campi saranno resi unici quando i moduli vengono concatenati. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | I contenuti opzionali dei documenti concatenati con nomi uguali saranno uniti in un unico livello nel documento risultante se questa proprietà è true. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | Se true, i contorni duplicati vengono uniti. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | Imposta la password del proprietario se il file PDF di input di origine è crittografato. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | Se vero, i diritti utente del primo documento vengono applicati al documento concatenato. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | Se vero, tutte le firme saranno rimosse dai campi (i campi rimarranno); altrimenti, potresti ottenere firme non valide. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Imposta le opzioni di salvataggio quando il risultato viene memorizzato come HttpServletResponse. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | Imposta il formato del suffisso che viene aggiunto al nome del campo per renderlo univoco quando i moduli sono concatenati. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | Dividi dall'inizio fino alla posizione specificata e salva la parte anteriore nello Stream di output. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | Dividi il file PDF dalla prima pagina fino alla posizione specificata e salva la parte anteriore come nuovo file. |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | Divide il file Pdf in diversi documenti. I documenti possono essere a pagina singola o multi-pagina. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | Divide il file Pdf in diversi documenti. I documenti possono essere a pagina singola o multi-pagina. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | Dividi dalla posizione specificata e salva la parte posteriore come nuovo Stream di file. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | Dividi dalla posizione e salva la parte posteriore come nuovo file. |
| [splitToPages](#splitToPages-java.io.InputStream-) | Divide il file Pdf in documenti a pagina singola. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | Dividi il file Pdf in documenti a pagina singola e salvalo nel percorso specificato. |
| [splitToPages](#splitToPages-java.lang.String-) | Dividi il file PDF in documenti a pagina singola. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | Dividi il file Pdf in documenti a pagina singola e salvalo nel percorso specificato. |

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Ridimensiona il contenuto della pagina e aggiunge i margini specificati.

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Ridimensiona il contenuto della pagina e aggiunge i margini specificati.

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Ridimensiona il contenuto della pagina e aggiunge i margini specificati.

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Ridimensiona il contenuto della pagina e aggiunge i margini specificati.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
Aggiunge pagine, scelte dall'array di documenti in portStreams.

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
Aggiunge pagine, scelte da portStream nell'intervallo da startPage a endPage, in portStream alla fine di firstInputStream.

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
Aggiunge pagine, scelte dai documenti di portFiles.

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
Aggiunge pagine, scelte da portFile nell'intervallo da startPage a endPage, in portFile alla fine di firstInputFile.

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
Concatena documenti.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
Concatena file

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Unisce due documenti Pdf in un nuovo documento Pdf con le pagine alternate e riempie gli spazi vuoti con pagine bianche.

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Concatena due file.

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
Concatena file in un unico file.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
Concatena due file.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Unisce due documenti Pdf in un nuovo documento Pdf con le pagine alternate e riempie gli spazi vuoti con pagine bianche.

### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
Elimina le pagine specificate da un array di numeri dal file di input, salvandole in un nuovo file Pdf.

### delete {#delete-java.lang.String-int:A-java.lang.String-}
Elimina le pagine specificate da un array di numeri dal file di input, salvandole in un nuovo file Pdf.

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
Estrae le pagine specificate da un array di numeri, salvandole in un nuovo file Pdf.

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
Estrae le pagine dal file di input, salvandole in un nuovo file Pdf.

### extract {#extract-java.lang.String-int:A-java.lang.String-}
Estrae le pagine specificate da un array di numeri, salvandole in un nuovo file PDF.

### extract {#extract-java.lang.String-int-int-java.lang.String-}
Estrae le pagine dal file di input, salvandole in un nuovo file Pdf.

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
boolean getAllowConcatenateExceptions()
```

è Consenti Concatenazione Eccezioni

**Returns:**
valore booleano

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Ottiene il nome dell'allegato quando il risultato dell'operazione è memorizzato negli oggetti HttpServletResponse come allegato.

**Returns:**
valore stringa

### getCloseConcatenatedStreams {#getCloseConcatenatedStreams--}
```
boolean getCloseConcatenatedStreams()
```

Se impostato su true, i flussi vengono chiusi dopo l'operazione.

**Returns:**
valore booleano

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

Ottiene come verrà memorizzato il contenuto quando il risultato dell'operazione viene memorizzato nell'oggetto HttpServletResponse.

**Returns:**
Elemento ContentDisposition

### getConversionLog {#getConversionLog--}
```
String getConversionLog()
```

Ottiene il log del processo di conversione.

**Returns:**
valore stringa

### getCorruptedFileAction {#getCorruptedFileAction--}
```
int getCorruptedFileAction()
```

Questa proprietà definisce il comportamento quando il processo di concatenazione incontra un file corrotto.

**Returns:**
Elemento ConcatenateCorruptedFileAction

### getIncrementalUpdates {#getIncrementalUpdates--}
```
boolean getIncrementalUpdates()
```

Se true, gli aggiornamenti incrementali vengono eseguiti durante la concatenazione.

**Returns:**
valore booleano

### getKeepFieldsUnique {#getKeepFieldsUnique--}
```
boolean getKeepFieldsUnique()
```

Se true, i nomi dei campi saranno resi unici quando i moduli vengono concatenati.

**Returns:**
valore booleano

### getLastException {#getLastException--}
```
Exception getLastException()
```

Ottiene l'ultima eccezione verificatasi.

**Returns:**
oggetto java.lang.Exception

### getMergeDuplicateLayers {#getMergeDuplicateLayers--}
```
boolean getMergeDuplicateLayers()
```

I contenuti opzionali dei documenti concatenati con nomi uguali saranno uniti in un unico livello nel documento risultante se questa proprietà è true.

**Returns:**
valore booleano

### getMergeDuplicateOutlines {#getMergeDuplicateOutlines--}
```
boolean getMergeDuplicateOutlines()
```

Se true, i contorni duplicati vengono uniti.

**Returns:**
valore booleano

### getOwnerPassword {#getOwnerPassword--}
```
String getOwnerPassword()
```

Ottiene la password del proprietario se il file PDF di input di origine è crittografato.

**Returns:**
valore stringa

### getPreserveUserRights {#getPreserveUserRights--}
```
boolean getPreserveUserRights()
```

Se vero, i diritti utente del primo documento vengono applicati al documento concatenato.

**Returns:**
valore booleano

### getRemoveSignatures {#getRemoveSignatures--}
```
boolean getRemoveSignatures()
```

Se vero, tutte le firme saranno rimosse dai campi (i campi rimarranno); altrimenti, potresti ottenere firme non valide.

**Returns:**
valore booleano

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Ottiene o imposta le opzioni di salvataggio quando il risultato viene memorizzato come HttpServletResponse.

**Returns:**
oggetto SaveOptions

### getUniqueSuffix {#getUniqueSuffix--}
```
String getUniqueSuffix()
```

Ottiene il formato del suffisso che viene aggiunto al nome del campo per renderlo unico quando i moduli sono concatenati.

**Returns:**
valore stringa

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
Inserisce pagine da un altro file nel file PDF di input.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
Inserisce pagine da un altro file nel file PDF di input.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
Inserisce pagine da un altro file nel file PDF di input.

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
Inserisce pagine da un altro file nel file PDF in una posizione.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
Crea un libretto dallo InputStream verso outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
Crea un libretto personalizzato dal firstInputStream verso outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
Crea un libretto dallo stream di input e salva il risultato nello stream di output.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
Crea un libretto dal firstInputStream verso outputStream.

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

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
Crea un documento N-Up dallo stream di input e salva il risultato nello stream di output.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
Crea un documento N-Up dal primo stream di input verso stream di output.

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
Crea un documento N-Up dai più file PDF di input verso outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
Crea un documento N-Up dal firstInputFile verso outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
Crea un documento N-Up dal file di input verso outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
Crea un documento N-Up dai due file PDF di input verso outputFile.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Ridimensiona i contenuti delle pagine del documento.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
Ridimensiona i contenuti delle pagine del documento.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Ridimensiona i contenuti delle pagine del documento.

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
Ridimensiona i contenuti delle pagine del documento.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
void setAllowConcatenateExceptions(boolean value)
```

Se impostato su true, vengono generate eccezioni se si verifica un errore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setAttachmentName {#setAttachmentName-java.lang.String-}
Imposta il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpServletResponse come allegato.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
void setCloseConcatenatedStreams(boolean value)
```

Se impostato su true, i flussi vengono chiusi dopo l'operazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Imposta come verrà memorizzato il contenuto quando il risultato dell'operazione viene memorizzato nell'oggetto HttpServletResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Imposta il formato del file PDF.

### setCorruptedFileAction {#setCorruptedFileAction-int-}
```
void setCorruptedFileAction(int value)
```

Questa proprietà definisce il comportamento quando il processo di concatenazione incontra un file corrotto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento ConcatenateCorruptedFileAction |

### setIncrementalUpdates {#setIncrementalUpdates-boolean-}
```
void setIncrementalUpdates(boolean value)
```

Se true, gli aggiornamenti incrementali vengono eseguiti durante la concatenazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setKeepFieldsUnique {#setKeepFieldsUnique-boolean-}
```
void setKeepFieldsUnique(boolean value)
```

Se true, i nomi dei campi saranno resi unici quando i moduli vengono concatenati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setMergeDuplicateLayers {#setMergeDuplicateLayers-boolean-}
```
void setMergeDuplicateLayers(boolean value)
```

I contenuti opzionali dei documenti concatenati con nomi uguali saranno uniti in un unico livello nel documento risultante se questa proprietà è true.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setMergeDuplicateOutlines {#setMergeDuplicateOutlines-boolean-}
```
void setMergeDuplicateOutlines(boolean value)
```

Se true, i contorni duplicati vengono uniti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setOwnerPassword {#setOwnerPassword-java.lang.String-}
Imposta la password del proprietario se il file PDF di input di origine è crittografato.

### setPreserveUserRights {#setPreserveUserRights-boolean-}
```
void setPreserveUserRights(boolean value)
```

Se vero, i diritti utente del primo documento vengono applicati al documento concatenato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setRemoveSignatures {#setRemoveSignatures-boolean-}
```
void setRemoveSignatures(boolean value)
```

Se vero, tutte le firme saranno rimosse dai campi (i campi rimarranno); altrimenti, potresti ottenere firme non valide.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Imposta le opzioni di salvataggio quando il risultato viene memorizzato come HttpServletResponse.

### setUniqueSuffix {#setUniqueSuffix-java.lang.String-}
Imposta il formato del suffisso che viene aggiunto al nome del campo per renderlo univoco quando i moduli sono concatenati.

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
Dividi dall'inizio fino alla posizione specificata e salva la parte anteriore nello Stream di output.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
Dividi il file PDF dalla prima pagina fino alla posizione specificata e salva la parte anteriore come nuovo file.

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
Divide il file Pdf in diversi documenti. I documenti possono essere a pagina singola o multi-pagina.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
Divide il file Pdf in diversi documenti. I documenti possono essere a pagina singola o multi-pagina.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
Dividi dalla posizione specificata e salva la parte posteriore come nuovo Stream di file.

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
