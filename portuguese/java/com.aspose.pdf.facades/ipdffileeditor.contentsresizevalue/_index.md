---
title: "IPdfFileEditor.ContentsResizeValue"
linktitle: "IPdfFileEditor.ContentsResizeValue"
second_title: "Referência da API Aspose.PDF para Java"
description: "Valor da margem ou tamanho do conteúdo especificado em porcentagem das unidades de espaço padrão. Esta classe é usada em ContentsResizeParameters."
type: docs
weight: 310
url: /pt/java/com.aspose.pdf.facades/ipdffileeditor.contentsresizevalue/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue

```
public static class IPdfFileEditor.ContentsResizeValue extends Object
```

Valor da margem ou tamanho do conteúdo especificado em porcentagem das unidades de espaço padrão. Esta classe é usada em ContentsResizeParameters.

## Métodos

| Método | Descrição |
| --- | --- |
| [auto](#auto--) | Inicializa o valor calculado automaticamente. |
| [getValue](#getValue--) | Obtém o valor especificado. Use a propriedade Unit para obter as unidades do valor. |
| [isPercent](#isPercent--) | Retorna true se o valor for expresso em porcentagem; False se o valor for expresso em unidades padrão. |
| [percents](#percents-double-) | Inicializa o valor em porcentagem. |
| [setPercentValue](#setPercentValue-double-) | Define o valor em porcentagem do tamanho da página. |
| [setUnitValue](#setUnitValue-double-) | Define o valor nas unidades padrão de espaço. |
| [units](#units-double-) | Inicializa o valor nas unidades padrão de espaço. |

### auto {#auto--}
```
public static IPdfFileEditor.ContentsResizeValue auto()
```

Inicializa o valor calculado automaticamente.

**Returns:**
Nova instância de valor.

### getValue {#getValue--}
```
public final double getValue()
```

Obtém o valor especificado. Use a propriedade Unit para obter as unidades do valor.

**Returns:**
valor double

### isPercent {#isPercent--}
```
public final boolean isPercent()
```

Retorna true se o valor for expresso em porcentagem; False se o valor for expresso em unidades padrão.

**Returns:**
valor booleano

### percents {#percents-double-}
```
public static IPdfFileEditor.ContentsResizeValue percents(double value)
```

Inicializa o valor em porcentagem.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Valor em porcentagem. |

**Returns:**
Nova instância de valor.

### setPercentValue {#setPercentValue-double-}
```
public final void setPercentValue(double value)
```

Define o valor em porcentagem do tamanho da página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setUnitValue {#setUnitValue-double-}
```
public final void setUnitValue(double value)
```

Define o valor nas unidades padrão de espaço.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### units {#units-double-}
```
public static IPdfFileEditor.ContentsResizeValue units(double value)
```

Inicializa o valor nas unidades padrão de espaço.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Valor em unidades. |

**Returns:**
Nova instância de valor.
