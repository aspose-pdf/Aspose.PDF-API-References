---
title: "HeadingLevels"
linktitle: "HeadingLevels"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase para trabajar con niveles de encabezado basados en el tamaño de fuente."
type: docs
weight: 20
url: /es/java/com.aspose.pdf.markdownoptions/headinglevels/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.markdownoptions.HeadingLevels

```
public class HeadingLevels extends Object
```

Representa una clase para trabajar con niveles de encabezado basados en el tamaño de fuente.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [HeadingLevels](#HeadingLevels--) | Crea una nueva instancia de la clase HeadingLevels. |
| [HeadingLevels](#HeadingLevels-double-) | Crea una nueva instancia de la clase HeadingLevels. |

## Métodos

| Método | Descripción |
| --- | --- |
| [addLevels](#addLevels-java.lang.Iterable-) | Agrega niveles de encabezado. |
| [estimateLevel](#estimateLevel-double-) | Estima el nivel de encabezado posible. Si fontSize no se encuentra en la lista de niveles, se devolverá el nivel más cercano a este valor de tamaño de fuente. Si fontSize está fuera del rango mínimo y máximo de niveles de encabezado especificado, el método devolverá false. |
| [findLevel](#findLevel-double-int:A-) | Busca el nivel correspondiente al tamaño de fuente. Busca una coincidencia exacta. |
| [getAllLevels](#getAllLevels--) | Obtiene todos los niveles de encabezado. |

### HeadingLevels {#HeadingLevels--}
```
public HeadingLevels()
```

Crea una nueva instancia de la clase HeadingLevels.

### HeadingLevels {#HeadingLevels-double-}
```
public HeadingLevels(double threshold)
```

Crea una nueva instancia de la clase HeadingLevels.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threshold |  | El valor de umbral para comparar tamaños de fuente. Dentro del umbral, los niveles de encabezado son los mismos. El valor predeterminado del umbral es 0.01. |

### addLevels {#addLevels-java.lang.Iterable-}
Agrega niveles de encabezado.

### estimateLevel {#estimateLevel-double-}
```
public final int estimateLevel(double fontSize)
```

Estima el nivel de encabezado posible. Si fontSize no se encuentra en la lista de niveles, se devolverá el nivel más cercano a este valor de tamaño de fuente. Si fontSize está fuera del rango mínimo y máximo de niveles de encabezado especificado, el método devolverá false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontSize |  | El tamaño de fuente. |

**Returns:**
Nivel de encabezado.

### findLevel {#findLevel-double-int:A-}
```
public final boolean findLevel(double fontSize, int[] level)
```

Busca el nivel correspondiente al tamaño de fuente. Busca una coincidencia exacta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontSize |  | El tamaño de fuente. |
| level |  | El nivel de encabezado correspondiente para el tamaño de fuente dado. |

**Returns:**
False Si fontSize no está dentro del rango especificado.

### getAllLevels {#getAllLevels--}
```
public final com.aspose.ms.System.Collections.IEnumerable< Double > getAllLevels()
```

Obtiene todos los niveles de encabezado.

**Returns:**
IEnumerable de Double
