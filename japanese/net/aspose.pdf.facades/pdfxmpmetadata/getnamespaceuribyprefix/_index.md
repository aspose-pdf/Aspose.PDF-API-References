---
title: "PdfXmpMetadata.GetNamespaceURIByPrefix"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfXmpMetadata メソッド。プレフィックスで名前空間 URI を取得します。"
type: docs
weight: 170
url: /ja/net/aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/
---
## PdfXmpMetadata.GetNamespaceURIByPrefix method

プレフィックスから名前空間 URI を取得します。

```csharp
public string GetNamespaceURIByPrefix(string prefix)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| prefix | String | プレフィックスです。 |

### 戻り値

Namespace URI。

## 例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetNamespaceURIByPrefix("xmp"));
```

### 関連項目

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


