---
title: FileAttachmentAnnotation
second_title: Aspose.PDF for Java API Reference
description: Class describes file attachment annotation.
type: docs
weight: 109
url: /java/com.aspose.pdf/fileattachmentannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.MarkupAnnotation](../../com.aspose.pdf/markupannotation)
```
public final class FileAttachmentAnnotation extends MarkupAnnotation
```

Class describes file attachment annotation.
## Constructors

| Constructor | Description |
| --- | --- |
| [FileAttachmentAnnotation(Page page, Rectangle rect, FileSpecification fileSpec)](#FileAttachmentAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.FileSpecification-) | Creates new FileAttachment annotation on the specified page. |
## Methods

| Method | Description |
| --- | --- |
| [getAnnotationType()](#getAnnotationType--) | Gets type of annotation. |
| [getFile()](#getFile--) | Get specification of the file associated with this annotation. |
| [setFile(FileSpecification value)](#setFile-com.aspose.pdf.FileSpecification-) | Set specification of the file associated with this annotation. |
| [getIcon()](#getIcon--) | Gets icon that shall be used in displaying annotation. |
| [setIcon(int value)](#setIcon-int-) | Sets icon that shall be used in displaying annotation. |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process annotation. |
### FileAttachmentAnnotation(Page page, Rectangle rect, FileSpecification fileSpec) {#FileAttachmentAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.FileSpecification-}
```
public FileAttachmentAnnotation(Page page, Rectangle rect, FileSpecification fileSpec)
```


Creates new FileAttachment annotation on the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Document's page where annotation should be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Required rectangle that sets annotation's border. |
| fileSpec | [FileSpecification](../../com.aspose.pdf/filespecification) | Describes the file that shoud be bound with the annotation. |

### getAnnotationType() {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```


Gets type of annotation.

**Returns:**
[AnnotationType](../../com.aspose.pdf/annotationtype) - int value
### getFile() {#getFile--}
```
public FileSpecification getFile()
```


Get specification of the file associated with this annotation.

**Returns:**
[FileSpecification](../../com.aspose.pdf/filespecification) - file specification.
### setFile(FileSpecification value) {#setFile-com.aspose.pdf.FileSpecification-}
```
public void setFile(FileSpecification value)
```


Set specification of the file associated with this annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FileSpecification](../../com.aspose.pdf/filespecification) | file specification. |

### getIcon() {#getIcon--}
```
public int getIcon()
```


Gets icon that shall be used in displaying annotation.

**Returns:**
int - FileIcon value
### setIcon(int value) {#setIcon-int-}
```
public void setIcon(int value)
```


Sets icon that shall be used in displaying annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | FileIcon value |

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts visitor object to process annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor object. |

