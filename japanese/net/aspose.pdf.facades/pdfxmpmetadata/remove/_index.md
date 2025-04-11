---
title: PdfXmpMetadata.Remove
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata メソッド。指定されたキーを持つ要素を削除します。
type: docs
weight: 210
url: /ja/net/aspose.pdf.facades/pdfxmpmetadata/remove/
---
## Remove(DefaultMetadataProperties) {#remove_2}

指定されたキーを持つ要素を削除します。

```csharp
public void Remove(DefaultMetadataProperties key)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| key | DefaultMetadataProperties | 削除される要素のキー。 |

## 例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove(DefaultMetadataProperties.Nickname);
```

### 参照

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(string) {#remove_1}

辞書からキーを削除します。

```csharp
public bool Remove(string key)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| key | String | 削除されるキー。 |

### 戻り値

True - キーが削除された場合; それ以外の場合は false。

## 例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove("xmp:Nickname");
```

### 参照

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, XmpValue&gt;) {#remove}

コレクションからキー/値ペアを削除します。

```csharp
public bool Remove(KeyValuePair<string, XmpValue> item)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | KeyValuePair`2 | 削除されるキー/値ペア。 |

### 戻り値

ペアが見つかり、削除された場合は true。

### 参照

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)