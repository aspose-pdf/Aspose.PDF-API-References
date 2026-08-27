---
title: "PdfFileInfo"
linktitle: "PdfFileInfo"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe per accedere alle meta‑informazioni del documento PDF."
type: docs
weight: 490
url: /it/java/com.aspose.pdf.facades/pdffileinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileInfo, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileInfo, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileInfo

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileInfo extends SaveableFacade
```

Rappresenta una classe per accedere alle meta‑informazioni del documento PDF.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfFileInfo](#PdfFileInfo--) | Inizializza una nuova istanza della classe com.aspose.pdf.facades.PdfFileInfo con valori predefiniti. |
| [PdfFileInfo](#PdfFileInfo-com.aspose.pdf.IDocument-) | Inizializza una nuova istanza della classe com.aspose.pdf.facades.PdfFileInfo con valori predefiniti. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-) | Inizializza una nuova istanza della classe com.aspose.pdf.facades.PdfFileInfo con valori predefiniti. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-java.lang.String-) | Inizializza una nuova istanza della classe com.aspose.pdf.facades.PdfFileInfo con valori predefiniti. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Inizializza una nuova istanza della classe com.aspose.pdf.facades.PdfFileInfo con valori predefiniti. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-) | Inizializza una nuova istanza della classe com.aspose.pdf.facades.PdfFileInfo con valori predefiniti. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-java.lang.String-) | Inizializza una nuova istanza della classe com.aspose.pdf.facades.PdfFileInfo con valori predefiniti. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Inizializza una nuova istanza della classe com.aspose.pdf.facades.PdfFileInfo con valori predefiniti. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | Inizializza la facciata. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Inizializza la facciata. |
| [clearInfo](#clearInfo--) | Cancella tutte le meta informazioni del documento PDF. |
| [close](#close--) | Chiude tutte le risorse utilizzate da questo documento. |
| [dispose](#dispose--) | Chiude tutte le risorse utilizzate da questa istanza. Questo metodo è obsoleto, usa close() invece. |
| [getAuthor](#getAuthor--) | Ottiene le informazioni sull'Autore del documento PDF. |
| [getCreationDate](#getCreationDate--) | Ottiene le informazioni su CreationDate del documento PDF. |
| [getCreator](#getCreator--) | Ottiene le informazioni sul Creator del documento PDF. |
| [getDocumentPrivilege](#getDocumentPrivilege--) | Ottiene le impostazioni dei privilegi del documento PDF. |
| [getHeader](#getHeader--) | <p> Ottiene le informazioni personalizzate del documento PDF. </p> |
| [getInputFile](#getInputFile--) | Ottiene il file di input. |
| [getInputStream](#getInputStream--) | Ottiene lo stream di input. |
| [getKeywords](#getKeywords--) | Ottiene le informazioni delle parole chiave del documento PDF. |
| [getMetaInfo](#getMetaInfo-java.lang.String-) | Ottiene le informazioni personalizzate del documento PDF con il nome della proprietà. Se non esiste alcuna proprietà corrispondente al nome, restituirà una stringa vuota. |
| [getModDate](#getModDate--) | Ottiene le informazioni della data ModDate del documento PDF. |
| [getNumberOfPages](#getNumberOfPages--) | Ottiene il numero di pagine del documento. |
| [getPageHeight](#getPageHeight-int-) | Ottiene l'altezza della pagina specificata. |
| [getPageRotation](#getPageRotation-int-) | Ottiene la rotazione della pagina specificata. |
| [getPageWidth](#getPageWidth-int-) | Ottiene la larghezza della pagina specificata. |
| [getPageXOffset](#getPageXOffset-int-) | Ottiene l'offset orizzontale dell'area di visualizzazione della pagina specificata. |
| [getPageYOffset](#getPageYOffset-int-) | Ottiene l'offset verticale dell'area di visualizzazione della pagina specificata. |
| [getPasswordType](#getPasswordType--) | Restituisce il tipo di password passato per creare l'istanza PdfFileInfo. Vedi i valori possibili in {@code PasswordType}. Nota che il documento PDF può essere aperto sia con la password utente (o di apertura) sia con la password proprietario (o di permessi, modifica). |
| [getPdfVersion](#getPdfVersion--) | Ottiene le informazioni sulla versione del documento PDF. |
| [getProducer](#getProducer--) | Ottiene le informazioni sul produttore del documento PDF. |
| [getSubject](#getSubject--) | Ottiene le informazioni sull'oggetto del documento PDF. |
| [getTitle](#getTitle--) | Ottiene le informazioni sul titolo del documento PDF. |
| [getUseStrictValidation](#getUseStrictValidation--) | Utilizza regole di validazione rigorose tramite la proprietà {@code IsPdfFile}({@link #isPdfFile}). |
| [hasCollection](#hasCollection--) | Restituisce true se il file di input corrente è un file 'Portfolio' che contiene una collezione di file PDF. |
| [hasEditPassword](#hasEditPassword--) | Restituisce true se è necessaria una password per modificare i permessi o la proprietà di sicurezza del documento. Nota che questa proprietà può essere letta solo se è stata fornita una password valida nel costruttore {@code PdfFileInfo}. Nel caso in cui PasswordType sia Inaccessible (significa che è stata fornita una password non valida) la lettura di questa proprietà fallirà con {@code InvalidPasswordException}. |
| [hasOpenPassword](#hasOpenPassword--) | Restituisce true se è necessaria una password per aprire un documento PDF protetto da password. |
| [isEncrypted](#isEncrypted--) | Verifica se il documento PDF è crittografato. |
| [isPdfFile](#isPdfFile--) | Verifica se l'input di origine è un file PDF valido. |
| [save](#save-java.io.OutputStream-) | Salva il documento PDF nel file specificato. |
| [saveNewInfo](#saveNewInfo-java.io.OutputStream-) | Salva il documento PDF aggiornato nello stream specificato. |
| [saveNewInfo](#saveNewInfo-java.lang.String-) | Salva il documento PDF aggiornato nel file specificato. |
| [saveNewInfoWithXmp](#saveNewInfoWithXmp-java.lang.String-) | Modifica le proprietà specificate esplicitamente impostando le informazioni del file, le altre proprietà rimangono. |
| [setAuthor](#setAuthor-java.lang.String-) | Imposta le informazioni dell'Autore del documento PDF. |
| [setCreationDate](#setCreationDate-java.lang.String-) | Imposta le informazioni della Data di Creazione del documento PDF. |
| [setCreator](#setCreator-java.lang.String-) | Imposta le informazioni del Creatore del documento PDF. |
| [setHeader](#setHeader-java.util.Map-) | Imposta le informazioni personalizzate del documento PDF. |
| [setInputFile](#setInputFile-java.lang.String-) | Imposta il file di input. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Imposta lo stream di input. |
| [setKeywords](#setKeywords-java.lang.String-) | Imposta le informazioni delle Parole chiave del documento PDF. |
| [setMetaInfo](#setMetaInfo-java.lang.String-java.lang.String-) | Imposta le informazioni personalizzate del documento PDF. |
| [setModDate](#setModDate-java.lang.String-) | Imposta le informazioni della data ModDate del documento PDF. |
| [setSubject](#setSubject-java.lang.String-) | Imposta le informazioni dell'Oggetto del documento PDF. |
| [setTitle](#setTitle-java.lang.String-) | Imposta le informazioni del Titolo del documento PDF. |
| [setUseStrictValidation](#setUseStrictValidation-boolean-) | Utilizza regole di validazione rigorose tramite la proprietà {@code IsPdfFile}({@link #isPdfFile}). |

### PdfFileInfo {#PdfFileInfo--}
```
public PdfFileInfo()
```

Inizializza una nuova istanza della classe com.aspose.pdf.facades.PdfFileInfo con valori predefiniti.

### PdfFileInfo {#PdfFileInfo-com.aspose.pdf.IDocument-}
Inizializza una nuova istanza della classe com.aspose.pdf.facades.PdfFileInfo con valori predefiniti.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-}
Inizializza una nuova istanza della classe com.aspose.pdf.facades.PdfFileInfo con valori predefiniti.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-java.lang.String-}
Inizializza una nuova istanza della classe com.aspose.pdf.facades.PdfFileInfo con valori predefiniti.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Inizializza una nuova istanza della classe com.aspose.pdf.facades.PdfFileInfo con valori predefiniti.

### PdfFileInfo {#PdfFileInfo-java.lang.String-}
Inizializza una nuova istanza della classe com.aspose.pdf.facades.PdfFileInfo con valori predefiniti.

### PdfFileInfo {#PdfFileInfo-java.lang.String-java.lang.String-}
Inizializza una nuova istanza della classe com.aspose.pdf.facades.PdfFileInfo con valori predefiniti.

### PdfFileInfo {#PdfFileInfo-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Inizializza una nuova istanza della classe com.aspose.pdf.facades.PdfFileInfo con valori predefiniti.

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
Inizializza la facciata.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Inizializza la facciata.

### clearInfo {#clearInfo--}
```
public void clearInfo()
```

Cancella tutte le meta informazioni del documento PDF.

### close {#close--}
```
public void close()
```

Chiude tutte le risorse utilizzate da questo documento.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Chiude tutte le risorse utilizzate da questa istanza. Questo metodo è obsoleto, usa close() invece.

### getAuthor {#getAuthor--}
```
public String getAuthor()
```

Ottiene le informazioni sull'Autore del documento PDF.

**Returns:**
valore String

### getCreationDate {#getCreationDate--}
```
public String getCreationDate()
```

Ottiene le informazioni su CreationDate del documento PDF.

**Returns:**
valore String

### getCreator {#getCreator--}
```
public String getCreator()
```

Ottiene le informazioni sul Creator del documento PDF.

**Returns:**
valore String

### getDocumentPrivilege {#getDocumentPrivilege--}
```
public DocumentPrivilege getDocumentPrivilege()
```

Ottiene le impostazioni dei privilegi del documento PDF.

**Returns:**
Le impostazioni dei privilegi del documento PDF.

### getHeader {#getHeader--}
```
public Map < String , String > getHeader()
```

<p> Ottiene le informazioni personalizzate del documento PDF. </p>

**Returns:**
{@code Map<String, String>} oggetto

### getInputFile {#getInputFile--}
```
@Deprecated public String getInputFile()
```

Ottiene il file di input.

**Returns:**
valore String

### getInputStream {#getInputStream--}
```
@Deprecated public InputStream getInputStream()
```

Ottiene lo stream di input.

**Returns:**
Oggetto InputStream

### getKeywords {#getKeywords--}
```
public String getKeywords()
```

Ottiene le informazioni delle parole chiave del documento PDF.

**Returns:**
valore String

### getMetaInfo {#getMetaInfo-java.lang.String-}
Ottiene le informazioni personalizzate del documento PDF con il nome della proprietà. Se non esiste alcuna proprietà corrispondente al nome, restituirà una stringa vuota.

### getModDate {#getModDate--}
```
public String getModDate()
```

Ottiene le informazioni della data ModDate del documento PDF.

**Returns:**
valore String

### getNumberOfPages {#getNumberOfPages--}
```
public int getNumberOfPages()
```

Ottiene il numero di pagine del documento.

**Returns:**
valore int

### getPageHeight {#getPageHeight-int-}
```
public float getPageHeight(int pageNum)
```

Ottiene l'altezza della pagina specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNum |  | Numero di pagina. |

**Returns:**
L'altezza della pagina.

### getPageRotation {#getPageRotation-int-}
```
public int getPageRotation(int pageNum)
```

Ottiene la rotazione della pagina specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNum |  | Numero di pagina. |

**Returns:**
La rotazione della pagina. Il valore può essere 0,90,180,270.

### getPageWidth {#getPageWidth-int-}
```
public float getPageWidth(int pageNum)
```

Ottiene la larghezza della pagina specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNum |  | Numero di pagina. |

**Returns:**
La larghezza della pagina.

### getPageXOffset {#getPageXOffset-int-}
```
public float getPageXOffset(int pageNum)
```

Ottiene l'offset orizzontale dell'area di visualizzazione della pagina specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNum |  | Numero di pagina. |

**Returns:**
L'offset orizzontale dal lato sinistro della pagina.

### getPageYOffset {#getPageYOffset-int-}
```
public float getPageYOffset(int pageNum)
```

Ottiene l'offset verticale dell'area di visualizzazione della pagina specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNum |  | Numero di pagina. |

**Returns:**
L'offset verticale dell'area di visualizzazione della pagina.

### getPasswordType {#getPasswordType--}
```
public PasswordType getPasswordType()
```

Restituisce il tipo di password passato per creare l'istanza PdfFileInfo. Vedi i valori possibili in {@code PasswordType}. Nota che il documento PDF può essere aperto sia con la password utente (o di apertura) sia con la password proprietario (o di permessi, modifica).

**Returns:**
Elemento PasswordType @see PasswordType

### getPdfVersion {#getPdfVersion--}
```
public String getPdfVersion()
```

Ottiene le informazioni sulla versione del documento PDF.

**Returns:**
La stringa di versione.

### getProducer {#getProducer--}
```
public String getProducer()
```

Ottiene le informazioni sul produttore del documento PDF.

**Returns:**
valore String

### getSubject {#getSubject--}
```
public String getSubject()
```

Ottiene le informazioni sull'oggetto del documento PDF.

**Returns:**
valore String

### getTitle {#getTitle--}
```
public String getTitle()
```

Ottiene le informazioni sul titolo del documento PDF.

**Returns:**
valore String

### getUseStrictValidation {#getUseStrictValidation--}
```
public final boolean getUseStrictValidation()
```

Utilizza regole di validazione rigorose tramite la proprietà {@code IsPdfFile}({@link #isPdfFile}).

**Returns:**
valore booleano

### hasCollection {#hasCollection--}
```
public boolean hasCollection()
```

Restituisce true se il file di input corrente è un file 'Portfolio' che contiene una collezione di file PDF.

**Returns:**
valore booleano

### hasEditPassword {#hasEditPassword--}
```
public boolean hasEditPassword()
```

Restituisce true se è necessaria una password per modificare i permessi o la proprietà di sicurezza del documento. Nota che questa proprietà può essere letta solo se è stata fornita una password valida nel costruttore {@code PdfFileInfo}. Nel caso in cui PasswordType sia Inaccessible (significa che è stata fornita una password non valida) la lettura di questa proprietà fallirà con {@code InvalidPasswordException}.

**Returns:**
valore booleano

### hasOpenPassword {#hasOpenPassword--}
```
public boolean hasOpenPassword()
```

Restituisce true se è necessaria una password per aprire un documento PDF protetto da password.

**Returns:**
valore booleano

### isEncrypted {#isEncrypted--}
```
public boolean isEncrypted()
```

Verifica se il documento PDF è crittografato.

**Returns:**
valore booleano

### isPdfFile {#isPdfFile--}
```
public boolean isPdfFile()
```

Verifica se l'input di origine è un file PDF valido.

**Returns:**
valore booleano

### save {#save-java.io.OutputStream-}
Salva il documento PDF nel file specificato.

### saveNewInfo {#saveNewInfo-java.io.OutputStream-}
Salva il documento PDF aggiornato nello stream specificato.

### saveNewInfo {#saveNewInfo-java.lang.String-}
Salva il documento PDF aggiornato nel file specificato.

### saveNewInfoWithXmp {#saveNewInfoWithXmp-java.lang.String-}
Modifica le proprietà specificate esplicitamente impostando le informazioni del file, le altre proprietà rimangono.

### setAuthor {#setAuthor-java.lang.String-}
Imposta le informazioni dell'Autore del documento PDF.

### setCreationDate {#setCreationDate-java.lang.String-}
Imposta le informazioni della Data di Creazione del documento PDF.

### setCreator {#setCreator-java.lang.String-}
Imposta le informazioni del Creatore del documento PDF.

### setHeader {#setHeader-java.util.Map-}
Imposta le informazioni personalizzate del documento PDF.

### setInputFile {#setInputFile-java.lang.String-}
Imposta il file di input.

### setInputStream {#setInputStream-java.io.InputStream-}
Imposta lo stream di input.

### setKeywords {#setKeywords-java.lang.String-}
Imposta le informazioni delle Parole chiave del documento PDF.

### setMetaInfo {#setMetaInfo-java.lang.String-java.lang.String-}
Imposta le informazioni personalizzate del documento PDF.

### setModDate {#setModDate-java.lang.String-}
Imposta le informazioni della data ModDate del documento PDF.

### setSubject {#setSubject-java.lang.String-}
Imposta le informazioni dell'Oggetto del documento PDF.

### setTitle {#setTitle-java.lang.String-}
Imposta le informazioni del Titolo del documento PDF.

### setUseStrictValidation {#setUseStrictValidation-boolean-}
```
public final void setUseStrictValidation(boolean value)
```

Utilizza regole di validazione rigorose tramite la proprietà {@code IsPdfFile}({@link #isPdfFile}).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |
