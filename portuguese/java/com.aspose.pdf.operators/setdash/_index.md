---
title: "SetDash"
linktitle: "SetDash"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o operador d (define o padrão de traço da linha)."
type: docs
weight: 610
url: /pt/java/com.aspose.pdf.operators/setdash/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetDash, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetDash

```
public class SetDash extends Operator
```

Classe que representa o operador d (define o padrão de traço da linha).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SetDash](#SetDash-int:A-int-) | Cria o operador de padrão de traço. |
| [SetDash](#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineDashPattern-) | Construtor da classe operador. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Aceita objeto visitante para processar o operador. |
| [getPattern](#getPattern--) | Padrão de traço. Os elementos da matriz devem ser números que especificam os comprimentos de traços e espaços alternados. No caso de uma matriz com um único elemento, os comprimentos do traço e do espaço são iguais. |
| [getPhase](#getPhase--) | Fase de traço. Antes de começar a desenhar um caminho, o array de traços deve ser percorrido ciclicamente, somando os comprimentos dos traços e dos espaços. Quando o comprimento acumulado for igual ao valor especificado pela fase de traço, o desenho do caminho deve começar, e o array de traços será usado ciclicamente a partir desse ponto. |
| [setPattern](#setPattern-int:A-) | Padrão de traço. Os elementos da matriz devem ser números que especificam os comprimentos de traços e espaços alternados. No caso de uma matriz com um único elemento, os comprimentos do traço e do espaço são iguais. |
| [setPhase](#setPhase-int-) | Fase de traço. Antes de começar a desenhar um caminho, o array de traços deve ser percorrido ciclicamente, somando os comprimentos dos traços e dos espaços. Quando o comprimento acumulado for igual ao valor especificado pela fase de traço, o desenho do caminho deve começar, e o array de traços será usado ciclicamente a partir desse ponto. |
| [toCommand](#toCommand--) | Somente para uso interno! |
| [toString](#toString--) | Obtém a representação em string do operador. |

### SetDash {#SetDash-int:A-int-}
```
public SetDash(int[] pattern, int phase)
```

Cria o operador de padrão de traço.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| padrão |  | Array que define o padrão de traço. |
| fase |  | Fase de traço. |

### SetDash {#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineDashPattern-}
Construtor da classe operador.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Aceita objeto visitante para processar o operador.

### getPattern {#getPattern--}
```
public int[] getPattern()
```

Padrão de traço. Os elementos da matriz devem ser números que especificam os comprimentos de traços e espaços alternados. No caso de uma matriz com um único elemento, os comprimentos do traço e do espaço são iguais.

**Returns:**
array de int

### getPhase {#getPhase--}
```
public int getPhase()
```

Fase de traço. Antes de começar a desenhar um caminho, o array de traços deve ser percorrido ciclicamente, somando os comprimentos dos traços e dos espaços. Quando o comprimento acumulado for igual ao valor especificado pela fase de traço, o desenho do caminho deve começar, e o array de traços será usado ciclicamente a partir desse ponto.

**Returns:**
valor int

### setPattern {#setPattern-int:A-}
```
public void setPattern(int[] value)
```

Padrão de traço. Os elementos da matriz devem ser números que especificam os comprimentos de traços e espaços alternados. No caso de uma matriz com um único elemento, os comprimentos do traço e do espaço são iguais.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | array de int |

### setPhase {#setPhase-int-}
```
public void setPhase(int value)
```

Fase de traço. Antes de começar a desenhar um caminho, o array de traços deve ser percorrido ciclicamente, somando os comprimentos dos traços e dos espaços. Quando o comprimento acumulado for igual ao valor especificado pela fase de traço, o desenho do caminho deve começar, e o array de traços será usado ciclicamente a partir desse ponto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Somente para uso interno!

**Returns:**
valor ICommand objeto ICommand

### toString {#toString--}
```
public String toString()
```

Obtém a representação em string do operador.

**Returns:**
[x1 x2] y d, where x1 - dash length, x2 - gap length, y - phase.
