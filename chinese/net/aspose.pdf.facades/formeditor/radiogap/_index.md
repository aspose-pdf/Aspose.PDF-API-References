---
title: FormEditor.RadioGap
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 属性。用于记录两个相邻单选按钮之间的间距（以像素为单位），默认值为 50
type: docs
weight: 70
url: /zh/net/aspose.pdf.facades/formeditor/radiogap/
---
## FormEditor.RadioGap 属性

用于记录两个相邻单选按钮之间的间距（以像素为单位），默认值为 50。

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

### 另请参阅

* 类 [FormEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)