---
title: PdfAnnotationEditor.ImportAnnotationsFromXfdf
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfAnnotationEditor. Importa tutte le annotazioni da un file XFDF
type: docs
weight: 110
url: /it/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/
---
## ImportAnnotationsFromXfdf(string) {#importannotationsfromxfdf_1}

Importa tutte le annotazioni da un file XFDF.

```csharp
public void ImportAnnotationsFromXfdf(string xfdfFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| xfdfFile | String | Il file XFDF di input. |

## Examples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf("annots.xfdf");
editor.Save("example_out.pdf");
```

### See Also

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotationsFromXfdf(Stream) {#importannotationsfromxfdf}

Importa tutte le annotazioni da un flusso di dati XFDF.

```csharp
public void ImportAnnotationsFromXfdf(Stream xfdfStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| xfdfStream | Stream | Il flusso di dati XFDF di input. |

## Examples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf(File.OpenRead("annots.xfdf"));
editor.Save("example_out.pdf");
```

### See Also

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)