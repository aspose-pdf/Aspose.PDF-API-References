---
title: "PdfXmpMetadata.Item"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété PdfXmpMetadata. Obtient ou définit la valeur par clé"
type: docs
weight: 70
url: /fr/net/aspose.pdf.facades/pdfxmpmetadata/item/
---
## PdfXmpMetadata indexer (1 of 2)

Obtient ou définit la valeur par clé.

```csharp
public XmpValue this[string key] { get; set; }
```

| Paramètre | Description |
| --- | --- |
| clé | Le nom de la clé à obtenir/définir. |

### Valeur de retour

Objet par clé

## Exemples

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm["xmp:Nickname"]);
```

### Voir aussi

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PdfXmpMetadata indexer (2 of 2)

Obtient la valeur des métadonnées XMP par clé.

```csharp
public XmpValue this[DefaultMetadataProperties key] { get; set; }
```

| Paramètre | Description |
| --- | --- |
| clé | Clé de la valeur. |

### Valeur de retour

Valeur des métadonnées XMP.

## Exemples

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm[DefaultMetadataProperties.CreatorTool]);
```

### Voir aussi

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


