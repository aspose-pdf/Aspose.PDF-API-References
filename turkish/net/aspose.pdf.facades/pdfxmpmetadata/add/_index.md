---
title: PdfXmpMetadata.Add
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata metodu. XMP meta verisine değer ekler
type: docs
weight: 110
url: /tr/net/aspose.pdf.facades/pdfxmpmetadata/add/
---
## Ekle(DefaultMetadataProperties, XmpValue) {#add}

XMP meta verisine değer ekler.

```csharp
public void Add(DefaultMetadataProperties key, XmpValue value)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | DefaultMetadataProperties | Anahtar adı. |
| değer | XmpValue | Eklenecek değer. |

## Örnekler

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add(DefaultMetadataProperties.Nickname, "name1");
xmp.Save(TestSettings.GetOutputFile("XMP_AddedValue.pdf"));
```

### Ayrıca Bakınız

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Ekle(XmpPdfAExtensionObject, string, string, string) {#add_1}

Meta veriye uzantı alanı ekler.

```csharp
public void Add(XmpPdfAExtensionObject xmpPdfAExtensionObject, string namespacePrefix, 
    string namespaceUri, string schemaDescription)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmpPdfAExtensionObject | XmpPdfAExtensionObject | Eklenecek pdf uzantı nesnesi. |
| namespacePrefix | String | Şemanın ön eki. |
| namespaceUri | String | Şemanın ad alanı uri'si. |
| schemaDescription | String | Şemanın isteğe bağlı açıklaması. |

### Ayrıca Bakınız

* class [XmpPdfAExtensionObject](../../../aspose.pdf/xmppdfaextensionobject/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Ekle(string, XmpValue) {#add_3}

Sözlük nesnesine yeni bir öğe ekler.

```csharp
public void Add(string key, XmpValue value)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | String | Yeni öğenin anahtarı. |
| değer | XmpValue | Öğenin değeri. |

## Örnekler

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
```

### Ayrıca Bakınız

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Ekle(string, object) {#add_4}

Sözlük nesnesine yeni bir öğe ekler.

```csharp
public void Add(string key, object value)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | String | Yeni öğenin anahtarı. |
| değer | Object | Öğenin değeri. |

### Ayrıca Bakınız

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Ekle(KeyValuePair&lt;string, XmpValue&gt;) {#add_2}

Sözlüğe anahtar ve değer ile çift ekler.

```csharp
public void Add(KeyValuePair<string, XmpValue> item)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| öğe | KeyValuePair`2 | Eklenecek öğe. |

### Ayrıca Bakınız

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)