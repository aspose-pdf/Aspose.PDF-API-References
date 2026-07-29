---
title: "PdfAction"
linktitle: "PdfAction"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta l'azione nel documento PDF"
type: docs
weight: 3670
url: /it/java/com.aspose.pdf/pdfaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction

**All Implemented Interfaces:**
IAppointment

```
public abstract class PdfAction extends Object implements IAppointment
```

Rappresenta l'azione nel documento PDF

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfAction](#PdfAction--) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getECMAScriptString](#getECMAScriptString--) | Restituisce la stringa per l'Azione ECMAScript. |
| [getNext](#getNext--) | Azioni successive nella sequenza. |

### PdfAction {#PdfAction--}
```
public PdfAction()
```



### getECMAScriptString {#getECMAScriptString--}
```
public final String getECMAScriptString()
```

Restituisce la stringa per l'Azione ECMAScript.

**Returns:**
Restituisce la stringa per l'entrata JS per l'Azione ECMAScript o null altrimenti.

### getNext {#getNext--}
```
public ActionCollection getNext()
```

Azioni successive nella sequenza.

**Returns:**
oggetto ActionCollection
