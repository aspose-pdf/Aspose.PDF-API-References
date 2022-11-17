---
title: MemoryFontSource
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示单个字体文件源。
type: docs
weight: 219
url: /zh/java/com.aspose.pdf/memoryfontsource/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.FontSource](../../com.aspose.pdf/fontsource)

**所有已实现的接口：**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public final class MemoryFontSource extends FontSource implements System.IDisposable, Closeable
```

表示单个字体文件源。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MemoryFontSource(byte[] fontBytes)](#MemoryFontSource-byte---) | 初始化 MemoryFontSource 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [close()](#close--) | 关闭此文档使用的所有资源。 |
| [dispose()](#dispose--) | 释放内部资源。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 检查字体文件源对象是否相等。 |
| [getClass()](#getClass--) |  |
| [getFontBytes()](#getFontBytes--) | 字体文件字节数组。 |
| [hashCode()](#hashCode--) | 返回对象的哈希码值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MemoryFontSource(byte[] fontBytes) {#MemoryFontSource-byte---}
```
public MemoryFontSource(byte[] fontBytes)
```


初始化 MemoryFontSource 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fontBytes | byte[] | 字体文件字节数组。 |

### close() {#close--}
```
public void close()
```


关闭此文档使用的所有资源。

### dispose() {#dispose--}
```
public void dispose()
```


释放内部资源。

此方法已过时，请改用 close() 。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


检查字体文件源对象是否相等。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 将进行比较的字体文件源对象。 |

**退货：**
boolean - 如果两个对象都是针对同一文件的字体文件源，则为真。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getFontBytes() {#getFontBytes--}
```
public byte[] getFontBytes()
```


字体文件字节数组。

**退货：**
字节[] - 字节[大批
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回对象的哈希码值。支持此方法是为了散列表的好处，例如 java.util.HashMap 提供的散列表。

hashCode的一般契约是：

 *  每当在 Java 应用程序的执行期间对同一对象多次调用它时，hashCode 方法必须一致地返回相同的整数，前提是在对象的 equals 比较中使用的信息没有被修改。从一个应用程序的一次执行到同一应用程序的另一次执行，该整数不需要保持一致。
 *  如果根据 equals(Object) 方法两个对象相等，则对这两个对象中的每一个调用 hashCode 方法必须产生相同的整数结果。
 *  这是*not*要求如果两个对象根据 java.lang.Object 不相等\#equals(java.lang.Object).equals(java.lang.Object) 方法，然后在两个对象中的每一个上调用 hashCode 方法必须产生不同的整数结果。但是，程序员应该知道，为不相等的对象生成不同的整数结果可能会提高哈希表的性能。

在相当实用的情况下，类 Object 定义的 hashCode 方法确实会为不同的对象返回不同的整数。 （这通常是通过将对象的内部地址转换为整数来实现的，但 JavaTM 编程语言不需要这种实现技术。）

**退货：**
int - 此对象的哈希码值。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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
