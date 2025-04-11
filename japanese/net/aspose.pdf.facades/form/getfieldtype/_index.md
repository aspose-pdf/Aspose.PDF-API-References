---
title: Form.GetFieldType
second_title: Aspose.PDF for .NET API Reference
description: Form メソッド。フィールドのタイプを返します
type: docs
weight: 240
url: /ja/net/aspose.pdf.facades/form/getfieldtype/
---
## Form.GetFieldType メソッド

フィールドのタイプを返します。

```csharp
public FieldType GetFieldType(string fieldName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | フィールド名。 |

### 戻り値

フィールドタイプに対応する FileType 列挙体の要素。

## 例

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldType("textField") == FieldType.Text)
{
   Console.WriteLine("Type of field is text");
}
```

### 関連項目

* enum [FieldType](../../fieldtype/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)