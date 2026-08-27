---
title: "PdfAction"
linktitle: "PdfAction"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente Action dans le document PDF"
type: docs
weight: 3670
url: /fr/java/com.aspose.pdf/pdfaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction

**All Implemented Interfaces:**
IAppointment

```
public abstract class PdfAction extends Object implements IAppointment
```

Représente Action dans le document PDF

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfAction](#PdfAction--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getECMAScriptString](#getECMAScriptString--) | Obtient la chaîne pour l'action ECMAScript. |
| [getNext](#getNext--) | Actions suivantes dans la séquence. |

### PdfAction {#PdfAction--}
```
public PdfAction()
```



### getECMAScriptString {#getECMAScriptString--}
```
public final String getECMAScriptString()
```

Obtient la chaîne pour l'action ECMAScript.

**Returns:**
Renvoie la chaîne pour l'entrée JS de l'action ECMAScript ou null sinon.

### getNext {#getNext--}
```
public ActionCollection getNext()
```

Actions suivantes dans la séquence.

**Returns:**
Objet ActionCollection
