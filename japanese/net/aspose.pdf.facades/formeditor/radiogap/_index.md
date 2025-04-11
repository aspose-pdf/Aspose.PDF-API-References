---
title: FormEditor.RadioGap
second_title: Aspose.PDF for .NET API Reference
description: FormEditor プロパティ。隣接するラジオボタン間のギャップをピクセル単位で記録するメンバー。デフォルトは 50。
type: docs
weight: 70
url: /ja/net/aspose.pdf.facades/formeditor/radiogap/
---
## FormEditor.RadioGap プロパティ

隣接するラジオボタン間のギャップをピクセル単位で記録するメンバー。デフォルトは 50。

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

* クラス [FormEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)