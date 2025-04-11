---
title: Enum ExplicitDestinationType
second_title: Aspose.PDF for .NET API Reference
description: Enumeração Aspose.Pdf.Annotations.ExplicitDestinationType. Enumera os tipos de destinos explícitos
type: docs
weight: 1690
url: /pt/net/aspose.pdf.annotations/explicitdestinationtype/
---
## Enumeração ExplicitDestinationType

Enumera os tipos de destinos explícitos.

```csharp
public enum ExplicitDestinationType
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| XYZ | `0` | Exibe a página com as coordenadas (esquerda, topo) posicionadas no canto superior esquerdo da janela e o conteúdo da página ampliado pelo fator de zoom. Um valor nulo para qualquer um dos parâmetros esquerda, topo ou zoom especifica que o valor atual desse parâmetro deve ser mantido inalterado. Um valor de zoom de 0 tem o mesmo significado que um valor nulo. |
| Fit | `1` | Exibe a página com seu conteúdo ampliado apenas o suficiente para caber toda a página dentro da janela, tanto horizontal quanto verticalmente. Se os fatores de ampliação horizontal e vertical necessários forem diferentes, use o menor dos dois, centralizando a página dentro da janela na outra dimensão. |
| FitH | `2` | Exibe a página com a coordenada vertical topo posicionada na borda superior da janela e o conteúdo da página ampliado apenas o suficiente para caber toda a largura da página dentro da janela. Um valor nulo para topo especifica que o valor atual desse parâmetro deve ser mantido inalterado. |
| FitV | `3` | Exibe a página com a coordenada horizontal esquerda posicionada na borda esquerda da janela e o conteúdo da página ampliado apenas o suficiente para caber toda a altura da página dentro da janela. Um valor nulo para esquerda especifica que o valor atual desse parâmetro deve ser mantido inalterado. |
| FitR | `4` | Exibe a página com seu conteúdo ampliado apenas o suficiente para caber o retângulo especificado pelas coordenadas esquerda, inferior, direita e topo totalmente dentro da janela, tanto horizontal quanto verticalmente. Se os fatores de ampliação horizontal e vertical necessários forem diferentes, use o menor dos dois, centralizando o retângulo dentro da janela na outra dimensão. Um valor nulo para qualquer um dos parâmetros pode resultar em comportamento imprevisível. |
| FitB | `5` | Exibe a página com seu conteúdo ampliado apenas o suficiente para caber sua caixa delimitadora totalmente dentro da janela, tanto horizontal quanto verticalmente. Se os fatores de ampliação horizontal e vertical necessários forem diferentes, use o menor dos dois, centralizando a caixa delimitadora dentro da janela na outra dimensão. |
| FitBH | `6` | Exibe a página com a coordenada vertical topo posicionada na borda superior da janela e o conteúdo da página ampliado apenas o suficiente para caber toda a largura de sua caixa delimitadora dentro da janela. Um valor nulo para topo especifica que o valor atual desse parâmetro deve ser mantido inalterado. |
| FitBV | `7` | Exibe a página com a coordenada horizontal esquerda posicionada na borda esquerda da janela e o conteúdo da página ampliado apenas o suficiente para caber toda a altura de sua caixa delimitadora dentro da janela. Um valor nulo para esquerda especifica que o valor atual desse parâmetro deve ser mantido inalterado. |

### Veja Também

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)