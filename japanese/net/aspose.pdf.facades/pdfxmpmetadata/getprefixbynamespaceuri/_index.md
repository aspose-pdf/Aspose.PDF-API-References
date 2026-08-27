---
title: "PdfXmpMetadata.GetPrefixByNamespaceURI"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfXmpMetadata メソッド。namespace URI によってプレフィックスを取得します。"
type: docs
weight: 180
url: /ja/net/aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/
---
## PdfXmpMetadata.GetPrefixByNamespaceURI method

名前空間 URI からプレフィックスを取得します。

```csharp
public string GetPrefixByNamespaceURI(string namespaceURI)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| namespaceURI | String | Namespace URI。 |

### 戻り値

プレフィックスの値。

## 例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/"));
```

### 関連項目

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


