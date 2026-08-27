---
title: "AnnotationFlags"
linktitle: "AnnotationFlags"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Flag Un insieme di flag binari che specificano varie caratteristiche dell'annotazione."
type: docs
weight: 90
url: /it/java/com.aspose.pdf/annotationflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.AnnotationFlags, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.AnnotationFlags, com.aspose.ms.System.Enum, com.aspose.pdf.AnnotationFlags

```
public final class AnnotationFlags extends com.aspose.ms.System.Enum
```

Flag Un insieme di flag binari che specificano varie caratteristiche dell'annotazione.

## Campi

| Campo | Descrizione |
| --- | --- |
| [Default](#Default) | Valore predefinito. |
| [Hidden](#Hidden) | Se impostato, non visualizzare né stampare l'annotazione né consentire l'interazione con l'utente, indipendentemente dal tipo di annotazione o dalla disponibilità di un gestore di annotazioni. Nei casi in cui lo spazio sullo schermo è limitato, la possibilità di nascondere e mostrare selettivamente le annotazioni può essere utilizzata in combinazione con i flussi di aspetto per visualizzare informazioni ausiliarie a comparsa simili, per funzione, ai sistemi di help online. |
| [Invisible](#Invisible) | Se impostato, non visualizzare l'annotazione se non appartiene a uno dei tipi di annotazione standard e non è disponibile alcun gestore di annotazioni. Se cancellato, visualizzare tale annotazione sconosciuta utilizzando un flusso di aspetto specificato dal suo dizionario di aspetto, se presente. |
| [Locked](#Locked) | Se impostato, non consentire che l'annotazione venga eliminata o che le sue proprietà (inclusi posizione e dimensione) vengano modificate dall'utente. Tuttavia, questa flag non limita le modifiche al contenuto dell'annotazione, come il valore di un campo modulo. |
| [LockedContents](#LockedContents) | Se impostato, non consentire che il contenuto dell'annotazione venga modificato dall'utente. Questa flag non limita l'eliminazione dell'annotazione né le modifiche ad altre proprietà dell'annotazione, come posizione e dimensione. |
| [NoRotate](#NoRotate) | Se impostato, non ruotare l'aspetto dell'annotazione per corrispondere alla rotazione della pagina. L'angolo in alto a sinistra del rettangolo dell'annotazione rimane in una posizione fissa sulla pagina, indipendentemente dalla rotazione della pagina. |
| [NoView](#NoView) | Se impostato, non visualizzare l'annotazione sullo schermo né consentirne l'interazione con l'utente. L'annotazione può essere stampata (a seconda dell'impostazione della flag Print) ma dovrebbe essere considerata nascosta ai fini della visualizzazione su schermo e dell'interazione dell'utente. |
| [NoZoom](#NoZoom) | Se impostato, non scalare l'aspetto dell'annotazione per corrispondere all'ingrandimento della pagina. La posizione dell'annotazione sulla pagina (definita dall'angolo in alto a sinistra del suo rettangolo) rimane fissa, indipendentemente dall'ingrandimento della pagina. |
| [Print](#Print) | Se impostato, stampa l'annotazione quando la pagina viene stampata. Se non impostato, non stampare mai l'annotazione, indipendentemente dal fatto che sia visualizzata sullo schermo. Questo può essere utile, ad esempio, per annotazioni che rappresentano pulsanti interattivi, i quali non avrebbero alcuno scopo significativo sulla pagina stampata. |
| [ReadOnly](#ReadOnly) | Se impostato, non consentire all'annotazione di interagire con l'utente. L'annotazione può essere visualizzata o stampata (a seconda delle impostazioni delle flag NoView e Print) ma non deve rispondere ai clic del mouse né modificare il proprio aspetto in risposta ai movimenti del mouse. Questa flag è ignorata per le annotazioni widget; la sua funzione è inglobata dalla flag ReadOnly del campo modulo associato. |
| [ToggleNoView](#ToggleNoView) | Se impostato, inverte l'interpretazione della flag NoView per alcuni eventi. Un uso tipico è avere un'annotazione che appare solo quando il cursore del mouse è posizionato sopra di essa. |

### Default {#Default}
```
public static final int Default
```

Valore predefinito.

### Hidden {#Hidden}
```
public static final int Hidden
```

Se impostato, non visualizzare né stampare l'annotazione né consentire l'interazione con l'utente, indipendentemente dal tipo di annotazione o dalla disponibilità di un gestore di annotazioni. Nei casi in cui lo spazio sullo schermo è limitato, la possibilità di nascondere e mostrare selettivamente le annotazioni può essere utilizzata in combinazione con i flussi di aspetto per visualizzare informazioni ausiliarie a comparsa simili, per funzione, ai sistemi di help online.

### Invisible {#Invisible}
```
public static final int Invisible
```

Se impostato, non visualizzare l'annotazione se non appartiene a uno dei tipi di annotazione standard e non è disponibile alcun gestore di annotazioni. Se cancellato, visualizzare tale annotazione sconosciuta utilizzando un flusso di aspetto specificato dal suo dizionario di aspetto, se presente.

### Locked {#Locked}
```
public static final int Locked
```

Se impostato, non consentire che l'annotazione venga eliminata o che le sue proprietà (inclusi posizione e dimensione) vengano modificate dall'utente. Tuttavia, questa flag non limita le modifiche al contenuto dell'annotazione, come il valore di un campo modulo.

### LockedContents {#LockedContents}
```
public static final int LockedContents
```

Se impostato, non consentire che il contenuto dell'annotazione venga modificato dall'utente. Questa flag non limita l'eliminazione dell'annotazione né le modifiche ad altre proprietà dell'annotazione, come posizione e dimensione.

### NoRotate {#NoRotate}
```
public static final int NoRotate
```

Se impostato, non ruotare l'aspetto dell'annotazione per corrispondere alla rotazione della pagina. L'angolo in alto a sinistra del rettangolo dell'annotazione rimane in una posizione fissa sulla pagina, indipendentemente dalla rotazione della pagina.

### NoView {#NoView}
```
public static final int NoView
```

Se impostato, non visualizzare l'annotazione sullo schermo né consentirne l'interazione con l'utente. L'annotazione può essere stampata (a seconda dell'impostazione della flag Print) ma dovrebbe essere considerata nascosta ai fini della visualizzazione su schermo e dell'interazione dell'utente.

### NoZoom {#NoZoom}
```
public static final int NoZoom
```

Se impostato, non scalare l'aspetto dell'annotazione per corrispondere all'ingrandimento della pagina. La posizione dell'annotazione sulla pagina (definita dall'angolo in alto a sinistra del suo rettangolo) rimane fissa, indipendentemente dall'ingrandimento della pagina.

### Print {#Print}
```
public static final int Print
```

Se impostato, stampa l'annotazione quando la pagina viene stampata. Se non impostato, non stampare mai l'annotazione, indipendentemente dal fatto che sia visualizzata sullo schermo. Questo può essere utile, ad esempio, per annotazioni che rappresentano pulsanti interattivi, i quali non avrebbero alcuno scopo significativo sulla pagina stampata.

### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```

Se impostato, non consentire all'annotazione di interagire con l'utente. L'annotazione può essere visualizzata o stampata (a seconda delle impostazioni delle flag NoView e Print) ma non deve rispondere ai clic del mouse né modificare il proprio aspetto in risposta ai movimenti del mouse. Questa flag è ignorata per le annotazioni widget; la sua funzione è inglobata dalla flag ReadOnly del campo modulo associato.

### ToggleNoView {#ToggleNoView}
```
public static final int ToggleNoView
```

Se impostato, inverte l'interpretazione della flag NoView per alcuni eventi. Un uso tipico è avere un'annotazione che appare solo quando il cursore del mouse è posizionato sopra di essa.
