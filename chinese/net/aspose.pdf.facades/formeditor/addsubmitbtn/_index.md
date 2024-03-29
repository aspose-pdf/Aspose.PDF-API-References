---
title: AddSubmitBtn
second_title: Aspose.PDF for .NET API 参考
description: 在表单上添加提交按钮
type: docs
weight: 170
url: /zh/net/aspose.pdf.facades/formeditor/addsubmitbtn/
---
## FormEditor.AddSubmitBtn method

在表单上添加提交按钮。

```csharp
public void AddSubmitBtn(string fieldName, int page, string label, string url, float llx, 
    float lly, float urx, float ury)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 新按钮的名称。 |
| page | Int32 | 将放置按钮的页面。 |
| label | String | 按钮标题。 |
| url | String | 提交按钮的 URL。 |
| llx | Single | 左下角的横坐标。 |
| lly | Single | 左下角的纵坐标。 |
| urx | Single | 右上角的横坐标。 |
| ury | Single | 右上角的纵坐标。 |

### 例子

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf");
formEditor.AddSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270);
```

### 也可以看看

* class [FormEditor](../../formeditor)
* 命名空间 [Aspose.Pdf.Facades](../../formeditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
