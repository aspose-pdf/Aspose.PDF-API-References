---
title: Redaction
second_title: 用于 Java API 参考的 Aspose.PDF
description: 仅供内部使用
type: docs
weight: 301
url: /zh/java/com.aspose.pdf/redaction/
---
**遗产：**
java.lang.Object
```
public class Redaction
```

仅供内部使用
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Redaction()](#Redaction--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [_RedactText(Page page, Rectangle rect)](#-RedactText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getRedactionAppearance(Rectangle rect, Color color)](#getRedactionAppearance-com.aspose.pdf.Rectangle-java.awt.Color-) | 获取编辑外观 |
| [getRedactionAppearanceInternal(Rectangle rect, System.Drawing.Color color)](#getRedactionAppearanceInternal-com.aspose.pdf.Rectangle-com.aspose.ms.System.Drawing.Color-) | 对于内部使用，仅获取编辑外观 |
| [getredactArea(Page page, Rectangle rect, Color color)](#getredactArea-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.awt.Color-) | 获取编辑区域 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [redactAnnotations(Page page, Rectangle rect)](#redactAnnotations-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 删除所需矩形中的注释 |
| [redactArea(Page page, Rectangle rect, Color color)](#redactArea-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.awt.Color-) | 仅供内部使用获取编辑区域 |
| [redactAreaInternal(Page page, Rectangle rect, System.Drawing.Color color, boolean exactArea)](#redactAreaInternal-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.ms.System.Drawing.Color-boolean-) |  |
| [redactImages(Page page, Rectangle rect, Color color)](#redactImages-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.awt.Color-) | 删除图像（或编辑图像的内容是图像被矩形部分覆盖） |
| [redactText(Page page, Rectangle rect)](#redactText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 删除所需矩形中的文本 |
| [redactText(XForm form, Rectangle rect)](#redactText-com.aspose.pdf.XForm-com.aspose.pdf.Rectangle-) | 删除所需矩形中的文本 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Redaction() {#Redaction--}
```
public Redaction()
```


### _RedactText(Page page, Rectangle rect) {#-RedactText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public static void _RedactText(Page page, Rectangle rect)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) |  |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getRedactionAppearance(Rectangle rect, Color color) {#getRedactionAppearance-com.aspose.pdf.Rectangle-java.awt.Color-}
```
public static List<Operator> getRedactionAppearance(Rectangle rect, Color color)
```


获取编辑外观

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | 矩形对象 |
| color | java.awt.Color | 颜色对象 |

**退货：**
java.util.List<com.aspose.pdf.Operator> - 列表对象 
### getRedactionAppearanceInternal(Rectangle rect, System.Drawing.Color color) {#getRedactionAppearanceInternal-com.aspose.pdf.Rectangle-com.aspose.ms.System.Drawing.Color-}
```
public static System.Collections.Generic.List<Operator> getRedactionAppearanceInternal(Rectangle rect, System.Drawing.Color color)
```


对于内部使用，仅获取编辑外观

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | 矩形对象 |
| color | com.aspose.ms.System.Drawing.Color | 颜色对象 |

**退货：**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> - 列表对象 
### getredactArea(Page page, Rectangle rect, Color color) {#getredactArea-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.awt.Color-}
```
public static void getredactArea(Page page, Rectangle rect, Color color)
```


获取编辑区域

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 页面对象 |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | 矩形对象 |
| color | java.awt.Color | 颜色对象 |

### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### redactAnnotations(Page page, Rectangle rect) {#redactAnnotations-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public static void redactAnnotations(Page page, Rectangle rect)
```


删除所需矩形中的注释

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 页面对象 |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | 矩形对象 |

### redactArea(Page page, Rectangle rect, Color color) {#redactArea-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.awt.Color-}
```
public static void redactArea(Page page, Rectangle rect, Color color)
```


仅供内部使用获取编辑区域

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 页面对象 |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | 矩形对象 |
| color | java.awt.Color | 颜色对象 |

### redactAreaInternal(Page page, Rectangle rect, System.Drawing.Color color, boolean exactArea) {#redactAreaInternal-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.ms.System.Drawing.Color-boolean-}
```
public static void redactAreaInternal(Page page, Rectangle rect, System.Drawing.Color color, boolean exactArea)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) |  |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) |  |
| color | com.aspose.ms.System.Drawing.Color |  |
| exactArea | boolean |  |

### redactImages(Page page, Rectangle rect, Color color) {#redactImages-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.awt.Color-}
```
public static void redactImages(Page page, Rectangle rect, Color color)
```


删除图像（或编辑图像的内容是图像被矩形部分覆盖）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 页面对象 |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | 矩形对象 |
| color | java.awt.Color | 颜色对象 |

### redactText(Page page, Rectangle rect) {#redactText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public static void redactText(Page page, Rectangle rect)
```


删除所需矩形中的文本

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 页面对象 |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | 矩形对象 |

### redactText(XForm form, Rectangle rect) {#redactText-com.aspose.pdf.XForm-com.aspose.pdf.Rectangle-}
```
public static void redactText(XForm form, Rectangle rect)
```


删除所需矩形中的文本

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| form | [XForm](../../com.aspose.pdf/xform) | 变形对象 |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | 矩形对象 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
