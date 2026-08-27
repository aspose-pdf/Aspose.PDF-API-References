---
title: "RichMediaAnnotation"
linktitle: "RichMediaAnnotation"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che descrive RichMediaAnnotation che consente di incorporare dati video/audio in un documento PDF."
type: docs
weight: 4260
url: /it/java/com.aspose.pdf/richmediaannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.RichMediaAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.RichMediaAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.RichMediaAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class RichMediaAnnotation extends Annotation
```

Classe che descrive RichMediaAnnotation che consente di incorporare dati video/audio in un documento PDF.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [RichMediaAnnotation](#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Inizializza RichMediaAnnotation. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accetta il visitatore per questa annotazione. |
| [addCustomData](#addCustomData-java.lang.String-java.io.InputStream-) | Aggiunge dati nominati personalizzati (ad esempio richiesti per lo script flash). |
| [getActivateOn](#getActivateOn--) | Evento che attiva l'applicazione. |
| [getAnnotationType](#getAnnotationType--) | Ottiene il tipo di annotazione. |
| [getContent](#getContent--) | Dati del contenuto Rich Media. |
| [getCustomFlashVariables](#getCustomFlashVariables--) | Imposta o ottiene le variabili flash passate al lettore. |
| [getCustomPlayer](#getCustomPlayer--) | Imposta o ottiene il lettore flash personalizzato per riprodurre dati video/audio. |
| [getType](#getType--) | Ottiene o imposta il tipo di contenuto. Valori possibili: Audio, Video. |
| [setActivateOn](#setActivateOn-int-) | Evento che attiva l'applicazione. |
| [setContent](#setContent-java.lang.String-java.io.InputStream-) | Imposta lo stream di contenuto. |
| [setCustomFlashVariables](#setCustomFlashVariables-java.lang.String-) | Imposta o ottiene le variabili flash passate al lettore. |
| [setCustomPlayer](#setCustomPlayer-java.io.InputStream-) | Imposta o ottiene il lettore flash personalizzato per riprodurre dati video/audio. |
| [setPoster](#setPoster-java.io.InputStream-) | Imposta il poster dell'annotazione. |
| [setType](#setType-int-) | Ottiene o imposta il tipo di contenuto. Valori possibili: Audio, Video. |
| [update](#update--) | Aggiorna i dati con i parametri specificati. |

### RichMediaAnnotation {#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Inizializza RichMediaAnnotation.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accetta il visitatore per questa annotazione.

### addCustomData {#addCustomData-java.lang.String-java.io.InputStream-}
Aggiunge dati nominati personalizzati (ad esempio richiesti per lo script flash).

### getActivateOn {#getActivateOn--}
```
public int getActivateOn()
```

Evento che attiva l'applicazione.

**Returns:**
Elemento ActivationEvent

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ottiene il tipo di annotazione.

**Returns:**
Elemento AnnotationType @see AnnotationType

### getContent {#getContent--}
```
public InputStream getContent()
```

Dati del contenuto Rich Media.

**Returns:**
Oggetto InputStream

### getCustomFlashVariables {#getCustomFlashVariables--}
```
public String getCustomFlashVariables()
```

Imposta o ottiene le variabili flash passate al lettore.

**Returns:**
Oggetto stringa

### getCustomPlayer {#getCustomPlayer--}
```
public InputStream getCustomPlayer()
```

Imposta o ottiene il lettore flash personalizzato per riprodurre dati video/audio.

**Returns:**
Oggetto InputStream

### getType {#getType--}
```
public int getType()
```

Ottiene o imposta il tipo di contenuto. Valori possibili: Audio, Video.

**Returns:**
Valore ContentType @see ContentType

### setActivateOn {#setActivateOn-int-}
```
public void setActivateOn(int value)
```

Evento che attiva l'applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento ActivationEvent |

### setContent {#setContent-java.lang.String-java.io.InputStream-}
Imposta lo stream di contenuto.

### setCustomFlashVariables {#setCustomFlashVariables-java.lang.String-}
Imposta o ottiene le variabili flash passate al lettore.

### setCustomPlayer {#setCustomPlayer-java.io.InputStream-}
Imposta o ottiene il lettore flash personalizzato per riprodurre dati video/audio.

### setPoster {#setPoster-java.io.InputStream-}
Imposta il poster dell'annotazione.

### setType {#setType-int-}
```
public void setType(int value)
```

Ottiene o imposta il tipo di contenuto. Valori possibili: Audio, Video.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento ContentType |

### update {#update--}
```
public void update()
```

Aggiorna i dati con i parametri specificati.
