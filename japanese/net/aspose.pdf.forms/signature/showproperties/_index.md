---
title: Signature.ShowProperties
second_title: Aspose.PDF for .NET API Reference
description: 署名プロパティ。署名プロパティを表示/非表示にするための強制。ShowPropertiesがtrueの場合、署名フィールドには、デジタル署名された証明書の主題、署名日、理由、場所を表す外観の文字列の事前定義された形式があります。ここで、XはX値のプレースホルダーです。また、署名には画像を含めることができ、この場合、リストされた文字列は画像の上に配置されます。ShowPropertiesはデフォルトでtrueです。
type: docs
weight: 130
url: /ja/net/aspose.pdf.forms/signature/showproperties/
---
## Signature.ShowPropertiesプロパティ

署名プロパティを表示/非表示にするための強制。ShowPropertiesがtrueの場合、署名フィールドには外観の事前定義された形式（表す文字列）が含まれます：------------------------------------------- デジタル署名された {certificate subject} 日付: {signature.Date} 理由: {signature.Reason} 場所: {signature.Location} ------------------------------------------- ここで、{X}はX値のプレースホルダーです。また、署名には画像を含めることができ、この場合、リストされた文字列は画像の上に配置されます。ShowPropertiesはデフォルトでtrueです。

```csharp
public bool ShowProperties { get; set; }
```

### 参照

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)