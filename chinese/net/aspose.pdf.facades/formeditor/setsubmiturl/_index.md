---
title: "FormEditor.SetSubmitUrl"
second_title: "Aspose.PDF for .NET API 参考"
description: "FormEditor 方法。设置按钮的 URL"
type: docs
weight: 340
url: /zh/net/aspose.pdf.facades/formeditor/setsubmiturl/
---
## FormEditor.SetSubmitUrl method

设置按钮的 URL。

```csharp
public bool SetSubmitUrl(string fieldName, string url)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 提交按钮名称。 |
| url | String | 完整的 URL。 |

### 返回值

如果成功设置按钮的 URL，则返回 true。

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
formEditor.SetSubmitUrl("btnSubmit", "www.mysite.com");
```

### 另请参见

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


