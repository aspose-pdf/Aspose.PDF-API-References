---
title: SvgExtractor.Extract
second_title: Aspose.PDF for .NET API Reference
description: Método SvgExtractor. Extrai imagem svg para string a partir de elementos gráficos representados por absorvedor com um filtro de predicado
type: docs
weight: 20
url: /pt/net/aspose.pdf.vector/svgextractor/extract/
---
## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page) {#extract_1}

Extrai imagem svg para string a partir de elementos gráficos representados por !:absorvedor com um filtro de predicado.

```csharp
public string Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| absorber | GraphicsAbsorber | O objeto GraphicsAbsorber que contém os elementos gráficos. |
| filter | Predicate`1 | Uma função de predicado usada para filtrar os elementos gráficos. |
| page | Page | A página onde o absorvedor obtém elementos gráficos. |

### Valor de Retorno

A string com o conteúdo SVG.

### Exceções

| exceção | condição |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Se ocorreu um erro ao converter para SVG. |

### Veja Também

* classe [GraphicsAbsorber](../../graphicsabsorber/)
* classe [GraphicElement](../../graphicelement/)
* classe [Page](../../../aspose.pdf/page/)
* classe [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page, string) {#extract_4}

Extrai imagem svg para arquivo a partir de elementos gráficos representados por !:absorvedor com um filtro de predicado.

```csharp
public void Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page, 
    string svgFilePath)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| absorber | GraphicsAbsorber | O objeto GraphicsAbsorber que contém os elementos gráficos. |
| filter | Predicate`1 | Uma função de predicado usada para filtrar os elementos gráficos. |
| page | Page | A página onde o absorvedor obtém elementos gráficos. |
| svgFilePath | String | O caminho do arquivo SVG de destino. |

### Exceções

| exceção | condição |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Se ocorreu um erro ao converter para SVG. |

### Veja Também

* classe [GraphicsAbsorber](../../graphicsabsorber/)
* classe [GraphicElement](../../graphicelement/)
* classe [Page](../../../aspose.pdf/page/)
* classe [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page) {#extract_2}

Extrai elementos gráficos em uma string SVG. Opções ignoradas - agrupamento, extraindo de retângulo

```csharp
public string Extract(IEnumerable<GraphicElement> elements, Page page)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| elements | IEnumerable`1 | Os elementos gráficos a serem convertidos. |
| page | Page | A página onde o absorvedor obtém elementos gráficos. |

### Valor de Retorno

A string com o conteúdo SVG.

### Exceções

| exceção | condição |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Se ocorreu um erro ao converter para SVG. |

### Veja Também

* classe [GraphicElement](../../graphicelement/)
* classe [Page](../../../aspose.pdf/page/)
* classe [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page, string) {#extract_5}

Extrai elementos gráficos em um único arquivo SVG. Opções ignoradas - agrupamento, extraindo de retângulo

```csharp
public void Extract(IEnumerable<GraphicElement> elements, Page page, string svgFilePath)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| elements | IEnumerable`1 | Os elementos gráficos a serem convertidos. |
| page | Page | A página onde o absorvedor obtém elementos gráficos. |
| svgFilePath | String | O caminho do arquivo SVG de destino. |

### Exceções

| exceção | condição |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Se ocorreu um erro ao converter para SVG. |

### Veja Também

* classe [GraphicElement](../../graphicelement/)
* classe [Page](../../../aspose.pdf/page/)
* classe [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page) {#extract}

Extrai imagens Svg de uma página para strings.

```csharp
public List<string> Extract(Page page)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| page | Page | A página a ser extraída. |

### Valor de Retorno

A lista de strings de conteúdo SVG.

### Exceções

| exceção | condição |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Se ocorreu um erro ao converter para SVG. |

### Veja Também

* classe [Page](../../../aspose.pdf/page/)
* classe [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page, string) {#extract_3}

Extrai imagens Svg de uma página para arquivos.

```csharp
public void Extract(Page page, string directory)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| page | Page | A página a ser extraída. |
| directory | String | O diretório de destino para colocar as imagens SVG. |

### Exceções

| exceção | condição |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Se ocorreu um erro ao converter para SVG. |

### Veja Também

* classe [Page](../../../aspose.pdf/page/)
* classe [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)