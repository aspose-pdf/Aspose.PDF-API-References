---
title: "FormEditor.Items"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "FormEditor プロパティ。新しく作成されたリストボックスまたはコンボボックスに追加される項目を設定します"
type: docs
weight: 50
url: /ja/net/aspose.pdf.facades/formeditor/items/
---
## FormEditor.Items property

新しく作成されたリストボックスまたはコンボボックスに追加される項目を設定します。

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

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


