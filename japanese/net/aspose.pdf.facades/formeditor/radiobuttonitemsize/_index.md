---
title: "FormEditor.RadioButtonItemSize"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "FormEditor プロパティ。新しいラジオボタンフィールドが追加される際のラジオボタン項目サイズを取得または設定します。"
type: docs
weight: 60
url: /ja/net/aspose.pdf.facades/formeditor/radiobuttonitemsize/
---
## FormEditor.RadioButtonItemSize property

新しいラジオボタンフィールドが追加される際のラジオボタン項目サイズを取得または設定します。

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

### 関連項目

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


