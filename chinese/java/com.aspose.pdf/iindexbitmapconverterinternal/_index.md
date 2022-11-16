---
title: IIndexBitmapConverterInternal
second_title: 用于 Java API 参考的 Aspose.PDF
description: 该接口声明用于自定义量化算法。
type: docs
weight: 436
url: /zh/java/com.aspose.pdf/iindexbitmapconverterinternal/
---
```
public interface IIndexBitmapConverterInternal
```

该接口声明用于自定义量化算法。用户可以实现自己的算法实现（例如基于非托管代码的算法）。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get1BppImageInternal(System.Drawing.Bitmap src)](#get1BppImageInternal-com.aspose.ms.System.Drawing.Bitmap-) | 仅内部返回 1Bpp 位图表示 |
| [get4BppImageInternal(System.Drawing.Bitmap src)](#get4BppImageInternal-com.aspose.ms.System.Drawing.Bitmap-) | 仅内部返回 4Bpp 位图表示 |
| [get8BppImageInternal(System.Drawing.Bitmap src)](#get8BppImageInternal-com.aspose.ms.System.Drawing.Bitmap-) | 仅内部返回 8Bpp 位图表示 |
### get1BppImageInternal(System.Drawing.Bitmap src) {#get1BppImageInternal-com.aspose.ms.System.Drawing.Bitmap-}
```
public abstract System.Drawing.Bitmap get1BppImageInternal(System.Drawing.Bitmap src)
```


仅内部返回 1Bpp 位图表示

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| src | com.aspose.ms.System.Drawing.Bitmap | 源位图。 |

**退货：**
com.aspose.ms.System.Drawing.Bitmap - 1 bpp 图像格式的位图。
### get4BppImageInternal(System.Drawing.Bitmap src) {#get4BppImageInternal-com.aspose.ms.System.Drawing.Bitmap-}
```
public abstract System.Drawing.Bitmap get4BppImageInternal(System.Drawing.Bitmap src)
```


仅内部返回 4Bpp 位图表示

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| src | com.aspose.ms.System.Drawing.Bitmap | 源位图。 |

**退货：**
com.aspose.ms.System.Drawing.Bitmap - 4 bpp 图像格式的位图。
### get8BppImageInternal(System.Drawing.Bitmap src) {#get8BppImageInternal-com.aspose.ms.System.Drawing.Bitmap-}
```
public abstract System.Drawing.Bitmap get8BppImageInternal(System.Drawing.Bitmap src)
```


仅内部返回 8Bpp 位图表示

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| src | com.aspose.ms.System.Drawing.Bitmap | 源位图。 |

**退货：**
com.aspose.ms.System.Drawing.Bitmap - 8 bpp 图像格式的位图。