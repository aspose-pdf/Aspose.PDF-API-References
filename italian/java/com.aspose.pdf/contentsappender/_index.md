---
title: "ContentsAppender"
linktitle: "ContentsAppender"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Esegue modifiche al contenuto solo in modalità APPEND. questa modalità consente di evitare l'analisi non necessaria e pesante del contenuto prima di apportare modifiche. Aggiunge solo nuovi contenuti."
type: docs
weight: 800
url: /it/java/com.aspose.pdf/contentsappender/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ContentsAppender

```
public class ContentsAppender extends Object
```

Esegue modifiche al contenuto solo in modalità APPEND. Questa modalità consente di evitare l'analisi non necessaria e pesante del contenuto prima che venga apportata una modifica. Aggiunge solo nuovi operatori alla fine o all'inizio del contenuto.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ContentsAppender](#ContentsAppender-com.aspose.pdf.Page-) | Inizializza una nuova istanza del contents appender con la pagina allegata |
| [ContentsAppender](#ContentsAppender-com.aspose.pdf.XForm-) | Inizializza una nuova istanza del contets appender con Form XObject. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [appendToBegin](#appendToBegin-com.aspose.ms.System.Collections.Generic.List-) | Aggiunge operatori alla fine del contenuto |
| [appendToBegin](#appendToBegin-com.aspose.pdf.Operator-) | Aggiunge un operatore alla fine del contenuto |
| [appendToBegin](#appendToBegin-com.aspose.pdf.Operator:A-) | Aggiunge operatori alla fine del contenuto |
| [appendToEnd](#appendToEnd-com.aspose.ms.System.Collections.Generic.List-) | Aggiunge operatori all'inizio del contenuto |
| [appendToEnd](#appendToEnd-com.aspose.pdf.Operator-) | Aggiunge un operatore all'inizio del contenuto |
| [appendToEnd](#appendToEnd-com.aspose.pdf.Operator:A-) | Aggiunge operatori all'inizio del contenuto |
| [getBeginCode](#getBeginCode--) | Stringa contenente operatori da inserire all'inizio della pagina. |
| [getBeginOperators](#getBeginOperators--) | <p> restituisce operatori di inizio </p> |
| [getEndCode](#getEndCode--) | Stringa contenente operatori da aggiungere alla fine della pagina. |
| [getEndOperators](#getEndOperators--) | <p> restituisce operatori di fine </p> |
| [resumeUpdate](#resumeUpdate--) | riprende l'aggiornamento del documento |
| [setBeginCode](#setBeginCode-java.lang.String-) | Stringa contenente operatori da inserire all'inizio della pagina. |
| [setEndCode](#setEndCode-java.lang.String-) | Stringa contenente operatori da inserire all'inizio della pagina. |
| [suppressUpdate](#suppressUpdate--) | Sopprime l'aggiornamento dei dati del contenuto. Il contenuto non viene aggiornato finché non viene chiamato ResumeUpdate. |
| [updateData](#updateData--) | questa è la nuova versione di UpdateData, che evita la decodifica del contenuto esistente. |
| [updateDataOld](#updateDataOld--) | Deve essere chiamato per applicare le modifiche |

### ContentsAppender {#ContentsAppender-com.aspose.pdf.Page-}
Inizializza una nuova istanza del contents appender con la pagina allegata

### ContentsAppender {#ContentsAppender-com.aspose.pdf.XForm-}
Inizializza una nuova istanza del contets appender con Form XObject.

### appendToBegin {#appendToBegin-com.aspose.ms.System.Collections.Generic.List-}
Aggiunge operatori alla fine del contenuto

### appendToBegin {#appendToBegin-com.aspose.pdf.Operator-}
Aggiunge un operatore alla fine del contenuto

### appendToBegin {#appendToBegin-com.aspose.pdf.Operator:A-}
Aggiunge operatori alla fine del contenuto

### appendToEnd {#appendToEnd-com.aspose.ms.System.Collections.Generic.List-}
Aggiunge operatori all'inizio del contenuto

### appendToEnd {#appendToEnd-com.aspose.pdf.Operator-}
Aggiunge un operatore all'inizio del contenuto

### appendToEnd {#appendToEnd-com.aspose.pdf.Operator:A-}
Aggiunge operatori all'inizio del contenuto

### getBeginCode {#getBeginCode--}
```
public String getBeginCode()
```

Stringa contenente operatori da inserire all'inizio della pagina.

**Returns:**
Oggetto stringa

### getBeginOperators {#getBeginOperators--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > getBeginOperators()
```

<p> restituisce operatori di inizio </p>

**Returns:**
oggetto {@code List<Operator>}

### getEndCode {#getEndCode--}
```
public String getEndCode()
```

Stringa contenente operatori da aggiungere alla fine della pagina.

**Returns:**
Oggetto stringa

### getEndOperators {#getEndOperators--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > getEndOperators()
```

<p> restituisce operatori di fine </p>

**Returns:**
oggetto {@code List<Operator>}

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

riprende l'aggiornamento del documento

### setBeginCode {#setBeginCode-java.lang.String-}
Stringa contenente operatori da inserire all'inizio della pagina.

### setEndCode {#setEndCode-java.lang.String-}
Stringa contenente operatori da inserire all'inizio della pagina.

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Sopprime l'aggiornamento dei dati del contenuto. Il contenuto non viene aggiornato finché non viene chiamato ResumeUpdate.

### updateData {#updateData--}
```
public void updateData()
```

questa è la nuova versione di UpdateData, che evita la decodifica del contenuto esistente.

### updateDataOld {#updateDataOld--}
```
public void updateDataOld()
```

Deve essere chiamato per applicare le modifiche
