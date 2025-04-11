---
title: Class TextEditOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.TextEditOptions. Descobre opções de operações de edição de texto
type: docs
weight: 10820
url: /pt/net/aspose.pdf.text/texteditoptions/
---
## Classe TextEditOptions

Descobre opções de operações de edição de texto.

```csharp
public sealed class TextEditOptions : TextOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [TextEditOptions](texteditoptions/#constructor)(bool) | Inicializa uma nova instância do objeto `TextEditOptions` para a permissão de transformação de linguagem especificada. |
| [TextEditOptions](texteditoptions/#constructor_1)(FontReplace) | Inicializa uma nova instância do objeto `TextEditOptions` para o modo de comportamento de substituição de fonte especificado. |
| [TextEditOptions](texteditoptions/#constructor_2)(LanguageTransformation) | Inicializa uma nova instância do objeto `TextEditOptions` para o modo de comportamento de transformação de linguagem especificado. |
| [TextEditOptions](texteditoptions/#constructor_3)(NoCharacterAction) | Inicializa uma nova instância do objeto `TextEditOptions` para o modo de comportamento sem caracteres especificado. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AllowLanguageTransformation](../../aspose.pdf.text/texteditoptions/allowlanguagetransformation/) { get; set; } | Obtém ou define o valor que permite o uso de transformação de linguagem durante a adição ou edição de texto. true - a transformação de linguagem será aplicada se necessário (valor padrão). false - a transformação de linguagem NÃO será aplicada. |
| [ClippingPathsProcessing](../../aspose.pdf.text/texteditoptions/clippingpathsprocessing/) { get; set; } | Obtém o modo para processamento do caminho de recorte do texto editado. |
| [FontReplaceBehavior](../../aspose.pdf.text/texteditoptions/fontreplacebehavior/) { get; set; } | Obtém o modo que define o comportamento para cenários de substituição de fontes. |
| [LanguageTransformationBehavior](../../aspose.pdf.text/texteditoptions/languagetransformationbehavior/) { get; set; } | Obtém o modo que define o comportamento para cenários de transformação de linguagem. |
| [NoCharacterBehavior](../../aspose.pdf.text/texteditoptions/nocharacterbehavior/) { get; set; } | Obtém ou define o modo que define o comportamento caso as fontes não contenham os caracteres solicitados. |
| [ReplacementFont](../../aspose.pdf.text/texteditoptions/replacementfont/) { get; set; } | Obtém ou define a fonte usada para substituição se a fonte do usuário não contiver o caractere necessário. |
| [ToAttemptGetUnderlineFromSource](../../aspose.pdf.text/texteditoptions/toattemptgetunderlinefromsource/) { get; set; } | Obtém ou define o valor que permite a busca por sublinhado de texto na página do documento de origem. (Obsoleto) Por favor, use TextSearchOptions.SearchForTextRelatedGraphics em vez disso. |

### Veja Também

* classe [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)