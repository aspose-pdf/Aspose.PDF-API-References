---
title: FormEditor.RadioHoriz
second_title: Aspose.PDF for .NET API Reference
description: FormEditor 属性。指示单选按钮是水平排列还是垂直排列的标志，默认值为 true
type: docs
weight: 80
url: /zh/net/aspose.pdf.facades/formeditor/radiohoriz/
---
## FormEditor.RadioHoriz 属性

指示单选按钮是水平排列还是垂直排列的标志，默认值为 true。

```csharp
public bool RadioHoriz { get; set; }
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