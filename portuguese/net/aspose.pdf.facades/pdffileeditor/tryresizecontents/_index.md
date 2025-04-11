---
title: PdfFileEditor.TryResizeContents
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Redimensiona o conteúdo das páginas do documento
type: docs
weight: 450
url: /pt/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents}

Redimensiona o conteúdo das páginas no documento. Se a página for reduzida, margens em branco são adicionadas ao redor da página. O resultado é armazenado no objeto HttpResponse.

```csharp
public bool TryResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | String | Caminho para o arquivo de origem. |
| pages | Int32[] | Array de páginas a serem redimensionadas. |
| parameters | ContentsResizeParameters | Parâmetros de redimensionamento. |
| response | HttpResponse | Objeto HttpResponse onde o resultado é salvo. |

### Valor de Retorno

true se a operação for concluída com sucesso; caso contrário, false.

## Observações

O método TryResizeContents é semelhante ao método ResizeContents, exceto que o método TryResizeContents não lança uma exceção se a operação falhar.

### Veja Também

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents}

Redimensiona o conteúdo das páginas no documento. Se a página for reduzida, margens em branco são adicionadas ao redor da página. O resultado é armazenado no objeto HttpResponse.

```csharp
public bool TryResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | Stream | Stream do arquivo de origem. |
| pages | Int32[] | Array de páginas a serem redimensionadas. |
| parameters | ContentsResizeParameters | Parâmetros de redimensionamento. |
| response | HttpResponse | Objeto HttpResponse onde o resultado é salvo. |

### Valor de Retorno

true se a operação for concluída com sucesso; caso contrário, false.

## Observações

O método TryResizeContents é semelhante ao método ResizeContents, exceto que o método TryResizeContents não lança uma exceção se a operação falhar.

### Veja Também

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents_1}

Redimensiona o conteúdo das páginas do documento.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | Stream | Stream com o documento de origem. |
| destination | Stream | Stream com o documento de destino. |
| pages | Int32[] | Array de índices de páginas. |
| parameters | ContentsResizeParameters | Parâmetros de redimensionamento. |

### Valor de Retorno

Retorna true se for bem-sucedido.

## Observações

O método TryResizeContents é semelhante ao método ResizeContents, exceto que o método TryResizeContents não lança uma exceção se a operação falhar.

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
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### Veja Também

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], double, double) {#tryresizecontents_1}

Redimensiona o conteúdo das páginas do documento. Reduz o conteúdo da página e adiciona margens. O novo tamanho do conteúdo é especificado em unidades de espaço padrão.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
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

true se a operação for concluída com sucesso; caso contrário, false.

## Observações

O método TryResizeContents é semelhante ao método ResizeContents, exceto que o método TryResizeContents não lança uma exceção se a operação falhar.

## Exemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
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

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_2}

Redimensiona o conteúdo das páginas no documento. Se a página for reduzida, margens em branco são adicionadas ao redor da página.

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | String | Caminho do documento de origem. |
| destination | String | Caminho do documento de destino. |
| pages | Int32[] | Array de índices de páginas (o índice da página começa em 1). |
| parameters | ContentsResizeParameters | Parâmetros de redimensionamento da página. |

### Valor de Retorno

true se o redimensionamento foi bem-sucedido.

## Observações

O método TryResizeContents é semelhante ao método ResizeContents, exceto que o método TryResizeContents não lança uma exceção se a operação falhar.

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
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### Veja Também

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)