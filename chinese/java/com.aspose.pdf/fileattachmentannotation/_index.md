---
title: "FileAttachmentAnnotation"
linktitle: "FileAttachmentAnnotation"
second_title: "Aspose.PDF for Java API 参考"
description: "描述文件附件注释的类。"
type: docs
weight: 1430
url: /zh/java/com.aspose.pdf/fileattachmentannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FileAttachmentAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FileAttachmentAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FileAttachmentAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.FileAttachmentAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class FileAttachmentAnnotation extends MarkupAnnotation
```

描述文件附件注释的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FileAttachmentAnnotation](#FileAttachmentAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.FileSpecification-) | 在指定页面上创建新的 FileAttachment 注释。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 接受 visitor 对象以处理注释。 |
| [getAnnotationType](#getAnnotationType--) | 获取注释类型。 |
| [getFile](#getFile--) | 获取与此注释关联的文件规范。 |
| [getIcon](#getIcon--) | 获取用于显示注释的图标。 |
| [setFile](#setFile-com.aspose.pdf.FileSpecification-) | 设置与此注释关联的文件规范。 |
| [setIcon](#setIcon-com.aspose.pdf.FileIcon-) | 设置用于显示注释的图标。 |

### FileAttachmentAnnotation {#FileAttachmentAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.FileSpecification-}
在指定页面上创建新的 FileAttachment 注释。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
接受 visitor 对象以处理注释。

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

获取注释类型。

**Returns:**
整数值 @see AnnotationType

### getFile {#getFile--}
```
public FileSpecification getFile()
```

获取与此注释关联的文件规范。

**Returns:**
文件规范。

### getIcon {#getIcon--}
```
public FileIcon getIcon()
```

获取用于显示注释的图标。

**Returns:**
FileIcon 值 @see FileIcon

### setFile {#setFile-com.aspose.pdf.FileSpecification-}
设置与此注释关联的文件规范。

### setIcon {#setIcon-com.aspose.pdf.FileIcon-}
设置用于显示注释的图标。
