---
title: Class ToUnicodeProcessingRules
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.ToUnicodeProcessingRules. Esta classe descreve regras que podem ser usadas para resolver o erro do Adobe Preflight "Texto não pode ser mapeado para Unicode"
type: docs
weight: 11110
url: /pt/net/aspose.pdf/tounicodeprocessingrules/
---
## Classe ToUnicodeProcessingRules

Esta classe descreve regras que podem ser usadas para resolver o erro do Adobe Preflight "Texto não pode ser mapeado para Unicode".

```csharp
public class ToUnicodeProcessingRules
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor)() | Inicializa uma nova instância da classe `ToUnicodeProcessingRules`. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_1)(bool) | Inicializa uma nova instância da classe `ToUnicodeProcessingRules` com a opção especificada para remover espaços dos nomes de CMap. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_2)(bool, bool) | Inicializa uma nova instância da classe `ToUnicodeProcessingRules` com opções especificadas. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [MapNonLinkedSymbolsOnSpace](../../aspose.pdf/tounicodeprocessingrules/mapnonlinkedsymbolsonspace/) { get; set; } | Algumas fontes não fornecem informações sobre unicodes para alguns símbolos de texto. Essa falta de informação gera um erro "Texto não pode ser mapeado para Unicode". Use esta flag para mapear símbolos não vinculados para o unicode "espaço" (código 32). |
| [RemoveSpacesFromCMapNames](../../aspose.pdf/tounicodeprocessingrules/removespacesfromcmapnames/) { get; set; } | Algumas fontes têm mapas de códigos de caracteres ToUnicode com espaços nos nomes. Esses espaços podem gerar erros com o mapeamento de texto unicode. Esta flag ordena a remoção de espaços dos nomes dos mapas de códigos de caracteres ToUnicode. Por padrão, falso. |

### Veja Também

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)