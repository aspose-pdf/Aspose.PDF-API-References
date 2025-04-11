---
title: PdfXmpMetadata.Item
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata プロパティ。キーによって値を取得または設定します
type: docs
weight: 70
url: /ja/net/aspose.pdf.facades/pdfxmpmetadata/item/
---
## PdfXmpMetadata インデクサー (1 of 2)

キーによって値を取得または設定します。

```csharp
public XmpValue this[string key] { get; set; }
```

| パラメーター | 説明 |
| --- | --- |
| key | 取得/設定するキー名。 |

### 戻り値

キーによるオブジェクト

## 例

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm["xmp:Nickname"]);
```

### 参照

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PdfXmpMetadata インデクサー (2 of 2)

キーによって XMP メタデータの値を取得します。

```csharp
public XmpValue this[DefaultMetadataProperties key] { get; set; }
```

| パラメーター | 説明 |
| --- | --- |
| key | 値のキー。 |

### 戻り値

XMP メタデータからの値。

## 例

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm[DefaultMetadataProperties.CreatorTool]);
```

### 参照

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)