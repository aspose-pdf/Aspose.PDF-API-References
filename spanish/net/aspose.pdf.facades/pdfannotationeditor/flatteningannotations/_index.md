---
title: PdfAnnotationEditor.FlatteningAnnotations
second_title: Aspose.PDF for .NET API Reference
description: Método PdfAnnotationEditor. Aplana todas las anotaciones en el documento
type: docs
weight: 70
url: /es/net/aspose.pdf.facades/pdfannotationeditor/flatteningannotations/
---
## AplanarAnotaciones() {#flatteningannotations}

Aplana todas las anotaciones en el documento.

```csharp
public void FlatteningAnnotations()
```

## Ejemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.FlatteningAnnotations();
editor.Save(example_out.pdf");
```

### Ver También

* clase [PdfAnnotationEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## AplanarAnotaciones(FlattenSettings) {#flatteningannotations_1}

Aplana todas las anotaciones en el documento.

```csharp
public void FlatteningAnnotations(FlattenSettings flattenSettings)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flattenSettings | FlattenSettings | Especifica los modos de aplanamiento. |

### Ver También

* clase [FlattenSettings](../../../aspose.pdf.forms/form.flattensettings/)
* clase [PdfAnnotationEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## AplanarAnotaciones(int, int, AnnotationType[]) {#flatteningannotations_2}

Aplana las anotaciones de los tipos especificados.

```csharp
public void FlatteningAnnotations(int start, int end, AnnotationType[] annotType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| start | Int32 | La página de inicio. |
| end | Int32 | La página final. |
| annotType | AnnotationType[] | Los tipos de anotaciones que deben ser aplanados. |

## Ejemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={AnnotationType.Line, AnnotationType.FreeText};
editor.FlatteningAnnotations(1, 2, annotTypes);
editor.Save("example_out.pdf");
```

### Ver También

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* clase [PdfAnnotationEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)