---
title: "PdfFileSanitization"
linktitle: "PdfFileSanitization"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta l'API di sanificazione e recupero. Usala se non riesci a creare/aprire i documenti in altro modo."
type: docs
weight: 510
url: /it/java/com.aspose.pdf.facades/pdffilesanitization/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSanitization, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSanitization, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSanitization

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.security.impl.signatures.sanitization.IRecovery, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSanitization extends SaveableFacade implements com.aspose.pdf.engine.security.impl.signatures.sanitization.IRecovery
```

Rappresenta l'API di sanificazione e recupero. Usala se non riesci a creare/aprire i documenti in altro modo.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfFileSanitization](#PdfFileSanitization--) | Inizializza una nuova istanza. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.Document-) | Inizializza la facciata. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Associa un stream Pdf per la sanificazione. |
| [bindPdf](#bindPdf-java.lang.String-) | Associa un file Pdf per la sanificazione. |
| [close](#close--) | Chiude la facciata. |
| [getLog](#getLog--) | Dopo che il file è stato salvato è possibile verificare cosa è stato fatto con il file. |
| [getUseRebuildXrefAndTrailer](#getUseRebuildXrefAndTrailer--) | Consente di generare un nuovo xref e trailer per il documento. |
| [getUseTrimBottom](#getUseTrimBottom--) | Consente di rimuovere i dati dopo i dati pdf |
| [getUseTrimTop](#getUseTrimTop--) | Consente di rimuovere i dati prima dei dati pdf. |
| [rebuildXrefAndTrailer](#rebuildXrefAndTrailer--) | Rimuove il vecchio xref con trailer e crea un nuovo xref con trailer. |
| [recover](#recover--) | Recupera il documento. Usa le proprietà per personalizzare. |
| [save](#save-java.io.OutputStream-) | Salva il PDF risultante nello stream. |
| [save](#save-java.lang.String-) | Salva il PDF risultante su file. |
| [setUseRebuildXrefAndTrailer](#setUseRebuildXrefAndTrailer-boolean-) | Consente di generare un nuovo xref e trailer per il documento. |
| [setUseTrimBottom](#setUseTrimBottom-boolean-) | Consente di rimuovere i dati dopo i dati pdf |
| [setUseTrimTop](#setUseTrimTop-boolean-) | Consente di rimuovere i dati prima dei dati pdf. |
| [trimBottom](#trimBottom--) | Rimuove i dati dopo l'ultimo %%EOF. |
| [trimTop](#trimTop--) | Rimuove i dati prima di %PDF. |

### PdfFileSanitization {#PdfFileSanitization--}
```
public PdfFileSanitization()
```

Inizializza una nuova istanza.

### bindPdf {#bindPdf-com.aspose.pdf.Document-}
Inizializza la facciata.

### bindPdf {#bindPdf-java.io.InputStream-}
Associa un stream Pdf per la sanificazione.

### bindPdf {#bindPdf-java.lang.String-}
Associa un file Pdf per la sanificazione.

### close {#close--}
```
public void close()
```

Chiude la facciata.

### getLog {#getLog--}
```
public final List < String > getLog()
```

Dopo che il file è stato salvato è possibile verificare cosa è stato fatto con il file.

**Returns:**
elenco di elementi String

### getUseRebuildXrefAndTrailer {#getUseRebuildXrefAndTrailer--}
```
public final boolean getUseRebuildXrefAndTrailer()
```

Consente di generare un nuovo xref e trailer per il documento.

**Returns:**
valore booleano

### getUseTrimBottom {#getUseTrimBottom--}
```
public final boolean getUseTrimBottom()
```

Consente di rimuovere i dati dopo i dati pdf

**Returns:**
valore booleano

### getUseTrimTop {#getUseTrimTop--}
```
public final boolean getUseTrimTop()
```

Consente di rimuovere i dati prima dei dati pdf.

**Returns:**
valore booleano

### rebuildXrefAndTrailer {#rebuildXrefAndTrailer--}
```
public final void rebuildXrefAndTrailer()
```

Rimuove il vecchio xref con trailer e crea un nuovo xref con trailer.

### recover {#recover--}
```
public final void recover()
```

Recupera il documento. Usa le proprietà per personalizzare.

### save {#save-java.io.OutputStream-}
Salva il PDF risultante nello stream.

### save {#save-java.lang.String-}
Salva il PDF risultante su file.

### setUseRebuildXrefAndTrailer {#setUseRebuildXrefAndTrailer-boolean-}
```
public final void setUseRebuildXrefAndTrailer(boolean value)
```

Consente di generare un nuovo xref e trailer per il documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setUseTrimBottom {#setUseTrimBottom-boolean-}
```
public final void setUseTrimBottom(boolean value)
```

Consente di rimuovere i dati dopo i dati pdf

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setUseTrimTop {#setUseTrimTop-boolean-}
```
public final void setUseTrimTop(boolean value)
```

Consente di rimuovere i dati prima dei dati pdf.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### trimBottom {#trimBottom--}
```
public final void trimBottom()
```

Rimuove i dati dopo l'ultimo %%EOF.

### trimTop {#trimTop--}
```
public final void trimTop()
```

Rimuove i dati prima di %PDF.
