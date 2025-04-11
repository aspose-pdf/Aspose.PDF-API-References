---
title: PdfXmpMetadata.Add
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfXmpMetadata. Menambahkan nilai ke metadata XMP
type: docs
weight: 110
url: /id/net/aspose.pdf.facades/pdfxmpmetadata/add/
---
## Add(DefaultMetadataProperties, XmpValue) {#add}

Menambahkan nilai ke metadata XMP.

```csharp
public void Add(DefaultMetadataProperties key, XmpValue value)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key | DefaultMetadataProperties | Nama kunci. |
| value | XmpValue | Nilai yang akan ditambahkan. |

## Contoh

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add(DefaultMetadataProperties.Nickname, "name1");
xmp.Save(TestSettings.GetOutputFile("XMP_AddedValue.pdf"));
```

### Lihat Juga

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(XmpPdfAExtensionObject, string, string, string) {#add_1}

Menambahkan field ekstensi ke dalam metadata.

```csharp
public void Add(XmpPdfAExtensionObject xmpPdfAExtensionObject, string namespacePrefix, 
    string namespaceUri, string schemaDescription)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xmpPdfAExtensionObject | XmpPdfAExtensionObject | Objek ekstensi pdf yang akan ditambahkan. |
| namespacePrefix | String | Prefiks skema. |
| namespaceUri | String | URI namespace dari skema. |
| schemaDescription | String | Deskripsi opsional dari skema. |

### Lihat Juga

* class [XmpPdfAExtensionObject](../../../aspose.pdf/xmppdfaextensionobject/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, XmpValue) {#add_3}

Menambahkan elemen baru ke objek kamus.

```csharp
public void Add(string key, XmpValue value)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key | String | Kunci elemen baru. |
| value | XmpValue | Nilai dari elemen. |

## Contoh

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
```

### Lihat Juga

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, object) {#add_4}

Menambahkan elemen baru ke objek kamus.

```csharp
public void Add(string key, object value)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key | String | Kunci elemen baru. |
| value | Object | Nilai dari elemen. |

### Lihat Juga

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(KeyValuePair&lt;string, XmpValue&gt;) {#add_2}

Menambahkan pasangan dengan kunci dan nilai ke dalam kamus.

```csharp
public void Add(KeyValuePair<string, XmpValue> item)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | KeyValuePair`2 | Item yang akan ditambahkan. |

### Lihat Juga

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)