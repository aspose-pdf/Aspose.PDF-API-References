---
title: Form.GetFieldFlag
second_title: Aspose.PDF for .NET API Reference
description: Form メソッド。フィールドのフラグを返します
type: docs
weight: 220
url: /ja/net/aspose.pdf.facades/form/getfieldflag/
---
## Form.GetFieldFlag メソッド

フィールドのフラグを返します。

```csharp
public PropertyFlag GetFieldFlag(string fieldName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | フィールド名 |

### 戻り値

プロパティフラグ (ReadOnly/ Required/NoExport

## 例

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldFlag("textField") == PropertyFlag.ReadOnly)
{
   Console.WriteLine("Field is read-only");
}
```

### 関連項目

* enum [PropertyFlag](../../propertyflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)