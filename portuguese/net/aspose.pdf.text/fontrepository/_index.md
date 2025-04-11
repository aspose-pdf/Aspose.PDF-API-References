---
title: Class FontRepository
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.FontRepository. Realiza busca de fontes. Pesquisa em fontes instaladas no sistema e fontes padrão do Pdf. Também fornece funcionalidade para abrir fontes personalizadas.
type: docs
weight: 10540
url: /pt/net/aspose.pdf.text/fontrepository/
---
## Classe FontRepository

Realiza busca de fontes. Pesquisa em fontes instaladas no sistema e fontes padrão do Pdf. Também fornece funcionalidade para abrir fontes personalizadas.

```csharp
public sealed class FontRepository
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [FontRepository](fontrepository/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| static [Sources](../../aspose.pdf.text/fontrepository/sources/) { get; } | Obtém a coleção de fontes. |
| static [Substitutions](../../aspose.pdf.text/fontrepository/substitutions/) { get; } | Obtém a coleção de estratégias de substituição de fontes. |

## Métodos

| Nome | Descrição |
| --- | --- |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont)(string) | Pesquisa e retorna a fonte com o nome de fonte especificado. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_3)(string, bool) | Pesquisa e retorna a fonte com o nome de fonte especificado ignorando ou respeitando a sensibilidade a maiúsculas e minúsculas. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_1)(string, FontStyles) | Pesquisa e retorna a fonte com o nome de fonte e estilo de fonte especificados. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_2)(string, FontStyles, bool) | Pesquisa e retorna a fonte com o nome de fonte e estilo de fonte especificados ignorando ou respeitando a sensibilidade a maiúsculas e minúsculas. |
| static [LoadFonts](../../aspose.pdf.text/fontrepository/loadfonts/)() | Carrega fontes instaladas no sistema e fontes padrão do Pdf. Este método foi projetado para acelerar o processo de carregamento de fontes. Por padrão, as fontes são carregadas na primeira solicitação para qualquer fonte. O uso deste método carrega fontes do sistema e fontes padrão do Pdf imediatamente antes que qualquer documento Pdf seja aberto. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_1)(string) | Abre a fonte com o caminho do arquivo de fonte especificado. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont)(Stream, FontTypes) | Abre a fonte com o fluxo de fonte especificado. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_2)(string, string) | Abre a fonte com o caminho do arquivo de fonte especificado e o caminho do arquivo de métricas. |
| static [ReloadFonts](../../aspose.pdf.text/fontrepository/reloadfonts/)() | Recarrega todas as fontes especificadas pela propriedade [`Sources`](./sources/) |

## Exemplos

O exemplo demonstra como encontrar uma fonte e substituir a fonte do texto da primeira página.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Veja Também

* classe [TextFragmentAbsorber](../textfragmentabsorber/)
* classe [Document](../../aspose.pdf/document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)