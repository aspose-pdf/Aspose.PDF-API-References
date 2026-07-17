---
title: PageInformationAnnotation
linktitle: PageInformationAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents a Page Information annotation in a PDF document. This annotation contains the file name, page number, and the date and time of the annotation creation. This class is.
type: docs
weight: 3380
url: /java/com.aspose.pdf/pageinformationannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.PageInformationAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.PageInformationAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.PageInformationAnnotation, com.aspose.pdf.PrinterMarkAnnotation, com.aspose.pdf.PageInformationAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PageInformationAnnotation extends PrinterMarkAnnotation
```

Represents a Page Information annotation in a PDF document. This annotation contains the file name, page number, and the date and time of the annotation creation. This class is primarily used to add metadata to a specific page in the PDF document, which can be useful for tracking and referencing purposes. For instance, it can be used to mark pages during the printing process or to provide additional information about the page when viewing the document.

## Constructors

| Constructor | Description |
| --- | --- |
| [PageInformationAnnotation](#PageInformationAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Initializes a new instance of the {@link PageInformationAnnotation} class on the given page in the given location. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor for annotation processing. |
| [getAnnotationType](#getAnnotationType--) | Gets type of annotation. |

### PageInformationAnnotation {#PageInformationAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Initializes a new instance of the {@link PageInformationAnnotation} class on the given page in the given location.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepts visitor for annotation processing.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Gets type of annotation.

**Returns:**
int value
