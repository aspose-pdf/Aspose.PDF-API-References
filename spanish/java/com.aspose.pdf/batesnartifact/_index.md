---
title: "BatesNArtifact"
linktitle: "BatesNArtifact"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que describe el artefacto de numeración Bates."
type: docs
weight: 290
url: /es/java/com.aspose.pdf/batesnartifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact com.aspose.pdf.PaginationArtifact com.aspose.pdf.BatesNArtifact, com.aspose.pdf.Artifact, com.aspose.pdf.PaginationArtifact com.aspose.pdf.BatesNArtifact, com.aspose.pdf.PaginationArtifact, com.aspose.pdf.BatesNArtifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public class BatesNArtifact extends PaginationArtifact
```

Clase que describe el artefacto de numeración Bates.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [BatesNArtifact](#BatesNArtifact--) | Inicializa una nueva instancia de la clase {@link BatesNArtifact}. Este constructor es interno y crea una instancia de artefacto de encabezado con valores predeterminados. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getNumberOfDigits](#getNumberOfDigits--) | Obtiene o establece el número de dígitos para la numeración Bates. El valor debe estar entre 3 y 15 inclusive. Si se establece un valor menor que 3, se ajustará a 3. Si se establece un valor mayor que 15, se ajustará a 15. El valor predeterminado es 6. |
| [getPrefix](#getPrefix--) | Obtiene o establece el prefijo que se añadirá al número Bates. |
| [getStartNumber](#getStartNumber--) | Obtiene o establece el número inicial para la numeración Bates. El valor debe ser mayor o igual a 1. Si se establece un valor menor que 1, se ajustará a 1. |
| [getSuffix](#getSuffix--) | Obtiene o establece el sufijo que se añadirá al número Bates. |
| [setNumberOfDigits](#setNumberOfDigits-int-) | Obtiene o establece el número de dígitos para la numeración Bates. El valor debe estar entre 3 y 15 inclusive. Si se establece un valor menor que 3, se ajustará a 3. Si se establece un valor mayor que 15, se ajustará a 15. El valor predeterminado es 6. |
| [setPrefix](#setPrefix-java.lang.String-) | Obtiene o establece el prefijo que se añadirá al número Bates. |
| [setStartNumber](#setStartNumber-int-) | Obtiene o establece el número inicial para la numeración Bates. El valor debe ser mayor o igual a 1. Si se establece un valor menor que 1, se ajustará a 1. |
| [setSuffix](#setSuffix-java.lang.String-) | Obtiene o establece el sufijo que se añadirá al número Bates. |

### BatesNArtifact {#BatesNArtifact--}
```
public BatesNArtifact()
```

Inicializa una nueva instancia de la clase {@link BatesNArtifact}. Este constructor es interno y crea una instancia de artefacto de encabezado con valores predeterminados.

### getNumberOfDigits {#getNumberOfDigits--}
```
public final int getNumberOfDigits()
```

Obtiene o establece el número de dígitos para la numeración Bates. El valor debe estar entre 3 y 15 inclusive. Si se establece un valor menor que 3, se ajustará a 3. Si se establece un valor mayor que 15, se ajustará a 15. El valor predeterminado es 6.

**Returns:**
valor int

### getPrefix {#getPrefix--}
```
public final String getPrefix()
```

Obtiene o establece el prefijo que se añadirá al número Bates.

**Returns:**
valor String

### getStartNumber {#getStartNumber--}
```
public final int getStartNumber()
```

Obtiene o establece el número inicial para la numeración Bates. El valor debe ser mayor o igual a 1. Si se establece un valor menor que 1, se ajustará a 1.

**Returns:**
valor int

### getSuffix {#getSuffix--}
```
public final String getSuffix()
```

Obtiene o establece el sufijo que se añadirá al número Bates.

**Returns:**
valor String

### setNumberOfDigits {#setNumberOfDigits-int-}
```
public final void setNumberOfDigits(int value)
```

Obtiene o establece el número de dígitos para la numeración Bates. El valor debe estar entre 3 y 15 inclusive. Si se establece un valor menor que 3, se ajustará a 3. Si se establece un valor mayor que 15, se ajustará a 15. El valor predeterminado es 6.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setPrefix {#setPrefix-java.lang.String-}
Obtiene o establece el prefijo que se añadirá al número Bates.

### setStartNumber {#setStartNumber-int-}
```
public final void setStartNumber(int value)
```

Obtiene o establece el número inicial para la numeración Bates. El valor debe ser mayor o igual a 1. Si se establece un valor menor que 1, se ajustará a 1.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setSuffix {#setSuffix-java.lang.String-}
Obtiene o establece el sufijo que se añadirá al número Bates.
