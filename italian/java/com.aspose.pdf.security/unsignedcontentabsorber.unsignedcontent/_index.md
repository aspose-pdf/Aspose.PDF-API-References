---
title: "UnsignedContentAbsorber.UnsignedContent"
linktitle: "UnsignedContentAbsorber.UnsignedContent"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Incapsula gli elementi di contenuto non firmato estratti da un documento PDF. Questa classe fornisce l'accesso a pagine, campi modulo, XForm e annotazioni che fanno parte del contenuto non firmato."
type: docs
weight: 50
url: /it/java/com.aspose.pdf.security/unsignedcontentabsorber.unsignedcontent/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber.UnsignedContent

```
public static final class UnsignedContentAbsorber.UnsignedContent extends Object
```

Incapsula gli elementi di contenuto non firmato estratti da un documento PDF. Questa classe fornisce l'accesso a pagine, campi modulo, XForm e annotazioni che fanno parte del contenuto non firmato all'interno del documento.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAnnotations](#getAnnotations--) | Ottiene un dizionario delle annotazioni modificate che potrebbero essere state cambiate o aggiunte. |
| [getForms](#getForms--) | Ottiene i campi modulo che sono stati modificati o aggiunti in modo incrementale. |
| [getPages](#getPages--) | Ottiene un elenco di pagine il cui contenuto non è firmato o è stato modificato in modo incrementale. La pagina è considerata modificata e gli XForm non vengono controllati e non compaiono nell'elenco degli XForm. |
| [getXForms](#getXForms--) | Ottiene un dizionario di oggetti XForm modificati che potrebbero essere cambiati, sebbene la pagina stessa non sia cambiata (non presente nell'elenco delle Pagine). |
| [setXForms](#setXForms-java.util.HashMap-) | Un dizionario di oggetti XForm modificati che potrebbero essere cambiati, sebbene la pagina stessa non sia cambiata (non presente nell'elenco delle Pagine). |

### getAnnotations {#getAnnotations--}
```
public final HashMap < Integer , Annotation > getAnnotations()
```

Ottiene un dizionario delle annotazioni modificate che potrebbero essere state cambiate o aggiunte.

**Returns:**
un dizionario di annotazioni modificate che potrebbero essere cambiate o aggiunte.

### getForms {#getForms--}
```
public final List < WidgetAnnotation > getForms()
```

Ottiene i campi modulo che sono stati modificati o aggiunti in modo incrementale.

**Returns:**
campi del modulo che sono stati modificati o aggiunti in modo incrementale.

### getPages {#getPages--}
```
public final List < Page > getPages()
```

Ottiene un elenco di pagine il cui contenuto non è firmato o è stato modificato in modo incrementale. La pagina è considerata modificata e gli XForm non vengono controllati e non compaiono nell'elenco degli XForm.

**Returns:**
un elenco di pagine il cui contenuto non è firmato o è stato modificato in modo incrementale.

### getXForms {#getXForms--}
```
public final HashMap < Integer , XForm > getXForms()
```

Ottiene un dizionario di oggetti XForm modificati che potrebbero essere cambiati, sebbene la pagina stessa non sia cambiata (non presente nell'elenco delle Pagine).

**Returns:**
un dizionario di oggetti XForm modificati che potrebbero essere cambiati, sebbene la pagina stessa non sia cambiata (non presente nell'elenco delle Pagine).

### setXForms {#setXForms-java.util.HashMap-}
Un dizionario di oggetti XForm modificati che potrebbero essere cambiati, sebbene la pagina stessa non sia cambiata (non presente nell'elenco delle Pagine).
