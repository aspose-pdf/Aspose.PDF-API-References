---
title: "LinkAnnotation"
linktitle: "LinkAnnotation"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa ya sea un enlace hipertexto a un destino en otra parte del documento o una acción a realizar."
type: docs
weight: 2760
url: /es/java/com.aspose.pdf/linkannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.LinkAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.LinkAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.LinkAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class LinkAnnotation extends Annotation
```

Representa ya sea un enlace hipertexto a un destino en otra parte del documento o una acción a realizar.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [LinkAnnotation](#LinkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Crea una nueva anotación Link en la página especificada. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Acepta un objeto visitante para procesar la anotación. |
| [getAction](#getAction--) | Obtiene una acción que se ejecutará cuando se active la anotación link. |
| [getAnnotationType](#getAnnotationType--) | Obtiene el tipo de anotación. |
| [getDestination](#getDestination--) | Obtiene un destino que se mostrará cuando se active la anotación. |
| [getHighlighting](#getHighlighting--) | Obtiene el efecto visual que se usará cuando se presione o mantenga pulsado el botón del ratón dentro de su área activa. |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | Establece una acción a realizar cuando se active la anotación link. |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | Establece un destino que se mostrará cuando se active la anotación. |
| [setHighlighting](#setHighlighting-com.aspose.pdf.HighlightingMode-) | Establece el efecto visual que se usará cuando se presione o mantenga pulsado el botón del ratón dentro de su área activa. |

### LinkAnnotation {#LinkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Crea una nueva anotación Link en la página especificada.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Acepta un objeto visitante para procesar la anotación.

### getAction {#getAction--}
```
public PdfAction getAction()
```

Obtiene una acción que se ejecutará cuando se active la anotación link.

**Returns:**
Valor PdfAction

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtiene el tipo de anotación.

**Returns:**
Elemento AnnotationType @see AnnotationType

### getDestination {#getDestination--}
```
public IAppointment getDestination()
```

Obtiene un destino que se mostrará cuando se active la anotación.

**Returns:**
valor IAppointment

### getHighlighting {#getHighlighting--}
```
public HighlightingMode getHighlighting()
```

Obtiene el efecto visual que se usará cuando se presione o mantenga pulsado el botón del ratón dentro de su área activa.

**Returns:**
Elemento HighlightingMode @see HighlightingMode

### setAction {#setAction-com.aspose.pdf.PdfAction-}
Establece una acción a realizar cuando se active la anotación link.

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
Establece un destino que se mostrará cuando se active la anotación.

### setHighlighting {#setHighlighting-com.aspose.pdf.HighlightingMode-}
Establece el efecto visual que se usará cuando se presione o mantenga pulsado el botón del ratón dentro de su área activa.
