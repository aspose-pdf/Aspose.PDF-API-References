---
title: PdfXmpMetadata.Add
second_title: Aspose.PDF for .NET API Reference
description: Método PdfXmpMetadata. Agrega valor a los metadatos XMP
type: docs
weight: 110
url: /es/net/aspose.pdf.facades/pdfxmpmetadata/add/
---
## Add(DefaultMetadataProperties, XmpValue) {#add}

Agrega valor a los metadatos XMP.

```csharp
public void Add(DefaultMetadataProperties key, XmpValue value)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | DefaultMetadataProperties | El nombre de la clave. |
| value | XmpValue | Valor que se agregará. |

## Ejemplos

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add(DefaultMetadataProperties.Nickname, "name1");
xmp.Save(TestSettings.GetOutputFile("XMP_AddedValue.pdf"));
```

### Ver También

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(XmpPdfAExtensionObject, string, string, string) {#add_1}

Agrega campo de extensión a los metadatos.

```csharp
public void Add(XmpPdfAExtensionObject xmpPdfAExtensionObject, string namespacePrefix, 
    string namespaceUri, string schemaDescription)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmpPdfAExtensionObject | XmpPdfAExtensionObject | El objeto de extensión pdf a agregar. |
| namespacePrefix | String | El prefijo del esquema. |
| namespaceUri | String | La URI del espacio de nombres del esquema. |
| schemaDescription | String | La descripción opcional del esquema. |

### Ver También

* class [XmpPdfAExtensionObject](../../../aspose.pdf/xmppdfaextensionobject/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, XmpValue) {#add_3}

Agrega un nuevo elemento al objeto diccionario.

```csharp
public void Add(string key, XmpValue value)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | String | Clave del nuevo elemento. |
| value | XmpValue | Valor del elemento. |

## Ejemplos

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
```

### Ver También

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, object) {#add_4}

Agrega un nuevo elemento al objeto diccionario.

```csharp
public void Add(string key, object value)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | String | Clave del nuevo elemento. |
| value | Object | Valor del elemento. |

### Ver También

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(KeyValuePair&lt;string, XmpValue&gt;) {#add_2}

Agrega un par con clave y valor al diccionario.

```csharp
public void Add(KeyValuePair<string, XmpValue> item)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | KeyValuePair`2 | Elemento a agregar. |

### Ver También

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)