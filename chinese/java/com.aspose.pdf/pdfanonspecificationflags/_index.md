---
title: PdfFormatConversionOptions.PdfANonSpecificationFlags
second_title: 用于 Java API 参考的 Aspose.PDF
description: 当源 PDF 文档不符合 PDF 规范时，此类包含控制 PDF/A 转换的标志。
type: docs
weight: 10
url: /zh/java/com.aspose.pdf/pdfformatconversionoptions.pdfanonspecificationflags/
---
**遗产：**
java.lang.Object
```
public static class PdfFormatConversionOptions.PdfANonSpecificationFlags
```

当源 PDF 文档不符合 PDF 规范时，此类包含控制 PDF/A 转换的标志。如果使用这个类的标志，它会降低性能，但当源 PDF 文档不能通过通常的方式转换为 PDF/A 格式时，这是必要的。默认情况下，所有标志都设置为 false。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfANonSpecificationFlags()](#PdfANonSpecificationFlags--) | 构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCheckDifferentNamesInFontDictionaries()](#getCheckDifferentNamesInFontDictionaries--) | 某些 PDF 文档包含在内部数据中具有不同名称的字体。 |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCheckDifferentNamesInFontDictionaries(boolean value)](#setCheckDifferentNamesInFontDictionaries-boolean-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfANonSpecificationFlags() {#PdfANonSpecificationFlags--}
```
public PdfANonSpecificationFlags()
```


构造函数

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
### getCheckDifferentNamesInFontDictionaries() {#getCheckDifferentNamesInFontDictionaries--}
```
public boolean getCheckDifferentNamesInFontDictionaries()
```


某些 PDF 文档包含在内部数据中具有不同名称的字体。当字段 BaseFont 和 FontDescriptor.FontName 不同时，使用此标志会强制执行特殊处理逻辑。

**退货：**
布尔值 - 
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




### setCheckDifferentNamesInFontDictionaries(boolean value) {#setCheckDifferentNamesInFontDictionaries-boolean-}
```
public void setCheckDifferentNamesInFontDictionaries(boolean value)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

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
