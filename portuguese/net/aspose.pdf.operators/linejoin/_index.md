---
title: Enum LineJoin
second_title: Aspose.PDF for .NET API Reference
description: Enumeração Aspose.Pdf.Operators.LineJoin. O estilo de junção de linha deve especificar a forma a ser usada nos cantos dos caminhos que são traçados
type: docs
weight: 7450
url: /pt/net/aspose.pdf.operators/linejoin/
---
## Enumeração LineJoin

O estilo de junção de linha deve especificar a forma a ser usada nos cantos dos caminhos que são traçados.

```csharp
public enum LineJoin
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| MiterJoin | `0` | Junção em miter. As bordas externas dos traços para os dois segmentos devem ser estendidas até se encontrarem em um ângulo, como em uma moldura de quadro. Se os segmentos se encontrarem em um ângulo muito agudo, conforme definido pelo parâmetro de limite de miter (veja 8.4.3.5, "Limite de Miter"), uma junção em bisel deve ser usada em vez disso. |
| RoundJoin | `1` | Junção arredondada. Um arco de um círculo com um diâmetro igual à largura da linha deve ser desenhado ao redor do ponto onde os dois segmentos se encontram, conectando as bordas externas dos traços para os dois segmentos. Esta figura em forma de fatia de torta deve ser preenchida, produzindo um canto arredondado. |
| BevelJoin | `2` | Junção em bisel. Os dois segmentos devem ser finalizados com tampas retas (veja 8.4.3.3, "Estilo de Tampa de Linha") e o entalhe resultante além das extremidades dos segmentos deve ser preenchido com um triângulo. |

### Veja Também

* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)