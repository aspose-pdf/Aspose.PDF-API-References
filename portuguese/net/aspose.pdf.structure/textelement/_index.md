---
title: Class TextElement
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Structure.TextElement. Elemento de texto geral da estrutura lógica do documento
type: docs
weight: 10190
url: /pt/net/aspose.pdf.structure/textelement/
---
## Classe TextElement

Elemento de texto geral da estrutura lógica do documento.

```csharp
public class TextElement : Element
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| virtual [ActualText](../../aspose.pdf.structure/element/actualtext/) { get; set; } | (Opcional; PDF 1.4) Texto que é uma substituição exata para o elemento de estrutura e seus filhos. Este texto de substituição (que deve se aplicar ao menor pedaço de conteúdo possível) é útil ao extrair o conteúdo do documento em apoio à acessibilidade para usuários com deficiência ou para outros fins. |
| virtual [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | (Opcional) Uma descrição alternativa do elemento de estrutura e seus filhos em forma legível por humanos, que é útil ao extrair o conteúdo do documento em apoio à acessibilidade para usuários com deficiência ou para outros fins. |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | Obtém a coleção de elementos filhos. |
| virtual [E](../../aspose.pdf.structure/element/e/) { get; set; } | (Opcional; PDF 1.5) A forma expandida de uma abreviação. |
| virtual [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | (Opcional; PDF 1.4) Uma linguagem que especifica a língua natural para todo o texto no elemento de estrutura, exceto onde é substituído por especificações de linguagem para elementos de estrutura aninhados ou conteúdo marcado. |
| [Text](../../aspose.pdf.structure/textelement/text/) { get; } | Obtém o valor do elemento de estrutura de texto. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Remove](../../aspose.pdf.structure/element/remove/)() | Remove o elemento. |

### Veja Também

* classe [Element](../element/)
* namespace [Aspose.Pdf.Structure](../../aspose.pdf.structure/)
* assembly [Aspose.PDF](../../)