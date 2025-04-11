---
title: PdfAnnotationEditor.ExportAnnotationsXfdf
second_title: Aspose.PDF for .NET API Reference
description: Método PdfAnnotationEditor. Exporta o conteúdo dos tipos de anotações especificados para XFDF
type: docs
weight: 50
url: /pt/net/aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/
---
## ExportAnnotationsXfdf(Stream, int, int, string[]) {#exportannotationsxfdf_1}

Exporta o conteúdo dos tipos de anotações especificados para XFDF

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, string[] annotTypes)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xmlOutputStream | Stream | O fluxo XFDF de saída. |
| start | Int32 | Página inicial da qual as anotações do documento serão exportadas. |
| end | Int32 | Página final para a qual as anotações do documento serão exportadas. |
| annotTypes | String[] | O array de tipos de anotações que precisam ser exportados. |

## Exemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
string[] annotTypes = new string[] {"Text", "Highlight"};
using (Stream stream = File.Create("example.xfdf"))
{
    editor.ExportAnnotationsXfdf(stream, 1, 2, annotTypes);
}
```

### Veja Também

* classe [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExportAnnotationsXfdf(Stream, int, int, AnnotationType[]) {#exportannotationsxfdf}

Exporta o conteúdo dos tipos de anotações especificados para XFDF

```csharp
public void ExportAnnotationsXfdf(Stream xmlOutputStream, int start, int end, 
    AnnotationType[] annotTypes)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xmlOutputStream | Stream | O fluxo XFDF de saída. |
| start | Int32 | Página inicial da qual as anotações do documento serão exportadas. |
| end | Int32 | Página final para a qual as anotações do documento serão exportadas. |
| annotTypes | AnnotationType[] | O array de tipos de anotações que precisam ser exportados. |

## Exemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = new AnnotationType[] {AnnotationType.Text, AnnotationType.Highlight};
using (Stream stream = File.Create("example.xfdf"))
{
    editor.ExportAnnotationsXfdf(stream, 1, 2, annotTypes);
}
```

### Veja Também

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* classe [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)