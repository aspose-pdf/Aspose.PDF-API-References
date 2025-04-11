---
title: PdfXmpMetadata.RegisterNamespaceURI
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata メソッド。名前空間 URI を登録します
type: docs
weight: 200
url: /ja/net/aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/
---
## PdfXmpMetadata.RegisterNamespaceURI メソッド

名前空間 URI を登録します。

```csharp
public void RegisterNamespaceURI(string prefix, string namespaceURI)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| prefix | String | プレフィックス。 |
| namespaceURI | String | 名前空間 URI。 |

## 例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
xmp.RegisterNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

### 参照

* クラス [PdfXmpMetadata](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)