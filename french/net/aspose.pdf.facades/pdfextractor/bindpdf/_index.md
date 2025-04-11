---
title: PdfExtractor.BindPdf
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfExtractor. Lier le fichier PDF d'entrée
type: docs
weight: 100
url: /fr/net/aspose.pdf.facades/pdfextractor/bindpdf/
---
## BindPdf(string) {#bindpdf_2}

Lier le fichier PDF d'entrée.

```csharp
public override void BindPdf(string inputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Fichier PDF à lier |

## Exemples

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindPdf("sample.pdf");
```

### Voir aussi

* classe [PdfExtractor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream) {#bindpdf_1}

Lie le document PDF à partir du flux.

```csharp
public override void BindPdf(Stream inputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux contenant les données du document PDF |

## Exemples

```csharp
PdfExtractor ext = new PdfExtractor();
Stream stream = new FileStream("sample.pdf", FileMode.Open, FileAccess.Read);
ext.BindPdf(stream);
```

### Voir aussi

* classe [PdfExtractor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)