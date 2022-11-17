---
title: Element
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示逻辑结构的基本元素的类。
type: docs
weight: 96
url: /zh/java/com.aspose.pdf/element/
---
**遗产：**
java.lang.Object
```
public abstract class Element
```

表示逻辑结构的基本元素的类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActualText()](#getActualText--) | （可选；PDF�1.4）完全替换结构元素及其子元素的文本。 |
| [getAlt()](#getAlt--) | （可选）以人类可读的形式对结构元素及其子元素的替代描述，这在提取文档时很有用\\u2019s 内容以支持残障用户的无障碍访问或用于其他目的。 |
| [getChildren()](#getChildren--) | 获取子元素集合。 |
| [getClass()](#getClass--) |  |
| [getE()](#getE--) | （可选；PDF�1.5）缩写的扩展形式。 |
| [getLang()](#getLang--) | （可选；PDF.1.4）一种语言，用于指定结构元素中所有文本的自然语言，除非被嵌套结构元素或标记内容的语言规范覆盖。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setActualText(String value)](#setActualText-java.lang.String-) | （可选；PDF�1.4）完全替换结构元素及其子元素的文本。 |
| [setAlt(String value)](#setAlt-java.lang.String-) | （可选）以人类可读的形式对结构元素及其子元素的替代描述，这在提取文档时很有用\\u2019s 内容以支持残障用户的无障碍访问或用于其他目的。 |
| [setE(String value)](#setE-java.lang.String-) | （可选；PDF�1.5）缩写的扩展形式。 |
| [setLang(String value)](#setLang-java.lang.String-) | （可选；PDF.1.4）一种语言，用于指定结构元素中所有文本的自然语言，除非被嵌套结构元素或标记内容的语言规范覆盖。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getActualText() {#getActualText--}
```
public String getActualText()
```


（可选；PDF�1.4）完全替换结构元素及其子元素的文本。此替换文本（应适用于尽可能小的内容）在提取文档时很有用\\u2019s 内容以支持残障用户的无障碍访问或用于其他目的。

**退货：**
java.lang.String - 字符串对象
### getAlt() {#getAlt--}
```
public String getAlt()
```


（可选）以人类可读的形式对结构元素及其子元素的替代描述，这在提取文档时很有用\\u2019s 内容以支持残障用户的无障碍访问或用于其他目的。

**退货：**
java.lang.String - 字符串对象
### getChildren() {#getChildren--}
```
public List<Element> getChildren()
```


获取子元素集合。

**退货：**
java.util.List<com.aspose.pdf.Element> - java.util.List 对象
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getE() {#getE--}
```
public String getE()
```


（可选；PDF�1.5）缩写的扩展形式。

**退货：**
java.lang.String - 字符串对象
### getLang() {#getLang--}
```
public String getLang()
```


（可选；PDF.1.4）一种语言，用于指定结构元素中所有文本的自然语言，除非被嵌套结构元素或标记内容的语言规范覆盖。

**退货：**
java.lang.String - 字符串对象
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




### setActualText(String value) {#setActualText-java.lang.String-}
```
public void setActualText(String value)
```


（可选；PDF�1.4）完全替换结构元素及其子元素的文本。此替换文本（应适用于尽可能小的内容）在提取文档时很有用\\u2019s 内容以支持残障用户的无障碍访问或用于其他目的。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串对象 |

### setAlt(String value) {#setAlt-java.lang.String-}
```
public void setAlt(String value)
```


（可选）以人类可读的形式对结构元素及其子元素的替代描述，这在提取文档时很有用\\u2019s 内容以支持残障用户的无障碍访问或用于其他目的。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串对象 |

### setE(String value) {#setE-java.lang.String-}
```
public void setE(String value)
```


（可选；PDF�1.5）缩写的扩展形式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串对象 |

### setLang(String value) {#setLang-java.lang.String-}
```
public void setLang(String value)
```


（可选；PDF.1.4）一种语言，用于指定结构元素中所有文本的自然语言，除非被嵌套结构元素或标记内容的语言规范覆盖。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串对象 |

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
