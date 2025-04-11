---
title: PdfAnnotationEditor.ExportAnnotationsXfdf
second_title: Aspose.PDF for .NET API Reference
description: Método PdfAnnotationEditor. Exporta el contenido de los tipos de anotación especificados a XFDF
type: docs
weight: 50
url: /es/net/aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/
---
## ExportAnnotationsXfdf(Stream, int, int, string[]) {#exportannotationsxfdf_1}

Exporta el contenido de los tipos de anotación especificados a XFDF

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, string[] annotTypes)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmlOutputStream | Stream | El flujo XFDF de salida. |
| start | Int32 | Página de inicio desde la cual se exportarán las anotaciones del documento. |
| end | Int32 | Página final a la cual se exportarán las anotaciones del documento. |
| annotTypes | String[] | El arreglo de tipos de anotación que necesitan ser exportados. |

## Ejemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
using (Stream stream = File.Create("example.xfdf"))
{
    editor.ExportAnnotationsXfdf(stream, 1, 2, annotTypes);
}
```

### Ver También

* clase [PdfAnnotationEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## ExportAnnotationsXfdf(Stream, int, int, AnnotationType[]) {#exportannotationsxfdf}

Exporta el contenido de los tipos de anotaciones especificados a XFDF

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, 
    AnnotationType[] annotTypes)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmlOutputStream | Stream | El flujo XFDF de salida. |
| start | Int32 | Página de inicio desde la cual se exportarán las anotaciones del documento. |
| end | Int32 | Página final a la cual se exportarán las anotaciones del documento. |
| annotTypes | AnnotationType[] | El arreglo de tipos de anotación que necesitan ser exportados. |

## Ejemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
using (Stream stream = File.Create("example.xfdf"))
{
    editor.ExportAnnotationsXfdf(stream, 1, 2, annotTypes);
}
```

### Ver También

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* clase [PdfAnnotationEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)