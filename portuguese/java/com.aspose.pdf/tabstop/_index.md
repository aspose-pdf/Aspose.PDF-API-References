---
title: "TabStop"
linktitle: "TabStop"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma posição personalizada de parada de tabulação em um parágrafo."
type: docs
weight: 4840
url: /pt/java/com.aspose.pdf/tabstop/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TabStop

```
public class TabStop extends Object
```

Representa uma posição personalizada de parada de tabulação em um parágrafo.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TabStop](#TabStop--) | Inicializa uma nova instância da classe {@code TabStop}. |
| [TabStop](#TabStop-float-) | Inicializa uma nova instância da classe {@code TabStop} com a posição especificada. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getAlignmentType](#getAlignmentType--) | Obtém ou define um enum {@code AlignmentType} que indica o tipo de alinhamento da tabulação. |
| [getLeaderType](#getLeaderType--) | Obtém ou define um enum {@code TabLeaderType} que indica o tipo de líder da tabulação. |
| [getPosition](#getPosition--) | Obtém ou define um valor float que indica a posição da parada de tabulação. |
| [isReadOnly](#isReadOnly--) | Obtém o valor que indica que esta instância {@code TabStop} já está anexada a {@code TextFragment} e tornou‑se somente leitura. |
| [setAlignmentType](#setAlignmentType-int-) | Obtém ou define um enum {@code AlignmentType} que indica o tipo de alinhamento da tabulação. |
| [setLeaderType](#setLeaderType-int-) | Obtém ou define um enum {@code TabLeaderType} que indica o tipo de líder da tabulação. |
| [setPosition](#setPosition-float-) | Define um valor float que indica a posição da parada de tabulação. |

### TabStop {#TabStop--}
```
public TabStop()
```

Inicializa uma nova instância da classe {@code TabStop}.

### TabStop {#TabStop-float-}
```
public TabStop(float position)
```

Inicializa uma nova instância da classe {@code TabStop} com a posição especificada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| posição |  | A posição do tab stop. |

### getAlignmentType {#getAlignmentType--}
```
public int getAlignmentType()
```

Obtém ou define um enum {@code AlignmentType} que indica o tipo de alinhamento da tabulação.

**Returns:**
Elemento TabAlignmentType @see TabAlignmentType

### getLeaderType {#getLeaderType--}
```
public int getLeaderType()
```

Obtém ou define um enum {@code TabLeaderType} que indica o tipo de líder da tabulação.

**Returns:**
Elemento TabLeaderType @see TabLeaderType

### getPosition {#getPosition--}
```
public float getPosition()
```

Obtém ou define um valor float que indica a posição da parada de tabulação.

**Returns:**
valor float

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Obtém o valor que indica que esta instância {@code TabStop} já está anexada a {@code TextFragment} e tornou‑se somente leitura.

**Returns:**
valor booleano

### setAlignmentType {#setAlignmentType-int-}
```
public void setAlignmentType(int value)
```

Obtém ou define um enum {@code AlignmentType} que indica o tipo de alinhamento da tabulação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento TabAlignmentType @see TabAlignmentType |

### setLeaderType {#setLeaderType-int-}
```
public void setLeaderType(int value)
```

Obtém ou define um enum {@code TabLeaderType} que indica o tipo de líder da tabulação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento TabLeaderType @see TabLeaderType |

### setPosition {#setPosition-float-}
```
public void setPosition(float value)
```

Define um valor float que indica a posição da parada de tabulação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |
