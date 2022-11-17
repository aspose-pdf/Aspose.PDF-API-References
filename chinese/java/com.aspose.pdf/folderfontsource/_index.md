---
title: FolderFontSource
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示包含字体文件的文件夹。
type: docs
weight: 129
url: /zh/java/com.aspose.pdf/folderfontsource/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.FontSource](../../com.aspose.pdf/fontsource)
```
public final class FolderFontSource extends FontSource
```

表示包含字体文件的文件夹。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FolderFontSource(String folderPath)](#FolderFontSource-java.lang.String-) | 初始化 FolderFontSource 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 检查文件夹字体源对象是否相等。 |
| [getClass()](#getClass--) |  |
| [getFolderPath()](#getFolderPath--) | 包含字体文件的文件夹的路径。 |
| [hashCode()](#hashCode--) | 返回对象的哈希码值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFolderPath(String value)](#setFolderPath-java.lang.String-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FolderFontSource(String folderPath) {#FolderFontSource-java.lang.String-}
```
public FolderFontSource(String folderPath)
```


初始化 FolderFontSource 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| folderPath | java.lang.String | 文件夹的路径。 |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


检查文件夹字体源对象是否相等。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 将进行比较的文件夹字体源对象。 |

**退货：**
布尔值 - 如果两个对象都是针对同一文件夹的文件夹字体源，则为真。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```


包含字体文件的文件夹的路径。

**退货：**
java.lang.String - 字符串值
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




### setFolderPath(String value) {#setFolderPath-java.lang.String-}
```
public void setFolderPath(String value)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

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
