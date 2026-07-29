---
title: "Measure.NumberFormat"
linktitle: "Measure.NumberFormat"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Formato numérico para medida."
type: docs
weight: 2940
url: /es/java/com.aspose.pdf/measure.numberformat/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Measure.NumberFormat

```
public static class Measure.NumberFormat extends Object
```

Formato numérico para medida.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [NumberFormat](#NumberFormat-com.aspose.pdf.Measure-) | Constructor de la clase NumberFormat. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getAfterText](#getAfterText--) | Texto que se concatenará después de la etiqueta |
| [getBeforeText](#getBeforeText--) | Texto que se concatenará a la izquierda de la etiqueta. |
| [getConvresionFactor](#getConvresionFactor--) | El factor de conversión utilizado para multiplicar un valor en unidades parciales del elemento anterior del arreglo de formatos numéricos para obtener un valor en las unidades de este formato numérico. |
| [getDenominator](#getDenominator--) | Si FractionDisplayment es ShowAsFraction, este valor es el denominador de la fracción. El valor predeterminado es 16. |
| [getFractionDisplayment](#getFractionDisplayment--) | De qué manera se muestran los valores fraccionarios. |
| [getFractionSeparator](#getFractionSeparator--) | Texto que se utilizará como posición decimal al mostrar valores numéricos. Una cadena vacía indica que se usará el valor predeterminado. El predeterminado es el carácter punto. |
| [getPrecision](#getPrecision--) | Si FractionDisplayment es ShowAsDecimal, este valor es la precisión del valor fraccionario; debe ser múltiplo de 10. El predeterminado es 100. |
| [getThousandsSeparator](#getThousandsSeparator--) | Texto que se utilizará entre los órdenes de miles al mostrar valores numéricos. Una cadena vacía indica que no se añadirá texto. El predeterminado es la coma. |
| [getUnitLabel](#getUnitLabel--) | Una cadena de texto que especifica una etiqueta para mostrar las unidades. |
| [isForceDenominator](#isForceDenominator--) | Si FractionDisplayment es ShowAsFraction, este valor determina si la fracción se reduce o no. Si el valor es verdadero, la fracción no se reducirá. |
| [setAfterText](#setAfterText-java.lang.String-) | Texto que se concatenará después de la etiqueta |
| [setBeforeText](#setBeforeText-java.lang.String-) | Texto que se concatenará a la izquierda de la etiqueta. |
| [setConvresionFactor](#setConvresionFactor-double-) | El factor de conversión utilizado para multiplicar un valor en unidades parciales del elemento anterior del arreglo de formatos numéricos para obtener un valor en las unidades de este formato numérico. |
| [setDenominator](#setDenominator-int-) | Si FractionDisplayment es ShowAsFraction, este valor es el denominador de la fracción. El valor predeterminado es 16. |
| [setForceDenominator](#setForceDenominator-boolean-) | Si FractionDisplayment es ShowAsFraction, este valor determina si la fracción se reduce o no. Si el valor es verdadero, la fracción no se reducirá. |
| [setFractionDisplayment](#setFractionDisplayment-com.aspose.pdf.Measure.NumberFormat.FractionStyle-) | De qué manera se muestran los valores fraccionarios. |
| [setFractionSeparator](#setFractionSeparator-java.lang.String-) | Texto que se utilizará como posición decimal al mostrar valores numéricos. Una cadena vacía indica que se usará el valor predeterminado. El predeterminado es el carácter punto. |
| [setPrecision](#setPrecision-int-) | Si FractionDisplayment es ShowAsDecimal, este valor es la precisión del valor fraccionario; debe ser múltiplo de 10. El predeterminado es 100. |
| [setThousandsSeparator](#setThousandsSeparator-java.lang.String-) | Texto que se utilizará entre los órdenes de miles al mostrar valores numéricos. Una cadena vacía indica que no se añadirá texto. El predeterminado es la coma. |
| [setUnitLabel](#setUnitLabel-java.lang.String-) |  |

### NumberFormat {#NumberFormat-com.aspose.pdf.Measure-}
Constructor de la clase NumberFormat.

### getAfterText {#getAfterText--}
```
public String getAfterText()
```

Texto que se concatenará después de la etiqueta

**Returns:**
Objeto String

### getBeforeText {#getBeforeText--}
```
public String getBeforeText()
```

Texto que se concatenará a la izquierda de la etiqueta.

**Returns:**
Objeto String

### getConvresionFactor {#getConvresionFactor--}
```
public double getConvresionFactor()
```

El factor de conversión utilizado para multiplicar un valor en unidades parciales del elemento anterior del arreglo de formatos numéricos para obtener un valor en las unidades de este formato numérico.

**Returns:**
valor double

### getDenominator {#getDenominator--}
```
public int getDenominator()
```

Si FractionDisplayment es ShowAsFraction, este valor es el denominador de la fracción. El valor predeterminado es 16.

**Returns:**
valor int

### getFractionDisplayment {#getFractionDisplayment--}
```
public Measure.NumberFormat.FractionStyle getFractionDisplayment()
```

De qué manera se muestran los valores fraccionarios.

**Returns:**
Valor FractionStyle @see FractionStyle

### getFractionSeparator {#getFractionSeparator--}
```
public String getFractionSeparator()
```

Texto que se utilizará como posición decimal al mostrar valores numéricos. Una cadena vacía indica que se usará el valor predeterminado. El predeterminado es el carácter punto.

**Returns:**
valor String

### getPrecision {#getPrecision--}
```
public int getPrecision()
```

Si FractionDisplayment es ShowAsDecimal, este valor es la precisión del valor fraccionario; debe ser múltiplo de 10. El predeterminado es 100.

**Returns:**
valor int

### getThousandsSeparator {#getThousandsSeparator--}
```
public String getThousandsSeparator()
```

Texto que se utilizará entre los órdenes de miles al mostrar valores numéricos. Una cadena vacía indica que no se añadirá texto. El predeterminado es la coma.

**Returns:**
valor String

### getUnitLabel {#getUnitLabel--}
```
public String getUnitLabel()
```

Una cadena de texto que especifica una etiqueta para mostrar las unidades.

**Returns:**
Objeto String

### isForceDenominator {#isForceDenominator--}
```
public boolean isForceDenominator()
```

Si FractionDisplayment es ShowAsFraction, este valor determina si la fracción se reduce o no. Si el valor es verdadero, la fracción no se reducirá.

**Returns:**
valor booleano

### setAfterText {#setAfterText-java.lang.String-}
Texto que se concatenará después de la etiqueta

### setBeforeText {#setBeforeText-java.lang.String-}
Texto que se concatenará a la izquierda de la etiqueta.

### setConvresionFactor {#setConvresionFactor-double-}
```
public void setConvresionFactor(double value)
```

El factor de conversión utilizado para multiplicar un valor en unidades parciales del elemento anterior del arreglo de formatos numéricos para obtener un valor en las unidades de este formato numérico.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setDenominator {#setDenominator-int-}
```
public void setDenominator(int value)
```

Si FractionDisplayment es ShowAsFraction, este valor es el denominador de la fracción. El valor predeterminado es 16.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setForceDenominator {#setForceDenominator-boolean-}
```
public void setForceDenominator(boolean value)
```

Si FractionDisplayment es ShowAsFraction, este valor determina si la fracción se reduce o no. Si el valor es verdadero, la fracción no se reducirá.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setFractionDisplayment {#setFractionDisplayment-com.aspose.pdf.Measure.NumberFormat.FractionStyle-}
De qué manera se muestran los valores fraccionarios.

### setFractionSeparator {#setFractionSeparator-java.lang.String-}
Texto que se utilizará como posición decimal al mostrar valores numéricos. Una cadena vacía indica que se usará el valor predeterminado. El predeterminado es el carácter punto.

### setPrecision {#setPrecision-int-}
```
public void setPrecision(int value)
```

Si FractionDisplayment es ShowAsDecimal, este valor es la precisión del valor fraccionario; debe ser múltiplo de 10. El predeterminado es 100.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setThousandsSeparator {#setThousandsSeparator-java.lang.String-}
Texto que se utilizará entre los órdenes de miles al mostrar valores numéricos. Una cadena vacía indica que no se añadirá texto. El predeterminado es la coma.

### setUnitLabel {#setUnitLabel-java.lang.String-}
