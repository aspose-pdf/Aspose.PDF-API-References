---
title: PdfXmpMetadata.GetNamespaceURIByPrefix
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata メソッド。プレフィックスによって名前空間 URI を取得します
type: docs
weight: 170
url: /ja/net/aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/
---
## PdfXmpMetadata.GetNamespaceURIByPrefix メソッド

プレフィックスによって名前空間 URI を取得します。

```csharp
public string GetNamespaceURIByPrefix(string prefix)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| prefix | String | プレフィックス。 |

### 戻り値

名前空間 URI。

## 例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetNamespaceURIByPrefix("xmp"));
```

### 関連項目

* クラス [PdfXmpMetadata](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)