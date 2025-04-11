---
title: PdfFileEditor.ResizeContentsPct
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Redimensiona o conteúdo das páginas do documento. Reduz o conteúdo da página e adiciona margens. O novo tamanho do conteúdo é especificado em porcentagens
type: docs
weight: 330
url: /pt/net/aspose.pdf.facades/pdffileeditor/resizecontentspct/
---
## ResizeContentsPct(Stream, Stream, int[], double, double) {#resizecontentspct}

Redimensiona o conteúdo das páginas do documento. Reduz o conteúdo da página e adiciona margens. O novo tamanho do conteúdo é especificado em porcentagens.

```csharp
public bool ResizeContentsPct(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | Stream | Stream que contém o documento de origem. |
| destination | Stream | Stream onde o documento resultante será salvo. |
| pages | Int32[] | Array de índices de páginas. Se nulo, todas as páginas do documento serão processadas. |
| newWidth | Double | Nova largura do conteúdo da página em porcentagens. |
| newHeight | Double | Nova altura do conteúdo da página em porcentagens. |

### Valor de Retorno

true se redimensionado com sucesso.

## Exemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizePct(src, dest, 
//resize all pages of document
null, 
//new contents width = 60% of initial size
60, 
//new contents height = 60% of initial size
60);
// Rest area of page will be empty (page margins).  Size of left and right margins is (100% - 60%) / 2 = 20%
// The same for top and bottom margins.
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContentsPct(string, string, int[], double, double) {#resizecontentspct_1}

Redimensiona o conteúdo das páginas do documento. Reduz o conteúdo da página e adiciona margens. O novo tamanho do conteúdo é especificado em porcentagens.

```csharp
public bool ResizeContentsPct(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | String | Caminho para o documento de origem. |
| destination | String | Caminho onde o documento resultante será salvo. |
| pages | Int32[] | Array de índices de páginas. Se nulo, todas as páginas do documento serão processadas. |
| newWidth | Double | Nova largura do conteúdo da página em porcentagens. |
| newHeight | Double | Nova altura do conteúdo da página em porcentagens. |

### Valor de Retorno

true se o redimensionamento foi bem-sucedido.

## Exemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizePct("input.pdf", "output.pdf",
//resize all pages of document
null, 
//new contents width = 60% of initial size
60, 
//new contents height = 60% of initial size
60);
// Rest area of page will be empty (page margins).  Size of left and right margins is (100% - 60%) / 2 = 20%
// The same for top and bottom margins.
```

### Veja Também

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)