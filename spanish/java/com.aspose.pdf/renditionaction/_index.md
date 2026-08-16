---
title: "RenditionAction"
linktitle: "RenditionAction"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Una acción de representación que controla la reproducción de contenido multimedia."
type: docs
weight: 4180
url: /es/java/com.aspose.pdf/renditionaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.RenditionAction, com.aspose.pdf.PdfAction, com.aspose.pdf.RenditionAction

**All Implemented Interfaces:**
IAppointment

```
public final class RenditionAction extends PdfAction
```

Una acción de representación que controla la reproducción de contenido multimedia.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [RenditionAction](#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-) | Crea la acción de representación. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getJavaScript](#getJavaScript--) | Obtiene o establece el código JavaScript asociado a la acción. |
| [getRendition](#getRendition--) | Obtiene o establece la representación asociada a la acción. |
| [getRenditionOperation](#getRenditionOperation--) | La operación a realizar cuando se activa la acción. |
| [setJavaScript](#setJavaScript-java.lang.String-) | Obtiene o establece el código JavaScript asociado a la acción. |
| [setRenditionOperation](#setRenditionOperation-int-) | La operación a realizar cuando se activa la acción. |

### RenditionAction {#RenditionAction-java.lang.String-com.aspose.pdf.ScreenAnnotation-}
Crea la acción de representación.

### getJavaScript {#getJavaScript--}
```
public final String getJavaScript()
```

Obtiene o establece el código JavaScript asociado a la acción.

**Returns:**
valor String

### getRendition {#getRendition--}
```
public final Rendition getRendition()
```

Obtiene o establece la representación asociada a la acción.

**Returns:**
Instancia de Rendition

### getRenditionOperation {#getRenditionOperation--}
```
public final int getRenditionOperation()
```

La operación a realizar cuando se activa la acción.

**Returns:**
Elemento RenditionOperation

### setJavaScript {#setJavaScript-java.lang.String-}
Obtiene o establece el código JavaScript asociado a la acción.

### setRenditionOperation {#setRenditionOperation-int-}
```
public final void setRenditionOperation(int value)
```

La operación a realizar cuando se activa la acción.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Elemento RenditionOperation |
