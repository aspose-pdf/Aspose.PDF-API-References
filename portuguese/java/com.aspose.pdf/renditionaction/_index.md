---
title: "RenditionAction"
linktitle: "RenditionAction"
second_title: "Referência da API Aspose.PDF para Java"
description: "Uma ação de renderização que controla a reprodução de conteúdo multimídia."
type: docs
weight: 4180
url: /pt/java/com.aspose.pdf/renditionaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.RenditionAction, com.aspose.pdf.PdfAction, com.aspose.pdf.RenditionAction

**All Implemented Interfaces:**
IAppointment

```
public final class RenditionAction extends PdfAction
```

Uma ação de renderização que controla a reprodução de conteúdo multimídia.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [RenditionAction](#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-) | Cria a ação de renderização. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getJavaScript](#getJavaScript--) | Obtém ou define o código JavaScript associado à ação. |
| [getRendition](#getRendition--) | Obtém ou define a renderização associada à ação. |
| [getRenditionOperation](#getRenditionOperation--) | A operação a ser executada quando a ação for acionada. |
| [setJavaScript](#setJavaScript-java.lang.String-) | Obtém ou define o código JavaScript associado à ação. |
| [setRenditionOperation](#setRenditionOperation-int-) | A operação a ser executada quando a ação for acionada. |

### RenditionAction {#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-}
Cria a ação de renderização.

### getJavaScript {#getJavaScript--}
```
public final String getJavaScript()
```

Obtém ou define o código JavaScript associado à ação.

**Returns:**
valor String

### getRendition {#getRendition--}
```
public final Rendition getRendition()
```

Obtém ou define a renderização associada à ação.

**Returns:**
Instância de Rendition

### getRenditionOperation {#getRenditionOperation--}
```
public final int getRenditionOperation()
```

A operação a ser executada quando a ação for acionada.

**Returns:**
Elemento RenditionOperation

### setJavaScript {#setJavaScript-java.lang.String-}
Obtém ou define o código JavaScript associado à ação.

### setRenditionOperation {#setRenditionOperation-int-}
```
public final void setRenditionOperation(int value)
```

A operação a ser executada quando a ação for acionada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento RenditionOperation |
