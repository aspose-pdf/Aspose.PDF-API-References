---
title: XImageCollection
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 XImage 集合的类。
type: docs
weight: 410
url: /zh/java/com.aspose.pdf/ximagecollection/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
java.lang.Iterable
```
public final class XImageCollection implements Iterable<XImage>
```

表示 XImage 集合的类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(XImage image)](#add-com.aspose.pdf.XImage-) | 将新图像添加到图像列表。 |
| [add(BufferedImage image)](#add-java.awt.image.BufferedImage-) | 将实体添加到集合的末尾，因此可以通过最后一个索引访问实体。 |
| [add(InputStream image)](#add-java.io.InputStream-) | 将实体添加到集合的末尾，因此可以通过最后一个索引访问实体。 |
| [add(InputStream image, int quality)](#add-java.io.InputStream-int-) | 将实体添加到集合的末尾，因此可以通过最后一个索引访问实体。 |
| [addWithImageFilterType(InputStream image, int filterType)](#addWithImageFilterType-java.io.InputStream-int-) | 将实体添加到集合的末尾，因此可以通过最后一个索引访问实体。 |
| [clear()](#clear--) | 清除集合中的所有项目。 |
| [contains(XImage item)](#contains-com.aspose.pdf.XImage-) | 确定集合是否包含特定值。 |
| [copyTo(XImage[] array, int index)](#copyTo-com.aspose.pdf.XImage---int-) | 将图像数组复制到集合中。 |
| [delete()](#delete--) | 从集合中删除图像。 |
| [delete(int index)](#delete-int-) | 按索引从集合中删除索引。 |
| [delete(int index, int action)](#delete-int-int-) | 通过执行操作参数指定的操作的索引从集合中删除索引。 |
| [delete(String name)](#delete-java.lang.String-) | 按名称从集合中删除项目。 |
| [delete(String name, int action)](#delete-java.lang.String-int-) | 按名称从集合中删除项目。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getImageName(XImage image)](#getImageName-com.aspose.pdf.XImage-) | 返回图像列表中的名称，它是给定图像的键。 |
| [getNames()](#getNames--) | 获取图像名称数组。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步对象。 |
| [get_Item(int index)](#get-Item-int-) | 通过其索引从集合中获取图像。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | 按名称从集合中获取图像。 |
| [hasImage(String imgName)](#hasImage-java.lang.String-) |  |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | 获取一个值，该值指示集合是否为只读。 |
| [isSynchronized()](#isSynchronized--) | 如果对象已同步，则返回 true。 |
| [iterator()](#iterator--) | 返回集合枚举器。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(XImage item)](#remove-com.aspose.pdf.XImage-) | 尚不支持，抛出异常。 |
| [replace(int index, InputStream stream)](#replace-int-java.io.InputStream-) | 用另一个图像替换集合中的图像。 |
| [replace(int index, InputStream stream, int quality)](#replace-int-java.io.InputStream-int-) | 用另一个图像替换集合中的图像。 |
| [replace(int index, InputStream stream, int quality, boolean isBlackAndWhite)](#replace-int-java.io.InputStream-int-boolean-) | 用另一个图像替换集合中的图像。 |
| [size()](#size--) | 集合中的图像计数。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(XImage image) {#add-com.aspose.pdf.XImage-}
```
public String add(XImage image)
```


将新图像添加到图像列表。此方法将图像添加为对同一 PdfObject 的引用（这允许减小文件大小）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | [XImage](../../com.aspose.pdf/ximage) | 要添加的 XImage。 |

**退货：**
java.lang.String - 添加图像的名称。
### add(BufferedImage image) {#add-java.awt.image.BufferedImage-}
```
public String add(BufferedImage image)
```


将实体添加到集合的末尾，因此可以通过最后一个索引访问实体。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | BufferedImage 包含图像数据。 |

**退货：**
java.lang.String - 添加图像的名称。
### add(InputStream image) {#add-java.io.InputStream-}
```
public String add(InputStream image)
```


将实体添加到集合的末尾，因此可以通过最后一个索引访问实体。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | java.io.InputStream | 包含图像数据的流（JPEG 格式）。 |

**退货：**
java.lang.String - 添加图像的名称。
### add(InputStream image, int quality) {#add-java.io.InputStream-int-}
```
public String add(InputStream image, int quality)
```


将实体添加到集合的末尾，因此可以通过最后一个索引访问实体。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | java.io.InputStream | 包含图像数据的流（JPEG 格式）。 |
| quality | int | JPEG 质量。 |

**退货：**
java.lang.String - 添加图像的名称。
### addWithImageFilterType(InputStream image, int filterType) {#addWithImageFilterType-java.io.InputStream-int-}
```
public String addWithImageFilterType(InputStream image, int filterType)
```


将实体添加到集合的末尾，因此可以通过最后一个索引访问实体。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | java.io.InputStream | 包含图像数据的流。 |
| filterType | int | 图像过滤器类型。 |

**退货：**
java.lang.String - 添加图像的名称。
### clear() {#clear--}
```
public void clear()
```


清除集合中的所有项目。

### contains(XImage item) {#contains-com.aspose.pdf.XImage-}
```
public boolean contains(XImage item)
```


确定集合是否包含特定值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [XImage](../../com.aspose.pdf/ximage) | 要在集合中定位的对象 |

**退货：**
boolean - 如果在集合中找到项目则为 true；否则，假的。
### copyTo(XImage[] array, int index) {#copyTo-com.aspose.pdf.XImage---int-}
```
public void copyTo(XImage[] array, int index)
```


将图像数组复制到集合中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| array | [XImage\[\]](../../com.aspose.pdf/ximage) | 要复制的数组。 |
| index | int | 将图像复制到集合中的索引。 |

### delete() {#delete--}
```
public void delete()
```


从集合中删除图像。

### delete(int index) {#delete-int-}
```
public void delete(int index)
```


按索引从集合中删除索引。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 图像索引。 |

### delete(int index, int action) {#delete-int-int-}
```
public final void delete(int index, int action)
```


通过执行操作参数指定的操作的索引从集合中删除索引。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要删除的图像的索引。 |
| action | int | ImageDeleteAction 元素。图像删除后执行的操作。 |

### delete(String name) {#delete-java.lang.String-}
```
public void delete(String name)
```


按名称从集合中删除项目。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 必须删除的图像的名称。 |

### delete(String name, int action) {#delete-java.lang.String-int-}
```
public final void delete(String name, int action)
```


按名称从集合中删除项目。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 必须删除的图像的名称。 |
| action | int | 要对图像对象执行的操作。 |

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
### getImageName(XImage image) {#getImageName-com.aspose.pdf.XImage-}
```
public String getImageName(XImage image)
```


返回图像列表中的名称，它是给定图像的键。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | [XImage](../../com.aspose.pdf/ximage) | 要搜索的图像。 |

**退货：**
java.lang.String - 找到的图像的名称（键）；如果未找到图像，则为 null。
### getNames() {#getNames--}
```
public String[] getNames()
```


获取图像名称数组。

**退货：**
java.lang.字符串[] - 细绳[大批
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


返回同步对象。

**退货：**
java.lang.Object - 对象元素
### get_Item(int index) {#get-Item-int-}
```
public XImage get_Item(int index)
```


通过其索引从集合中获取图像。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 图片索引 |

**退货：**
[XImage](../../com.aspose.pdf/ximage) 检索图像。
### get_Item(String name) {#get-Item-java.lang.String-}
```
public XImage get_Item(String name)
```


按名称从集合中获取图像。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 图片名称。 |

**退货：**
[XImage](../../com.aspose.pdf/ximage) 检索图像。
### hasImage(String imgName) {#hasImage-java.lang.String-}
```
public boolean hasImage(String imgName)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imgName | java.lang.String |  |

**退货：**
布尔值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


获取一个值，该值指示集合是否为只读。

**退货：**
boolean - 布尔值
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


如果对象已同步，则返回 true。

**退货：**
boolean - 布尔值
### iterator() {#iterator--}
```
public Iterator<XImage> iterator()
```


返回集合枚举器。

**退货：**
java.util.Iterator<com.aspose.pdf.XImage> - 集合枚举器
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(XImage item) {#remove-com.aspose.pdf.XImage-}
```
public boolean remove(XImage item)
```


尚不支持，抛出异常。

总是抛出 NotImplementedException

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | [XImage](../../com.aspose.pdf/ximage) | XImage 实例要删除的项目。 |

**退货：**
boolean - 布尔值
### replace(int index, InputStream stream) {#replace-int-java.io.InputStream-}
```
public void replace(int index, InputStream stream)
```


用另一个图像替换集合中的图像。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 将被替换的收集项的索引。 |
| stream | java.io.InputStream | 包含图像数据的流（JPEG 格式）。 |

### replace(int index, InputStream stream, int quality) {#replace-int-java.io.InputStream-int-}
```
public void replace(int index, InputStream stream, int quality)
```


用另一个图像替换集合中的图像。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 将被替换的收集项的索引。 |
| stream | java.io.InputStream | 包含图像数据的流（JPEG 格式）。 |
| quality | int | JPEG 质量。 |

### replace(int index, InputStream stream, int quality, boolean isBlackAndWhite) {#replace-int-java.io.InputStream-int-boolean-}
```
public final void replace(int index, InputStream stream, int quality, boolean isBlackAndWhite)
```


用另一个图像替换集合中的图像。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 将被替换的收集项的索引。 |
| stream | java.io.InputStream | 包含图像数据的流（JPEG 格式）。 |
| quality | int | JPEG 压缩质量，以百分比表示（有效值为 0..100）。 |
| isBlackAndWhite | boolean | 如果为 true，则使用 CCITT 压缩方法压缩图像，该方法为黑白图像提供更好的压缩。只能用于黑白图像。 |

### size() {#size--}
```
public int size()
```


集合中的图像计数。

**退货：**
int - 整数值
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
