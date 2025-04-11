---
title: Form.RenameField
second_title: Aspose.PDF for .NET API Reference
description: フォームメソッド。フィールドの名前を変更します。AcroFormフィールドまたはXFAフィールドのいずれでも構いません。
type: docs
weight: 330
url: /ja/net/aspose.pdf.facades/form/renamefield/
---
## Form.RenameField メソッド

フィールドの名前を変更します。AcroFormフィールドまたはXFAフィールドのいずれでも構いません。

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| パラメーター | 型 | 説明 |
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

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)