---
title: "SubmitFormAction"
linktitle: "SubmitFormAction"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che descrive l'azione submit-form."
type: docs
weight: 4690
url: /it/java/com.aspose.pdf/submitformaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.SubmitFormAction, com.aspose.pdf.PdfAction, com.aspose.pdf.SubmitFormAction

**All Implemented Interfaces:**
IAppointment

```
public final class SubmitFormAction extends PdfAction
```

Classe che descrive l'azione submit-form.

## Campi

| Campo | Descrizione |
| --- | --- |
| [CANONICAL_FORMAT](#CANONICAL_FORMAT) | Se impostato, tutti i valori dei campi inviati che rappresentano date saranno convertiti nel formato standard. |
| [EMBED_FORM](#EMBED_FORM) | Se impostato, la voce F del FDF inviato sarà una specifica di file contenente un flusso di file incorporato che rappresenta il file PDF da cui il FDF viene inviato. |
| [EXCL_F_KEY](#EXCL_F_KEY) | Se impostato, il FDF inviato escluderà la voce F. |
| [EXCL_NON_USER_ANNOTS](#EXCL_NON_USER_ANNOTS) | Se impostato, includerà solo quelle annotazioni di markup la cui voce T corrisponde al nome dell'utente corrente. |
| [EXCLUDE](#EXCLUDE) | Se cancellato, l'array Fields specifica quali campi includere nella sottomissione. |
| [EXPORT_FORMAT](#EXPORT_FORMAT) | Se impostato, i nomi e i valori dei campi saranno inviati nel formato HTML Form. |
| [GET_METHOD](#GET_METHOD) | Se impostato, i nomi e i valori dei campi saranno inviati usando una richiesta HTTP GET. |
| [INCLUDE_ANNOTATIONS](#INCLUDE_ANNOTATIONS) | Se impostato, il file FDF inviato includerà tutte le annotazioni di markup nel documento PDF sottostante. |
| [INCLUDE_APPEND_SAVES](#INCLUDE_APPEND_SAVES) | Se impostato, il file FDF inviato includerà il contenuto di tutti gli aggiornamenti incrementali. |
| [INCLUDE_NO_VALUE_FIELDS](#INCLUDE_NO_VALUE_FIELDS) | Se impostato, tutti i campi designati dall'array Fields e dal flag Includi/Escludi saranno inviati. |
| [SUBMIT_COORDINATES](#SUBMIT_COORDINATES) | Se impostato, le coordinate del clic del mouse che ha causato l'azione submit-form saranno trasmesse come parte dei dati del modulo. |
| [SUBMIT_PDF](#SUBMIT_PDF) | Se impostato, il documento sarà inviato come PDF, usando il tipo MIME application/pdf. |
| [XFDF](#XFDF) | Se impostato, i nomi e i valori dei campi saranno inviati come XFDF. |

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SubmitFormAction](#SubmitFormAction--) | Inizializza l'oggetto SubmitFormAction. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFlags](#getFlags--) | Ottiene i flagas dell'azione di invio |
| [getUrl](#getUrl--) | URL di destinazione. |
| [setFlags](#setFlags-int-) | Imposta i flagas dell'azione di invio |
| [setUrl](#setUrl-com.aspose.pdf.FileSpecification-) | URL di destinazione. |

### CANONICAL_FORMAT {#CANONICAL_FORMAT}
```
public static final int CANONICAL_FORMAT
```

Se impostato, tutti i valori dei campi inviati che rappresentano date saranno convertiti nel formato standard.

### EMBED_FORM {#EMBED_FORM}
```
public static final int EMBED_FORM
```

Se impostato, la voce F del FDF inviato sarà una specifica di file contenente un flusso di file incorporato che rappresenta il file PDF da cui il FDF viene inviato.

### EXCL_F_KEY {#EXCL_F_KEY}
```
public static final int EXCL_F_KEY
```

Se impostato, il FDF inviato escluderà la voce F.

### EXCL_NON_USER_ANNOTS {#EXCL_NON_USER_ANNOTS}
```
public static final int EXCL_NON_USER_ANNOTS
```

Se impostato, includerà solo quelle annotazioni di markup la cui voce T corrisponde al nome dell'utente corrente.

### EXCLUDE {#EXCLUDE}
```
public static final int EXCLUDE
```

Se cancellato, l'array Fields specifica quali campi includere nella sottomissione.

### EXPORT_FORMAT {#EXPORT_FORMAT}
```
public static final int EXPORT_FORMAT
```

Se impostato, i nomi e i valori dei campi saranno inviati nel formato HTML Form.

### GET_METHOD {#GET_METHOD}
```
public static final int GET_METHOD
```

Se impostato, i nomi e i valori dei campi saranno inviati usando una richiesta HTTP GET.

### INCLUDE_ANNOTATIONS {#INCLUDE_ANNOTATIONS}
```
public static final int INCLUDE_ANNOTATIONS
```

Se impostato, il file FDF inviato includerà tutte le annotazioni di markup nel documento PDF sottostante.

### INCLUDE_APPEND_SAVES {#INCLUDE_APPEND_SAVES}
```
public static final int INCLUDE_APPEND_SAVES
```

Se impostato, il file FDF inviato includerà il contenuto di tutti gli aggiornamenti incrementali.

### INCLUDE_NO_VALUE_FIELDS {#INCLUDE_NO_VALUE_FIELDS}
```
public static final int INCLUDE_NO_VALUE_FIELDS
```

Se impostato, tutti i campi designati dall'array Fields e dal flag Includi/Escludi saranno inviati.

### SUBMIT_COORDINATES {#SUBMIT_COORDINATES}
```
public static final int SUBMIT_COORDINATES
```

Se impostato, le coordinate del clic del mouse che ha causato l'azione submit-form saranno trasmesse come parte dei dati del modulo.

### SUBMIT_PDF {#SUBMIT_PDF}
```
public static final int SUBMIT_PDF
```

Se impostato, il documento sarà inviato come PDF, usando il tipo MIME application/pdf.

### XFDF {#XFDF}
```
public static final int XFDF
```

Se impostato, i nomi e i valori dei campi saranno inviati come XFDF.

### SubmitFormAction {#SubmitFormAction--}
```
public SubmitFormAction()
```

Inizializza l'oggetto SubmitFormAction.

### getFlags {#getFlags--}
```
public int getFlags()
```

Ottiene i flagas dell'azione di invio

**Returns:**
valore int

### getUrl {#getUrl--}
```
public FileSpecification getUrl()
```

URL di destinazione.

**Returns:**
Valore FileSpecification

### setFlags {#setFlags-int-}
```
public void setFlags(int value)
```

Imposta i flagas dell'azione di invio

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setUrl {#setUrl-com.aspose.pdf.FileSpecification-}
URL di destinazione.
