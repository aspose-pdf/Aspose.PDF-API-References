---
title: PdfXmpMetadata.Add
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata-metod. Lägger till värde i XMP-metadata
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
| key | DefaultMetadataProperties | Nyckelnamn. |
| value | XmpValue | Värde som kommer att läggas till. |

## Exempel

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add(DefaultMetadataProperties.Nickname, "name1");
xmp.Save(TestSettings.GetOutputFile("XMP_AddedValue.pdf"));
```

### Se Även

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(XmpPdfAExtensionObject, string, string, string) {#add_1}

Lägger till utvidgningsfält i metadata.

```csharp
public void Add(XmpPdfAExtensionObject xmpPdfAExtensionObject, string namespacePrefix, 
    string namespaceUri, string schemaDescription)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmpPdfAExtensionObject | XmpPdfAExtensionObject | PDF-utvidgningsobjektet som ska läggas till. |
| namespacePrefix | String | Prefixet för schemat. |
| namespaceUri | String | Namnrymdens URI för schemat. |
| schemaDescription | String | Den valfria beskrivningen av schemat. |

### Se Även

* class [XmpPdfAExtensionObject](../../../aspose.pdf/xmppdfaextensionobject/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, XmpValue) {#add_3}

Lägger till nytt element i ordboksobjektet.

```csharp
public void Add(string key, XmpValue value)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| key | String | Nyckel för det nya elementet. |
| value | XmpValue | Värde för elementet. |

## Exempel

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
```

### Se Även

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, object) {#add_4}

Lägger till nytt element i ordboksobjektet.

```csharp
public void Add(string key, object value)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| key | String | Nyckel för det nya elementet. |
| value | Object | Värde för elementet. |

### Se Även

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(KeyValuePair&lt;string, XmpValue&gt;) {#add_2}

Lägger till par med nyckel och värde i ordboken.

```csharp
public void Add(KeyValuePair<string, XmpValue> item)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | KeyValuePair`2 | Objekt som ska läggas till. |

### Se Även

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)