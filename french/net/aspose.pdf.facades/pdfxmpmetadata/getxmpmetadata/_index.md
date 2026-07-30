---
title: "PdfXmpMetadata.GetXmpMetadata"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfXmpMetadata. Obtient le XmpMetadata du PDF d'entrée au format XML"
type: docs
weight: 190
url: /fr/net/aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/
---
## GetXmpMetadata() {#getxmpmetadata}

Obtient le XmpMetadata du pdf d'entrée au format XML.

```csharp
public byte[] GetXmpMetadata()
```

### Valeur de retour

Les octets du XmpMetadata.

## Exemples

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata();
```

### Voir aussi

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetXmpMetadata(string) {#getxmpmetadata_1}

Obtient une partie du XmpMetadata du pdf d'entrée selon un nom de métadonnée.

```csharp
public byte[] GetXmpMetadata(string name)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nom | String | Nom des métadonnées. |

### Valeur de retour

Octets des métadonnées.

## Exemples

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata("dc:creator");
```

### Voir aussi

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


