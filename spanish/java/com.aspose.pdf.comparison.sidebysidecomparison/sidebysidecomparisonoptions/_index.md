---
title: "SideBySideComparisonOptions"
linktitle: "SideBySideComparisonOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase de opciones para comparar documentos con salida lado a lado."
type: docs
weight: 60
url: /es/java/com.aspose.pdf.comparison.sidebysidecomparison/sidebysidecomparisonoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.outputgenerator.IVentureLicenseTarget com.aspose.pdf.comparison.sidebysidecomparison.SideBySideComparisonOptions, com.aspose.pdf.comparison.outputgenerator.IVentureLicenseTarget, com.aspose.pdf.comparison.sidebysidecomparison.SideBySideComparisonOptions

```
public class SideBySideComparisonOptions extends IVentureLicenseTarget
```

Representa una clase de opciones para comparar documentos con salida lado a lado.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SideBySideComparisonOptions](#SideBySideComparisonOptions--) | Crea una instancia de la clase {@link SideBySideComparisonOptions}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getAdditionalChangeMarks](#getAdditionalChangeMarks--) | Obtenga y establezca la propiedad que determina si se muestran marcadores de cambio adicionales. Si se establece, muestra marcas de cambio que no están en la página actual pero sí están presentes en otra página. Si el cambio se ubica entre palabras, la marca puede no estar posicionada exactamente en relación con el carácter de espacio. El valor predeterminado es {@code false}. |
| [getComparisonArea1](#getComparisonArea1--) | Obtenga y establezca el área de comparación. Se utiliza para la primera página o documento en el método de comparación. Esta opción no puede configurarse junto con las opciones {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) y {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) . |
| [getComparisonArea2](#getComparisonArea2--) | Obtenga y establezca el área de comparación. Se utiliza para la segunda página o documento en el método de comparación. Esta opción no puede configurarse junto con las opciones {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) y {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) . |
| [getComparisonMode](#getComparisonMode--) | Obtiene y establece un modo de comparación. El valor predeterminado es {@link ComparisonMode#IgnoreSpaces}. |
| [getDeleteColor](#getDeleteColor--) | Obtiene el color utilizado para marcar el contenido eliminado durante una comparación lado a lado. Esta propiedad define la representación visual de las eliminaciones en el resultado de la comparación. |
| [getExcludeAreas1](#getExcludeAreas1--) | Obtenga y establezca las áreas de exclusión. Se utiliza para la primera página o documento en el método de comparación. Esta opción puede configurarse junto con {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opción no puede configurarse junto con la opción {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}). |
| [getExcludeAreas2](#getExcludeAreas2--) | Obtenga y establezca las áreas de exclusión. Se utiliza para la segunda página o documento en el método de comparación. Esta opción puede configurarse junto con {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opción no puede configurarse junto con la opción {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). |
| [getExcludeTables](#getExcludeTables--) | Obtenga y establezca la opción que determina si las tablas se excluyen de la comparación. Esta opción no puede configurarse junto con {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) y {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). El valor predeterminado es {@code false}. |
| [getInsertColor](#getInsertColor--) | Obtiene el color utilizado para marcar el contenido insertado durante una comparación lado a lado. Esta propiedad define la representación visual de la inserción en el resultado de la comparación. |
| [setAdditionalChangeMarks](#setAdditionalChangeMarks-boolean-) | Obtenga y establezca la propiedad que determina si se muestran marcadores de cambio adicionales. Si se establece, muestra marcas de cambio que no están en la página actual pero sí están presentes en otra página. Si el cambio se ubica entre palabras, la marca puede no estar posicionada exactamente en relación con el carácter de espacio. El valor predeterminado es {@code false}. |
| [setComparisonArea1](#setComparisonArea1-com.aspose.pdf.Rectangle-) | Obtenga y establezca el área de comparación. Se utiliza para la primera página o documento en el método de comparación. Esta opción no puede configurarse junto con las opciones {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) y {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) . |
| [setComparisonArea2](#setComparisonArea2-com.aspose.pdf.Rectangle-) | Obtenga y establezca el área de comparación. Se utiliza para la segunda página o documento en el método de comparación. Esta opción no puede configurarse junto con las opciones {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) y {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) . |
| [setComparisonMode](#setComparisonMode-int-) | Obtiene y establece un modo de comparación. El valor predeterminado es {@link ComparisonMode#IgnoreSpaces}. |
| [setDeleteColor](#setDeleteColor-com.aspose.pdf.Color-) | Establece el color utilizado para marcar el contenido eliminado durante una comparación lado a lado. Esta propiedad define la representación visual de las eliminaciones en el resultado de la comparación. |
| [setExcludeAreas1](#setExcludeAreas1-com.aspose.pdf.Rectangle:A-) | Obtenga y establezca las áreas de exclusión. Se utiliza para la primera página o documento en el método de comparación. Esta opción puede configurarse junto con {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opción no puede configurarse junto con la opción {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}). |
| [setExcludeAreas2](#setExcludeAreas2-com.aspose.pdf.Rectangle:A-) | Obtenga y establezca las áreas de exclusión. Se utiliza para la segunda página o documento en el método de comparación. Esta opción puede configurarse junto con {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opción no puede configurarse junto con la opción {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). |
| [setExcludeTables](#setExcludeTables-boolean-) | Obtenga y establezca la opción que determina si las tablas se excluyen de la comparación. Esta opción no puede configurarse junto con {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) y {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). El valor predeterminado es {@code false}. |
| [setInsertColor](#setInsertColor-com.aspose.pdf.Color-) | Establece el color utilizado para marcar el contenido insertado durante una comparación lado a lado. Esta propiedad define la representación visual de la inserción en el resultado de la comparación. |
| [setVentureLicense](#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-) |  |

### SideBySideComparisonOptions {#SideBySideComparisonOptions--}
```
public SideBySideComparisonOptions()
```

Crea una instancia de la clase {@link SideBySideComparisonOptions}.

### getAdditionalChangeMarks {#getAdditionalChangeMarks--}
```
public final boolean getAdditionalChangeMarks()
```

Obtenga y establezca la propiedad que determina si se muestran marcadores de cambio adicionales. Si se establece, muestra marcas de cambio que no están en la página actual pero sí están presentes en otra página. Si el cambio se ubica entre palabras, la marca puede no estar posicionada exactamente en relación con el carácter de espacio. El valor predeterminado es {@code false}.

**Returns:**
valor booleano

### getComparisonArea1 {#getComparisonArea1--}
```
public final Rectangle getComparisonArea1()
```

Obtenga y establezca el área de comparación. Se utiliza para la primera página o documento en el método de comparación. Esta opción no puede configurarse junto con las opciones {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) y {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) .

**Returns:**
Instancia de Rectangle

### getComparisonArea2 {#getComparisonArea2--}
```
public final Rectangle getComparisonArea2()
```

Obtenga y establezca el área de comparación. Se utiliza para la segunda página o documento en el método de comparación. Esta opción no puede configurarse junto con las opciones {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) y {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) .

**Returns:**
Instancia de Rectangle

### getComparisonMode {#getComparisonMode--}
```
public final int getComparisonMode()
```

Obtiene y establece un modo de comparación. El valor predeterminado es {@link ComparisonMode#IgnoreSpaces}.

**Returns:**
Elemento ComparisonMode

### getDeleteColor {#getDeleteColor--}
```
public final Color getDeleteColor()
```

Obtiene el color utilizado para marcar el contenido eliminado durante una comparación lado a lado. Esta propiedad define la representación visual de las eliminaciones en el resultado de la comparación.

**Returns:**
el color utilizado para marcar el contenido eliminado durante una comparación lado a lado.

### getExcludeAreas1 {#getExcludeAreas1--}
```
public final Rectangle [] getExcludeAreas1()
```

Obtenga y establezca las áreas de exclusión. Se utiliza para la primera página o documento en el método de comparación. Esta opción puede configurarse junto con {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opción no puede configurarse junto con la opción {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}).

**Returns:**
matriz de instancias de Rectangle

### getExcludeAreas2 {#getExcludeAreas2--}
```
public final Rectangle [] getExcludeAreas2()
```

Obtenga y establezca las áreas de exclusión. Se utiliza para la segunda página o documento en el método de comparación. Esta opción puede configurarse junto con {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opción no puede configurarse junto con la opción {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}).

**Returns:**
matriz de instancias de Rectangle

### getExcludeTables {#getExcludeTables--}
```
public final boolean getExcludeTables()
```

Obtenga y establezca la opción que determina si las tablas se excluyen de la comparación. Esta opción no puede configurarse junto con {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) y {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). El valor predeterminado es {@code false}.

**Returns:**
valor booleano

### getInsertColor {#getInsertColor--}
```
public final Color getInsertColor()
```

Obtiene el color utilizado para marcar el contenido insertado durante una comparación lado a lado. Esta propiedad define la representación visual de la inserción en el resultado de la comparación.

**Returns:**
el color utilizado para marcar el contenido insertado durante una comparación lado a lado.

### setAdditionalChangeMarks {#setAdditionalChangeMarks-boolean-}
```
public final void setAdditionalChangeMarks(boolean value)
```

Obtenga y establezca la propiedad que determina si se muestran marcadores de cambio adicionales. Si se establece, muestra marcas de cambio que no están en la página actual pero sí están presentes en otra página. Si el cambio se ubica entre palabras, la marca puede no estar posicionada exactamente en relación con el carácter de espacio. El valor predeterminado es {@code false}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setComparisonArea1 {#setComparisonArea1-com.aspose.pdf.Rectangle-}
Obtenga y establezca el área de comparación. Se utiliza para la primera página o documento en el método de comparación. Esta opción no puede configurarse junto con las opciones {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) y {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) .

### setComparisonArea2 {#setComparisonArea2-com.aspose.pdf.Rectangle-}
Obtenga y establezca el área de comparación. Se utiliza para la segunda página o documento en el método de comparación. Esta opción no puede configurarse junto con las opciones {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) y {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) .

### setComparisonMode {#setComparisonMode-int-}
```
public final void setComparisonMode(int value)
```

Obtiene y establece un modo de comparación. El valor predeterminado es {@link ComparisonMode#IgnoreSpaces}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Elemento ComparisonMode |

### setDeleteColor {#setDeleteColor-com.aspose.pdf.Color-}
Establece el color utilizado para marcar el contenido eliminado durante una comparación lado a lado. Esta propiedad define la representación visual de las eliminaciones en el resultado de la comparación.

### setExcludeAreas1 {#setExcludeAreas1-com.aspose.pdf.Rectangle:A-}
Obtenga y establezca las áreas de exclusión. Se utiliza para la primera página o documento en el método de comparación. Esta opción puede configurarse junto con {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opción no puede configurarse junto con la opción {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}).

### setExcludeAreas2 {#setExcludeAreas2-com.aspose.pdf.Rectangle:A-}
Obtenga y establezca las áreas de exclusión. Se utiliza para la segunda página o documento en el método de comparación. Esta opción puede configurarse junto con {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Esta opción no puede configurarse junto con la opción {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}).

### setExcludeTables {#setExcludeTables-boolean-}
```
public final void setExcludeTables(boolean value)
```

Obtenga y establezca la opción que determina si las tablas se excluyen de la comparación. Esta opción no puede configurarse junto con {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) y {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). El valor predeterminado es {@code false}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setInsertColor {#setInsertColor-com.aspose.pdf.Color-}
Establece el color utilizado para marcar el contenido insertado durante una comparación lado a lado. Esta propiedad define la representación visual de la inserción en el resultado de la comparación.

### setVentureLicense {#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-}
