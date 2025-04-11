---
title: FormEditor.Items
second_title: Aspose.PDF for .NET API Reference
description: FormEditor プロパティ。新しく作成されたリストボックスまたはコンボボックスに追加されるアイテムを設定します。
type: docs
weight: 50
url: /ja/net/aspose.pdf.facades/formeditor/items/
---
## FormEditor.Items プロパティ

新しく作成されたリストボックスまたはコンボボックスに追加されるアイテムを設定します。

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("input.pdf", "output.pdf");
formEditor.Items = new string[] { "AAA", "BBB", "CCC" };
formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130);
formEditor.Save();
```

```csharp
public string[] Items { get; set; }
```

### 関連項目

* クラス [FormEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)