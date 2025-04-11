---
title: PdfAnnotationEditor.ModifyAnnotations
second_title: Aspose.PDF for .NET API Reference
description: Método PdfAnnotationEditor. Modifica as anotações do tipo especificado no intervalo de páginas especificado. Suporta a modificação das seguintes propriedades da anotação: Modificado, Título, Conteúdos, Cor, Assunto e Aberto.
type: docs
weight: 120
url: /pt/net/aspose.pdf.facades/pdfannotationeditor/modifyannotations/
---
## Método PdfAnnotationEditor.ModifyAnnotations

Modifica as anotações do tipo especificado no intervalo de páginas especificado. Suporta a modificação das seguintes propriedades da anotação: Modificado, Título, Conteúdos, Cor, Assunto e Aberto.

```csharp
public void ModifyAnnotations(int start, int end, Annotation annotation)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| start | Int32 | O número da página inicial. |
| end | Int32 | O número da página final. |
| annotation | Annotation | O objeto de anotação contém novas propriedades. |

## Exemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
TextAnnotation annot = new TextAnnotation();
annot.Modified = DateTime.Now;
annot.Title = "NEW AUTHOR";
annot.Contents = "NEW CONTENTS";
annot.Color = Color.Red;
annot.Subject = "NEW SUBJECT";
annot.Open = true;
editor.ModifyAnnotations(1, 2, annot);
editor.Save("example_out.pdf");
```

### Veja Também

* classe [Annotation](../../../aspose.pdf.annotations/annotation/)
* classe [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)