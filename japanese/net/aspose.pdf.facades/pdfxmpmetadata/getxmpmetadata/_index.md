---
title: "PdfXmpMetadata.GetXmpMetadata"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfXmpMetadata メソッド。 入力 PDF の XmpMetadata を XML 形式で取得します。"
type: docs
weight: 190
url: /ja/net/aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/
---
## GetXmpMetadata() {#getxmpmetadata}

入力 PDF の XmpMetadata を XML 形式で取得します。

```csharp
public byte[] GetXmpMetadata()
```

### 戻り値

XmpMetadata のバイト配列。

## 例

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata();
```

### 関連項目

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetXmpMetadata(string) {#getxmpmetadata_1}

メタ名に基づいて入力 PDF の XmpMetadata の一部を取得します。

```csharp
public byte[] GetXmpMetadata(string name)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| 名前 | String | メタデータ名。 |

### 戻り値

メタデータのバイト。

## 例

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata("dc:creator");
```

### 関連項目

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


