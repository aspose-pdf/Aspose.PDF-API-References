---
title: IIndexBitmapConverter
second_title: 用于 Java API 参考的 Aspose.PDF
description: 该接口声明用于自定义量化算法。
type: docs
weight: 435
url: /zh/java/com.aspose.pdf/iindexbitmapconverter/
---
```
public interface IIndexBitmapConverter
```

该接口声明用于自定义量化算法。用户可以实现自己的算法实现（例如基于非托管代码的算法）。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get1BppImage(BufferedImage src)](#get1BppImage-java.awt.image.BufferedImage-) | 返回 1Bpp 位图表示 |
| [get4BppImage(BufferedImage src)](#get4BppImage-java.awt.image.BufferedImage-) | 返回 4Bpp 位图表示 |
| [get8BppImage(BufferedImage src)](#get8BppImage-java.awt.image.BufferedImage-) | 返回 4Bpp 位图表示 |
### get1BppImage(BufferedImage src) {#get1BppImage-java.awt.image.BufferedImage-}
```
public abstract BufferedImage get1BppImage(BufferedImage src)
```


返回 1Bpp 位图表示

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| src | java.awt.image.BufferedImage | 源位图。 |

**退货：**
java.awt.image.BufferedImage - 1 bpp 图像格式的位图。
### get4BppImage(BufferedImage src) {#get4BppImage-java.awt.image.BufferedImage-}
```
public abstract BufferedImage get4BppImage(BufferedImage src)
```


返回 4Bpp 位图表示

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| src | java.awt.image.BufferedImage | 源位图。 |

**退货：**
java.awt.image.BufferedImage - 4 bpp 图像格式的位图。
### get8BppImage(BufferedImage src) {#get8BppImage-java.awt.image.BufferedImage-}
```
public abstract BufferedImage get8BppImage(BufferedImage src)
```


返回 4Bpp 位图表示

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| src | java.awt.image.BufferedImage | 源位图。 |

**退货：**
java.awt.image.BufferedImage - 4 bpp 图像格式的位图。