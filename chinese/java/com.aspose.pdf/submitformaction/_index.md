---
title: SubmitFormAction
second_title: 用于 Java API 参考的 Aspose.PDF
description: 描述提交表单操作的类。
type: docs
weight: 342
url: /zh/java/com.aspose.pdf/submitformaction/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.PdfAction](../../com.aspose.pdf/pdfaction)
```
public final class SubmitFormAction extends PdfAction
```

描述提交表单操作的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SubmitFormAction()](#SubmitFormAction--) | 初始化 SubmitFormAction 对象。 |
## 领域

| 场地 | 描述 |
| --- | --- |
| [CANONICAL_FORMAT](#CANONICAL-FORMAT) | 如果设置，任何提交的表示日期的字段值都应转换为标准格式。 |
| [EMBED_FORM](#EMBED-FORM) | 如果设置，提交的 FDF 的 F 条目应是包含嵌入文件流的文件规范，表示从中提交 FDF 的 PDF 文件。 |
| [EXCLUDE](#EXCLUDE) | 如果清除，则 Fields 数组指定要包含在提交中的字段。 |
| [EXCL_F_KEY](#EXCL-F-KEY) | 如果设置，提交的 FDF 应排除 F 条目。 |
| [EXCL_NON_USER_ANNOTS](#EXCL-NON-USER-ANNOTS) | 如果设置，它应仅包括那些 T 条目与当前用户的名称匹配的标记注释。 |
| [EXPORT_FORMAT](#EXPORT-FORMAT) | 如果设置，字段名称和值应以 HTML 表单格式提交。 |
| [GET_METHOD](#GET-METHOD) | 如果设置，应使用 HTTP GET 请求提交字段名称和值。 |
| [INCLUDE_ANNOTATIONS](#INCLUDE-ANNOTATIONS) | 如果设置，提交的 FDF 文件应包括基础 PDF 文档中的所有标记注释。 |
| [INCLUDE_APPEND_SAVES](#INCLUDE-APPEND-SAVES) | 如果设置，提交的 FDF 文件应包括所有增量更新的内容。 |
| [INCLUDE_NO_VALUE_FIELDS](#INCLUDE-NO-VALUE-FIELDS) | 如果设置，则应提交由 Fields 数组和 Include/Exclude 标志指定的所有字段。 |
| [SUBMIT_COORDINATES](#SUBMIT-COORDINATES) | 如果设置，引起提交表单动作的鼠标点击坐标应作为表单数据的一部分传输。 |
| [SUBMIT_PDF](#SUBMIT-PDF) | 如果设置，文档应以 PDF 格式提交，使用 MIME 内容类型 application/pdf。 |
| [XFDF](#XFDF) | 如果设置，字段名称和值应作为 XFDF 提交。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFlags()](#getFlags--) | 获取提交操作的标志 |
| [getNext()](#getNext--) | 接下来的动作依次进行。 |
| [getUrl()](#getUrl--) | 目标网址。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFlags(int value)](#setFlags-int-) | 设置提交操作的标志 |
| [setUrl(FileSpecification value)](#setUrl-com.aspose.pdf.FileSpecification-) | 目标网址。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SubmitFormAction() {#SubmitFormAction--}
```
public SubmitFormAction()
```


初始化 SubmitFormAction 对象。

### CANONICAL_FORMAT {#CANONICAL-FORMAT}
```
public static final int CANONICAL_FORMAT
```


如果设置，任何提交的表示日期的字段值都应转换为标准格式。

### EMBED_FORM {#EMBED-FORM}
```
public static final int EMBED_FORM
```


如果设置，提交的 FDF 的 F 条目应是包含嵌入文件流的文件规范，表示从中提交 FDF 的 PDF 文件。

### EXCLUDE {#EXCLUDE}
```
public static final int EXCLUDE
```


如果清除，则 Fields 数组指定要包含在提交中的字段。

### EXCL_F_KEY {#EXCL-F-KEY}
```
public static final int EXCL_F_KEY
```


如果设置，提交的 FDF 应排除 F 条目。

### EXCL_NON_USER_ANNOTS {#EXCL-NON-USER-ANNOTS}
```
public static final int EXCL_NON_USER_ANNOTS
```


如果设置，它应仅包括那些 T 条目与当前用户的名称匹配的标记注释。

### EXPORT_FORMAT {#EXPORT-FORMAT}
```
public static final int EXPORT_FORMAT
```


如果设置，字段名称和值应以 HTML 表单格式提交。

### GET_METHOD {#GET-METHOD}
```
public static final int GET_METHOD
```


如果设置，应使用 HTTP GET 请求提交字段名称和值。

### INCLUDE_ANNOTATIONS {#INCLUDE-ANNOTATIONS}
```
public static final int INCLUDE_ANNOTATIONS
```


如果设置，提交的 FDF 文件应包括基础 PDF 文档中的所有标记注释。

### INCLUDE_APPEND_SAVES {#INCLUDE-APPEND-SAVES}
```
public static final int INCLUDE_APPEND_SAVES
```


如果设置，提交的 FDF 文件应包括所有增量更新的内容。

### INCLUDE_NO_VALUE_FIELDS {#INCLUDE-NO-VALUE-FIELDS}
```
public static final int INCLUDE_NO_VALUE_FIELDS
```


如果设置，则应提交由 Fields 数组和 Include/Exclude 标志指定的所有字段。

### SUBMIT_COORDINATES {#SUBMIT-COORDINATES}
```
public static final int SUBMIT_COORDINATES
```


如果设置，引起提交表单动作的鼠标点击坐标应作为表单数据的一部分传输。

### SUBMIT_PDF {#SUBMIT-PDF}
```
public static final int SUBMIT_PDF
```


如果设置，文档应以 PDF 格式提交，使用 MIME 内容类型 application/pdf。

### XFDF {#XFDF}
```
public static final int XFDF
```


如果设置，字段名称和值应作为 XFDF 提交。

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
### getFlags() {#getFlags--}
```
public int getFlags()
```


获取提交操作的标志

**退货：**
int - 整数值
### getNext() {#getNext--}
```
public ActionCollection getNext()
```


接下来的动作依次进行。

**退货：**
[ActionCollection](../../com.aspose.pdf/actioncollection) 动作集合对象
### getUrl() {#getUrl--}
```
public FileSpecification getUrl()
```


目标网址。

**退货：**
[FileSpecification](../../com.aspose.pdf/filespecification) FileSpecification 值
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




### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


设置提交操作的标志

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setUrl(FileSpecification value) {#setUrl-com.aspose.pdf.FileSpecification-}
```
public void setUrl(FileSpecification value)
```


目标网址。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [FileSpecification](../../com.aspose.pdf/filespecification) | 文件规格值 |

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
