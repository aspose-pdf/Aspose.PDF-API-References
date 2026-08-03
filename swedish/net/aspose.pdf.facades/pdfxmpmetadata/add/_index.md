---
title: "PdfXmpMetadata.Add"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfXmpMetadata metod. Lägger till värde i XMP-metadata"
type: docs
weight: 110
url: /sv/net/aspose.pdf.facades/pdfxmpmetadata/add/
---
## Add(DefaultMetadataProperties, XmpValue) {#add}

Lägger till värde i XMP-metadata.

```csharp
public void Add(DefaultMetadataProperties key, XmpValue value)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | DefaultMetadataProperties | Nyckelnamnet. |
| värde | XmpValue | Värdet som kommer att läggas till. |

## Exempel

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add(DefaultMetadataProperties.Nickname, "name1");
xmp.Save(TestSettings.GetOutputFile("XMP_AddedValue.pdf"));
```

### Se även

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(XmpPdfAExtensionObject, string, string, string) {#add_1}

Lägger till ett extensionsfält i metadata.

```csharp
public void Add(XmpPdfAExtensionObject xmpPdfAExtensionObject, string namespacePrefix, 
    string namespaceUri, string schemaDescription)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmpPdfAExtensionObject | XmpPdfAExtensionObject | PDF-utökningobjektet att lägga till. |
| namespacePrefix | String | Prefixet för schemat. |
| namespaceUri | String | Namnrymds-URI för schemat. |
| schemaDescription | String | Den valfria beskrivningen av schemat. |

### Se även

* class [XmpPdfAExtensionObject](../../../aspose.pdf/xmppdfaextensionobject/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, XmpValue) {#add_3}

Lägger till ett nytt element i dictionary-objektet.

```csharp
public void Add(string key, XmpValue value)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | String | Nyckeln för nytt element. |
| värde | XmpValue | Värdet för elementet. |

## Exempel

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
```

### Se även

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, object) {#add_4}

Lägger till ett nytt element i dictionary-objektet.

```csharp
public void Add(string key, object value)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | String | Nyckeln för nytt element. |
| värde | Objekt | Värdet för elementet. |

### Se även

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(KeyValuePair&lt;string, XmpValue&gt;) {#add_2}

Lägger till ett par med nyckel och värde i ordboken.

```csharp
public void Add(KeyValuePair<string, XmpValue> item)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | KeyValuePair`2 | Objekt att läggas till. |

### Se även

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


