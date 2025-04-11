---
title: PdfXmpMetadata.Add
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfXmpMetadata. Aggiunge valore ai metadati XMP
type: docs
weight: 110
url: /it/net/aspose.pdf.facades/pdfxmpmetadata/add/
---
## Add(DefaultMetadataProperties, XmpValue) {#add}

Aggiunge valore ai metadati XMP.

```csharp
public void Add(DefaultMetadataProperties key, XmpValue value)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | DefaultMetadataProperties | Il nome della chiave. |
| value | XmpValue | Valore che sarà aggiunto. |

## Esempi

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add(DefaultMetadataProperties.Nickname, "name1");
xmp.Save(TestSettings.GetOutputFile("XMP_AddedValue.pdf"));
```

### Vedi Anche

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(XmpPdfAExtensionObject, string, string, string) {#add_1}

Aggiunge campo di estensione nei metadati.

```csharp
public void Add(XmpPdfAExtensionObject xmpPdfAExtensionObject, string namespacePrefix, 
    string namespaceUri, string schemaDescription)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xmpPdfAExtensionObject | XmpPdfAExtensionObject | L'oggetto di estensione pdf da aggiungere. |
| namespacePrefix | String | Il prefisso dello schema. |
| namespaceUri | String | L'uri del namespace dello schema. |
| schemaDescription | String | La descrizione opzionale dello schema. |

### Vedi Anche

* class [XmpPdfAExtensionObject](../../../aspose.pdf/xmppdfaextensionobject/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, XmpValue) {#add_3}

Aggiunge un nuovo elemento all'oggetto dizionario.

```csharp
public void Add(string key, XmpValue value)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | String | Chiave del nuovo elemento. |
| value | XmpValue | Valore dell'elemento. |

## Esempi

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
```

### Vedi Anche

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, object) {#add_4}

Aggiunge un nuovo elemento all'oggetto dizionario.

```csharp
public void Add(string key, object value)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | String | Chiave del nuovo elemento. |
| value | Object | Valore dell'elemento. |

### Vedi Anche

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(KeyValuePair&lt;string, XmpValue&gt;) {#add_2}

Aggiunge coppia con chiave e valore nel dizionario.

```csharp
public void Add(KeyValuePair<string, XmpValue> item)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | KeyValuePair`2 | Elemento da aggiungere. |

### Vedi Anche

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)