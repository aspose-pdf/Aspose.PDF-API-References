---
title: "SaveOptions.MarginPartStyle"
linktitle: "SaveOptions.MarginPartStyle"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa informações de uma parte da margem (superior, inferior, lado esquerdo ou lado direito)."
type: docs
weight: 4420
url: /pt/java/com.aspose.pdf/saveoptions.marginpartstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.MarginPartStyle

```
public static class SaveOptions.MarginPartStyle extends Object
```

Representa informações de uma parte da margem (superior, inferior, lado esquerdo ou lado direito).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [MarginPartStyle](#MarginPartStyle-boolean-) | Cria uma instância da classe MarginPartStyle e inicializa seu valor em pontos |
| [MarginPartStyle](#MarginPartStyle-int-) | Cria uma instância da classe MarginPartStyle e define seu valor em pontos |

## Métodos

| Método | Descrição |
| --- | --- |
| [getValueInPoints](#getValueInPoints--) | Representa a margem em pontos. Deve ser um número maior que zero. |
| [isAuto](#isAuto--) | Obtém ou define um valor que indica se esta instância está automática. Valor: {@code true} se esta instância está automática; caso contrário, {@code false}. |
| [setAuto](#setAuto-boolean-) | Obtém ou define um valor que indica se esta instância está automática. Valor: {@code true} se esta instância está automática; caso contrário, {@code false}. |
| [setValueInPoints](#setValueInPoints-int-) | Representa a margem em pontos. Deve ser um número maior que zero. |

### MarginPartStyle {#MarginPartStyle-boolean-}
```
public MarginPartStyle(boolean isAuto)
```

Cria uma instância da classe MarginPartStyle e inicializa seu valor em pontos

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isAuto |  | Marcar margem como automática |

### MarginPartStyle {#MarginPartStyle-int-}
```
public MarginPartStyle(int valueInPoints)
```

Cria uma instância da classe MarginPartStyle e define seu valor em pontos

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valueInPoints |  | Valor inteiro em pontos |

### getValueInPoints {#getValueInPoints--}
```
public final int getValueInPoints()
```

Representa a margem em pontos. Deve ser um número maior que zero.

**Returns:**
valor int

### isAuto {#isAuto--}
```
public final boolean isAuto()
```

Obtém ou define um valor que indica se esta instância está automática. Valor: {@code true} se esta instância está automática; caso contrário, {@code false}.

**Returns:**
valor booleano

### setAuto {#setAuto-boolean-}
```
public final void setAuto(boolean value)
```

Obtém ou define um valor que indica se esta instância está automática. Valor: {@code true} se esta instância está automática; caso contrário, {@code false}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setValueInPoints {#setValueInPoints-int-}
```
public final void setValueInPoints(int value)
```

Representa a margem em pontos. Deve ser um número maior que zero.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |
