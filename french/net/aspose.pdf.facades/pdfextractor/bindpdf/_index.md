---
title: "PdfExtractor.BindPdf"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfExtractor. Lier le fichier PDF d'entrée"
type: docs
weight: 100
url: /fr/net/aspose.pdf.facades/pdfextractor/bindpdf/
---
## BindPdf(string) {#bindpdf_2}

Lie le fichier PDF d'entrée.

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

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream) {#bindpdf_1}

Lie le document PDF depuis le flux.

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

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


