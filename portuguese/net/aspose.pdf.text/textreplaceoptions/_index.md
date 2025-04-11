---
title: Class TextReplaceOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.TextReplaceOptions. Representa opções de substituição de texto
type: docs
weight: 11010
url: /pt/net/aspose.pdf.text/textreplaceoptions/
---
## Classe TextReplaceOptions

Representa opções de substituição de texto

```csharp
public sealed class TextReplaceOptions : TextOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [TextReplaceOptions](textreplaceoptions/#constructor)(ReplaceAdjustment) | Inicializa uma nova instância do objeto `TextReplaceOptions` para a ação de substituição especificada. |
| [TextReplaceOptions](textreplaceoptions/#constructor_1)(Scope) | Inicializa uma nova instância do objeto `TextReplaceOptions` para o escopo especificado. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AdjustmentNewLineSpacing](../../aspose.pdf.text/textreplaceoptions/adjustmentnewlinespacing/) { get; set; } | Obtém ou define o valor do espaçamento entre linhas que é usado se o ajuste de substituição for forçado a criar uma nova linha de texto. O valor esperado é um multiplicador do tamanho da fonte do texto substituído. O padrão é 1.2. |
| [IgnoreParagraphs](../../aspose.pdf.text/textreplaceoptions/ignoreparagraphs/) { get; set; } | Obtém ou define um valor que indica se deve ignorar parágrafos distintos ao ajustar o texto na página após a substituição do texto. |
| [LeftAdjustment](../../aspose.pdf.text/textreplaceoptions/leftadjustment/) { get; set; } | Define ou obtém o ajuste da posição esquerda para o texto substituído ao usar TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [ReplaceAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/replaceadjustmentaction/) { get; set; } | Obtém ou define uma ação que será realizada após a substituição do fragmento de texto por um mais curto. |
| [ReplaceScope](../../aspose.pdf.text/textreplaceoptions/replacescope/) { get; set; } | Obtém ou define um escopo onde a operação de substituição de texto é aplicada |
| [RightAdjustment](../../aspose.pdf.text/textreplaceoptions/rightadjustment/) { get; set; } | Define ou obtém o ajuste da posição direita para o texto substituído ao usar TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### Veja Também

* classe [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)