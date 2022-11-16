---
title: StructureTypeCategory
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示标准结构类型的类别。
type: docs
weight: 17
url: /zh/java/com.aspose.pdf.tagged.logicalstructure/structuretypecategory/
---
**遗产：**
java.lang.Object
```
public final class StructureTypeCategory
```

表示标准结构类型的类别。
## 领域

| 场地 | 描述 |
| --- | --- |
| [BLSEs](#BLSEs) | 块级结构元素 (BLSE) 描述了页面上内容的整体布局，沿块级进方向前进。 |
| [GroupingElements](#GroupingElements) | 分组元素将其他元素分组到序列或层次结构中，但不直接包含内容并且对布局没有直接影响。 |
| [ILSEs](#ILSEs) | 内联级结构元素 (ILSE) 描述 BLSE 内的内容布局，沿内联级进方向进行。 |
| [IllustrationElements](#IllustrationElements) | 插图元素是内容的紧凑序列，按页面内容顺序排列，在页面布局方面被视为单一对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 返回表示当前对象的字符串。 |
| [to_StructureTypeCategory(String name)](#to-StructureTypeCategory-java.lang.String-) | 执行从 String 到[StructureTypeCategory](../../com.aspose.pdf.tagged.logicalstructure/structuretypecategory). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BLSEs {#BLSEs}
```
public static final StructureTypeCategory BLSEs
```


块级结构元素 (BLSE) 描述了页面上内容的整体布局，沿块级进方向前进。

### GroupingElements {#GroupingElements}
```
public static final StructureTypeCategory GroupingElements
```


分组元素将其他元素分组到序列或层次结构中，但不直接包含内容并且对布局没有直接影响。

### ILSEs {#ILSEs}
```
public static final StructureTypeCategory ILSEs
```


内联级结构元素 (ILSE) 描述 BLSE 内的内容布局，沿内联级进方向进行。

### IllustrationElements {#IllustrationElements}
```
public static final StructureTypeCategory IllustrationElements
```


插图元素是内容的紧凑序列，按页面内容顺序排列，在页面布局方面被视为单一对象。插图可以被视为 BLSE 或 ILSE。

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




### toString() {#toString--}
```
public String toString()
```


返回表示当前对象的字符串。

**退货：**
java.lang.String - 表示当前对象的字符串。
### to_StructureTypeCategory(String name) {#to-StructureTypeCategory-java.lang.String-}
```
public static StructureTypeCategory to_StructureTypeCategory(String name)
```


执行从 String 到[StructureTypeCategory](../../com.aspose.pdf.tagged.logicalstructure/structuretypecategory).

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 名字。 |

**退货：**
[StructureTypeCategory](../../com.aspose.pdf.tagged.logicalstructure/structuretypecategory) 转换的结果。
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
