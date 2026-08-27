---
title: "PdfAnnotationEditor.ImportAnnotationsFromXfdf"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfAnnotationEditor. Importa tutte le annotazioni dal file XFDF"
type: docs
weight: 110
url: /it/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/
---
## ImportAnnotationsFromXfdf(string) {#importannotationsfromxfdf_1}

Importa tutte le annotazioni dal file XFDF.

```csharp
public void ImportAnnotationsFromXfdf(string xfdfFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xfdfFile | String | Il file XFDF di input. |

## Esempi

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf("annots.xfdf");
editor.Save("example_out.pdf");
```

### Vedi anche

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotationsFromXfdf(Stream) {#importannotationsfromxfdf}

Importa tutte le annotazioni dal flusso di dati XFDF.

```csharp
public void ImportAnnotationsFromXfdf(Stream xfdfStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xfdfStream | Stream | Il flusso di dati XFDF di input. |

## Esempi

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf(File.OpenRead("annots.xfdf"));
editor.Save("example_out.pdf");
```

### Vedi anche

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


