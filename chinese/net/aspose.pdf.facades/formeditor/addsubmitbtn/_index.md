---
title: FormEditor.AddSubmitBtn
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 方法。 在表单上添加提交按钮
type: docs
weight: 130
url: /zh/net/aspose.pdf.facades/formeditor/addsubmitbtn/
---
## FormEditor.AddSubmitBtn 方法

在表单上添加提交按钮。

```csharp
public void AddSubmitBtn(string fieldName, int page, string label, string url, float llx, 
    float lly, float urx, float ury)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 新按钮的名称。 |
| page | Int32 | 按钮将放置的页面。 |
| label | 字符串 | 按钮标题。 |
| url | 字符串 | 提交按钮的 URL。 |
| llx | 单精度 | 左下角的横坐标。 |
| lly | 单精度 | 左下角的纵坐标。 |
| urx | 单精度 | 右上角的横坐标。 |
| ury | 单精度 | 右上角的纵坐标。 |

## 示例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf");
formEditor.AddSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270);
```

### 另请参阅

* 类 [FormEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)