---
title: Item
second_title: Referencia de API de Aspose.PDF para .NET
description: Obtiene o establece valor por clave.
type: docs
weight: 70
url: /es/net/aspose.pdf.facades/pdfxmpmetadata/item/
---
## PdfXmpMetadata indexer (1 of 2)

Obtiene o establece valor por clave.

```csharp
public XmpValue this[string key] { get; set; }
```

| Parámetro | Descripción |
| --- | --- |
| key | El nombre de la clave para obtener/establecer. |

### Valor_devuelto

Objeto por clave

### Ejemplos

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm["xmp:Nickname"]);
```

### Ver también

* class [XmpValue](../../../aspose.pdf/xmpvalue)
* class [PdfXmpMetadata](../../pdfxmpmetadata)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfxmpmetadata)
* asamblea [Aspose.PDF](../../../)

---

## PdfXmpMetadata indexer (2 of 2)

Obtiene el valor de los metadatos XMP por clave.

```csharp
public XmpValue this[DefaultMetadataProperties key] { get; set; }
```

| Parámetro | Descripción |
| --- | --- |
| key | Clave del valor. |

### Valor_devuelto

Valor de metadatos XMP.

### Ejemplos

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm[DefaultMetadataProperties.CreatorTool]);
```

### Ver también

* class [XmpValue](../../../aspose.pdf/xmpvalue)
* enum [DefaultMetadataProperties](../../defaultmetadataproperties)
* class [PdfXmpMetadata](../../pdfxmpmetadata)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfxmpmetadata)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->