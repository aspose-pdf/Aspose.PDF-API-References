---
title: "PageInformationAnnotation"
linktitle: "PageInformationAnnotation"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una anotación de Información de Página en un documento PDF. Esta anotación contiene el nombre del archivo, el número de página y la fecha y hora de creación de la anotación. Esta clase es."
type: docs
weight: 3380
url: /es/java/com.aspose.pdf/pageinformationannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.PageInformationAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.PageInformationAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.PageInformationAnnotation, com.aspose.pdf.PrinterMarkAnnotation, com.aspose.pdf.PageInformationAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PageInformationAnnotation extends PrinterMarkAnnotation
```

Representa una anotación Page Information en un documento PDF. Esta anotación contiene el nombre del archivo, el número de página y la fecha y hora de creación de la anotación. Esta clase se utiliza principalmente para agregar metadatos a una página específica del documento PDF, lo que puede ser útil para fines de seguimiento y referencia. Por ejemplo, puede usarse para marcar páginas durante el proceso de impresión o para proporcionar información adicional sobre la página al visualizar el documento.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PageInformationAnnotation](#PageInformationAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Inicializa una nueva instancia de la clase {@link PageInformationAnnotation} en la página dada en la ubicación especificada. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Acepta visitante para el procesamiento de anotaciones. |
| [getAnnotationType](#getAnnotationType--) | Obtiene el tipo de anotación. |

### PageInformationAnnotation {#PageInformationAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Inicializa una nueva instancia de la clase {@link PageInformationAnnotation} en la página dada en la ubicación especificada.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Acepta visitante para el procesamiento de anotaciones.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtiene el tipo de anotación.

**Returns:**
valor int
