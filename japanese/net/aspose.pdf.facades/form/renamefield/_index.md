---
title: "Form.RenameField"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Form メソッド。フィールドの名前を変更します。AcroForm フィールドまたは XFA フィールドのいずれでも構いません。"
type: docs
weight: 330
url: /ja/net/aspose.pdf.facades/form/renamefield/
---
## Form.RenameField method

フィールドの名前を変更します。AcroForm フィールドまたは XFA フィールドのいずれでも構いません。

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | 古いフィールド名 |
| newFieldName | String | 新しいフィールド名 |

## 例

```csharp
Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf");
form.RenameField("field", "field1");
form.Save();
```

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


