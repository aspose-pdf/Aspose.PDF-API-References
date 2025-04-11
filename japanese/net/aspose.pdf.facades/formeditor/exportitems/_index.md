---
title: FormEditor.ExportItems
second_title: Aspose.PDF for .NET API Reference
description: FormEditor プロパティ。エクスポート値を持つコンボボックスのオプションを設定します
type: docs
weight: 30
url: /ja/net/aspose.pdf.facades/formeditor/exportitems/
---
## FormEditor.ExportItems プロパティ

エクスポート値を持つコンボボックスのオプションを設定します。

```csharp
public string[][] ExportItems { get; set; }
```

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_Updated.pdf"));
formEditor.ExportItems = new string[][] 
{ 
    new string[] { "1", "Firs" }, 
    new string[] { "2", "Second" }, 
    new string[] { "3", "Third" } 
};
formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

### 関連項目

* クラス [FormEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)