---
title: PdfFileEditor.ResizeContents
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Redimensiona o conteúdo das páginas do documento
type: docs
weight: 320
url: /pt/net/aspose.pdf.facades/pdffileeditor/resizecontents/
---
## ResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#resizecontents}

Redimensiona o conteúdo das páginas do documento.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | Stream | Stream com o documento de origem. |
| destination | Stream | Stream com o documento de destino. |
| pages | Int32[] | Array de índices de páginas. |
| parameters | ContentsResizeParameters | Parâmetros de redimensionamento. |

### Valor de Retorno

Retorna verdadeiro se for bem-sucedido.

## Exemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(src, dest, new int[] { 1, 2,.3}, parameters);
dest.Close();
```

### Veja Também

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], double, double) {#resizecontents_1}

Redimensiona o conteúdo das páginas do documento. Reduz o conteúdo da página e adiciona margens. O novo tamanho do conteúdo é especificado em unidades de espaço padrão.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | Stream | Stream que contém o documento de origem. |
| destination | Stream | Stream onde o documento resultante será salvo. |
| pages | Int32[] | Array de índices de páginas. Se nulo, todas as páginas do documento serão processadas. |
| newWidth | Double | Nova largura do conteúdo da página em unidades de espaço padrão. |
| newHeight | Double | Nova altura do conteúdo da página em unidades de espaço padrão. |

### Valor de Retorno

Verdadeiro se o redimensionamento foi bem-sucedido.

## Exemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizeContents(src, dest, 
//resize all pages of document
null, 
//new contents width = 200
200, 
//new contents height = 300
300);
// rest area of page will be empty
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], double, double) {#resizecontents_3}

Redimensiona o conteúdo das páginas do documento. Reduz o conteúdo da página e adiciona margens. O novo tamanho do conteúdo é especificado em unidades de espaço padrão.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | String | Caminho para o documento de origem. |
| destination | String | Caminho onde o documento resultante será salvo. |
| pages | Int32[] | Array de índices de páginas. Se nulo, todas as páginas do documento serão processadas. |
| newWidth | Double | Nova largura do conteúdo da página em unidades de espaço padrão. |
| newHeight | Double | Nova altura do conteúdo da página em unidades de espaço padrão. |

### Valor de Retorno

verdadeiro se o redimensionamento foi bem-sucedido.

## Exemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizeContents("input.pdf", "output.pdf", 
//resize all pages of document
null, 
//new contents width = 200
200, 
//new contents height = 300
300);
// rest area of page will be empty
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], ContentsResizeParameters) {#resizecontents_2}

Redimensiona o conteúdo das páginas no documento. Se a página for reduzida, margens em branco são adicionadas ao redor da página.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | String | Caminho do documento de origem. |
| destination | String | Caminho do documento de destino. |
| pages | Int32[] | Array de índices de páginas (o índice da página começa em 1). |
| parameters | ContentsResizeParameters | Parâmetros de redimensionamento da página. |

### Valor de Retorno

verdadeiro se o redimensionamento foi bem-sucedido.

## Exemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3 }, parameters);
```

### Veja Também

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Document, int[], ContentsResizeParameters) {#resizecontents_5}

Redimensiona as páginas do documento. Margens em branco são adicionadas ao redor da página reduzida.

```csharp
public void ResizeContents(Document source, int[] pages, ContentsResizeParameters parameters)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | Document | Documento de origem. |
| pages | Int32[] | Lista de índices de páginas. |
| parameters | ContentsResizeParameters | Parâmetros de redimensionamento. |

## Exemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, new int[] { 1, 2, 3 }, parameters);
doc.Save("output.pdf");
```

### Veja Também

* class [Document](../../../aspose.pdf/document/)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Document, ContentsResizeParameters) {#resizecontents_4}

Redimensiona as páginas do documento. Margens em branco são adicionadas ao redor da página reduzida.

```csharp
public void ResizeContents(Document source, ContentsResizeParameters parameters)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | Document | Documento de origem. |
| parameters | ContentsResizeParameters | Parâmetros de redimensionamento. |

## Exemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, parameters);
doc.Save("output.pdf");
```

### Veja Também

* class [Document](../../../aspose.pdf/document/)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)