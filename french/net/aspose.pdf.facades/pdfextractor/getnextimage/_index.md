---
title: "PdfExtractor.GetNextImage"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfExtractor. Récupère l'image suivante du document PDF. Note : ExtractImage doit être appelé avant l'utilisation de cette méthode"
type: docs
weight: 170
url: /fr/net/aspose.pdf.facades/pdfextractor/getnextimage/
---
## GetNextImage(string) {#getnextimage_2}

Récupère l'image suivante du document PDF. Remarque : ExtractImage doit être appelé avant d'utiliser cette méthode.

```csharp
public bool GetNextImage(string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | String | Fichier où l'image sera stockée |

### Valeur de retour

Vrai si l'image a été extraite avec succès

## Exemples

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf("sample.pdf");
extractor.ExtractImage();
int i = 1;
while (extractor.HasNextImage())
{
    extractor.GetNextImage("image-" + i +".pdf");
}
```

### Voir aussi

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_3}

Récupère l'image suivante du document PDF avec le format d'image donné. Remarque : ExtractImage doit être appelé avant d'utiliser cette méthode.

```csharp
public bool GetNextImage(string outputFile, ImageFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | String | Fichier où l'image sera stockée |
| format | ImageFormat | Le format de l'image. |

### Valeur de retour

Vrai si l'image a été extraite avec succès

### Voir aussi

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_1}

Récupère l'image suivante du fichier PDF et l'enregistre dans un flux avec le format d'image donné.

```csharp
public bool GetNextImage(Stream outputStream, ImageFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Flux où les données de l'image seront enregistrées |
| format | ImageFormat | Le format de l'image. |

### Valeur de retour

Vrai dans le cas où l'image est extraite avec succès.

### Voir aussi

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Récupère l'image suivante du fichier PDF et l'enregistre dans un flux.

```csharp
public bool GetNextImage(Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Flux où les données de l'image seront enregistrées |

### Valeur de retour

Vrai dans le cas où l'image est extraite avec succès.

### Voir aussi

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


