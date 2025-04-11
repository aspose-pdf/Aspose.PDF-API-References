---
title: FormEditor.RadioHoriz
second_title: Aspose.PDF for .NET API Reference
description: FormEditor プロパティ。ラジオボタンが水平または垂直に配置されているかどうかを示すフラグ、デフォルト値は true
type: docs
weight: 80
url: /ja/net/aspose.pdf.facades/formeditor/radiohoriz/
---
## FormEditor.RadioHoriz プロパティ

ラジオボタンが水平または垂直に配置されているかどうかを示すフラグ、デフォルト値は true です。

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

* クラス [FormEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)