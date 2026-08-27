---
title: "LineJoin"
linktitle: "LineJoin"
second_title: "Referência da API Aspose.PDF para Java"
description: "O estilo de união de linha deve especificar a forma a ser usada nos cantos dos caminhos que são contornados."
type: docs
weight: 370
url: /pt/java/com.aspose.pdf.operators/linejoin/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.operators.LineJoin, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.operators.LineJoin, com.aspose.ms.System.Enum, com.aspose.pdf.operators.LineJoin

```
public final class LineJoin extends com.aspose.ms.System.Enum
```

O estilo de união de linha deve especificar a forma a ser usada nos cantos dos caminhos que são contornados.

## Campos

| Campo | Descrição |
| --- | --- |
| [BevelJoin](#BevelJoin) | Junção chanfrada. Os dois segmentos devem ser finalizados com tampas retas (veja 8.4.3.3, "Line Cap Style") e a entalhe resultante além das extremidades dos segmentos deve ser preenchida com um triângulo. |
| [MiterJoin](#MiterJoin) | Junção em meia-esquadria. As bordas externas dos traços dos dois segmentos devem ser estendidas até se encontrarem em um ângulo, como em uma moldura de quadro. Se os segmentos se encontrarem em um ângulo muito agudo, conforme definido pelo parâmetro limite de meia-esquadria (veja 8.4.3.5, "Miter Limit"), será usada uma junção chanfrada. |
| [RoundJoin](#RoundJoin) | Junção arredondada. Um arco de círculo com diâmetro igual à largura da linha deve ser desenhado ao redor do ponto onde os dois segmentos se encontram, conectando as bordas externas dos traços dos dois segmentos. Essa figura em forma de fatia de pizza deve ser preenchida, produzindo um canto arredondado. |

### BevelJoin {#BevelJoin}
```
public static final int BevelJoin
```

Junção chanfrada. Os dois segmentos devem ser finalizados com tampas retas (veja 8.4.3.3, "Line Cap Style") e a entalhe resultante além das extremidades dos segmentos deve ser preenchida com um triângulo.

### MiterJoin {#MiterJoin}
```
public static final int MiterJoin
```

Junção em meia-esquadria. As bordas externas dos traços dos dois segmentos devem ser estendidas até se encontrarem em um ângulo, como em uma moldura de quadro. Se os segmentos se encontrarem em um ângulo muito agudo, conforme definido pelo parâmetro limite de meia-esquadria (veja 8.4.3.5, "Miter Limit"), será usada uma junção chanfrada.

### RoundJoin {#RoundJoin}
```
public static final int RoundJoin
```

Junção arredondada. Um arco de círculo com diâmetro igual à largura da linha deve ser desenhado ao redor do ponto onde os dois segmentos se encontram, conectando as bordas externas dos traços dos dois segmentos. Essa figura em forma de fatia de pizza deve ser preenchida, produzindo um canto arredondado.
