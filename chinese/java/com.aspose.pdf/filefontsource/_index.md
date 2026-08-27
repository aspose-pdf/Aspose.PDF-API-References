---
title: "FileFontSource"
linktitle: "FileFontSource"
second_title: "Aspose.PDF for Java API 参考"
description: "表示单个字体文件来源。"
type: docs
weight: 1450
url: /zh/java/com.aspose.pdf/filefontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.FileFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.FileFontSource

```
public final class FileFontSource extends FontSource
```

表示单个字体文件来源。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FileFontSource](#FileFontSource-java.lang.String-) | 初始化 {@code FileFontSource} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [equals](#equals-java.lang.Object-) | 检查字体文件源对象是否相等。 |
| [getFilePath](#getFilePath--) | 字体文件的路径。 |
| [hashCode](#hashCode--) | 返回对象的哈希码值。此方法支持用于诸如 {@link java.util.HashMap} 提供的哈希表。 <p> {@code hashCode} 的一般约定是： <ul> <li>当在同一对象上在一次 Java 应用程序执行期间多次调用时，{@code hashCode} 方法必须始终返回相同的整数，前提是用于 {@code equals} 比较的对象信息未被修改。该整数在一次执行与另一执行之间不必保持一致。 <li>如果两个对象根据 {@code equals(Object)} 方法相等，则对这两个对象调用 {@code hashCode} 方法必须产生相同的整数结果。 <li>如果两个对象根据 {@link java.lang.Object#equals(java.lang.Object)} 方法不相等，则不要求 {@code hashCode} 方法对这两个对象返回不同的整数结果。不过，程序员应注意，为不相等的对象产生不同的整数结果可能会提升哈希表的性能。 </ul> <p> 在合理可行的范围内，类 {@code Object} 定义的 hashCode 方法确实会为不同的对象返回不同的整数。（这通常通过将对象的内部地址转换为整数实现，但 Java <span style=\"font-size:70%\"><sup>TM</sup></span> 编程语言并未强制要求此实现技术。） |
| [setFilePath](#setFilePath-java.lang.String-) | 字体文件的路径。 |

### FileFontSource {#FileFontSource-java.lang.String-}
初始化 {@code FileFontSource} 类的新实例。

### equals {#equals-java.lang.Object-}
检查字体文件源对象是否相等。

### getFilePath {#getFilePath--}
```
public String getFilePath()
```

字体文件的路径。

**Returns:**
字符串值

### hashCode {#hashCode--}
```
public int hashCode()
```

返回对象的哈希码值。此方法支持用于诸如 {@link java.util.HashMap} 提供的哈希表。 <p> {@code hashCode} 的一般约定是： <ul> <li>当在同一对象上在一次 Java 应用程序执行期间多次调用时，{@code hashCode} 方法必须始终返回相同的整数，前提是用于 {@code equals} 比较的对象信息未被修改。该整数在一次执行与另一执行之间不必保持一致。 <li>如果两个对象根据 {@code equals(Object)} 方法相等，则对这两个对象调用 {@code hashCode} 方法必须产生相同的整数结果。 <li>如果两个对象根据 {@link java.lang.Object#equals(java.lang.Object)} 方法不相等，则不要求 {@code hashCode} 方法对这两个对象返回不同的整数结果。不过，程序员应注意，为不相等的对象产生不同的整数结果可能会提升哈希表的性能。 </ul> <p> 在合理可行的范围内，类 {@code Object} 定义的 hashCode 方法确实会为不同的对象返回不同的整数。（这通常通过将对象的内部地址转换为整数实现，但 Java <span style=\"font-size:70%\"><sup>TM</sup></span> 编程语言并未强制要求此实现技术。）

**Returns:**
此对象的哈希码值。 @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### setFilePath {#setFilePath-java.lang.String-}
字体文件的路径。
