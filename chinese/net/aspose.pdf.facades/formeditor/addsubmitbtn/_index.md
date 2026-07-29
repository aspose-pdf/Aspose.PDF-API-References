---
title: "FormEditor.AddSubmitBtn"
second_title: "Aspose.PDF for .NET API 参考"
description: "FormEditor 方法。向表单添加提交按钮"
type: docs
weight: 130
url: /zh/net/aspose.pdf.facades/formeditor/addsubmitbtn/
---
## FormEditor.AddSubmitBtn method

在表单上添加提交按钮。

```csharp
public void AddSubmitBtn(string fieldName, int page, string label, string url, float llx, 
    float lly, float urx, float ury)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 新按钮的名称。 |
| 页面 | Int32 | 按钮将放置的页面。 |
| label | String | 按钮标题。 |
| url | String | 提交按钮的 URL。 |
| llx | Single | 左下角的横坐标。 |
| lly | Single | 左下角的纵坐标。 |
| urx | Single | 右上角的横坐标。 |
| ury | Single | 右上角的纵坐标。 |

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf");
formEditor.AddSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270);
```

### 另请参见

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


