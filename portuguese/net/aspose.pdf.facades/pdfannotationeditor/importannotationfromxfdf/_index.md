---
title: PdfAnnotationEditor.ImportAnnotationFromXfdf
second_title: Aspose.PDF for .NET API Reference
description: Método PdfAnnotationEditor. Importa as anotações especificadas do arquivo XFDF
type: docs
weight: 80
url: /pt/net/aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/
---
## ImportAnnotationFromXfdf(string, AnnotationType[]) {#importannotationfromxfdf_3}

Importa as anotações especificadas do arquivo XFDF.

```csharp
public void ImportAnnotationFromXfdf(string xfdfFile, AnnotationType[] annotType)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xfdfFile | String | O arquivo XFDF de entrada. |
| annotType | AnnotationType[] | O array de anotações a ser importado. |

## Exemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes = {AnnotationType.Highlight, AnnotationType.Text};
editor.ImportAnnotationFromXfdf("annots.xfdf", annotTypes);
editor.Save("example_out.pdf");
```

### Veja Também

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotationFromXfdf(Stream, AnnotationType[]) {#importannotationfromxfdf_1}

Importa as anotações especificadas do fluxo de dados XFDF.

```csharp
public void ImportAnnotationFromXfdf(Stream xfdfStream, AnnotationType[] annotType)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xfdfStream | Stream | O fluxo de dados XFDF de entrada. |
| annotType | AnnotationType[] | O array de tipos de anotações a ser importado. |

## Exemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
AnnotationType[] annotTypes ={ AnnotationType.Highlight, AnnotationType.Line };
editor.ImportAnnotationFromXfdf(File.OpenRead("annots.xfdf"), annotTypes);
editor.Save("example_out.pdf");
```

### Veja Também

* enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)