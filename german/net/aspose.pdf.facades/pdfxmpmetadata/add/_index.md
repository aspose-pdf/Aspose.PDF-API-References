---
title: PdfXmpMetadata.Add
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata-Methode. Fügt einen Wert zu den XMP-Metadaten hinzu
type: docs
weight: 110
url: /de/net/aspose.pdf.facades/pdfxmpmetadata/add/
---
## Add(DefaultMetadataProperties, XmpValue) {#add}

Fügt einen Wert zu den XMP-Metadaten hinzu.

```csharp
public void Add(DefaultMetadataProperties key, XmpValue value)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key | DefaultMetadataProperties | Der Schlüsselname. |
| value | XmpValue | Wert, der hinzugefügt wird. |

## Beispiele

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add(DefaultMetadataProperties.Nickname, "name1");
xmp.Save(TestSettings.GetOutputFile("XMP_AddedValue.pdf"));
```

### Siehe auch

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(XmpPdfAExtensionObject, string, string, string) {#add_1}

Fügt ein Erweiterungsfeld in die Metadaten ein.

```csharp
public void Add(XmpPdfAExtensionObject xmpPdfAExtensionObject, string namespacePrefix, 
    string namespaceUri, string schemaDescription)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmpPdfAExtensionObject | XmpPdfAExtensionObject | Das PDF-Erweiterungsobjekt, das hinzugefügt werden soll. |
| namespacePrefix | String | Der Präfix des Schemas. |
| namespaceUri | String | Die Namespace-URI des Schemas. |
| schemaDescription | String | Die optionale Beschreibung des Schemas. |

### Siehe auch

* class [XmpPdfAExtensionObject](../../../aspose.pdf/xmppdfaextensionobject/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, XmpValue) {#add_3}

Fügt ein neues Element zum Wörterbuchobjekt hinzu.

```csharp
public void Add(string key, XmpValue value)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key | String | Schlüssel des neuen Elements. |
| value | XmpValue | Wert des Elements. |

## Beispiele

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
```

### Siehe auch

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, object) {#add_4}

Fügt ein neues Element zum Wörterbuchobjekt hinzu.

```csharp
public void Add(string key, object value)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key | String | Schlüssel des neuen Elements. |
| value | Object | Wert des Elements. |

### Siehe auch

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(KeyValuePair&lt;string, XmpValue&gt;) {#add_2}

Fügt ein Paar mit Schlüssel und Wert in das Wörterbuch ein.

```csharp
public void Add(KeyValuePair<string, XmpValue> item)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | KeyValuePair`2 | Element, das hinzugefügt werden soll. |

### Siehe auch

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)