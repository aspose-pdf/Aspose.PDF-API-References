---
title: PdfXmpMetadata.Contains
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata メソッド。辞書に指定されたキーが含まれているかどうかを確認します
type: docs
weight: 130
url: /ja/net/aspose.pdf.facades/pdfxmpmetadata/contains/
---
## Contains(string) {#contains_2}

辞書に指定されたキーが含まれているかどうかを確認します。

```csharp
public bool Contains(string key)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| key | String | チェックされるキー。 |

### 戻り値

True - 辞書に指定されたキーが含まれている場合。それ以外の場合は false。

## 例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
if (!xmp.Contains("xmp:Nickname"))
  Console.WriteLine("Key does not exists");
```

### 参照

* クラス [PdfXmpMetadata](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## Contains(DefaultMetadataProperties) {#contains}

辞書に指定されたプロパティが含まれているかどうかを確認します。

```csharp
public bool Contains(DefaultMetadataProperties property)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| property | DefaultMetadataProperties | チェックされるプロパティ。 |

### 戻り値

True - 辞書に指定されたプロパティが含まれている場合。それ以外の場合は false。

### 参照

* 列挙型 [DefaultMetadataProperties](../../defaultmetadataproperties/)
* クラス [PdfXmpMetadata](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## Contains(KeyValuePair&lt;string, XmpValue&gt;) {#contains_1}

指定されたキーと値のペアが辞書に含まれているかどうかを確認します。

```csharp
public bool Contains(KeyValuePair<string, XmpValue> item)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | KeyValuePair`2 | キーと値のペア。 |

### 戻り値

このペアが見つかった場合は true。

### 参照

* クラス [XmpValue](../../../aspose.pdf/xmpvalue/)
* クラス [PdfXmpMetadata](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)