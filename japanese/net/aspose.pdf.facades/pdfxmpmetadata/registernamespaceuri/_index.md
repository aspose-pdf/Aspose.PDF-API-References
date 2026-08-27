---
title: "PdfXmpMetadata.RegisterNamespaceURI"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfXmpMetadata メソッド。名前空間 URI を登録します。"
type: docs
weight: 200
url: /ja/net/aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/
---
## PdfXmpMetadata.RegisterNamespaceURI method

名前空間 URI を登録します。

```csharp
public void RegisterNamespaceURI(string prefix, string namespaceURI)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| prefix | String | プレフィックスです。 |
| namespaceURI | String | 名前空間 URIです。 |

## 例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
xmp.RegisterNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

### 関連項目

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


