---
title: "PdfXmpMetadata.Contains"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfXmpMetadata メソッド。辞書が指定されたキーを含んでいるかチェックします。"
type: docs
weight: 130
url: /ja/net/aspose.pdf.facades/pdfxmpmetadata/contains/
---
## Contains(string) {#contains_2}

辞書が指定されたキーを含んでいるか確認します。

```csharp
public bool Contains(string key)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| キー | String | チェックされるキーです。 |

### 戻り値

辞書が指定されたキーを含んでいる場合は True、そうでなければ false。

## 例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
if (!xmp.Contains("xmp:Nickname"))
  Console.WriteLine("Key does not exists");
```

### 関連項目

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(DefaultMetadataProperties) {#contains}

辞書が指定されたプロパティを含んでいるか確認します。

```csharp
public bool Contains(DefaultMetadataProperties property)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| プロパティ | DefaultMetadataProperties | チェックされるプロパティです。 |

### 戻り値

辞書が指定されたプロパティを含んでいる場合は True、そうでなければ false。

### 関連項目

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(KeyValuePair&lt;string, XmpValue&gt;) {#contains_1}

指定されたキーと値のペアが辞書に含まれているか確認します。

```csharp
public bool Contains(KeyValuePair<string, XmpValue> item)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| アイテム | KeyValuePair`2 | キーと値のペア。 |

### 戻り値

このペアが見つかった場合は true。

### 関連項目

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


