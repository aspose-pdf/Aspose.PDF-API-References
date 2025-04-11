---
title: PdfXmpMetadata.Item
second_title: Aspose.PDF for .NET API Reference
description: Propriété PdfXmpMetadata. Obtient ou définit la valeur par clé
type: docs
weight: 70
url: /fr/net/aspose.pdf.facades/pdfxmpmetadata/item/
---
## Indexeur PdfXmpMetadata (1 sur 2)

Obtient ou définit la valeur par clé.

```csharp
public XmpValue this[string key] { get; set; }
```

| Paramètre | Description |
| --- | --- |
| key | Le nom de la clé à obtenir/définir. |

### Valeur de retour

Objet par clé

## Exemples

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm["xmp:Nickname"]);
```

### Voir aussi

* classe [XmpValue](../../../aspose.pdf/xmpvalue/)
* classe [PdfXmpMetadata](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Indexeur PdfXmpMetadata (2 sur 2)

Obtient la valeur des métadonnées XMP par clé.

```csharp
public XmpValue this[DefaultMetadataProperties key] { get; set; }
```

| Paramètre | Description |
| --- | --- |
| key | Clé de la valeur. |

### Valeur de retour

Valeur des métadonnées XMP.

## Exemples

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm[DefaultMetadataProperties.CreatorTool]);
```

### Voir aussi

* classe [XmpValue](../../../aspose.pdf/xmpvalue/)
* énum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* classe [PdfXmpMetadata](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)