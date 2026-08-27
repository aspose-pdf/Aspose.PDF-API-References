---
title: "FormEditor.RadioGap"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "FormEditor プロパティ。隣接するラジオボタン間のギャップ（ピクセル）を記録するメンバーです。デフォルトは 50 です。"
type: docs
weight: 70
url: /ja/net/aspose.pdf.facades/formeditor/radiogap/
---
## FormEditor.RadioGap property

隣接するラジオボタン間のギャップをピクセル単位で記録するメンバーで、デフォルトは 50 です。

```csharp
public float RadioGap { get; set; }
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


