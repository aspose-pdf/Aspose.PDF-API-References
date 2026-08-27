---
title: "FieldSerializationResult"
linktitle: "FieldSerializationResult"
second_title: "Aspose.PDF for Java API 参考"
description: "表示表单字段序列化过程的结果。"
type: docs
weight: 1390
url: /zh/java/com.aspose.pdf/fieldserializationresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FieldSerializationResult

```
public class FieldSerializationResult extends Object
```

表示表单字段序列化过程的结果。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FieldSerializationResult](#FieldSerializationResult--) | 初始化 {@link FieldSerializationResult} 类的新实例。 |
| [FieldSerializationResult](#FieldSerializationResult-java.lang.String-) | 初始化 {@link FieldSerializationResult} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getErrorMessages](#getErrorMessages--) | 获取与序列化过程相关的错误消息。值：一组错误消息。 |
| [getFieldFullName](#getFieldFullName--) | 获取字段的完整名称。值：字段的完整名称。 |
| [getFieldSerializationStatus](#getFieldSerializationStatus--) | 获取表单字段序列化的状态。值：表单字段的序列化状态。 |
| [getWarningMessages](#getWarningMessages--) | 获取与序列化过程相关的警告消息。值：一组警告消息。 |
| [updateStatus](#updateStatus-int-java.lang.String-) | 更新序列化状态并将消息添加到相应的集合中。 |

### FieldSerializationResult {#FieldSerializationResult--}
```
public FieldSerializationResult()
```

初始化 {@link FieldSerializationResult} 类的新实例。

### FieldSerializationResult {#FieldSerializationResult-java.lang.String-}
初始化 {@link FieldSerializationResult} 类的新实例。

### getErrorMessages {#getErrorMessages--}
```
public final HashSet < String > getErrorMessages()
```

获取与序列化过程相关的错误消息。值：一组错误消息。

**Returns:**
String 实例的 HashSet

### getFieldFullName {#getFieldFullName--}
```
public final String getFieldFullName()
```

获取字段的完整名称。值：字段的完整名称。

**Returns:**
字符串值

### getFieldSerializationStatus {#getFieldSerializationStatus--}
```
public final int getFieldSerializationStatus()
```

获取表单字段序列化的状态。值：表单字段的序列化状态。

**Returns:**
FieldSerializationStatus 元素

### getWarningMessages {#getWarningMessages--}
```
public final HashSet < String > getWarningMessages()
```

获取与序列化过程相关的警告消息。值：一组警告消息。

**Returns:**
String 实例的 HashSet

### updateStatus {#updateStatus-int-java.lang.String-}
更新序列化状态并将消息添加到相应的集合中。
