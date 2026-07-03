---
title: FileAttachmentAnnotation
second_title: Aspose.PDF for Java API Reference
description: Class describes file attachment annotation.
type: docs
weight: 1430
url: /java/com.aspose.pdf/fileattachmentannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FileAttachmentAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FileAttachmentAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FileAttachmentAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.FileAttachmentAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class FileAttachmentAnnotation extends MarkupAnnotation
```

Class describes file attachment annotation.

## Constructors

| Constructor | Description |
| --- | --- |
| [FileAttachmentAnnotation](#FileAttachmentAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.FileSpecification-) | Creates new FileAttachment annotation on the specified page. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process annotation. |
| [getAnnotationType](#getAnnotationType--) | Gets type of annotation. |
| [getFile](#getFile--) | Get specification of the file associated with this annotation. |
| [getIcon](#getIcon--) | Gets icon that shall be used in displaying annotation. |
| [setFile](#setFile-com.aspose.pdf.FileSpecification-) | Set specification of the file associated with this annotation. |
| [setIcon](#setIcon-com.aspose.pdf.FileIcon-) | Sets icon that shall be used in displaying annotation. |

### FileAttachmentAnnotation {#FileAttachmentAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.FileSpecification-}
Creates new FileAttachment annotation on the specified page.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepts visitor object to process annotation.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Gets type of annotation.

**Returns:**
int value @see AnnotationType

### getFile {#getFile--}
```
public FileSpecification getFile()
```

Get specification of the file associated with this annotation.

**Returns:**
file specification.

### getIcon {#getIcon--}
```
public FileIcon getIcon()
```

Gets icon that shall be used in displaying annotation.

**Returns:**
FileIcon value @see FileIcon

### setFile {#setFile-com.aspose.pdf.FileSpecification-}
Set specification of the file associated with this annotation.

### setIcon {#setIcon-com.aspose.pdf.FileIcon-}
Sets icon that shall be used in displaying annotation.
