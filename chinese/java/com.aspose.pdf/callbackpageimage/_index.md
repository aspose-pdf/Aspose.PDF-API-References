---
title: MemoryExtender.CallBackPageImage
second_title: 用于 Java API 参考的 Aspose.PDF
description: 操作缓存的回调过程。
type: docs
weight: 10
url: /zh/java/com.aspose.pdf/memoryextender.callbackpageimage/
---
```
public static interface MemoryExtender.CallBackPageImage
```

操作缓存的回调过程。
## 方法

| 方法 | 描述 |
| --- | --- |
| [invoke(BufferedImage img)](#invoke-java.awt.image.BufferedImage-) | 这个方法应该给出一个答案，是否将新图像添加到缓存中。 |
### invoke(BufferedImage img) {#invoke-java.awt.image.BufferedImage-}
```
public abstract boolean invoke(BufferedImage img)
```


这个方法应该给出一个答案，是否将新图像添加到缓存中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| img | java.awt.image.BufferedImage | 图像对象 |

**退货：**
boolean - 布尔值