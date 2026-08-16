---
title: "PdfAction"
linktitle: "PdfAction"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa Acción en el documento PDF"
type: docs
weight: 3670
url: /es/java/com.aspose.pdf/pdfaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction

**All Implemented Interfaces:**
IAppointment

```
public abstract class PdfAction extends Object implements IAppointment
```

Representa Acción en el documento PDF

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfAction](#PdfAction--) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [getECMAScriptString](#getECMAScriptString--) | Obtiene la cadena para la Acción ECMAScript. |
| [getNext](#getNext--) | Acciones siguientes en secuencia. |

### PdfAction {#PdfAction--}
```
public PdfAction()
```



### getECMAScriptString {#getECMAScriptString--}
```
public final String getECMAScriptString()
```

Obtiene la cadena para la Acción ECMAScript.

**Returns:**
Devuelve la cadena para la entrada JS de la Acción ECMAScript o null en caso contrario.

### getNext {#getNext--}
```
public ActionCollection getNext()
```

Acciones siguientes en secuencia.

**Returns:**
ActionCollection object
