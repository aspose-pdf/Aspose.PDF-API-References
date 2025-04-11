---
title: PdfContentEditor.CreateApplicationLink
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Cria um link para iniciar um aplicativo no documento PDF
type: docs
weight: 110
url: /pt/net/aspose.pdf.facades/pdfcontenteditor/createapplicationlink/
---
## CreateApplicationLink(Rectangle, string, int, Color, Enum[]) {#createapplicationlink_2}

Cria um link para iniciar um aplicativo no documento PDF.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr, 
    Enum[] actionName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | Rectangle | O retângulo para clique ativo. |
| application | String | O caminho do aplicativo a ser iniciado. |
| page | Int32 | O número da página original onde o retângulo vinculado ao link será criado. |
| clr | Color | A cor do retângulo para clique ativo. |
| actionName | Enum[] | O array de ações (membros do enum PredefinedAction) correspondentes à execução de itens de menu no visualizador Acrobat. |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int, Color) {#createapplicationlink_1}

Cria um link para iniciar um aplicativo no documento PDF.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | Rectangle | O retângulo para clique ativo. |
| application | String | O caminho do aplicativo a ser iniciado. |
| page | Int32 | O número da página original onde o retângulo vinculado ao link será criado. |
| clr | Color | A cor do retângulo para clique ativo. |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int) {#createapplicationlink}

Cria um link para iniciar um aplicativo no documento PDF.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | Rectangle | O retângulo para clique ativo. |
| application | String | O caminho do aplicativo a ser iniciado. |
| page | Int32 | O número da página original onde o retângulo vinculado ao link será criado. |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100), "explorer", 1 });
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)