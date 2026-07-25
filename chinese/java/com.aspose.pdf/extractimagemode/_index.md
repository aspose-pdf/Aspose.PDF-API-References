---
title: "ExtractImageMode"
linktitle: "ExtractImageMode"
second_title: "Aspose.PDF for Java API 参考"
description: "定义在从文档中提取图像时可使用的不同模式。"
type: docs
weight: 1360
url: /zh/java/com.aspose.pdf/extractimagemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ExtractImageMode > com.aspose.pdf.ExtractImageMode, java.lang.Enum < ExtractImageMode >, com.aspose.pdf.ExtractImageMode

**All Implemented Interfaces:**
Serializable, Comparable < ExtractImageMode >

```
public enum ExtractImageMode extends Enum < ExtractImageMode >
```

定义在从文档中提取图像时可使用的不同模式。

## 字段

| 字段 | 描述 |
| --- | --- |
| [ActuallyUsed](#ActuallyUsed) | 定义图像提取模式，仅提取实际在页面上显示的图像。 |
| [DefinedInResources](#DefinedInResources) | 定义图像提取模式，提取特定页面资源中定义的所有图像。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | 返回此类型中具有指定名称的枚举常量。 |
| [values](#values--) | 返回一个数组，包含此枚举类型的常量，按声明顺序排列。 |

### ActuallyUsed {#ActuallyUsed}
```
public static final ExtractImageMode ActuallyUsed
```

定义图像提取模式，仅提取实际在页面上显示的图像。

### DefinedInResources {#DefinedInResources}
```
public static final ExtractImageMode DefinedInResources
```

定义图像提取模式，提取特定页面资源中定义的所有图像。

### getByValue {#getByValue-int-}
```
public static ExtractImageMode getByValue(int value)
```



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
返回此类型中具有指定名称的枚举常量。

### values {#values--}
```
public static ExtractImageMode [] values()
```

返回一个数组，包含此枚举类型的常量，按声明顺序排列。

**Returns:**
一个数组，包含此枚举类型的常量，按声明顺序排列
