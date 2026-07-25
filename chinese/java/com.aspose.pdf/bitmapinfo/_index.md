---
title: "BitmapInfo"
linktitle: "BitmapInfo"
second_title: "Aspose.PDF for Java API 参考"
description: "对象包含像素数组和位图信息。"
type: docs
weight: 300
url: /zh/java/com.aspose.pdf/bitmapinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BitmapInfo

```
public class BitmapInfo extends Object
```

对象包含像素数组和位图信息。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BitmapInfo](#BitmapInfo-byte:A-int-int-int-) | 创建该类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFormat](#getFormat--) | 获取位图的像素格式。 |
| [getHeight](#getHeight--) | 获取位图的高度。 |
| [getPixelBytes](#getPixelBytes--) | 获取像素数组。 |
| [getWidth](#getWidth--) | 获取位图的宽度。 |

### BitmapInfo {#BitmapInfo-byte:A-int-int-int-}
```
public BitmapInfo(byte[] pixelBytes, int width, int height, int format)
```

创建该类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pixelBytes |  | 像素数组。 |
| 宽度 |  | 位图的宽度。 |
| 高度 |  | 位图的高度。 |
| 格式 |  | 位图的像素格式。 @see BitmapInfo |

### getFormat {#getFormat--}
```
public final int getFormat()
```

获取位图的像素格式。

**Returns:**
int 值 PixelFormat 元素

### getHeight {#getHeight--}
```
public final int getHeight()
```

获取位图的高度。

**Returns:**
int 值

### getPixelBytes {#getPixelBytes--}
```
public final byte[] getPixelBytes()
```

获取像素数组。

**Returns:**
byte[] 数组

### getWidth {#getWidth--}
```
public final int getWidth()
```

获取位图的宽度。

**Returns:**
int 值
