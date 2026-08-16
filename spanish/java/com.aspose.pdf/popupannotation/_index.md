---
title: "PopupAnnotation"
linktitle: "PopupAnnotation"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa la anotación emergente que muestra texto en una ventana emergente para la introducción y edición."
type: docs
weight: 3930
url: /es/java/com.aspose.pdf/popupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PopupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PopupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PopupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PopupAnnotation extends Annotation
```

Representa la anotación emergente que muestra texto en una ventana emergente para la introducción y edición.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PopupAnnotation](#PopupAnnotation-com.aspose.pdf.IDocument-) | Constructor. para usar en Generator. |
| [PopupAnnotation](#PopupAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Crea una nueva anotación Popup en la página especificada. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Acepta un objeto visitante para procesar la anotación. |
| [getAnnotationType](#getAnnotationType--) | Obtiene el tipo de anotación. |
| [getOpen](#getOpen--) | Obtiene una bandera que indica si la anotación emergente debe mostrarse inicialmente abierta. |
| [getParent](#getParent--) | Obtiene la anotación principal con la que esta anotación emergente debe estar asociada. Si esta entrada está presente, las entradas Contents, M, C y T de la anotación principal sobrescribirán a las de la propia anotación emergente. |
| [setOpen](#setOpen-boolean-) | Establece una bandera que indica si la anotación emergente debe mostrarse inicialmente abierta. |
| [setParent](#setParent-com.aspose.pdf.MarkupAnnotation-) | Establece la anotación principal con la que esta anotación emergente debe estar asociada. Si esta entrada está presente, las entradas Contents, M, C y T de la anotación principal sobrescribirán a las de la propia anotación emergente. |

### PopupAnnotation {#PopupAnnotation-com.aspose.pdf.IDocument-}
Constructor. para usar en Generator.

### PopupAnnotation {#PopupAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Crea una nueva anotación Popup en la página especificada.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Acepta un objeto visitante para procesar la anotación.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtiene el tipo de anotación.

**Returns:**
Elemento AnnotationType @see AnnotationType

### getOpen {#getOpen--}
```
public boolean getOpen()
```

Obtiene una bandera que indica si la anotación emergente debe mostrarse inicialmente abierta.

**Returns:**
valor booleano

### getParent {#getParent--}
```
public Annotation getParent()
```

Obtiene la anotación principal con la que esta anotación emergente debe estar asociada. Si esta entrada está presente, las entradas Contents, M, C y T de la anotación principal sobrescribirán a las de la propia anotación emergente.

**Returns:**
Objeto MarkupAnnotation

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Establece una bandera que indica si la anotación emergente debe mostrarse inicialmente abierta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setParent {#setParent-com.aspose.pdf.MarkupAnnotation-}
Establece la anotación principal con la que esta anotación emergente debe estar asociada. Si esta entrada está presente, las entradas Contents, M, C y T de la anotación principal sobrescribirán a las de la propia anotación emergente.
