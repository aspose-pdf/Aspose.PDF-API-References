---
title: "ContentsAppender"
linktitle: "ContentsAppender"
second_title: "Aspose.PDF for Java API 参考"
description: "仅在 APPEND 模式下执行内容修改。此模式可避免在对内容进行更改之前进行不必要且繁重的内容解析。它仅追加新内容。"
type: docs
weight: 800
url: /zh/java/com.aspose.pdf/contentsappender/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ContentsAppender

```
public class ContentsAppender extends Object
```

仅在 APPEND 模式下执行内容修改。此模式可避免在对内容进行更改之前进行不必要且繁重的内容解析。它仅将新操作符追加到内容的末尾或开头。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ContentsAppender](#ContentsAppender-com.aspose.pdf.Page-) | 初始化一个附加页面的 contents appender 的新实例 |
| [ContentsAppender](#ContentsAppender-com.aspose.pdf.XForm-) | 初始化一个带有 Form XObject 的 contets appender 的新实例 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [appendToBegin](#appendToBegin-com.aspose.ms.System.Collections.Generic.List-) | 将操作符追加到内容的末尾 |
| [appendToBegin](#appendToBegin-com.aspose.pdf.Operator-) | 将操作符追加到内容的末尾 |
| [appendToBegin](#appendToBegin-com.aspose.pdf.Operator:A-) | 将操作符追加到内容的末尾 |
| [appendToEnd](#appendToEnd-com.aspose.ms.System.Collections.Generic.List-) | 将操作符追加到内容的开头 |
| [appendToEnd](#appendToEnd-com.aspose.pdf.Operator-) | 将操作符追加到内容的开头 |
| [appendToEnd](#appendToEnd-com.aspose.pdf.Operator:A-) | 将操作符追加到内容的开头 |
| [getBeginCode](#getBeginCode--) | 包含要插入页面起始位置的操作符的字符串。 |
| [getBeginOperators](#getBeginOperators--) | <p> 返回起始操作符 </p> |
| [getEndCode](#getEndCode--) | 包含要追加到页面末尾的操作符的字符串。 |
| [getEndOperators](#getEndOperators--) | <p> 返回结束操作符 </p> |
| [resumeUpdate](#resumeUpdate--) | 恢复文档更新 |
| [setBeginCode](#setBeginCode-java.lang.String-) | 包含要插入页面起始位置的操作符的字符串。 |
| [setEndCode](#setEndCode-java.lang.String-) | 包含要插入页面起始位置的操作符的字符串。 |
| [suppressUpdate](#suppressUpdate--) | 抑制内容数据的更新，内容在调用 ResumeUpdate 之前不会更新 |
| [updateData](#updateData--) | 这是 UpdateData 的新版本，可避免对现有内容进行解码。 |
| [updateDataOld](#updateDataOld--) | 必须调用以应用更改。 |

### ContentsAppender {#ContentsAppender-com.aspose.pdf.Page-}
初始化一个附加页面的 contents appender 的新实例

### ContentsAppender {#ContentsAppender-com.aspose.pdf.XForm-}
初始化一个带有 Form XObject 的 contets appender 的新实例

### appendToBegin {#appendToBegin-com.aspose.ms.System.Collections.Generic.List-}
将操作符追加到内容的末尾

### appendToBegin {#appendToBegin-com.aspose.pdf.Operator-}
将操作符追加到内容的末尾

### appendToBegin {#appendToBegin-com.aspose.pdf.Operator:A-}
将操作符追加到内容的末尾

### appendToEnd {#appendToEnd-com.aspose.ms.System.Collections.Generic.List-}
将操作符追加到内容的开头

### appendToEnd {#appendToEnd-com.aspose.pdf.Operator-}
将操作符追加到内容的开头

### appendToEnd {#appendToEnd-com.aspose.pdf.Operator:A-}
将操作符追加到内容的开头

### getBeginCode {#getBeginCode--}
```
public String getBeginCode()
```

包含要插入页面起始位置的操作符的字符串。

**Returns:**
字符串对象

### getBeginOperators {#getBeginOperators--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > getBeginOperators()
```

<p> 返回起始操作符 </p>

**Returns:**
{@code List<Operator>} 对象

### getEndCode {#getEndCode--}
```
public String getEndCode()
```

包含要追加到页面末尾的操作符的字符串。

**Returns:**
字符串对象

### getEndOperators {#getEndOperators--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > getEndOperators()
```

<p> 返回结束操作符 </p>

**Returns:**
{@code List<Operator>} 对象

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

恢复文档更新

### setBeginCode {#setBeginCode-java.lang.String-}
包含要插入页面起始位置的操作符的字符串。

### setEndCode {#setEndCode-java.lang.String-}
包含要插入页面起始位置的操作符的字符串。

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

抑制内容数据的更新，内容在调用 ResumeUpdate 之前不会更新

### updateData {#updateData--}
```
public void updateData()
```

这是 UpdateData 的新版本，可避免对现有内容进行解码。

### updateDataOld {#updateDataOld--}
```
public void updateDataOld()
```

必须调用以应用更改。
