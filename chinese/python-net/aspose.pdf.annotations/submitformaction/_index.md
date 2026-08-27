---
title: "SubmitFormAction"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "描述 submit-form 操作的类。"
type: docs
weight: 810
url: /zh/python-net/aspose.pdf.annotations/submitformaction/
---

## SubmitFormAction class

描述 submit-form 操作的类。

SubmitFormAction 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| SubmitFormAction() | 初始化 SubmitFormAction 对象。 |
## 属性
| 名称 | 描述 |
| :- | :- |
| 下一步 | 顺序中的下一个操作。 |
| flags | 获取或设置提交操作的标志。 |
| url | 目标 URL。 |
| EXCLUDE | 如果为 clear，Fields 数组指定要在提交中包含的字段。 |
| INCLUDE_NO_VALUE_FIELDS | 如果设置，将提交由 Fields 数组和 Include/Exclude 标志指定的所有字段。 |
| EXPORT_FORMAT | 如果设置，将以 HTML 表单格式提交字段名称和值。 |
| GET_METHOD | 如果设置，将使用 HTTP GET 请求提交字段名称和值。 |
| SUBMIT_COORDINATES | 如果设置，将把导致 submit-form 操作的鼠标点击坐标作为表单数据的一部分传输。 |
| XFDF | 如果设置，将以 XFDF 形式提交字段名称和值。 |
| INCLUDE_APPEND_SAVES | 如果设置，则提交的 FDF 文件应包含所有增量更新的内容。 |
| INCLUDE_ANNOTATIONS | 如果设置，则提交的 FDF 文件应包含底层 PDF 文档中的所有标记注释。 |
| SUBMIT_PDF | 如果设置，则文档应以 PDF 形式提交，使用 MIME 内容类型 application/pdf。 |
| CANONICAL_FORMAT | 如果设置，任何表示日期的提交字段值应转换为标准格式。 |
| EXCL_NON_USER_ANNOTS | 如果设置，则仅包括 T 条目与当前用户名称匹配的标记注释。 |
| EXCL_F_KEY | 如果设置，提交的 FDF 应排除 F 条目。 |
| EMBED_FORM | 如果设置，提交的 FDF 的 F 条目应为一个文件规范，包含一个 <br/>            嵌入的文件流，表示提交 FDF 的 PDF 文件。 |

### 另请参阅

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

