---
title: HtmlSaveOptions.SplitCssIntoPages
second_title: Aspose.PDF for .NET API Reference
description: Propriedade HtmlSaveOptions. Quando o modo multipágina é selecionado, ou seja, SplitIntoPages é verdadeiro, então este atributo define se deve ser criado um arquivo CSS separado para cada página HTML resultante. Por padrão, este atributo é falso, então será criado um grande CSS comum para todas as páginas criadas. O tamanho total de todos os CSS gerados neste modo geralmente é muito maior do que o tamanho de um grande arquivo CSS, porque no primeiro caso as classes CSS são duplicadas em vários arquivos CSS para cada página. Portanto, esta configuração é pior de ser usada apenas quando você está interessado no processamento futuro de cada página HTML de forma independente e, portanto, o tamanho do CSS de cada página separadamente é a questão mais crítica.
type: docs
weight: 190
url: /pt/net/aspose.pdf/htmlsaveoptions/splitcssintopages/
---
## Propriedade HtmlSaveOptions.SplitCssIntoPages

Quando o modo multipágina é selecionado (ou seja, 'SplitIntoPages' é 'true'), então este atributo define se deve ser criado um arquivo CSS separado para cada página HTML resultante. Por padrão, este atributo é falso, então, será criado um grande CSS comum para todas as páginas criadas. O tamanho total de todos os CSS gerados neste modo (um CSS por página) geralmente é muito maior do que o tamanho de um grande arquivo CSS, porque no primeiro caso as classes CSS são duplicadas em vários arquivos CSS para cada página. Portanto, esta configuração é pior de ser usada apenas quando você está interessado no processamento futuro de cada página HTML de forma independente e, portanto, o tamanho do CSS de cada página separadamente é a questão mais crítica.

```csharp
public bool SplitCssIntoPages { get; set; }
```

### Veja Também

* classe [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)