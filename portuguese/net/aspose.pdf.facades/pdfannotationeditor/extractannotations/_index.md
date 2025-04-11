---
title: PdfAnnotationEditor.ExtractAnnotations
second_title: Aspose.PDF for .NET API Reference
description: Método PdfAnnotationEditor. Obtém a lista de anotações dos tipos especificados
type: docs
weight: 60
url: /pt/net/aspose.pdf.facades/pdfannotationeditor/extractannotations/
---
## ExtractAnnotations(int, int, string[]) {#extractannotations_1}

Obtém a lista de anotações dos tipos especificados.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, string[] annotTypes)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| start | Int32 | Página inicial a partir da qual as anotações serão selecionadas. |
| end | Int32 | Página final para a qual as anotações serão selecionadas. |
| annotTypes | String[] | O array dos tipos de anotações necessários. |

### Valor de Retorno

Lista de anotações.

## Exemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### Veja Também

* classe [Annotation](../../../aspose.pdf.annotations/annotation/)
* classe [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractAnnotations(int, int, AnnotationType[]) {#extractannotations}

Obtém a lista de anotações dos tipos especificados.

```csharp
public IList<Annotation> ExtractAnnotations(int start, int end, AnnotationType[] annotTypes)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| start | Int32 | Página inicial a partir da qual as anotações serão selecionadas. |
| end | Int32 | Página final para a qual as anotações serão selecionadas. |
| annotTypes | AnnotationType[] | O array dos tipos de anotações necessários. |

### Valor de Retorno

Lista de anotações.

## Exemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
IList annotList = editor.ExtractAnnotations(1, 2 , annotTypes);
```

### Veja Também

* classe [Annotation](../../../aspose.pdf.annotations/annotation/)
* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* classe [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)