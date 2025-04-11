---
title: PdfFileEditor.AddMargins
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Redimensiona o conteúdo da página e adiciona margens especificadas. As margens são especificadas em unidades de espaço padrão
type: docs
weight: 220
url: /pt/net/aspose.pdf.facades/pdffileeditor/addmargins/
---
## AddMargins(Stream, Stream, int[], double, double, double, double) {#addmargins}

Redimensiona o conteúdo da página e adiciona margens especificadas. As margens são especificadas em unidades de espaço padrão.

```csharp
public bool AddMargins(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | Stream | Stream que contém o documento de origem. |
| destination | Stream | Stream onde o documento resultante será salvo. |
| pages | Int32[] | Array de índices de página. Se nulo, todas as páginas do documento serão processadas. |
| leftMargin | Double | Margem esquerda. |
| rightMargin | Double | Margem direita. |
| topMargin | Double | Margem superior. |
| bottomMargin | Double | Margem inferior. |

### Valor de Retorno

true se a operação foi bem-sucedida.

## Exemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMargins(src, dest, 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 10 units
    10, 
    //right margin is 5 units
    5, 
    //top margin is 5 units
    5, 
    //bottom margin is 5 units
    5);
    dest.Close();
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMargins(string, string, int[], double, double, double, double) {#addmargins_1}

Redimensiona o conteúdo da página e adiciona margens especificadas. As margens são especificadas em unidades de espaço padrão.

```csharp
public bool AddMargins(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | String | Caminho para o documento de origem. |
| destination | String | Caminho onde o documento resultante será salvo. |
| pages | Int32[] | Array de índices de página. Se nulo, todas as páginas do documento serão processadas. |
| leftMargin | Double | Margem esquerda. |
| rightMargin | Double | Margem direita. |
| topMargin | Double | Margem superior. |
| bottomMargin | Double | Margem inferior. |

### Valor de Retorno

true se o redimensionamento foi bem-sucedido.

## Exemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMargins("input.pdf", "output.pdf", 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 10 units
    10, 
    //right margin is 5 units
    5, 
    //top margin is 5 units
    5, 
    //bottom margin is 5 units
    5);
```

### Veja Também

* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)