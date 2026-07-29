---
title: "FormEditor.RadioGap"
second_title: "Aspose.PDF for .NET API 参考"
description: "FormEditor 属性。记录相邻两个单选按钮之间间距的成员，单位为像素，默认值为 50"
type: docs
weight: 70
url: /zh/net/aspose.pdf.facades/formeditor/radiogap/
---
## FormEditor.RadioGap property

用于记录两个相邻单选按钮之间像素间距的成员，默认值为 50。

```csharp
public float RadioGap { get; set; }
```

## 示例

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
formEditor.RadioGap = 4;
formEditor.RadioHoriz = false;
formEditor.Items = new string[] { "First", "Second", "Third" };
formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

### 另请参见

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


