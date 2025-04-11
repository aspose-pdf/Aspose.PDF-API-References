---
title: PdfXmpMetadata.Item
second_title: Aspose.PDF for .NET API Reference
description: Propiedad PdfXmpMetadata. Obtiene o establece el valor por clave
type: docs
weight: 70
url: /es/net/aspose.pdf.facades/pdfxmpmetadata/item/
---
## Indexador PdfXmpMetadata (1 de 2)

Obtiene o establece el valor por clave.

```csharp
public XmpValue this[string key] { get; set; }
```

| Parámetro | Descripción |
| --- | --- |
| key | El nombre de la clave para obtener/establecer. |

### Valor de Retorno

Objeto por clave

## Ejemplos

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm["xmp:Nickname"]);
```

### Ver También

* clase [XmpValue](../../../aspose.pdf/xmpvalue/)
* clase [PdfXmpMetadata](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## Indexador PdfXmpMetadata (2 de 2)

Obtiene el valor de los metadatos XMP por clave.

```csharp
public XmpValue this[DefaultMetadataProperties key] { get; set; }
```

| Parámetro | Descripción |
| --- | --- |
| key | Clave del valor. |

### Valor de Retorno

Valor de los metadatos XMP.

## Ejemplos

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm[DefaultMetadataProperties.CreatorTool]);
```

### Ver También

* clase [XmpValue](../../../aspose.pdf/xmpvalue/)
* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* clase [PdfXmpMetadata](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)