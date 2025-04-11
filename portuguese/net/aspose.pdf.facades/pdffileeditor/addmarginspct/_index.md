---
title: PdfFileEditor.AddMarginsPct
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Redimensiona o conteúdo da página e adiciona margens especificadas. As margens são especificadas em porcentagens do tamanho inicial da página
type: docs
weight: 230
url: /pt/net/aspose.pdf.facades/pdffileeditor/addmarginspct/
---
## AddMarginsPct(Stream, Stream, int[], double, double, double, double) {#addmarginspct}

Redimensiona o conteúdo da página e adiciona margens especificadas. As margens são especificadas em porcentagens do tamanho inicial da página.

```csharp
public bool AddMarginsPct(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | Stream | Stream que contém o documento de origem. |
| destination | Stream | Stream onde o documento resultante será salvo. |
| pages | Int32[] | Array de índices de página. Se nulo, todas as páginas do documento serão processadas. |
| leftMargin | Double | Margem esquerda em porcentagens do tamanho inicial da página. |
| rightMargin | Double | Margem direita em porcentagens do tamanho inicial da página. |
| topMargin | Double | Margem superior em porcentagens do tamanho inicial da página. |
| bottomMargin | Double | Margem inferior em porcentagens do tamanho inicial da página. |

### Valor de Retorno

true se a ação foi realizada com sucesso.

## Exemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMarginsPct(src, dest, 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 15% of page width 
    15, 
    //right margin is 10% of page width
    10, 
    //top margin is 20% of page width
    20, 
    //bottom margin is 5% of page width
    5);
    dest.Close();
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMarginsPct(string, string, int[], double, double, double, double) {#addmarginspct_1}

Redimensiona o conteúdo da página e adiciona margens especificadas. As margens são especificadas em porcentagens do tamanho inicial da página.

```csharp
public bool AddMarginsPct(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | String | Caminho para o documento de origem. |
| destination | String | Caminho onde o documento resultante será salvo. |
| pages | Int32[] | Array de índices de página. Se nulo, todas as páginas do documento serão processadas. |
| leftMargin | Double | Margem esquerda em porcentagens do tamanho inicial da página. |
| rightMargin | Double | Margem direita em porcentagens do tamanho inicial da página. |
| topMargin | Double | Margem superior em porcentagens do tamanho inicial da página. |
| bottomMargin | Double | Margem inferior em porcentagens do tamanho inicial da página. |

### Valor de Retorno

true se o redimensionamento foi bem-sucedido

## Exemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMarginsPct("input.pdf", "output.pdf", 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 15% of page width 
    15, 
    //right margin is 10% of page width
    10, 
    //top margin is 20% of page width
    20, 
    //bottom margin is 5% of page width
    5);
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)