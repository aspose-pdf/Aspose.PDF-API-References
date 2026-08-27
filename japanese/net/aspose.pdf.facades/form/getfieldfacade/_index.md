---
title: "Form.GetFieldFacade"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Form メソッド。すべての外観属性を含む FrohmFieldFacade オブジェクトを返します"
type: docs
weight: 210
url: /ja/net/aspose.pdf.facades/form/getfieldfacade/
---
## Form.GetFieldFacade method

すべての外観属性を含む FrofmFieldFacade オブジェクトを返します。

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("form.pdf");
FormFieldFacade field = form.GetFieldFacade("field1");
Console.WriteLine("Color of field border: " + field.BorderColor);
```

```csharp
public FormFieldFacade GetFieldFacade(string fieldName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | 読み取るフィールドの名前。 |

### 戻り値

FormFieldFacade オブジェクト

### 関連項目

* class [FormFieldFacade](../../formfieldfacade/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


