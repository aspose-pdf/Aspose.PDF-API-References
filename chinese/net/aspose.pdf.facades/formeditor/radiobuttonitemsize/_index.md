---
title: RadioButtonItemSize
second_title: Aspose.PDF for .NET API 参考
description: 获取或设置单选按钮项目大小的大小添加新单选按钮字段时
type: docs
weight: 80
url: /zh/net/aspose.pdf.facades/formeditor/radiobuttonitemsize/
---
## FormEditor.RadioButtonItemSize property

获取或设置单选按钮项目大小的大小（添加新单选按钮字段时）。

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
formEditor.RadioGap = 4;
formEditor.RadioHoriz = false;
formEditor.RadioButtonItemSize = 20;
formEditor.Items = new string[] { "First", "Second", "Third" };
formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

```csharp
public double RadioButtonItemSize { get; set; }
```

### 也可以看看

* class [FormEditor](../../formeditor)
* 命名空间 [Aspose.Pdf.Facades](../../formeditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->