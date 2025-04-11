---
title: PdfXmpMetadata.Remove
second_title: Aspose.PDF for .NET API Reference
description: Método PdfXmpMetadata. Elimina el elemento con la clave especificada
type: docs
weight: 210
url: /es/net/aspose.pdf.facades/pdfxmpmetadata/remove/
---
## Remove(DefaultMetadataProperties) {#remove_2}

Elimina el elemento con la clave especificada.

```csharp
public void Remove(DefaultMetadataProperties key)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | DefaultMetadataProperties | Clave del elemento que será eliminado. |

## Ejemplos

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove(DefaultMetadataProperties.Nickname);
```

### Ver También

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(string) {#remove_1}

Elimina la clave del diccionario.

```csharp
public bool Remove(string key)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | String | Clave que será eliminada. |

### Valor de Retorno

True - si la clave fue eliminada; de lo contrario, false.

## Ejemplos

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Remove("xmp:Nickname");
```

### Ver También

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, XmpValue&gt;) {#remove}

Elimina el par clave/valor de la colección.

```csharp
public bool Remove(KeyValuePair<string, XmpValue> item)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | KeyValuePair`2 | Par clave/valor que será eliminado. |

### Valor de Retorno

true si el par fue encontrado y eliminado.

### Ver También

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)