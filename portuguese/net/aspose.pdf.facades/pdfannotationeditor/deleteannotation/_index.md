---
title: PdfAnnotationEditor.DeleteAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Método PdfAnnotationEditor. Exclui a anotação com o nome de anotação especificado
type: docs
weight: 20
url: /pt/net/aspose.pdf.facades/pdfannotationeditor/deleteannotation/
---
## Método PdfAnnotationEditor.DeleteAnnotation

Exclui a anotação com o nome de anotação especificado.

```csharp
public void DeleteAnnotation(string annotName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| annotName | String | O nome da anotação |

## Exemplos

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38");
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)