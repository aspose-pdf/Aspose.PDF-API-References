---
title: "OutputIntent"
linktitle: "OutputIntent"
second_title: "Aspose.PDF for Java API 参考"
description: "表示一种输出意图，使 PDF 文档的颜色特性与目标输出设备或生产环境的颜色特性相匹配。"
type: docs
weight: 3290
url: /zh/java/com.aspose.pdf/outputintent/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.OutputIntent

```
public final class OutputIntent extends Object
```

表示一种输出意图，使 PDF 文档的颜色特性与目标输出设备或文档将被打印的生产环境的颜色特性相匹配。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OutputIntent](#OutputIntent-java.lang.String-) | 使用指定的输出条件标识符初始化 {@link OutputIntent} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getInfo](#getInfo--) | 获取可读的文本，包含有关预期目标设备或生产条件的附加信息或注释。 |
| [getOutputCondition](#getOutputCondition--) | 获取一段简洁标识预期输出设备或生产条件的可读文本。 |
| [getOutputConditionIdentifier](#getOutputConditionIdentifier--) | 获取一段以人类或机器可读形式标识预期输出设备或生产条件的文本。 |
| [getRegistryName](#getRegistryName--) | 获取标识定义了由 {@code OutputConditionIdentifier}（{@link #getOutputConditionIdentifier}）指定的条件的注册表的文本。 |
| [getSubtype](#getSubtype--) | 获取输出意图子类型。 |
| [setInfo](#setInfo-java.lang.String-) | 设置包含有关预期目标设备或生产条件的附加信息或注释的可读文本。 |
| [setOutputCondition](#setOutputCondition-java.lang.String-) | 获取或设置一段简洁标识预期输出设备或生产条件的文本（人类可读形式）。 |
| [setOutputConditionIdentifier](#setOutputConditionIdentifier-java.lang.String-) | 设置一段以人类或机器可读形式标识预期输出设备或生产条件的文本。 |
| [setRegistryName](#setRegistryName-java.lang.String-) | 设置一段文本，用于标识定义了由 {@code OutputConditionIdentifier}（{@link #getOutputConditionIdentifier}/{@link #setOutputConditionIdentifier(String)}）指定的条件的注册表。 |

### OutputIntent {#OutputIntent-java.lang.String-}
使用指定的输出条件标识符初始化 {@link OutputIntent} 类的新实例。

### getInfo {#getInfo--}
```
public final String getInfo()
```

获取可读的文本，包含有关预期目标设备或生产条件的附加信息或注释。

**Returns:**
字符串值

### getOutputCondition {#getOutputCondition--}
```
public final String getOutputCondition()
```

获取一段简洁标识预期输出设备或生产条件的可读文本。

**Returns:**
字符串值

### getOutputConditionIdentifier {#getOutputConditionIdentifier--}
```
public final String getOutputConditionIdentifier()
```

获取一段以人类或机器可读形式标识预期输出设备或生产条件的文本。

**Returns:**
字符串值

### getRegistryName {#getRegistryName--}
```
public final String getRegistryName()
```

获取标识定义了由 {@code OutputConditionIdentifier}（{@link #getOutputConditionIdentifier}）指定的条件的注册表的文本。

**Returns:**
字符串值

### getSubtype {#getSubtype--}
```
public final String getSubtype()
```

获取输出意图子类型。

**Returns:**
字符串值

### setInfo {#setInfo-java.lang.String-}
设置包含有关预期目标设备或生产条件的附加信息或注释的可读文本。

### setOutputCondition {#setOutputCondition-java.lang.String-}
获取或设置一段简洁标识预期输出设备或生产条件的文本（人类可读形式）。

### setOutputConditionIdentifier {#setOutputConditionIdentifier-java.lang.String-}
设置一段以人类或机器可读形式标识预期输出设备或生产条件的文本。

### setRegistryName {#setRegistryName-java.lang.String-}
设置一段文本，用于标识定义了由 {@code OutputConditionIdentifier}（{@link #getOutputConditionIdentifier}/{@link #setOutputConditionIdentifier(String)}）指定的条件的注册表。
