---
title: "Traço"
linktitle: "Traço"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o padrão de traço de linha."
type: docs
weight: 910
url: /pt/java/com.aspose.pdf/dash/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Dash

```
public final class Dash extends Object
```

Classe que representa o padrão de traço de linha.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Dash](#Dash-int:A-) | Construtor para Dash. Define um padrão de traços e espaços que será usado ao desenhar uma borda tracejada. |
| [Dash](#Dash-int-int-) | Construtor para Dash. Define uma borda tracejada com traço e espaço especificados, que permanecem inalterados ao longo de toda a borda tracejada. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getOff](#getOff--) | Obtém ou define o comprimento do primeiro espaço entre os traços. |
| [getOn](#getOn--) | Obtém ou define o comprimento do primeiro traço. |
| [getPattern](#getPattern--) | Obtém o array de traços que define um padrão de traços e espaços que será usado ao desenhar uma borda tracejada. |
| [setOff](#setOff-int-) | Obtém ou define o comprimento do primeiro espaço entre os traços. |
| [setOn](#setOn-int-) | Obtém ou define o comprimento do primeiro traço. |

### Dash {#Dash-int:A-}
```
public Dash(int[] pattern)
```

Construtor para Dash. Define um padrão de traços e espaços que será usado ao desenhar uma borda tracejada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| padrão |  | Um array de traços (com no mínimo dois valores) que define um padrão de traços e espaços que será usado ao desenhar uma borda tracejada. |

### Dash {#Dash-int-int-}
```
public Dash(int on, int off)
```

Construtor para Dash. Define uma borda tracejada com traço e espaço especificados, que permanecem inalterados ao longo de toda a borda tracejada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ligado |  | Comprimento do traço. |
| desligado |  | Comprimento do espaço. |

### getOff {#getOff--}
```
public final int getOff()
```

Obtém ou define o comprimento do primeiro espaço entre os traços.

**Returns:**
valor int

### getOn {#getOn--}
```
public final int getOn()
```

Obtém ou define o comprimento do primeiro traço.

**Returns:**
valor int

### getPattern {#getPattern--}
```
public final int[] getPattern()
```

Obtém o array de traços que define um padrão de traços e espaços que será usado ao desenhar uma borda tracejada.

**Returns:**
array de int

### setOff {#setOff-int-}
```
public final void setOff(int value)
```

Obtém ou define o comprimento do primeiro espaço entre os traços.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setOn {#setOn-int-}
```
public final void setOn(int value)
```

Obtém ou define o comprimento do primeiro traço.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |
