---
title: "PdfXmpMetadata.Add"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfXmpMetadata. Aggiunge il valore ai metadati XMP"
type: docs
weight: 110
url: /it/net/aspose.pdf.facades/pdfxmpmetadata/add/
---
## Add(DefaultMetadataProperties, XmpValue) {#add}

Aggiunge un valore ai metadati XMP.

```csharp
public void Add(DefaultMetadataProperties key, XmpValue value)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chiave | DefaultMetadataProperties | Il nome della chiave. |
| valore | XmpValue | Valore che sarà aggiunto. |

## Esempi

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add(DefaultMetadataProperties.Nickname, "name1");
xmp.Save(TestSettings.GetOutputFile("XMP_AddedValue.pdf"));
```

### Vedi anche

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(XmpPdfAExtensionObject, string, string, string) {#add_1}

Aggiunge un campo di estensione nei metadati.

```csharp
public void Add(XmpPdfAExtensionObject xmpPdfAExtensionObject, string namespacePrefix, 
    string namespaceUri, string schemaDescription)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xmpPdfAExtensionObject | XmpPdfAExtensionObject | L'oggetto di estensione pdf da aggiungere. |
| namespacePrefix | String | Il prefisso dello schema. |
| namespaceUri | String | L'uri dello spazio dei nomi dello schema. |
| schemaDescription | String | La descrizione opzionale dello schema. |

### Vedi anche

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
| chiave | String | Chiave del nuovo elemento. |
| valore | XmpValue | Valore dell'elemento. |

## Esempi

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
```

### Vedi anche

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
| chiave | String | Chiave del nuovo elemento. |
| valore | Oggetto | Valore dell'elemento. |

### Vedi anche

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(KeyValuePair&lt;string, XmpValue&gt;) {#add_2}

Aggiunge una coppia chiave-valore nel dizionario.

```csharp
public void Add(KeyValuePair<string, XmpValue> item)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | KeyValuePair`2 | Elemento da aggiungere. |

### Vedi anche

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


