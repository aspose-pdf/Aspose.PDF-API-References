---
title: PdfXmpMetadata.Add
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata メソッド。XMP メタデータに値を追加します
type: docs
weight: 110
url: /ja/net/aspose.pdf.facades/pdfxmpmetadata/add/
---
## Add(DefaultMetadataProperties, XmpValue) {#add}

XMP メタデータに値を追加します。

```csharp
public void Add(DefaultMetadataProperties key, XmpValue value)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| key | DefaultMetadataProperties | キー名。 |
| value | XmpValue | 追加される値。 |

## 例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add(DefaultMetadataProperties.Nickname, "name1");
xmp.Save(TestSettings.GetOutputFile("XMP_AddedValue.pdf"));
```

### 参照

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

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xmpPdfAExtensionObject | XmpPdfAExtensionObject | 追加する PDF 拡張オブジェクト。 |
| namespacePrefix | String | スキーマのプレフィックス。 |
| namespaceUri | String | スキーマの名前空間 URI。 |
| schemaDescription | String | スキーマのオプションの説明。 |

### 参照

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

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| key | String | 新しい要素のキー。 |
| value | XmpValue | 要素の値。 |

## 例

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
```

### 参照

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

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| key | String | 新しい要素のキー。 |
| value | Object | 要素の値。 |

### 参照

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(KeyValuePair&lt;string, XmpValue&gt;) {#add_2}

辞書にキーと値のペアを追加します。

```csharp
public void Add(KeyValuePair<string, XmpValue> item)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | KeyValuePair`2 | 追加されるアイテム。 |

### 参照

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)