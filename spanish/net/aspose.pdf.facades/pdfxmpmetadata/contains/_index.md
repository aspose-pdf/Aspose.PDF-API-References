---
title: PdfXmpMetadata.Contains
second_title: Aspose.PDF for .NET API Reference
description: Método PdfXmpMetadata. Verifica si el diccionario contiene la clave especificada
type: docs
weight: 130
url: /es/net/aspose.pdf.facades/pdfxmpmetadata/contains/
---
## Contains(string) {#contains_2}

Verifica si el diccionario contiene la clave especificada.

```csharp
public bool Contains(string key)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | String | Clave que será verificada. |

### Valor de Retorno

True - si el diccionario contiene la clave especificada; de lo contrario, false.

## Ejemplos

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
if (!xmp.Contains("xmp:Nickname"))
  Console.WriteLine("Key does not exists");
```

### Ver También

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(DefaultMetadataProperties) {#contains}

Verifica si el diccionario contiene la propiedad especificada.

```csharp
public bool Contains(DefaultMetadataProperties property)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| property | DefaultMetadataProperties | Propiedad que será verificada. |

### Valor de Retorno

True - si el diccionario contiene la propiedad especificada; de lo contrario, false.

### Ver También

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Contains(KeyValuePair&lt;string, XmpValue&gt;) {#contains_1}

Verifica si el par clave-valor especificado está contenido en el diccionario.

```csharp
public bool Contains(KeyValuePair<string, XmpValue> item)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | KeyValuePair`2 | Par clave-valor. |

### Valor de Retorno

true si este par fue encontrado.

### Ver También

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)