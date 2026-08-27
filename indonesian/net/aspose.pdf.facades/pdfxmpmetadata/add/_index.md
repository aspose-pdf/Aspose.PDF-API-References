---
title: "PdfXmpMetadata.Add"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfXmpMetadata. Menambahkan nilai ke metadata XMP"
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
| kunci | DefaultMetadataProperties | Nama kunci. |
| nilai | XmpValue | Nilai yang akan ditambahkan. |

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

Menambahkan bidang ekstensi ke dalam metadata.

```csharp
public void Add(XmpPdfAExtensionObject xmpPdfAExtensionObject, string namespacePrefix, 
    string namespaceUri, string schemaDescription)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xmpPdfAExtensionObject | XmpPdfAExtensionObject | Objek ekstensi pdf yang akan ditambahkan. |
| namespacePrefix | String | Awalan skema. |
| namespaceUri | String | URI namespace skema. |
| schemaDescription | String | Deskripsi opsional skema. |

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
| kunci | String | Kunci elemen baru. |
| nilai | XmpValue | Nilai elemen. |

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
| kunci | String | Kunci elemen baru. |
| nilai | Object | Nilai elemen. |

### Lihat Juga

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(KeyValuePair&lt;string, XmpValue&gt;) {#add_2}

Menambahkan pasangan kunci dan nilai ke dalam kamus.

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


