---
title: "PdfXmpMetadata.Remove"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfXmpMetadata メソッド。 指定されたキーを持つ要素を削除します。"
type: docs
weight: 210
url: /ja/net/aspose.pdf.facades/pdfxmpmetadata/remove/
---
## Remove(DefaultMetadataProperties) {#remove_2}

指定されたキーの要素を削除します。

```csharp
public void Remove(DefaultMetadataProperties key)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| キー | DefaultMetadataProperties | 削除される要素のキー。 |

## 例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove(DefaultMetadataProperties.Nickname);
```

### 関連項目

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

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| キー | String | 削除されるキー。 |

### 戻り値

キーが削除された場合は true、そうでない場合は false。

## 例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove("xmp:Nickname");
```

### 関連項目

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, XmpValue&gt;) {#remove}

コレクションからキー/値のペアを削除します。

```csharp
public bool Remove(KeyValuePair<string, XmpValue> item)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| アイテム | KeyValuePair`2 | 削除されるキー/値のペア。 |

### 戻り値

ペアが見つかり削除された場合は true。

### 関連項目

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


