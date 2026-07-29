---
title: "RichMediaAnnotation"
linktitle: "RichMediaAnnotation"
second_title: "Aspose.PDF for Java API 参考"
description: "描述 RichMediaAnnotation 的类，该类允许将视频/音频数据嵌入 PDF 文档。"
type: docs
weight: 4260
url: /zh/java/com.aspose.pdf/richmediaannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.RichMediaAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.RichMediaAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.RichMediaAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class RichMediaAnnotation extends Annotation
```

描述 RichMediaAnnotation 的类，该类允许将视频/音频数据嵌入 PDF 文档。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RichMediaAnnotation](#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 初始化 RichMediaAnnotation。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 接受此注释的访问者。 |
| [addCustomData](#addCustomData-java.lang.String-java.io.InputStream-) | 添加自定义命名数据（例如 flash 脚本所需）。 |
| [getActivateOn](#getActivateOn--) | 激活应用程序的事件。 |
| [getAnnotationType](#getAnnotationType--) | 获取注释类型。 |
| [getContent](#getContent--) | Rich Media 内容的数据。 |
| [getCustomFlashVariables](#getCustomFlashVariables--) | 设置或获取传递给播放器的 flash 变量。 |
| [getCustomPlayer](#getCustomPlayer--) | 设置或获取用于播放视频/音频数据的自定义 flash 播放器。 |
| [getType](#getType--) | 获取或设置内容类型。可能的值：Audio，Video。 |
| [setActivateOn](#setActivateOn-int-) | 激活应用程序的事件。 |
| [setContent](#setContent-java.lang.String-java.io.InputStream-) | 设置内容流。 |
| [setCustomFlashVariables](#setCustomFlashVariables-java.lang.String-) | 设置或获取传递给播放器的 flash 变量。 |
| [setCustomPlayer](#setCustomPlayer-java.io.InputStream-) | 设置或获取用于播放视频/音频数据的自定义 flash 播放器。 |
| [setPoster](#setPoster-java.io.InputStream-) | 设置注释的海报。 |
| [setType](#setType-int-) | 获取或设置内容类型。可能的值：Audio，Video。 |
| [update](#update--) | 使用指定参数更新数据。 |

### RichMediaAnnotation {#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
初始化 RichMediaAnnotation。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
接受此注释的访问者。

### addCustomData {#addCustomData-java.lang.String-java.io.InputStream-}
添加自定义命名数据（例如 flash 脚本所需）。

### getActivateOn {#getActivateOn--}
```
public int getActivateOn()
```

激活应用程序的事件。

**Returns:**
ActivationEvent 元素

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

获取注释类型。

**Returns:**
AnnotationType 元素 @see AnnotationType

### getContent {#getContent--}
```
public InputStream getContent()
```

Rich Media 内容的数据。

**Returns:**
InputStream 对象

### getCustomFlashVariables {#getCustomFlashVariables--}
```
public String getCustomFlashVariables()
```

设置或获取传递给播放器的 flash 变量。

**Returns:**
字符串对象

### getCustomPlayer {#getCustomPlayer--}
```
public InputStream getCustomPlayer()
```

设置或获取用于播放视频/音频数据的自定义 flash 播放器。

**Returns:**
InputStream 对象

### getType {#getType--}
```
public int getType()
```

获取或设置内容类型。可能的值：Audio，Video。

**Returns:**
ContentType 值 @see ContentType

### setActivateOn {#setActivateOn-int-}
```
public void setActivateOn(int value)
```

激活应用程序的事件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | ActivationEvent 元素 |

### setContent {#setContent-java.lang.String-java.io.InputStream-}
设置内容流。

### setCustomFlashVariables {#setCustomFlashVariables-java.lang.String-}
设置或获取传递给播放器的 flash 变量。

### setCustomPlayer {#setCustomPlayer-java.io.InputStream-}
设置或获取用于播放视频/音频数据的自定义 flash 播放器。

### setPoster {#setPoster-java.io.InputStream-}
设置注释的海报。

### setType {#setType-int-}
```
public void setType(int value)
```

获取或设置内容类型。可能的值：Audio，Video。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | ContentType 元素 |

### update {#update--}
```
public void update()
```

使用指定参数更新数据。
