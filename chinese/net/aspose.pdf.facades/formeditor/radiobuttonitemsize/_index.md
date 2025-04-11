---
title: FormEditor.RadioButtonItemSize
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 属性。获取或设置添加新单选按钮字段时单选按钮项的大小
type: docs
weight: 60
url: /zh/net/aspose.pdf.facades/formeditor/radiobuttonitemsize/
---
## FormEditor.RadioButtonItemSize 属性

获取或设置单选按钮项的大小（当添加新单选按钮字段时）。

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

### 另请参阅

* 类 [FormEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)