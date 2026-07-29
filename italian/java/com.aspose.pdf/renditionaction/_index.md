---
title: "RenditionAction"
linktitle: "RenditionAction"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Un'azione di resa che controlla la riproduzione di contenuti multimediali."
type: docs
weight: 4180
url: /it/java/com.aspose.pdf/renditionaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.RenditionAction, com.aspose.pdf.PdfAction, com.aspose.pdf.RenditionAction

**All Implemented Interfaces:**
IAppointment

```
public final class RenditionAction extends PdfAction
```

Un'azione di resa che controlla la riproduzione di contenuti multimediali.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [RenditionAction](#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-) | Crea l'azione di riproduzione. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getJavaScript](#getJavaScript--) | Ottiene o imposta il codice JavaScript associato all'azione. |
| [getRendition](#getRendition--) | Ottiene o imposta la riproduzione associata all'azione. |
| [getRenditionOperation](#getRenditionOperation--) | L'operazione da eseguire quando l'azione viene attivata. |
| [setJavaScript](#setJavaScript-java.lang.String-) | Ottiene o imposta il codice JavaScript associato all'azione. |
| [setRenditionOperation](#setRenditionOperation-int-) | L'operazione da eseguire quando l'azione viene attivata. |

### RenditionAction {#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-}
Crea l'azione di riproduzione.

### getJavaScript {#getJavaScript--}
```
public final String getJavaScript()
```

Ottiene o imposta il codice JavaScript associato all'azione.

**Returns:**
valore String

### getRendition {#getRendition--}
```
public final Rendition getRendition()
```

Ottiene o imposta la riproduzione associata all'azione.

**Returns:**
Istanza di riproduzione

### getRenditionOperation {#getRenditionOperation--}
```
public final int getRenditionOperation()
```

L'operazione da eseguire quando l'azione viene attivata.

**Returns:**
Elemento RenditionOperation

### setJavaScript {#setJavaScript-java.lang.String-}
Ottiene o imposta il codice JavaScript associato all'azione.

### setRenditionOperation {#setRenditionOperation-int-}
```
public final void setRenditionOperation(int value)
```

L'operazione da eseguire quando l'azione viene attivata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento RenditionOperation |
