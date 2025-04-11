---
title: PdfXmpMetadata.GetPrefixByNamespaceURI
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata メソッド。名前空間 URI によってプレフィックスを取得します
type: docs
weight: 180
url: /ja/net/aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/
---
## PdfXmpMetadata.GetPrefixByNamespaceURI メソッド

名前空間 URI によってプレフィックスを取得します。

```csharp
public string GetPrefixByNamespaceURI(string namespaceURI)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| namespaceURI | 文字列 | 名前空間 URI。 |

### 戻り値

プレフィックス値。

## 例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/"));
```

### 参照

* クラス [PdfXmpMetadata](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)