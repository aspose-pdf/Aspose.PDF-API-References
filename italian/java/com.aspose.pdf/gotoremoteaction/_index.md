---
title: "GoToRemoteAction"
linktitle: "GoToRemoteAction"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un'azione vai-a remota simile a un'azione vai-a ordinaria ma salta a una destinazione in un altro file PDF invece del file corrente."
type: docs
weight: 1820
url: /it/java/com.aspose.pdf/gotoremoteaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.GoToAction com.aspose.pdf.GoToRemoteAction, com.aspose.pdf.PdfAction, com.aspose.pdf.GoToAction com.aspose.pdf.GoToRemoteAction, com.aspose.pdf.GoToAction, com.aspose.pdf.GoToRemoteAction

**All Implemented Interfaces:**
IAppointment

```
public final class GoToRemoteAction extends GoToAction
```

Rappresenta un'azione vai-a remota simile a un'azione vai-a ordinaria ma salta a una destinazione in un altro file PDF invece del file corrente.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GoToRemoteAction](#GoToRemoteAction-java.lang.String-com.aspose.pdf.ExplicitDestination-) | Inizializza l'oggetto GoToRemoteAction. |
| [GoToRemoteAction](#GoToRemoteAction-java.lang.String-int-) | Inizializza l'oggetto GoToRemoteAction. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFile](#getFile--) | Ottiene la specifica del file in cui si trova la destinazione. |
| [getNewWindow](#getNewWindow--) | Ottiene un flag che specifica se aprire il documento di destinazione in una nuova finestra. |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | / * / * Ottiene la destinazione a cui saltare. / * / * / * |
| [setFile](#setFile-com.aspose.pdf.FileSpecification-) | Imposta la specifica del file in cui si trova la destinazione. |
| [setNewWindow](#setNewWindow-com.aspose.pdf.ExtendedBoolean-) | Imposta un flag che specifica se aprire il documento di destinazione in una nuova finestra. |

### GoToRemoteAction {#GoToRemoteAction-java.lang.String-com.aspose.pdf.ExplicitDestination-}
Inizializza l'oggetto GoToRemoteAction.

### GoToRemoteAction {#GoToRemoteAction-java.lang.String-int-}
Inizializza l'oggetto GoToRemoteAction.

### getFile {#getFile--}
```
public FileSpecification getFile()
```

Ottiene la specifica del file in cui si trova la destinazione.

**Returns:**
Oggetto FileSpecification

### getNewWindow {#getNewWindow--}
```
public ExtendedBoolean getNewWindow()
```

Ottiene un flag che specifica se aprire il documento di destinazione in una nuova finestra.

**Returns:**
Elemento ExtendedBoolean @see ExtendedBoolean

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
/ * / * Ottiene la destinazione a cui saltare. / * / * / *

### setFile {#setFile-com.aspose.pdf.FileSpecification-}
Imposta la specifica del file in cui si trova la destinazione.

### setNewWindow {#setNewWindow-com.aspose.pdf.ExtendedBoolean-}
Imposta un flag che specifica se aprire il documento di destinazione in una nuova finestra.
