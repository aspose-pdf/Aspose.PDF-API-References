---
title: "FormEditor.Facade"
second_title: "Aspose.PDF for .NET API 参考"
description: "FormEditor 属性。设置字段的可视属性。"
type: docs
weight: 40
url: /zh/net/aspose.pdf.facades/formeditor/facade/
---
## FormEditor.Facade property

设置字段的可视属性。

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

### 另请参见

* class [FormFieldFacade](../../formfieldfacade/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


