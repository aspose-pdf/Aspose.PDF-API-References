---
title: "ComparisonOptions"
linktitle: "ComparisonOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase de opciones de comparación de documentos PDF."
type: docs
weight: 10
url: /es/java/com.aspose.pdf.comparison/comparisonoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.ComparisonOptions

```
public class ComparisonOptions extends Object
```

Representa una clase de opciones de comparación de documentos PDF.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ComparisonOptions](#ComparisonOptions--) | Crea una instancia de la clase {@link ComparisonOptions}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getEditOperationsOrder](#getEditOperationsOrder--) | Obtiene y establece el orden de las operaciones de edición. |
| [getExcludeAreas1](#getExcludeAreas1--) | Obtiene y establece las áreas excluidas. Se utiliza para la primera página o documento en el método de comparación. Esta opción puede configurarse junto con {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opción no puede configurarse junto con la opción {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). |
| [getExcludeAreas2](#getExcludeAreas2--) | Obtiene y establece las áreas excluidas. Se utiliza para la segunda página o documento en el método de comparación. Esta opción puede configurarse junto con {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opción no puede configurarse junto con la opción {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). |
| [getExtractionArea](#getExtractionArea--) | Obtiene y establece el área rectangular en la que se comparará el texto de las páginas. Esta opción no puede configurarse junto con {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) y { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) opciones. |
| [isExcludeTables](#isExcludeTables--) | Obtiene y establece la opción que determina si las tablas se excluyen de la comparación. Esta opción no puede configurarse junto con la opción {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). El valor predeterminado es {@code false}. |
| [setEditOperationsOrder](#setEditOperationsOrder-com.aspose.pdf.comparison.EditOperationsOrder-) | Obtiene y establece el orden de las operaciones de edición. |
| [setExcludeAreas1](#setExcludeAreas1-com.aspose.pdf.Rectangle:A-) | Obtiene y establece las áreas excluidas. Se utiliza para la primera página o documento en el método de comparación. Esta opción puede configurarse junto con {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opción no puede configurarse junto con la opción {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). |
| [setExcludeAreas2](#setExcludeAreas2-com.aspose.pdf.Rectangle:A-) | Obtiene y establece las áreas excluidas. Se utiliza para la segunda página o documento en el método de comparación. Esta opción puede configurarse junto con {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opción no puede configurarse junto con la opción {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). |
| [setExcludeTables](#setExcludeTables-boolean-) | Obtiene y establece la opción que determina si las tablas se excluyen de la comparación. Esta opción no puede configurarse junto con la opción {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). El valor predeterminado es {@code false}. |
| [setExtractionArea](#setExtractionArea-com.aspose.pdf.Rectangle-) | Obtiene y establece el área rectangular en la que se comparará el texto de las páginas. Esta opción no puede configurarse junto con {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) y { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) opciones. |

### ComparisonOptions {#ComparisonOptions--}
```
public ComparisonOptions()
```

Crea una instancia de la clase {@link ComparisonOptions}.

### getEditOperationsOrder {#getEditOperationsOrder--}
```
public final EditOperationsOrder getEditOperationsOrder()
```

Obtiene y establece el orden de las operaciones de edición.

**Returns:**
Elemento EditOperationsOrder

### getExcludeAreas1 {#getExcludeAreas1--}
```
public final Rectangle [] getExcludeAreas1()
```

Obtiene y establece las áreas excluidas. Se utiliza para la primera página o documento en el método de comparación. Esta opción puede configurarse junto con {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opción no puede configurarse junto con la opción {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}).

**Returns:**
matriz de instancias de Rectangle

### getExcludeAreas2 {#getExcludeAreas2--}
```
public final Rectangle [] getExcludeAreas2()
```

Obtiene y establece las áreas excluidas. Se utiliza para la segunda página o documento en el método de comparación. Esta opción puede configurarse junto con {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opción no puede configurarse junto con la opción {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}).

**Returns:**
matriz de instancias de Rectangle

### getExtractionArea {#getExtractionArea--}
```
public final Rectangle getExtractionArea()
```

Obtiene y establece el área rectangular en la que se comparará el texto de las páginas. Esta opción no puede configurarse junto con {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) y { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) opciones.

**Returns:**
Instancia de Rectangle

### isExcludeTables {#isExcludeTables--}
```
public final boolean isExcludeTables()
```

Obtiene y establece la opción que determina si las tablas se excluyen de la comparación. Esta opción no puede configurarse junto con la opción {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). El valor predeterminado es {@code false}.

**Returns:**
valor booleano

### setEditOperationsOrder {#setEditOperationsOrder-com.aspose.pdf.comparison.EditOperationsOrder-}
Obtiene y establece el orden de las operaciones de edición.

### setExcludeAreas1 {#setExcludeAreas1-com.aspose.pdf.Rectangle:A-}
Obtiene y establece las áreas excluidas. Se utiliza para la primera página o documento en el método de comparación. Esta opción puede configurarse junto con {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opción no puede configurarse junto con la opción {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}).

### setExcludeAreas2 {#setExcludeAreas2-com.aspose.pdf.Rectangle:A-}
Obtiene y establece las áreas excluidas. Se utiliza para la segunda página o documento en el método de comparación. Esta opción puede configurarse junto con {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opción no puede configurarse junto con la opción {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}).

### setExcludeTables {#setExcludeTables-boolean-}
```
public final void setExcludeTables(boolean value)
```

Obtiene y establece la opción que determina si las tablas se excluyen de la comparación. Esta opción no puede configurarse junto con la opción {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). El valor predeterminado es {@code false}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setExtractionArea {#setExtractionArea-com.aspose.pdf.Rectangle-}
Obtiene y establece el área rectangular en la que se comparará el texto de las páginas. Esta opción no puede configurarse junto con {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) y { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) opciones.
