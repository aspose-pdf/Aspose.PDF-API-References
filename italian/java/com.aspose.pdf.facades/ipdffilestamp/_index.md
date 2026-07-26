---
title: "IPdfFileStamp"
linktitle: "IPdfFileStamp"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Interfaccia per aggiungere timbri (filigrana o sfondo) ai file PDF."
type: docs
weight: 320
url: /it/java/com.aspose.pdf.facades/ipdffilestamp/
---
```
public interface IPdfFileStamp
```

Interfaccia per aggiungere timbri (filigrana o sfondo) ai file PDF.

## Campi

| Campo | Descrizione |
| --- | --- |
| [POS_BOTTOM_LEFT](#POS_BOTTOM_LEFT) | Posizione in basso a sinistra. |
| [POS_BOTTOM_MIDDLE](#POS_BOTTOM_MIDDLE) | Posizione in basso al centro. |
| [POS_BOTTOM_RIGHT](#POS_BOTTOM_RIGHT) | Posizione in basso a destra. |
| [POS_SIDES_LEFT](#POS_SIDES_LEFT) | Posizione a sinistra. |
| [POS_SIDES_RIGHT](#POS_SIDES_RIGHT) | Posizione a destra. |
| [POS_UPPER_LEFT](#POS_UPPER_LEFT) | Posizione in alto a sinistra. |
| [POS_UPPER_MIDDLE](#POS_UPPER_MIDDLE) | Posizione al centro superiore. |
| [POS_UPPER_RIGHT](#POS_UPPER_RIGHT) | Posizione in alto a destra. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | Aggiunge il piè di pagina alle pagine del documento. |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | Aggiunge il piè di pagina alle pagine del documento. |
| [addFooter](#addFooter-java.io.InputStream-float-) | Aggiunge l'immagine come piè di pagina della pagina. |
| [addFooter](#addFooter-java.io.InputStream-float-float-float-) | Aggiunge l'immagine come piè di pagina della pagina. |
| [addFooter](#addFooter-java.lang.String-float-) | Aggiunge l'immagine come piè di pagina alle pagine del documento. |
| [addFooter](#addFooter-java.lang.String-float-float-float-) | Aggiunge l'immagine come piè di pagina delle pagine. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | Aggiunge l'intestazione alla pagina. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | Aggiunge l'intestazione alle pagine del file. |
| [addHeader](#addHeader-java.io.InputStream-float-) | Aggiunge l'immagine come intestazione sulle pagine. |
| [addHeader](#addHeader-java.io.InputStream-float-float-float-) | Aggiunge l'immagine nella parte superiore della pagina. |
| [addHeader](#addHeader-java.lang.String-float-) | Aggiunge l'immagine come intestazione alle pagine del file. |
| [addHeader](#addHeader-java.lang.String-float-float-float-) | Aggiunge l'immagine come intestazione sulle pagine. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | Aggiunge il numero di pagina alla pagina. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | Aggiunge il numero di pagina nella posizione specificata sulla pagina. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | Aggiunge il numero di pagina alle pagine. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | Aggiunge il numero di pagina alle pagine del documento. |
| [addPageNumber](#addPageNumber-java.lang.String-) | Aggiungi il numero di pagina al file. |
| [addPageNumber](#addPageNumber-java.lang.String-float-float-) | Aggiunge il numero di pagina nella posizione specificata sulla pagina. |
| [addPageNumber](#addPageNumber-java.lang.String-int-) | Aggiunge il numero di pagina alle pagine. |
| [addPageNumber](#addPageNumber-java.lang.String-int-float-float-float-float-) | Aggiunge il numero di pagina alle pagine del documento. |
| [addStamp](#addStamp-com.aspose.pdf.facades.Stamp-) | Aggiunge il timbro al file. |
| [close](#close--) | Chiude i file aperti e salva le modifiche. |
| [dispose](#dispose--) | Obsoleto. |
| [getAttachmentName](#getAttachmentName--) | Ottiene il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpResponse come allegato. |
| [getContentDisposition](#getContentDisposition--) | Ottiene come il contenuto sarà memorizzato quando il risultato dell'operazione viene memorizzato nell'oggetto HttpResponse. |
| [getDocument](#getDocument--) | Ottiene il documento su cui PdfFileStamp sta lavorando. |
| [getInputFile](#getInputFile--) | Ottiene il nome e il percorso del file di input. |
| [getInputStream](#getInputStream--) | Ottiene lo stream di input. |
| [getKeepSecurity](#getKeepSecurity--) | Mantiene la sicurezza se vero. |
| [getOutputFile](#getOutputFile--) | Ottiene il nome e il percorso del file di output. |
| [getOutputStream](#getOutputStream--) | Ottiene lo stream di output. |
| [getPageHeight](#getPageHeight--) | Ottiene l'altezza della prima pagina nel file di origine. |
| [getPageNumberRotation](#getPageNumberRotation--) | Ottiene la rotazione del numero di pagina. |
| [getPageWidth](#getPageWidth--) | Ottiene la larghezza della prima pagina nel file di input. |
| [getSaveOptions](#getSaveOptions--) | Ottiene le opzioni di salvataggio quando il risultato è memorizzato come HttpResponse. |
| [getStartingNumber](#getStartingNumber--) | Ottiene o imposta il numero iniziale per la prima pagina nel file di input. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Imposta il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpResponse come allegato. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Imposta come il contenuto verrà memorizzato quando il risultato dell'operazione è salvato nell'oggetto HttpResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Imposta il formato del file PDF. |
| [setInputFile](#setInputFile-java.lang.String-) | Imposta il nome e il percorso del file di input. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Imposta lo stream di input. |
| [setKeepSecurity](#setKeepSecurity-boolean-) | Imposta Mantieni Sicurezza |
| [setOutputFile](#setOutputFile-java.lang.String-) | Imposta il nome e il percorso del file di output. |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Imposta o imposta lo stream di output. |
| [setPageNumberRotation](#setPageNumberRotation-float-) | Imposta la rotazione del numero di pagina. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Imposta le opzioni di salvataggio quando il risultato è memorizzato come HttpResponse. |
| [setStartingNumber](#setStartingNumber-int-) | Imposta il numero iniziale per la prima pagina nel file di input. |

### POS_BOTTOM_LEFT {#POS_BOTTOM_LEFT}
```
static final int POS_BOTTOM_LEFT
```

Posizione in basso a sinistra.

### POS_BOTTOM_MIDDLE {#POS_BOTTOM_MIDDLE}
```
static final int POS_BOTTOM_MIDDLE
```

Posizione in basso al centro.

### POS_BOTTOM_RIGHT {#POS_BOTTOM_RIGHT}
```
static final int POS_BOTTOM_RIGHT
```

Posizione in basso a destra.

### POS_SIDES_LEFT {#POS_SIDES_LEFT}
```
static final int POS_SIDES_LEFT
```

Posizione a sinistra.

### POS_SIDES_RIGHT {#POS_SIDES_RIGHT}
```
static final int POS_SIDES_RIGHT
```

Posizione a destra.

### POS_UPPER_LEFT {#POS_UPPER_LEFT}
```
static final int POS_UPPER_LEFT
```

Posizione in alto a sinistra.

### POS_UPPER_MIDDLE {#POS_UPPER_MIDDLE}
```
static final int POS_UPPER_MIDDLE
```

Posizione al centro superiore.

### POS_UPPER_RIGHT {#POS_UPPER_RIGHT}
```
static final int POS_UPPER_RIGHT
```

Posizione in alto a destra.

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
Aggiunge il piè di pagina alle pagine del documento.

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
Aggiunge il piè di pagina alle pagine del documento.

### addFooter {#addFooter-java.io.InputStream-float-}
Aggiunge l'immagine come piè di pagina della pagina.

### addFooter {#addFooter-java.io.InputStream-float-float-float-}
Aggiunge l'immagine come piè di pagina della pagina.

### addFooter {#addFooter-java.lang.String-float-}
Aggiunge l'immagine come piè di pagina alle pagine del documento.

### addFooter {#addFooter-java.lang.String-float-float-float-}
Aggiunge l'immagine come piè di pagina delle pagine.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
Aggiunge l'intestazione alla pagina.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
Aggiunge l'intestazione alle pagine del file.

### addHeader {#addHeader-java.io.InputStream-float-}
Aggiunge l'immagine come intestazione sulle pagine.

### addHeader {#addHeader-java.io.InputStream-float-float-float-}
Aggiunge l'immagine nella parte superiore della pagina.

### addHeader {#addHeader-java.lang.String-float-}
Aggiunge l'immagine come intestazione alle pagine del file.

### addHeader {#addHeader-java.lang.String-float-float-float-}
Aggiunge l'immagine come intestazione sulle pagine.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
Aggiunge il numero di pagina alla pagina.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
Aggiunge il numero di pagina nella posizione specificata sulla pagina.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
Aggiunge il numero di pagina alle pagine.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
Aggiunge il numero di pagina alle pagine del documento.

### addPageNumber {#addPageNumber-java.lang.String-}
Aggiungi il numero di pagina al file.

### addPageNumber {#addPageNumber-java.lang.String-float-float-}
Aggiunge il numero di pagina nella posizione specificata sulla pagina.

### addPageNumber {#addPageNumber-java.lang.String-int-}
Aggiunge il numero di pagina alle pagine.

### addPageNumber {#addPageNumber-java.lang.String-int-float-float-float-float-}
Aggiunge il numero di pagina alle pagine del documento.

### addStamp {#addStamp-com.aspose.pdf.facades.Stamp-}
Aggiunge il timbro al file.

### close {#close--}
```
void close()
```

Chiude i file aperti e salva le modifiche.

### dispose {#dispose--}
```
@Deprecated void dispose()
```

Obsoleto.

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Ottiene il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpResponse come allegato.

**Returns:**
valore String

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

Ottiene come il contenuto sarà memorizzato quando il risultato dell'operazione viene memorizzato nell'oggetto HttpResponse.

**Returns:**
Elemento ContentDisposition

### getDocument {#getDocument--}
```
IDocument getDocument()
```

Ottiene il documento su cui PdfFileStamp sta lavorando.

**Returns:**
Oggetto IDocument

### getInputFile {#getInputFile--}
```
String getInputFile()
```

Ottiene il nome e il percorso del file di input.

**Returns:**
Oggetto stringa

### getInputStream {#getInputStream--}
```
InputStream getInputStream()
```

Ottiene lo stream di input.

**Returns:**
Oggetto InputStream

### getKeepSecurity {#getKeepSecurity--}
```
boolean getKeepSecurity()
```

Mantiene la sicurezza se vero.

**Returns:**
valore booleano

### getOutputFile {#getOutputFile--}
```
String getOutputFile()
```

Ottiene il nome e il percorso del file di output.

**Returns:**
Oggetto stringa

### getOutputStream {#getOutputStream--}
```
OutputStream getOutputStream()
```

Ottiene lo stream di output.

**Returns:**
oggetto OutputStream

### getPageHeight {#getPageHeight--}
```
float getPageHeight()
```

Ottiene l'altezza della prima pagina nel file di origine.

**Returns:**
valore float

### getPageNumberRotation {#getPageNumberRotation--}
```
float getPageNumberRotation()
```

Ottiene la rotazione del numero di pagina.

**Returns:**
valore float

### getPageWidth {#getPageWidth--}
```
float getPageWidth()
```

Ottiene la larghezza della prima pagina nel file di input.

**Returns:**
valore float

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Ottiene le opzioni di salvataggio quando il risultato è memorizzato come HttpResponse.

**Returns:**
oggetto SaveOptions

### getStartingNumber {#getStartingNumber--}
```
int getStartingNumber()
```

Ottiene o imposta il numero iniziale per la prima pagina nel file di input.

**Returns:**
valore int

### setAttachmentName {#setAttachmentName-java.lang.String-}
Imposta il nome dell'allegato quando il risultato dell'operazione viene memorizzato negli oggetti HttpResponse come allegato.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Imposta come il contenuto verrà memorizzato quando il risultato dell'operazione è salvato nell'oggetto HttpResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Imposta il formato del file PDF.

### setInputFile {#setInputFile-java.lang.String-}
Imposta il nome e il percorso del file di input.

### setInputStream {#setInputStream-java.io.InputStream-}
Imposta lo stream di input.

### setKeepSecurity {#setKeepSecurity-boolean-}
```
void setKeepSecurity(boolean value)
```

Imposta Mantieni Sicurezza

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setOutputFile {#setOutputFile-java.lang.String-}
Imposta il nome e il percorso del file di output.

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Imposta o imposta lo stream di output.

### setPageNumberRotation {#setPageNumberRotation-float-}
```
void setPageNumberRotation(float value)
```

Imposta la rotazione del numero di pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Imposta le opzioni di salvataggio quando il risultato è memorizzato come HttpResponse.

### setStartingNumber {#setStartingNumber-int-}
```
void setStartingNumber(int value)
```

Imposta il numero iniziale per la prima pagina nel file di input.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |
