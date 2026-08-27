---
title: "PdfAction"
linktitle: "PdfAction"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa Ação em documento PDF"
type: docs
weight: 3670
url: /pt/java/com.aspose.pdf/pdfaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction

**All Implemented Interfaces:**
IAppointment

```
public abstract class PdfAction extends Object implements IAppointment
```

Representa Ação em documento PDF

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PdfAction](#PdfAction--) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [getECMAScriptString](#getECMAScriptString--) | Obtém a string para a Ação ECMAScript. |
| [getNext](#getNext--) | Próximas ações na sequência. |

### PdfAction {#PdfAction--}
```
public PdfAction()
```



### getECMAScriptString {#getECMAScriptString--}
```
public final String getECMAScriptString()
```

Obtém a string para a Ação ECMAScript.

**Returns:**
Retorna a string para a entrada JS da Ação ECMAScript ou null caso contrário.

### getNext {#getNext--}
```
public ActionCollection getNext()
```

Próximas ações na sequência.

**Returns:**
Objeto ActionCollection
