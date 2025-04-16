---
title: ParagraphAbsorber.SectionsSearchDepth
second_title: Aspose.PDF for .NET API Reference
description: Propriedade ParagraphAbsorber. Obtém ou define o valor que instrui quantas vezes as buscas sequenciais por elementos mais finos da estrutura serão realizadas. A profundidade de busca padrão é 3. Isso significa três buscas por seções divididas horizontalmente e três buscas por aquelas divididas verticalmente.
type: docs
weight: 50
url: /pt/net/aspose.pdf.text/paragraphabsorber/sectionssearchdepth/
---
## Propriedade ParagraphAbsorber.SectionsSearchDepth

Obtém ou define o valor que instrui quantas vezes as buscas sequenciais por elementos mais finos da estrutura serão realizadas. A profundidade de busca padrão é 3. Isso significa três buscas por seções divididas horizontalmente (cabeçalhos, parágrafos etc.) e três buscas por aquelas divididas verticalmente (colunas).

```csharp
public int SectionsSearchDepth { get; set; }
```

## Observações

O aumento desse valor pode levar a uma leve diminuição no desempenho sem mudanças visíveis no resultado da busca. A diminuição desse valor pode levar à determinação incorreta de parágrafos em seções. Não recomendamos definir um valor menor que o padrão se você não deseja obter apenas elementos 'brutos' da estrutura da página.

### Veja Também

* classe [ParagraphAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)