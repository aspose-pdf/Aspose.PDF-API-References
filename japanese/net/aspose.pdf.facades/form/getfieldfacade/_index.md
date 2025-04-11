---
title: Form.GetFieldFacade
second_title: Aspose.PDF for .NET API Reference
description: フォームメソッド。すべての外観属性を含む FrofmFieldFacade オブジェクトを返します
type: docs
weight: 210
url: /ja/net/aspose.pdf.facades/form/getfieldfacade/
---
## Form.GetFieldFacade メソッド

すべての外観属性を含む FrofmFieldFacade オブジェクトを返します。

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("form.pdf");
FormFieldFacade field = form.GetFieldFacade("field1");
Console.WriteLine("Color of field border: " + field.BorderColor);
```

```csharp
public FormFieldFacade GetFieldFacade(string fieldName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | 文字列 | 読み取るフィールドの名前。 |

### 戻り値

FormFieldFacade オブジェクト

### 参照

* クラス [FormFieldFacade](../../formfieldfacade/)
* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)