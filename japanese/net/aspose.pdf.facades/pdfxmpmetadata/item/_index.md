---
title: "PdfXmpMetadata.Item"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfXmpMetadata プロパティ。 キーで値を取得または設定します。"
type: docs
weight: 70
url: /ja/net/aspose.pdf.facades/pdfxmpmetadata/item/
---
## PdfXmpMetadata indexer (1 of 2)

キーで値を取得または設定します。

```csharp
public XmpValue this[string key] { get; set; }
```

| パラメーター | 説明 |
| --- | --- |
| キー | 取得/設定するキー名。 |

### 戻り値

キーによるオブジェクト

## 例

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm["xmp:Nickname"]);
```

### 関連項目

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PdfXmpMetadata indexer (2 of 2)

キーで XMP メタデータの値を取得します。

```csharp
public XmpValue this[DefaultMetadataProperties key] { get; set; }
```

| パラメーター | 説明 |
| --- | --- |
| キー | 値のキーです。 |

### 戻り値

XMP メタデータからの値です。

## 例

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm[DefaultMetadataProperties.CreatorTool]);
```

### 関連項目

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


