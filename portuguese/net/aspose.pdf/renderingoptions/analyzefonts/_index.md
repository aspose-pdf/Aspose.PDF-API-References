---
title: RenderingOptions.AnalyzeFonts
second_title: Aspose.PDF for .NET API Reference
description: Propriedade RenderingOptions. Substitui fontes conforme necessário para garantir que todos os caracteres no texto possam ser exibidos. O algoritmo de substituição de fontes segue estas etapas: 1. Se o usuário definir explicitamente a propriedade DefaultFontName, verifique se a fonte especificada pode exibir os caracteres desejados. 2. Se nenhuma fonte definida pelo usuário estiver configurada, pesquise entre as fontes adicionadas via FontRepository.Sources. 3. Analise o texto para identificar seu alfabeto ou escrita e sugira nomes de fontes de acordo. Tente localizar e usar essas fontes do sistema. 4. Como uma alternativa, pesquise no sistema qualquer fonte capaz de exibir os caracteres necessários.
type: docs
weight: 20
url: /pt/net/aspose.pdf/renderingoptions/analyzefonts/
---
## Propriedade RenderingOptions.AnalyzeFonts

Substitui fontes conforme necessário para garantir que todos os caracteres no texto possam ser exibidos. O algoritmo de substituição de fontes segue estas etapas: 1. Se o usuário definir explicitamente a propriedade DefaultFontName, verifique se a fonte especificada pode exibir os caracteres desejados. 2. Se nenhuma fonte definida pelo usuário estiver configurada, pesquise entre as fontes adicionadas via !:FontRepository.Sources. 3. Analise o texto para identificar seu alfabeto ou escrita e sugira nomes de fontes de acordo. Tente localizar e usar essas fontes do sistema. 4. Como uma alternativa, pesquise no sistema qualquer fonte capaz de exibir os caracteres necessários.

```csharp
public bool AnalyzeFonts { get; set; }
```

### Veja Também

* classe [RenderingOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)