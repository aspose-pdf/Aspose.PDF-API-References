---
title: Class Font
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.Font. Representa objeto de fonte
type: docs
weight: 10510
url: /pt/net/aspose.pdf.text/font/
---
## Classe Fonte

Representa objeto de fonte.

```csharp
public sealed class Font
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [BaseFont](../../aspose.pdf.text/font/basefont/) { get; } | Obtém o valor BaseFont do objeto de fonte PDF. Também conhecido como nome PostScript da fonte. |
| [DecodedFontName](../../aspose.pdf.text/font/decodedfontname/) { get; } | Às vezes, fontes PDF (geralmente fontes chinesas/japonesas/coreanas) podem ter um nome de fonte específico. Este nome é o valor da propriedade "BaseFont" da fonte PDF e, às vezes, essa propriedade pode ser representada em forma hexadecimal. Se lido diretamente, esse nome pode ser representado em uma forma não legível. Para obter uma forma legível, é necessário decodificar o nome da fonte pelas regras específicas para essa fonte. Esta propriedade retorna o nome da fonte decodificado, então use-a para casos em que você se depara com um [`FontName`](./fontname/) não legível. Se a propriedade [`FontName`](./fontname/) tiver uma forma legível, esta propriedade será a mesma que [`FontName`](./fontname/), então você pode usar esta propriedade para qualquer caso em que precise obter o nome da fonte em uma forma legível. |
| [FontName](../../aspose.pdf.text/font/fontname/) { get; } | Obtém o nome da fonte do objeto `Font`. |
| [FontOptions](../../aspose.pdf.text/font/fontoptions/) { get; } | Propriedades úteis para ajustar o comportamento da Fonte |
| [IsAccessible](../../aspose.pdf.text/font/isaccessible/) { get; } | Obtém indicando se a fonte está presente (instalada) no sistema. |
| [IsEmbedded](../../aspose.pdf.text/font/isembedded/) { get; set; } | Obtém ou define um valor que indica se a fonte está incorporada. Fontes baseadas em IFont serão automaticamente subconjuntos e incorporadas |
| [IsSubset](../../aspose.pdf.text/font/issubset/) { get; set; } | Obtém ou define um valor que indica se a fonte é um subconjunto. Fontes baseadas em IFont serão automaticamente subconjuntos e incorporadas |

## Métodos

| Nome | Descrição |
| --- | --- |
| [GetLastFontEmbeddingError](../../aspose.pdf.text/font/getlastfontembeddingerror/)() | O objetivo deste método é retornar a descrição do erro se uma tentativa de incorporar a fonte falhar. Se não houver casos de erro, retorna uma string vazia. |
| [MeasureString](../../aspose.pdf.text/font/measurestring/)(string, float) | Mede a string. |
| [Save](../../aspose.pdf.text/font/save/)(Stream) | Salva a fonte no fluxo. Observe que a fonte é salva em um formato TTF intermediário destinado a ser usado apenas em uma cópia convertida do documento original. O arquivo de fonte não é destinado a ser usado fora do contexto do documento original. |

## Exemplos

O exemplo demonstra como pesquisar texto na primeira página e alterar a fonte da primeira ocorrência da pesquisa.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Create font and mark it to be embedded
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;


// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Veja Também

* classe [TextFragmentAbsorber](../textfragmentabsorber/)
* classe [FontRepository](../fontrepository/)
* classe [Document](../../aspose.pdf/document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)