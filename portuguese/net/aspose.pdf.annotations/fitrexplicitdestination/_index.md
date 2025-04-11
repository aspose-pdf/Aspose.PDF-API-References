---
title: Class FitRExplicitDestination
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Annotations.FitRExplicitDestination. Representa um destino explícito que exibe a página com seu conteúdo ampliado o suficiente para caber no retângulo especificado pelas coordenadas esquerda, inferior, direita e superior, totalmente dentro da janela, tanto horizontal quanto verticalmente. Se os fatores de ampliação horizontal e vertical necessários forem diferentes, use o menor dos dois, centralizando o retângulo dentro da janela na outra dimensão. Um valor nulo para qualquer um dos parâmetros pode resultar em comportamento imprevisível.
type: docs
weight: 1780
url: /pt/net/aspose.pdf.annotations/fitrexplicitdestination/
---
## Classe FitRExplicitDestination

Representa um destino explícito que exibe a página com seu conteúdo ampliado o suficiente para caber no retângulo especificado pelas coordenadas esquerda, inferior, direita e superior, totalmente dentro da janela, tanto horizontal quanto verticalmente. Se os fatores de ampliação horizontal e vertical necessários forem diferentes, use o menor dos dois, centralizando o retângulo dentro da janela na outra dimensão. Um valor nulo para qualquer um dos parâmetros pode resultar em comportamento imprevisível.

```csharp
public sealed class FitRExplicitDestination : ExplicitDestination
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_2)(int, double, double, double, double) | Cria um destino explícito remoto. |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_1)(Page, double, double, double, double) | Cria um destino explícito local. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Bottom](../../aspose.pdf.annotations/fitrexplicitdestination/bottom/) { get; } | Obtém a coordenada vertical inferior do retângulo visível. |
| [Left](../../aspose.pdf.annotations/fitrexplicitdestination/left/) { get; } | Obtém a coordenada horizontal esquerda do retângulo visível. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Obtém o objeto da página de destino |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Obtém o número da página de destino |
| [Right](../../aspose.pdf.annotations/fitrexplicitdestination/right/) { get; } | Obtém a coordenada horizontal direita do retângulo visível. |
| [Top](../../aspose.pdf.annotations/fitrexplicitdestination/top/) { get; } | Obtém a coordenada vertical superior do retângulo visível. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [ToString](../../aspose.pdf.annotations/fitrexplicitdestination/tostring/)() | Converte o estado do objeto em um valor de string. Exemplo: "1 FitR 100 200 300 400". |

### Veja Também

* classe [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)