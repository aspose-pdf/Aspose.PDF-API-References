---
title: "FormEditor.RadioHoriz"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "FormEditor プロパティ。ラジオボタンが水平に配置されるか垂直に配置されるかを示すフラグです。デフォルト値は true です。"
type: docs
weight: 80
url: /ja/net/aspose.pdf.facades/formeditor/radiohoriz/
---
## FormEditor.RadioHoriz property

ラジオボタンが水平に配置されているか垂直に配置されているかを示すフラグで、デフォルト値は true です。

```csharp
public bool RadioHoriz { get; set; }
```

## 例

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
formEditor.RadioGap = 4;
formEditor.RadioHoriz = false;
formEditor.Items = new string[] { "First", "Second", "Third" };
formEditor.AddField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

### 関連項目

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


