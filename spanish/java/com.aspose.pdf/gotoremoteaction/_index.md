---
title: "GoToRemoteAction"
linktitle: "GoToRemoteAction"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una acción ir a remota que es similar a una acción ir a ordinaria pero salta a un destino en otro archivo PDF en lugar del archivo actual."
type: docs
weight: 1820
url: /es/java/com.aspose.pdf/gotoremoteaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.GoToAction com.aspose.pdf.GoToRemoteAction, com.aspose.pdf.PdfAction, com.aspose.pdf.GoToAction com.aspose.pdf.GoToRemoteAction, com.aspose.pdf.GoToAction, com.aspose.pdf.GoToRemoteAction

**All Implemented Interfaces:**
IAppointment

```
public final class GoToRemoteAction extends GoToAction
```

Representa una acción ir a remota que es similar a una acción ir a ordinaria pero salta a un destino en otro archivo PDF en lugar del archivo actual.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [GoToRemoteAction](#GoToRemoteAction-java.lang.String-com.aspose.pdf.ExplicitDestination-) | Inicializa el objeto GoToRemoteAction. |
| [GoToRemoteAction](#GoToRemoteAction-java.lang.String-int-) | Inicializa el objeto GoToRemoteAction. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getFile](#getFile--) | Obtiene la especificación del archivo en el que se encuentra el destino. |
| [getNewWindow](#getNewWindow--) | Obtiene una bandera que especifica si se debe abrir el documento de destino en una nueva ventana. |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | / * / * Obtiene el destino al que saltar. / * / * / * |
| [setFile](#setFile-com.aspose.pdf.FileSpecification-) | Establece la especificación del archivo en el que se encuentra el destino. |
| [setNewWindow](#setNewWindow-com.aspose.pdf.ExtendedBoolean-) | Establece una bandera que especifica si se debe abrir el documento de destino en una nueva ventana. |

### GoToRemoteAction {#GoToRemoteAction-java.lang.String-com.aspose.pdf.ExplicitDestination-}
Inicializa el objeto GoToRemoteAction.

### GoToRemoteAction {#GoToRemoteAction-java.lang.String-int-}
Inicializa el objeto GoToRemoteAction.

### getFile {#getFile--}
```
public FileSpecification getFile()
```

Obtiene la especificación del archivo en el que se encuentra el destino.

**Returns:**
Objeto FileSpecification

### getNewWindow {#getNewWindow--}
```
public ExtendedBoolean getNewWindow()
```

Obtiene una bandera que especifica si se debe abrir el documento de destino en una nueva ventana.

**Returns:**
Elemento ExtendedBoolean @see ExtendedBoolean

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
/ * / * Obtiene el destino al que saltar. / * / * / *

### setFile {#setFile-com.aspose.pdf.FileSpecification-}
Establece la especificación del archivo en el que se encuentra el destino.

### setNewWindow {#setNewWindow-com.aspose.pdf.ExtendedBoolean-}
Establece una bandera que especifica si se debe abrir el documento de destino en una nueva ventana.
