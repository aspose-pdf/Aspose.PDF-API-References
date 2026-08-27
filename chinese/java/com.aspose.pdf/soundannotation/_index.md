---
title: "SoundAnnotation"
linktitle: "SoundAnnotation"
second_title: "Aspose.PDF for Java API 参考"
description: "表示包含从计算机麦克风录制或从文件导入的声音的声音注释。"
type: docs
weight: 4530
url: /zh/java/com.aspose.pdf/soundannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.SoundAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class SoundAnnotation extends MarkupAnnotation
```

表示包含从计算机麦克风录制或从文件导入的声音的声音注释。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SoundAnnotation](#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | 在指定页面上创建新的 Sound 注释。 |
| [SoundAnnotation](#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-com.aspose.pdf.SoundSampleData-) | 在指定页面上创建新的 Sound 注释。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 接受访问者对象以处理该注释。 |
| [getAnnotationType](#getAnnotationType--) | 获取注释类型。 |
| [getIcon](#getIcon--) | 获取用于显示注释的图标。 |
| [getSoundData](#getSoundData--) | 获取一个声音对象，定义在激活注释时要播放的声音。 |
| [setIcon](#setIcon-int-) | 设置用于显示注释的图标。 |

### SoundAnnotation {#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
在指定页面上创建新的 Sound 注释。

### SoundAnnotation {#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-com.aspose.pdf.SoundSampleData-}
在指定页面上创建新的 Sound 注释。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
接受访问者对象以处理该注释。

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

获取注释类型。

**Returns:**
AnnotationType 值 @see AnnotationType

### getIcon {#getIcon--}
```
public int getIcon()
```

获取用于显示注释的图标。

**Returns:**
SoundIcon 值 @see SoundIcon

### getSoundData {#getSoundData--}
```
public SoundData getSoundData()
```

获取一个声音对象，定义在激活注释时要播放的声音。

**Returns:**
SoundData 值

### setIcon {#setIcon-int-}
```
public void setIcon(int value)
```

设置用于显示注释的图标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | SoundIcon 值 @see SoundIcon |
