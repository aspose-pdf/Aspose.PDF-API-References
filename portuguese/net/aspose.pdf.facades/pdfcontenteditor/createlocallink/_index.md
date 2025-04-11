---
title: PdfContentEditor.CreateLocalLink
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Cria um link local no documento PDF
type: docs
weight: 190
url: /pt/net/aspose.pdf.facades/pdfcontenteditor/createlocallink/
---
## CreateLocalLink(Rectangle, int, int, Color, Enum[]) {#createlocallink_2}

Cria um link local no documento PDF.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage, Color clr, 
    Enum[] actionName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | Rectangle | O retângulo para clique ativo. |
| desPage | Int32 | A página de destino. |
| originalPage | Int32 | O número da página original onde o retângulo vinculado ao link local será criado. |
| clr | Color | A cor do retângulo para clique ativo. |
| actionName | Enum[] | O array de ações (membros do enum PredefinedAction) correspondentes à execução de itens de menu no visualizador Acrobat. |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    2, 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateLocalLink(Rectangle, int, int, Color) {#createlocallink_1}

Cria um link local no documento PDF.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage, Color clr)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | Rectangle | O retângulo para clique ativo. |
| desPage | Int32 | A página de destino. |
| originalPage | Int32 | O número da página original onde o retângulo vinculado ao link local será criado. |
| clr | Color | A cor do retângulo para clique ativo. |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    2, 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateLocalLink(Rectangle, int, int) {#createlocallink}

Cria um link local no documento PDF.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | Rectangle | O retângulo para clique ativo. |
| desPage | Int32 | A página de destino. |
| originalPage | Int32 | O número da página original onde o retângulo vinculado ao link local será criado. |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100), 2, 1});
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)