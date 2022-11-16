---
title: ToUnicodeProcessingRules
second_title: 用于 Java API 参考的 Aspose.PDF
description: 此类描述可用于解决 Adobe Preflight 错误文本无法映射到 Unicode 的规则。
type: docs
weight: 392
url: /zh/java/com.aspose.pdf/tounicodeprocessingrules/
---
**遗产：**
java.lang.Object
```
public class ToUnicodeProcessingRules
```

此类描述可用于解决 Adobe Preflight 错误“文本无法映射到 Unicode”的规则。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ToUnicodeProcessingRules()](#ToUnicodeProcessingRules--) | 构造函数 |
| [ToUnicodeProcessingRules(boolean removeSpaces)](#ToUnicodeProcessingRules-boolean-) | 构造函数 |
| [ToUnicodeProcessingRules(boolean removeSpaces, boolean mapNonLinkedUnicodesOnSpace)](#ToUnicodeProcessingRules-boolean-boolean-) | 构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMapNonLinkedSymbolsOnSpace()](#getMapNonLinkedSymbolsOnSpace--) | 某些字体不提供有关某些文本符号的 unicode 的信息。 |
| [getRemoveSpacesFromCMapNames()](#getRemoveSpacesFromCMapNames--) | 某些字体具有名称中带有空格的 ToUnicode 字符代码映射。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMapNonLinkedSymbolsOnSpace(boolean value)](#setMapNonLinkedSymbolsOnSpace-boolean-) | 某些字体不提供有关某些文本符号的 unicode 的信息。 |
| [setRemoveSpacesFromCMapNames(boolean value)](#setRemoveSpacesFromCMapNames-boolean-) | 某些字体具有名称中带有空格的 ToUnicode 字符代码映射。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ToUnicodeProcessingRules() {#ToUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules()
```


构造函数

### ToUnicodeProcessingRules(boolean removeSpaces) {#ToUnicodeProcessingRules-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces)
```


构造函数

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| removeSpaces | boolean | 设置 RemoveSpacesFromCMapNames 标志 |

### ToUnicodeProcessingRules(boolean removeSpaces, boolean mapNonLinkedUnicodesOnSpace) {#ToUnicodeProcessingRules-boolean-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces, boolean mapNonLinkedUnicodesOnSpace)
```


构造函数

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| removeSpaces | boolean | 设置 RemoveSpacesFromCMapNames 标志 |
| mapNonLinkedUnicodesOnSpace | boolean | 设置 MapNonLinkedSymbolsOnSpace 标志 |

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
### getMapNonLinkedSymbolsOnSpace() {#getMapNonLinkedSymbolsOnSpace--}
```
public boolean getMapNonLinkedSymbolsOnSpace()
```


某些字体不提供有关某些文本符号的 unicode 的信息。缺少信息会导致错误“文本无法映射到 Unicode”。使用此标志将非链接符号映射到 unicode“空格”（代码 32）上。

**退货：**
boolean - 布尔值
### getRemoveSpacesFromCMapNames() {#getRemoveSpacesFromCMapNames--}
```
public boolean getRemoveSpacesFromCMapNames()
```


某些字体具有名称中带有空格的 ToUnicode 字符代码映射。这些空格可能会调用 unicode 文本映射错误。此标志命令从 ToUnicode 字符代码映射的名称中删除空格。默认为假。

**退货：**
boolean - 布尔值
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




### setMapNonLinkedSymbolsOnSpace(boolean value) {#setMapNonLinkedSymbolsOnSpace-boolean-}
```
public void setMapNonLinkedSymbolsOnSpace(boolean value)
```


某些字体不提供有关某些文本符号的 unicode 的信息。缺少信息会导致错误“文本无法映射到 Unicode”。使用此标志将非链接符号映射到 unicode“空格”（代码 32）上。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setRemoveSpacesFromCMapNames(boolean value) {#setRemoveSpacesFromCMapNames-boolean-}
```
public void setRemoveSpacesFromCMapNames(boolean value)
```


某些字体具有名称中带有空格的 ToUnicode 字符代码映射。这些空格可能会调用 unicode 文本映射错误。此标志命令从 ToUnicode 字符代码映射的名称中删除空格。默认为假。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

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
