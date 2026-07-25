---
title: "SubmitFormAction"
linktitle: "SubmitFormAction"
second_title: "Aspose.PDF for Java API 参考"
description: "描述 submit-form 操作的类。"
type: docs
weight: 4690
url: /zh/java/com.aspose.pdf/submitformaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.SubmitFormAction, com.aspose.pdf.PdfAction, com.aspose.pdf.SubmitFormAction

**All Implemented Interfaces:**
IAppointment

```
public final class SubmitFormAction extends PdfAction
```

描述 submit-form 操作的类。

## 字段

| 字段 | 描述 |
| --- | --- |
| [CANONICAL_FORMAT](#CANONICAL_FORMAT) | 如果设置，则任何表示日期的提交字段值应转换为标准格式。 |
| [EMBED_FORM](#EMBED_FORM) | 如果设置，提交的 FDF 的 F 条目应为文件规范，包含表示提交 FDF 所来源的 PDF 文件的嵌入文件流。 |
| [EXCL_F_KEY](#EXCL_F_KEY) | 如果设置，提交的 FDF 应排除 F 条目。 |
| [EXCL_NON_USER_ANNOTS](#EXCL_NON_USER_ANNOTS) | 如果设置，则仅包括那些 T 条目与当前用户名称匹配的标记注释。 |
| [EXCLUDE](#EXCLUDE) | 如果未设置，则 Fields 数组指定要在提交中包含的字段。 |
| [EXPORT_FORMAT](#EXPORT_FORMAT) | 如果设置，则字段名称和值应以 HTML 表单格式提交。 |
| [GET_METHOD](#GET_METHOD) | 如果设置，则字段名称和值应使用 HTTP GET 请求提交。 |
| [INCLUDE_ANNOTATIONS](#INCLUDE_ANNOTATIONS) | 如果设置，则提交的 FDF 文件应包含底层 PDF 文档中的所有标记注释。 |
| [INCLUDE_APPEND_SAVES](#INCLUDE_APPEND_SAVES) | 如果设置，则提交的 FDF 文件应包括所有增量更新的内容。 |
| [INCLUDE_NO_VALUE_FIELDS](#INCLUDE_NO_VALUE_FIELDS) | 如果设置，则应提交由 Fields 数组和 Include/Exclude 标志指定的所有字段。 |
| [SUBMIT_COORDINATES](#SUBMIT_COORDINATES) | 如果设置，则导致 submit-form 动作的鼠标点击坐标应作为表单数据的一部分传输。 |
| [SUBMIT_PDF](#SUBMIT_PDF) | 如果设置，则文档应以 PDF 形式提交，使用 MIME 内容类型 application/pdf。 |
| [XFDF](#XFDF) | 如果设置，则字段名称和值应以 XFDF 形式提交。 |

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SubmitFormAction](#SubmitFormAction--) | 初始化 SubmitFormAction 对象。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFlags](#getFlags--) | 获取提交操作的标志。 |
| [getUrl](#getUrl--) | 目标 URL。 |
| [setFlags](#setFlags-int-) | 设置提交操作的标志。 |
| [setUrl](#setUrl-com.aspose.pdf.FileSpecification-) | 目标 URL。 |

### CANONICAL_FORMAT {#CANONICAL_FORMAT}
```
public static final int CANONICAL_FORMAT
```

如果设置，则任何表示日期的提交字段值应转换为标准格式。

### EMBED_FORM {#EMBED_FORM}
```
public static final int EMBED_FORM
```

如果设置，提交的 FDF 的 F 条目应为文件规范，包含表示提交 FDF 所来源的 PDF 文件的嵌入文件流。

### EXCL_F_KEY {#EXCL_F_KEY}
```
public static final int EXCL_F_KEY
```

如果设置，提交的 FDF 应排除 F 条目。

### EXCL_NON_USER_ANNOTS {#EXCL_NON_USER_ANNOTS}
```
public static final int EXCL_NON_USER_ANNOTS
```

如果设置，则仅包括那些 T 条目与当前用户名称匹配的标记注释。

### EXCLUDE {#EXCLUDE}
```
public static final int EXCLUDE
```

如果未设置，则 Fields 数组指定要在提交中包含的字段。

### EXPORT_FORMAT {#EXPORT_FORMAT}
```
public static final int EXPORT_FORMAT
```

如果设置，则字段名称和值应以 HTML 表单格式提交。

### GET_METHOD {#GET_METHOD}
```
public static final int GET_METHOD
```

如果设置，则字段名称和值应使用 HTTP GET 请求提交。

### INCLUDE_ANNOTATIONS {#INCLUDE_ANNOTATIONS}
```
public static final int INCLUDE_ANNOTATIONS
```

如果设置，则提交的 FDF 文件应包含底层 PDF 文档中的所有标记注释。

### INCLUDE_APPEND_SAVES {#INCLUDE_APPEND_SAVES}
```
public static final int INCLUDE_APPEND_SAVES
```

如果设置，则提交的 FDF 文件应包括所有增量更新的内容。

### INCLUDE_NO_VALUE_FIELDS {#INCLUDE_NO_VALUE_FIELDS}
```
public static final int INCLUDE_NO_VALUE_FIELDS
```

如果设置，则应提交由 Fields 数组和 Include/Exclude 标志指定的所有字段。

### SUBMIT_COORDINATES {#SUBMIT_COORDINATES}
```
public static final int SUBMIT_COORDINATES
```

如果设置，则导致 submit-form 动作的鼠标点击坐标应作为表单数据的一部分传输。

### SUBMIT_PDF {#SUBMIT_PDF}
```
public static final int SUBMIT_PDF
```

如果设置，则文档应以 PDF 形式提交，使用 MIME 内容类型 application/pdf。

### XFDF {#XFDF}
```
public static final int XFDF
```

如果设置，则字段名称和值应以 XFDF 形式提交。

### SubmitFormAction {#SubmitFormAction--}
```
public SubmitFormAction()
```

初始化 SubmitFormAction 对象。

### getFlags {#getFlags--}
```
public int getFlags()
```

获取提交操作的标志。

**Returns:**
int 值

### getUrl {#getUrl--}
```
public FileSpecification getUrl()
```

目标 URL。

**Returns:**
FileSpecification 值

### setFlags {#setFlags-int-}
```
public void setFlags(int value)
```

设置提交操作的标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setUrl {#setUrl-com.aspose.pdf.FileSpecification-}
目标 URL。
