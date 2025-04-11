---
title: Form.FormSubmitButtonNames
second_title: Aspose.PDF for .NET API Reference
description: 表单属性。获取所有表单提交按钮名称
type: docs
weight: 40
url: /zh/net/aspose.pdf.facades/form/formsubmitbuttonnames/
---
## Form.FormSubmitButtonNames 属性

获取所有表单提交按钮名称。

```csharp
public string[] FormSubmitButtonNames { get; }
```

## 示例

```csharp
Form form = new Form("PdfForm.pdf");
string[] submits = form.FormSubmitButtonNames;
foreach(string btn in submits)
{
  Console.WriteLine(btn);
}
```

### 另请参阅

* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)