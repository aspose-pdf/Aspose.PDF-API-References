---
title: Class Rectangle
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Rectangle. Classe representa retângulo
type: docs
weight: 9750
url: /pt/net/aspose.pdf/rectangle/
---
## Classe Retângulo

Classe representa retângulo.

```csharp
public sealed class Rectangle : ICloneable
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [Rectangle](rectangle/)(double, double, double, double, bool) | Construtor de Retângulo. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| static [Empty](../../aspose.pdf/rectangle/empty/) { get; } | Retângulo vazio |
| static [Trivial](../../aspose.pdf/rectangle/trivial/) { get; } | Inicializa retângulo trivial, ou seja, retângulo com posição e tamanho zero. |
| [Height](../../aspose.pdf/rectangle/height/) { get; } | Altura do retângulo. |
| [IsEmpty](../../aspose.pdf/rectangle/isempty/) { get; } | Verifica se o retângulo está vazio. |
| [IsPoint](../../aspose.pdf/rectangle/ispoint/) { get; } | Verifica se o retângulo é um ponto, ou seja, LLX é igual a URX e LLY é igual a URY. |
| [IsTrivial](../../aspose.pdf/rectangle/istrivial/) { get; } | Verifica se o retângulo é trivial, ou seja, tem tamanho e posição zero. |
| [LLX](../../aspose.pdf/rectangle/llx/) { get; set; } | Coordenada X do canto inferior esquerdo. |
| [LLY](../../aspose.pdf/rectangle/lly/) { get; set; } | Coordenada Y do canto inferior esquerdo. |
| [URX](../../aspose.pdf/rectangle/urx/) { get; set; } | Coordenada X do canto superior direito. |
| [URY](../../aspose.pdf/rectangle/ury/) { get; set; } | Coordenada Y do canto superior direito. |
| [Width](../../aspose.pdf/rectangle/width/) { get; } | Largura do retângulo. |

## Métodos

| Nome | Descrição |
| --- | --- |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect)(Rectangle) | Inicializa um novo retângulo a partir da instância dada de System.Drawing.Rectangle. |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect_1)(RectangleF) | Inicializa um novo retângulo a partir da instância dada de System.Drawing.Rectangle. |
| static [Parse](../../aspose.pdf/rectangle/parse/)(string) | Tenta analisar a string e extrair dela os componentes do retângulo llx, lly, urx, ury. |
| [Center](../../aspose.pdf/rectangle/center/)() | Retorna as coordenadas do centro do retângulo. |
| [Clone](../../aspose.pdf/rectangle/clone/)() | Clona o objeto Retângulo. |
| [Contains](../../aspose.pdf/rectangle/contains/)(Point, bool) | Determina se o ponto dado está dentro do retângulo. |
| [ContainsLine](../../aspose.pdf/rectangle/containsline/)(double, double, double, double) | Determina se o retângulo contém uma linha representada por dois pontos. |
| [ContainsPoint](../../aspose.pdf/rectangle/containspoint/)(double, double) | Determina se o ponto dado está contido dentro do retângulo. |
| [Equals](../../aspose.pdf/rectangle/equals/#equals)(Rectangle) | Verifica se os retângulos são iguais, ou seja, têm a mesma posição e tamanhos. |
| [Intersect](../../aspose.pdf/rectangle/intersect/)(Rectangle) | Intersecciona dois retângulos. |
| [IsIntersect](../../aspose.pdf/rectangle/isintersect/)(Rectangle) | Determina se este retângulo intersecta com outro retângulo. |
| [Join](../../aspose.pdf/rectangle/join/)(Rectangle) | Junta retângulos. |
| [MoveBy](../../aspose.pdf/rectangle/moveby/)(double, double) | Move o retângulo pelos deltas especificados. |
| [NearEquals](../../aspose.pdf/rectangle/nearequals/)(Rectangle, double) | Verifica se os retângulos são quase iguais, ou seja, têm posições e tamanhos quase iguais (até o delta). |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate_1)(int) | Rotaciona o retângulo pelo ângulo especificado. |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate)(Rotation) | Rotaciona o retângulo pelo ângulo especificado. |
| [ToPoints](../../aspose.pdf/rectangle/topoints/)() | Converte o retângulo em um array de pontos ("QuadPoints"). |
| [ToRect](../../aspose.pdf/rectangle/torect/)() | Converte o retângulo em uma instância de System.Drawing.Rectangle. As posições e tamanhos em ponto flutuante são truncados. |
| override [ToString](../../aspose.pdf/rectangle/tostring/)() | Obtém a representação em string do retângulo. |

### Veja Também

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)