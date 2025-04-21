---
title: PdfExtractor.GetNextImage
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfExtractor. Récupère la prochaine image du document PDF. Remarque  ExtractImage doit être appelé avant d'utiliser cette méthode
type: docs
weight: 170
url: /fr/net/aspose.pdf.facades/pdfextractor/getnextimage/
---
## GetNextImage(string) {#getnextimage_2}

Récupère la prochaine image du document PDF. Remarque : ExtractImage doit être appelé avant d'utiliser cette méthode.

```csharp
public bool GetNextImage(string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | String | Fichier où l'image sera stockée |

### Valeur de retour

Vrai si l'image est extraite avec succès

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

* classe [PdfExtractor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_3}

Récupère la prochaine image du document PDF avec le format d'image donné. Remarque : ExtractImage doit être appelé avant d'utiliser cette méthode.

```csharp
public bool GetNextImage(string outputFile, ImageFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | String | Fichier où l'image sera stockée |
| format | ImageFormat | Le format de l'image. |

### Valeur de retour

Vrai si l'image est extraite avec succès

### Voir aussi

* classe [PdfExtractor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_1}

Récupère la prochaine image du fichier PDF et la stocke dans un flux avec le format d'image donné.

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

* classe [PdfExtractor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Récupère la prochaine image du fichier PDF et la stocke dans un flux.

```csharp
public bool GetNextImage(Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Flux où les données de l'image seront enregistrées |

### Valeur de retour

Vrai dans le cas où l'image est extraite avec succès.

### Voir aussi

* classe [PdfExtractor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)