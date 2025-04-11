---
title: PdfContentEditor.CreateCustomActionLink
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Cria um link para ações personalizadas no documento PDF
type: docs
weight: 140
url: /pt/net/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/
---
## Método PdfContentEditor.CreateCustomActionLink

Cria um link para ações personalizadas no documento PDF.

```csharp
public void CreateCustomActionLink(Rectangle rect, int originalPage, Color color, Enum[] actionName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | Rectangle | O retângulo para clique ativo. |
| originalPage | Int32 | O número da página original onde o retângulo vinculado ao link será criado. |
| color | Color | A cor do retângulo para clique ativo. |
| actionName | Enum[] | O array de ações (membros do enum PredefinedAction) correspondentes à execução de itens de menu no visualizador Acrobat. |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCustomActionLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)