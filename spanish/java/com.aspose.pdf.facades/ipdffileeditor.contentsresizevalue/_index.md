---
title: "IPdfFileEditor.ContentsResizeValue"
linktitle: "IPdfFileEditor.ContentsResizeValue"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Valor del margen o del tamaño del contenido especificado en porcentajes de unidades de espacio predeterminadas. Esta clase se usa en ContentsResizeParameters."
type: docs
weight: 310
url: /es/java/com.aspose.pdf.facades/ipdffileeditor.contentsresizevalue/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue

```
public static class IPdfFileEditor.ContentsResizeValue extends Object
```

Valor del margen o del tamaño del contenido especificado en porcentajes de unidades de espacio predeterminadas. Esta clase se usa en ContentsResizeParameters.

## Métodos

| Método | Descripción |
| --- | --- |
| [auto](#auto--) | Inicializa el valor calculado automáticamente. |
| [getValue](#getValue--) | Obtiene el valor especificado. Use la propiedad Unit para obtener las unidades del valor. |
| [isPercent](#isPercent--) | Devuelve true si el valor está expresado en porcentajes; False si el valor está expresado en unidades predeterminadas. |
| [percents](#percents-double-) | Inicializa el valor en porcentajes. |
| [setPercentValue](#setPercentValue-double-) | Establece el valor en porcentajes del tamaño de la página. |
| [setUnitValue](#setUnitValue-double-) | Establece el valor en unidades de espacio predeterminadas. |
| [units](#units-double-) | Inicializa el valor en unidades de espacio predeterminadas. |

### auto {#auto--}
```
public static IPdfFileEditor.ContentsResizeValue auto()
```

Inicializa el valor calculado automáticamente.

**Returns:**
Nueva instancia de valor.

### getValue {#getValue--}
```
public final double getValue()
```

Obtiene el valor especificado. Use la propiedad Unit para obtener las unidades del valor.

**Returns:**
valor double

### isPercent {#isPercent--}
```
public final boolean isPercent()
```

Devuelve true si el valor está expresado en porcentajes; False si el valor está expresado en unidades predeterminadas.

**Returns:**
valor booleano

### percents {#percents-double-}
```
public static IPdfFileEditor.ContentsResizeValue percents(double value)
```

Inicializa el valor en porcentajes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Valor en porcentajes. |

**Returns:**
Nueva instancia de valor.

### setPercentValue {#setPercentValue-double-}
```
public final void setPercentValue(double value)
```

Establece el valor en porcentajes del tamaño de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setUnitValue {#setUnitValue-double-}
```
public final void setUnitValue(double value)
```

Establece el valor en unidades de espacio predeterminadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### units {#units-double-}
```
public static IPdfFileEditor.ContentsResizeValue units(double value)
```

Inicializa el valor en unidades de espacio predeterminadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Valor en unidades. |

**Returns:**
Nueva instancia de valor.
