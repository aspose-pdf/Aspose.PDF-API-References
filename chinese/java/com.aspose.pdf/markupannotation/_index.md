---
title: "MarkupAnnotation"
linktitle: "MarkupAnnotation"
second_title: "Aspose.PDF for Java API 参考"
description: "表示标记注释的抽象类。"
type: docs
weight: 2870
url: /zh/java/com.aspose.pdf/markupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class MarkupAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

表示标记注释的抽象类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MarkupAnnotation](#MarkupAnnotation--) | 构造函数 |
| [MarkupAnnotation](#MarkupAnnotation-com.aspose.pdf.IDocument-) | 构造函数 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [clearState](#clearState--) | 清除注释的状态和状态模型。例如，清除注释的审阅状态。注意，状态存储在具有 state 和 statemodel 键的其他文本注释中。 |
| [getCreationDate](#getCreationDate--) | 获取注释创建的日期和时间。 |
| [getInReplyTo](#getInReplyTo--) | 对该注释所"in reply to"的注释的引用。两个注释必须位于文档的同一页上。 |
| [getOpacity](#getOpacity--) | 获取用于绘制注释的常量不透明度值。 |
| [getPopup](#getPopup--) | 用于输入或编辑与此注释关联的文本的弹出注释。 |
| [getReplyType](#getReplyType--) | 指定此注释与 InReplyTo 指定的注释之间关系（"reply type"）的字符串。 |
| [getRichText](#getRichText--) | 获取在打开注释时显示在弹出窗口中的富文本字符串。 |
| [getRichText](#getRichText-com.aspose.pdf.engine.data.IPdfDictionary-) | 获取在打开注释时显示在弹出窗口中的富文本字符串。 |
| [getState](#getState--) | 获取注释的状态。注意，状态存储在具有 state 和 statemodel 键的其他文本注释中。 |
| [getStateModel](#getStateModel--) | 获取注释的状态模型。注意，状态存储在具有 state 和 statemodel 键的其他文本注释中。 |
| [getSubject](#getSubject--) | 获取表示对象描述的文本。 |
| [getTitle](#getTitle--) | 获取在注释пїЅs 弹出窗口标题栏中打开且激活时应显示的文本标签。此条目应标识添加该注释的用户。 |
| [setCreationDate](#setCreationDate-java.util.Date-) | 获取注释创建的日期和时间。 |
| [setInReplyTo](#setInReplyTo-com.aspose.pdf.Annotation-) | 对该注释所"in reply to"的注释的引用。两个注释必须位于文档的同一页上。 |
| [setMarkedState](#setMarkedState-boolean-) | 为注释设置已标记和未标记状态。注意，状态存储在具有 state 和 statemodel 键的其他文本注释中。 |
| [setOpacity](#setOpacity-double-) | 设置用于绘制注释的常量不透明度值。 |
| [setPopup](#setPopup-com.aspose.pdf.PopupAnnotation-) | 用于输入或编辑与此注释关联的文本的弹出注释。 |
| [setReplyType](#setReplyType-com.aspose.pdf.ReplyType-) | 指定此注释与 InReplyTo 指定的注释之间关系（"reply type"）的字符串。 |
| [setReviewState](#setReviewState-com.aspose.pdf.AnnotationState-) | 为注释设置审阅状态。已标记和未标记状态将被忽略，因为它们不属于 Review StateModel。该状态由创建目标注释的用户设置。值取自目标注释的 Title 属性。注意，状态存储在具有 state 和 statemodel 键的其他文本注释中。 |
| [setReviewState](#setReviewState-com.aspose.pdf.AnnotationState-java.lang.String-) | 为注释设置审阅状态。已标记和未标记状态将被忽略，因为它们不属于 Review StateModel。注意，状态存储在具有 state 和 statemodel 键的其他文本注释中。 |
| [setRichText](#setRichText-java.lang.String-) | 设置在打开注释时显示在弹出窗口中的富文本字符串。 |
| [setSubject](#setSubject-java.lang.String-) | 设置表示对象描述的文本。 |
| [setTitle](#setTitle-java.lang.String-) | 设置在注释пїЅs 弹出窗口标题栏中打开且激活时应显示的文本标签。此条目应标识添加该注释的用户。 |

### MarkupAnnotation {#MarkupAnnotation--}
```
public MarkupAnnotation()
```

构造函数

### MarkupAnnotation {#MarkupAnnotation-com.aspose.pdf.IDocument-}
构造函数

### clearState {#clearState--}
```
public final void clearState()
```

清除注释的状态和状态模型。例如，清除注释的审阅状态。注意，状态存储在具有 state 和 statemodel 键的其他文本注释中。

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

获取注释创建的日期和时间。

**Returns:**
Date 对象

### getInReplyTo {#getInReplyTo--}
```
public Annotation getInReplyTo()
```

对该注释所"in reply to"的注释的引用。两个注释必须位于文档的同一页上。

**Returns:**
注释值

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

获取用于绘制注释的常量不透明度值。

**Returns:**
double 值

### getPopup {#getPopup--}
```
public PopupAnnotation getPopup()
```

用于输入或编辑与此注释关联的文本的弹出注释。

**Returns:**
PopupAnnotation 值

### getReplyType {#getReplyType--}
```
public ReplyType getReplyType()
```

指定此注释与 InReplyTo 指定的注释之间关系（"reply type"）的字符串。

**Returns:**
ReplyType 值 @see ReplyType

### getRichText {#getRichText--}
```
public final String getRichText()
```

获取在打开注释时显示在弹出窗口中的富文本字符串。

**Returns:**
字符串值

### getRichText {#getRichText-com.aspose.pdf.engine.data.IPdfDictionary-}
获取在打开注释时显示在弹出窗口中的富文本字符串。

**Returns:**
字符串值

### getState {#getState--}
```
public final AnnotationState getState()
```

获取注释的状态。注意，状态存储在具有 state 和 statemodel 键的其他文本注释中。

**Returns:**
注释状态。

### getStateModel {#getStateModel--}
```
public final AnnotationStateModel getStateModel()
```

获取注释的状态模型。注意，状态存储在具有 state 和 statemodel 键的其他文本注释中。

**Returns:**
注释状态模型。

### getSubject {#getSubject--}
```
public String getSubject()
```

获取表示对象描述的文本。

**Returns:**
字符串值

### getTitle {#getTitle--}
```
public String getTitle()
```

获取在注释пїЅs 弹出窗口标题栏中打开且激活时应显示的文本标签。此条目应标识添加该注释的用户。

**Returns:**
字符串值

### setCreationDate {#setCreationDate-java.util.Date-}
获取注释创建的日期和时间。

### setInReplyTo {#setInReplyTo-com.aspose.pdf.Annotation-}
对该注释所"in reply to"的注释的引用。两个注释必须位于文档的同一页上。

### setMarkedState {#setMarkedState-boolean-}
```
public final void setMarkedState(boolean marked)
```

为注释设置已标记和未标记状态。注意，状态存储在具有 state 和 statemodel 键的其他文本注释中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 已标记 |  | 如果设置为已标记状态则为 true，设置为未标记状态则为 false。 |

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

设置用于绘制注释的常量不透明度值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setPopup {#setPopup-com.aspose.pdf.PopupAnnotation-}
用于输入或编辑与此注释关联的文本的弹出注释。

### setReplyType {#setReplyType-com.aspose.pdf.ReplyType-}
指定此注释与 InReplyTo 指定的注释之间关系（"reply type"）的字符串。

### setReviewState {#setReviewState-com.aspose.pdf.AnnotationState-}
为注释设置审阅状态。已标记和未标记状态将被忽略，因为它们不属于 Review StateModel。该状态由创建目标注释的用户设置。值取自目标注释的 Title 属性。注意，状态存储在具有 state 和 statemodel 键的其他文本注释中。

### setReviewState {#setReviewState-com.aspose.pdf.AnnotationState-java.lang.String-}
为注释设置审阅状态。已标记和未标记状态将被忽略，因为它们不属于 Review StateModel。注意，状态存储在具有 state 和 statemodel 键的其他文本注释中。

### setRichText {#setRichText-java.lang.String-}
设置在打开注释时显示在弹出窗口中的富文本字符串。

### setSubject {#setSubject-java.lang.String-}
设置表示对象描述的文本。

### setTitle {#setTitle-java.lang.String-}
设置在注释пїЅs 弹出窗口标题栏中打开且激活时应显示的文本标签。此条目应标识添加该注释的用户。
