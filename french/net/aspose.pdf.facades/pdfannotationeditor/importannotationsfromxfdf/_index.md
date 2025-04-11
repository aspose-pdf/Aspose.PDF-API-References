---
title: PdfAnnotationEditor.ImportAnnotationsFromXfdf
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfAnnotationEditor. Importe toutes les annotations à partir du fichier XFDF
type: docs
weight: 110
url: /fr/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/
---
## ImportAnnotationsFromXfdf(string) {#importannotationsfromxfdf_1}

Importe toutes les annotations à partir du fichier XFDF.

```csharp
public void ImportAnnotationsFromXfdf(string xfdfFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| xfdfFile | String | Le fichier XFDF d'entrée. |

## Exemples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf("annots.xfdf");
editor.Save("example_out.pdf");
```

### Voir aussi

* classe [PdfAnnotationEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotationsFromXfdf(Stream) {#importannotationsfromxfdf}

Importe toutes les annotations à partir du flux de données XFDF.

```csharp
public void ImportAnnotationsFromXfdf(Stream xfdfStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| xfdfStream | Stream | Le flux de données XFDF d'entrée. |

## Exemples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf(File.OpenRead("annots.xfdf"));
editor.Save("example_out.pdf");
```

### Voir aussi

* classe [PdfAnnotationEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)