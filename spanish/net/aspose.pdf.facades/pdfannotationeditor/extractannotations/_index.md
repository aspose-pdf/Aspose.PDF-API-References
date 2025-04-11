---
title: PdfAnnotationEditor.ExtractAnnotations
second_title: Aspose.PDF for .NET API Reference
description: Método PdfAnnotationEditor. Obtiene la lista de anotaciones de los tipos especificados
type: docs
weight: 60
url: /es/net/aspose.pdf.facades/pdfannotationeditor/extractannotations/
---
## ExtractAnnotations(int, int, string[]) {#extractannotations_1}

Obtiene la lista de anotaciones de los tipos especificados.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, string[] annotTypes)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| start | Int32 | Página de inicio desde la cual se seleccionarán las anotaciones. |
| end | Int32 | Página final hasta la cual se seleccionarán las anotaciones. |
| annotTypes | String[] | El arreglo de tipos de anotaciones necesarias. |

### Valor de Retorno

Lista de anotaciones.

## Ejemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### Véase También

* clase [Annotation](../../../aspose.pdf.annotations/annotation/)
* clase [PdfAnnotationEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## ExtractAnnotations(int, int, AnnotationType[]) {#extractannotations}

Obtiene la lista de anotaciones de los tipos especificados.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, AnnotationType[] annotTypes)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| start | Int32 | Página de inicio desde la cual se seleccionarán las anotaciones. |
| end | Int32 | Página final hasta la cual se seleccionarán las anotaciones. |
| annotTypes | AnnotationType[] | El arreglo de tipos de anotaciones necesarias. |

### Valor de Retorno

Lista de anotaciones.

## Ejemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### Véase También

* clase [Annotation](../../../aspose.pdf.annotations/annotation/)
* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* clase [PdfAnnotationEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)