---
title: Class XYZExplicitDestination
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Annotations.XYZExplicitDestination. Representa um destino explícito que exibe a página com as coordenadas esquerda e superior posicionadas no canto superior esquerdo da janela e o conteúdo da página ampliado pelo fator de zoom. Um valor nulo para qualquer um dos parâmetros esquerda, superior ou zoom especifica que o valor atual desse parâmetro deve ser mantido inalterado. Um valor de zoom de 0 tem o mesmo significado que um valor nulo.
type: docs
weight: 2730
url: /pt/net/aspose.pdf.annotations/xyzexplicitdestination/
---
## Classe XYZExplicitDestination

Representa um destino explícito que exibe a página com as coordenadas (esquerda, superior) posicionadas no canto superior esquerdo da janela e o conteúdo da página ampliado pelo fator de zoom. Um valor nulo para qualquer um dos parâmetros esquerda, superior ou zoom especifica que o valor atual desse parâmetro deve ser mantido inalterado. Um valor de zoom de 0 tem o mesmo significado que um valor nulo.

```csharp
public sealed class XYZExplicitDestination : ExplicitDestination
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_2)(int, double, double, double) | Cria um destino explícito remoto. |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_1)(Page, double, double, double) | Cria um destino explícito local. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Left](../../aspose.pdf.annotations/xyzexplicitdestination/left/) { get; } | Obtém a coordenada horizontal esquerda do canto superior esquerdo da janela. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Obtém o objeto da página de destino |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Obtém o número da página de destino |
| [Top](../../aspose.pdf.annotations/xyzexplicitdestination/top/) { get; } | Obtém a coordenada vertical superior do canto superior esquerdo da janela. |
| [Zoom](../../aspose.pdf.annotations/xyzexplicitdestination/zoom/) { get; } | Obtém o fator de zoom. |

## Métodos

| Nome | Descrição |
| --- | --- |
| static [CreateDestination](../../aspose.pdf.annotations/xyzexplicitdestination/createdestination/)(Page, double, double, double, bool) | Cria um destino para a localização especificada da página considerando a rotação da página, se necessário. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner)(Page) | Cria um destino para a página especificada. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner_1)(Page, double) | Cria um destino para o canto superior esquerdo da página especificada. |
| override [ToString](../../aspose.pdf.annotations/xyzexplicitdestination/tostring/)() | Converte o estado do objeto em um valor de string. Exemplo: "1 XYZ 100 200 3". |

## Exemplos

```csharp
Document doc = new Document("example.pdf");
XYZExplicitDestination dest = (XYZExplicitDestination)doc.Outlines[1].Destination;
string left = dest.Left;
string top = dest.Top;
string zoom = dest.Zoom;
```

### Veja Também

* classe [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)