---
title: "SystemFontSource"
linktitle: "SystemFontSource"
second_title: "Aspose.PDF for Java API 参考"
description: "表示系统中已安装的所有字体。"
type: docs
weight: 4770
url: /zh/java/com.aspose.pdf/systemfontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.SystemFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.SystemFontSource

```
public final class SystemFontSource extends FontSource
```

表示系统中已安装的所有字体。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SystemFontSource](#SystemFontSource--) | 初始化类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [equals](#equals-java.lang.Object-) | 检查系统字体源对象是否相等。 |
| [getFontDefinitions](#getFontDefinitions--) | 仅供内部使用 |
| [hashCode](#hashCode--) | 返回对象的哈希码值。此方法支持哈希表，例如 {@link java.util.HashMap} 提供的哈希表。 <p> {@code hashCode} 的一般约定是： <ul> <li>只要在 Java 应用程序的执行期间对同一对象多次调用且未修改用于 {@code equals} 比较的信息，{@code hashCode} 方法必须始终返回相同的整数。该整数在一次应用执行与另一执行之间不必保持一致。 <li>如果两个对象根据 {@code equals(Object)} 方法相等，则对这两个对象调用 {@code hashCode} 方法必须产生相同的整数结果。 <li>并<em>不</em>要求如果两个对象根据 {@link java.lang.Object#equals(java.lang.Object)} 方法不相等，则对这两个对象调用 {@code hashCode} 方法必须产生不同的整数结果。不过，程序员应注意，为不相等的对象产生不同的整数可能会提升哈希表的性能。 </ul> <p> 在合理可行的范围内，类 {@code Object} 定义的 hashCode 方法确实会为不同对象返回不同的整数。（通常通过将对象的内部地址转换为整数来实现，但此实现技术并非 Java<span style="font-size:70%"><sup>TM</sup></span> 编程语言所要求。） |

### SystemFontSource {#SystemFontSource--}
```
public SystemFontSource()
```

初始化类的新实例。

### equals {#equals-java.lang.Object-}
检查系统字体源对象是否相等。

### getFontDefinitions {#getFontDefinitions--}
```
public com.aspose.font.FontDefinition[] getFontDefinitions()
```

仅供内部使用

**Returns:**
FontDefinition[] 对象

### hashCode {#hashCode--}
```
public int hashCode()
```

返回对象的哈希码值。此方法支持哈希表，例如 {@link java.util.HashMap} 提供的哈希表。 <p> {@code hashCode} 的一般约定是： <ul> <li>只要在 Java 应用程序的执行期间对同一对象多次调用且未修改用于 {@code equals} 比较的信息，{@code hashCode} 方法必须始终返回相同的整数。该整数在一次应用执行与另一执行之间不必保持一致。 <li>如果两个对象根据 {@code equals(Object)} 方法相等，则对这两个对象调用 {@code hashCode} 方法必须产生相同的整数结果。 <li>并<em>不</em>要求如果两个对象根据 {@link java.lang.Object#equals(java.lang.Object)} 方法不相等，则对这两个对象调用 {@code hashCode} 方法必须产生不同的整数结果。不过，程序员应注意，为不相等的对象产生不同的整数可能会提升哈希表的性能。 </ul> <p> 在合理可行的范围内，类 {@code Object} 定义的 hashCode 方法确实会为不同对象返回不同的整数。（通常通过将对象的内部地址转换为整数来实现，但此实现技术并非 Java<span style="font-size:70%"><sup>TM</sup></span> 编程语言所要求。）

**Returns:**
此对象的哈希码值。 @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode
