---
title: FormEditor.Facade
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 属性。设置字段的视觉属性
type: docs
weight: 40
url: /zh/net/aspose.pdf.facades/formeditor/facade/
---
## FormEditor.Facade 属性

设置字段的视觉属性。

```csharp
public FormFieldFacade Facade { get; set; }
```

## 示例

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "PdfForm_DecorateField_text.pdf");
fe.Facade = new FormFieldFacade();
fe.Facade.BackgroundColor = System.Drawing.Color.Red;
fe.Facade.TextColor = System.Drawing.Color.Blue;
fe.Facade.BorderColor = System.Drawing.Color.Green;
fe.Facade.Alignment = FormFieldFacade.AlignCenter;
fe.DecorateField("textField");
fe.Save();
```

### 另请参阅

* 类 [FormFieldFacade](../../formfieldfacade/)
* 类 [FormEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)