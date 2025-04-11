---
title: FormEditor.SetSubmitUrl
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 方法。设置按钮的 URL
type: docs
weight: 340
url: /zh/net/aspose.pdf.facades/formeditor/setsubmiturl/
---
## FormEditor.SetSubmitUrl 方法

设置按钮的 URL。

```csharp
public bool SetSubmitUrl(string fieldName, string url)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 提交按钮名称。 |
| url | 字符串 | 完全限定的 URL。 |

### 返回值

如果按钮的 URL 成功设置，则返回 true。

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
formEditor.SetSubmitUrl("btnSubmit", "www.mysite.com");
```

### 另请参见

* 类 [FormEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)