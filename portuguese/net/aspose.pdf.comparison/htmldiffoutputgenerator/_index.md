---
title: Class HtmlDiffOutputGenerator
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Comparison.HtmlDiffOutputGenerator. Representa uma classe para gerar a representação html das diferenças de textos. Quebras de linha deletadas são indicadas pelo marcador de parágrafo
type: docs
weight: 3200
url: /pt/net/aspose.pdf.comparison/htmldiffoutputgenerator/
---
## Classe HtmlDiffOutputGenerator

Representa uma classe para gerar a representação html das diferenças de textos. Quebras de linha deletadas são indicadas pelo marcador de parágrafo.

```csharp
public class HtmlDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor)() | Cria uma instância da classe `HtmlDiffOutputGenerator`. |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor_1)(OutputTextStyle) | Cria uma instância da classe `HtmlDiffOutputGenerator`. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [DeleteStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/deletestyle/) { get; set; } | Obtém e define a string de estilo CSS para a operação de Deletar. Exemplo: |
| [EqualStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/equalstyle/) { get; set; } | Obtém e define a string de estilo CSS para a operação de Igual. Exemplo: |
| [InsertStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/insertstyle/) { get; set; } | Obtém e define a string de estilo CSS para a operação de Inserir. Exemplo: |
| [StrikethroughDeleted](../../aspose.pdf.comparison/htmldiffoutputgenerator/strikethroughdeleted/) { get; set; } | Obtém ou define o estilo de decoração de texto: linha através para a operação de deletar. O valor padrão é `False`. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | Gera a saída com base nas diferenças entre os textos e a salva em um arquivo. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | Gera a saída com base nas diferenças entre os textos e a salva em um arquivo. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | Gera a saída com base nas diferenças entre os textos e a salva em um arquivo. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | Gera a saída com base nas diferenças entre os textos e a salva em um arquivo. |

### Veja Também

* interface [IFileOutputGenerator](../ifileoutputgenerator/)
* interface [IStringOutputGenerator](../istringoutputgenerator/)
* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)