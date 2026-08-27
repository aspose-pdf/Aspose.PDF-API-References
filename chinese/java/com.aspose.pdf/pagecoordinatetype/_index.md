---
title: "PageCoordinateType"
linktitle: "PageCoordinateType"
second_title: "Aspose.PDF for Java API 参考"
description: "描述页面坐标类型。MediaBox = 0，CropBox = 1。"
type: docs
weight: 3350
url: /zh/java/com.aspose.pdf/pagecoordinatetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PageCoordinateType > com.aspose.pdf.PageCoordinateType, java.lang.Enum < PageCoordinateType >, com.aspose.pdf.PageCoordinateType

**All Implemented Interfaces:**
Serializable, Comparable < PageCoordinateType >

```
public enum PageCoordinateType extends Enum < PageCoordinateType >
```

描述页面坐标类型。MediaBox = 0，CropBox = 1。

## 字段

| 字段 | 描述 |
| --- | --- |
| [CropBox](#CropBox) | CropBox 定义了页面内容应被裁剪的区域。 |
| [MediaBox](#MediaBox) | MediaBox 用于指定页面的宽度和高度。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | 返回此类型中具有指定名称的枚举常量。 |
| [values](#values--) | 返回一个数组，包含此枚举类型的常量，按声明顺序排列。 |

### CropBox {#CropBox}
```
public static final PageCoordinateType CropBox
```

CropBox 定义了页面内容应被裁剪的区域。

### MediaBox {#MediaBox}
```
public static final PageCoordinateType MediaBox
```

MediaBox 用于指定页面的宽度和高度。

### getByValue {#getByValue-int-}
```
public static PageCoordinateType getByValue(int value)
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
public static PageCoordinateType [] values()
```

返回一个数组，包含此枚举类型的常量，按声明顺序排列。

**Returns:**
一个数组，包含此枚举类型的常量，按声明顺序排列
