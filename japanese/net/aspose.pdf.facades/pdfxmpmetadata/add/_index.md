---
title: "PdfXmpMetadata.Add"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfXmpMetadata メソッド。XMP メタデータに値を追加します。"
type: docs
weight: 110
url: /ja/net/aspose.pdf.facades/pdfxmpmetadata/add/
---
## Add(DefaultMetadataProperties, XmpValue) {#add}

XMP メタデータに値を追加します。

```csharp
public void Add(DefaultMetadataProperties key, XmpValue value)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| キー | DefaultMetadataProperties | キー名。 |
| 値 | XmpValue | 追加される値。 |

## 例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add(DefaultMetadataProperties.Nickname, "name1");
xmp.Save(TestSettings.GetOutputFile("XMP_AddedValue.pdf"));
```

### 関連項目

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(XmpPdfAExtensionObject, string, string, string) {#add_1}

メタデータに拡張フィールドを追加します。

```csharp
public void Add(XmpPdfAExtensionObject xmpPdfAExtensionObject, string namespacePrefix, 
    string namespaceUri, string schemaDescription)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| xmpPdfAExtensionObject | XmpPdfAExtensionObject | 追加する pdf 拡張オブジェクト。 |
| namespacePrefix | String | スキーマのプレフィックス。 |
| namespaceUri | String | スキーマの名前空間 uriです。 |
| schemaDescription | String | スキーマのオプションの説明です。 |

### 関連項目

* class [XmpPdfAExtensionObject](../../../aspose.pdf/xmppdfaextensionobject/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, XmpValue) {#add_3}

辞書オブジェクトに新しい要素を追加します。

```csharp
public void Add(string key, XmpValue value)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| キー | String | 新しい要素のキーです。 |
| 値 | XmpValue | 要素の値です。 |

## 例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
```

### 関連項目

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, object) {#add_4}

辞書オブジェクトに新しい要素を追加します。

```csharp
public void Add(string key, object value)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| キー | String | 新しい要素のキーです。 |
| 値 | Object | 要素の値です。 |

### 関連項目

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(KeyValuePair&lt;string, XmpValue&gt;) {#add_2}

辞書にキーと値のペアを追加します。

```csharp
public void Add(KeyValuePair<string, XmpValue> item)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| アイテム | KeyValuePair`2 | 追加する項目です。 |

### 関連項目

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


