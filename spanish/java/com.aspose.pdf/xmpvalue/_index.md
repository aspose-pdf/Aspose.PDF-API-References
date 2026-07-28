---
title: "XmpValue"
linktitle: "XmpValue"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa el valor XMP"
type: docs
weight: 5750
url: /es/java/com.aspose.pdf/xmpvalue/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpValue

```
public class XmpValue extends Object
```

Representa el valor XMP

## Constructores

| Constructor | Descripción |
| --- | --- |
| [XmpValue](#XmpValue-java.util.Date-) | Constructor para valor de fecha y hora. |
| [XmpValue](#XmpValue-double-) | Constructor para valor de punto flotante. |
| [XmpValue](#XmpValue-int-) | Constructor para valor entero. |
| [XmpValue](#XmpValue-java.lang.Object-) |  |
| [XmpValue](#XmpValue-java.lang.String-) | Constructor para valor de cadena. |
| [XmpValue](#XmpValue-java.lang.String-boolean-) | Inicializa un nuevo valor XMP de cadena. |
| [XmpValue](#XmpValue-com.aspose.pdf.XmpValue:A-) | Constructor para valor de matriz. |

## Métodos

| Método | Descripción |
| --- | --- |
| [isArray](#isArray--) | Devuelve true si XmpValue es una matriz. |
| [isDateTime](#isDateTime--) | Devuelve true si el valor es DateTime. |
| [isDouble](#isDouble--) | Devuelve true si el valor es de punto flotante. |
| [isField](#isField--) | Devuelve true si XmpValue es un campo. |
| [isInteger](#isInteger--) | Devuelve true si el valor es entero. |
| [isNamedValue](#isNamedValue--) | Devuelve true si XmpValue es un valor nombrado. |
| [isNamedValues](#isNamedValues--) | Devuelve true si XmpValue representa valores nombrados. |
| [isRaw](#isRaw--) | El valor no es compatible/desconocido y se proporciona código XML sin procesar. |
| [isString](#isString--) | Devuelve true si el valor es una cadena. |
| [isStructure](#isStructure--) | Devuelve true si XmpValue representa una estructura. |
| [to_](#to_-com.aspose.pdf.XmpValue-) | Convierte XmpValue en una matriz. |
| [to_Array](#to_Array-com.aspose.pdf.XmpValue-) | Convierte XmpValue a una matriz. |
| [to_Generic](#to_Generic-com.aspose.pdf.XmpValue-) | Obtener matriz KeyValuePair |
| [to_KeyValuePair](#to_KeyValuePair-com.aspose.pdf.XmpValue-) | Convierte XmpValue a un valor nombrado. |
| [to_String](#to_String-com.aspose.pdf.XmpValue-) | Convierte XmpValue en una cadena. |
| [to_XmpValue](#to_XmpValue-java.util.Date-) | Convierte DateTime en XmpValue. |
| [to_XmpValue](#to_XmpValue-double-) | Convierte double en XmpValue. |
| [to_XmpValue](#to_XmpValue-int-) | Convierte entero en XmpValue. |
| [to_XmpValue](#to_XmpValue-java.lang.Object:A-) | Convierte matriz a XmpValue. |
| [to_XmpValue](#to_XmpValue-java.lang.String-) | Convierte cadena a XmpValue. |
| [toArray](#toArray--) | Devuelve una matriz. |
| [toDateTime](#toDateTime--) | Convierte a fecha y hora. |
| [toDateTimeOffset](#toDateTimeOffset--) | Convierte el valor XMP actual a una representación {@link DateTimeOffset}. |
| [toDictionary](#toDictionary--) | Devuelve un diccionario que contiene valores nombrados. |
| [toDouble](#toDouble--) | Convierte a doble. |
| [toField](#toField--) | Devuelve el valor XMP como campo XMP. |
| [toInteger](#toInteger--) | Convierte a entero. |
| [toNamedValue](#toNamedValue--) | Devuelve el valor XMP como valor nombrado. |
| [toNamedValueInternal](#toNamedValueInternal--) | Solo para uso interno |
| [toNamedValues](#toNamedValues--) | Devuelve el valor XMP como colección de valores nombrados. |
| [toNamedValuesInternal](#toNamedValuesInternal--) |  |
| [toRaw](#toRaw--) | Código XML sin procesar para valores desconocidos/no compatibles. |
| [toString](#toString--) | Devuelve la representación en cadena de XmpValue. |
| [toString](#toString-com.aspose.ms.System.IFormatProvider-) | Devuelve la representación en cadena de XmpValue. |
| [toStringValue](#toStringValue--) | Convierte a cadena. |
| [toStructure](#toStructure--) | Devuelve el valor XMP como estructura (conjunto de campos). |

### XmpValue {#XmpValue-java.util.Date-}
Constructor para valor de fecha y hora.

### XmpValue {#XmpValue-double-}
```
public XmpValue(double value)
```

Constructor para valor de punto flotante.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Valor doble. |

### XmpValue {#XmpValue-int-}
```
public XmpValue(int value)
```

Constructor para valor entero.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Valor entero. |

### XmpValue {#XmpValue-java.lang.Object-}


### XmpValue {#XmpValue-java.lang.String-}
Constructor para valor de cadena.

### XmpValue {#XmpValue-java.lang.String-boolean-}
Inicializa un nuevo valor XMP de cadena.

### XmpValue {#XmpValue-com.aspose.pdf.XmpValue:A-}
Constructor para valor de matriz.

### isArray {#isArray--}
```
public boolean isArray()
```

Devuelve true si XmpValue es una matriz.

**Returns:**
valor booleano

### isDateTime {#isDateTime--}
```
public boolean isDateTime()
```

Devuelve true si el valor es DateTime.

**Returns:**
valor booleano

### isDouble {#isDouble--}
```
public boolean isDouble()
```

Devuelve true si el valor es de punto flotante.

**Returns:**
valor booleano

### isField {#isField--}
```
public boolean isField()
```

Devuelve true si XmpValue es un campo.

**Returns:**
valor booleano

### isInteger {#isInteger--}
```
public boolean isInteger()
```

Devuelve true si el valor es entero.

**Returns:**
valor booleano

### isNamedValue {#isNamedValue--}
```
public boolean isNamedValue()
```

Devuelve true si XmpValue es un valor nombrado.

**Returns:**
valor booleano

### isNamedValues {#isNamedValues--}
```
public boolean isNamedValues()
```

Devuelve true si XmpValue representa valores nombrados.

**Returns:**
valor booleano

### isRaw {#isRaw--}
```
public final boolean isRaw()
```

El valor no es compatible/desconocido y se proporciona código XML sin procesar.

**Returns:**
Verdadero si el valor se devuelve como datos sin procesar.

### isString {#isString--}
```
public boolean isString()
```

Devuelve true si el valor es una cadena.

**Returns:**
valor booleano

### isStructure {#isStructure--}
```
public boolean isStructure()
```

Devuelve true si XmpValue representa una estructura.

**Returns:**
valor booleano

### to_ {#to_-com.aspose.pdf.XmpValue-}
Convierte XmpValue en una matriz.

### to_Array {#to_Array-com.aspose.pdf.XmpValue-}
Convierte XmpValue a una matriz.

### to_Generic {#to_Generic-com.aspose.pdf.XmpValue-}
Obtener matriz KeyValuePair

### to_KeyValuePair {#to_KeyValuePair-com.aspose.pdf.XmpValue-}
Convierte XmpValue a un valor nombrado.

### to_String {#to_String-com.aspose.pdf.XmpValue-}
Convierte XmpValue en una cadena.

### to_XmpValue {#to_XmpValue-java.util.Date-}
Convierte DateTime en XmpValue.

### to_XmpValue {#to_XmpValue-double-}
```
public static XmpValue to_XmpValue(double value)
```

Convierte double en XmpValue.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor doble (Valor a convertir) |

**Returns:**
instancia de XmpValue

### to_XmpValue {#to_XmpValue-int-}
```
public static XmpValue to_XmpValue(int value)
```

Convierte entero en XmpValue.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int (Valor a convertir) |

**Returns:**
instancia de XmpValue

### to_XmpValue {#to_XmpValue-java.lang.Object:A-}
Convierte matriz a XmpValue.

### to_XmpValue {#to_XmpValue-java.lang.String-}
Convierte cadena a XmpValue.

### toArray {#toArray--}
```
public XmpValue [] toArray()
```

Devuelve una matriz.

**Returns:**
matriz de XmpValue

### toDateTime {#toDateTime--}
```
public Date toDateTime()
```

Convierte a fecha y hora.

**Returns:**
instancia de Date

### toDateTimeOffset {#toDateTimeOffset--}
```
public final com.aspose.ms.System.DateTimeOffset toDateTimeOffset()
```

Convierte el valor XMP actual a una representación {@link DateTimeOffset}.

**Returns:**
Un {@link DateTimeOffset} que representa el valor XMP actual.

### toDictionary {#toDictionary--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary< String , XmpValue > toDictionary()
```

Devuelve un diccionario que contiene valores nombrados.

**Returns:**
Diccionario

### toDouble {#toDouble--}
```
public double toDouble()
```

Convierte a doble.

**Returns:**
valor double

### toField {#toField--}
```
public XmpField toField()
```

Devuelve el valor XMP como campo XMP.

**Returns:**
Instancia de XmpField

### toInteger {#toInteger--}
```
public int toInteger()
```

Convierte a entero.

**Returns:**
valor int

### toNamedValue {#toNamedValue--}
```
public HashMap < String , XmpValue > toNamedValue()
```

Devuelve el valor XMP como valor nombrado.

**Returns:**
(Valor nombrado) instancia de HashMap con String Key y valor XmpValue

### toNamedValueInternal {#toNamedValueInternal--}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue > toNamedValueInternal()
```

Solo para uso interno

**Returns:**
Solo para uso interno

### toNamedValues {#toNamedValues--}
```
public HashMap < String , XmpValue > toNamedValues()
```

Devuelve el valor XMP como colección de valores nombrados.

**Returns:**
(Valor de colección nombrada) instancia de HashMap con String Key y valor XmpValue

### toNamedValuesInternal {#toNamedValuesInternal--}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >[] toNamedValuesInternal()
```



### toRaw {#toRaw--}
```
public final com.aspose.ms.System.Xml.XmlNode toRaw()
```

Código XML sin procesar para valores desconocidos/no compatibles.

**Returns:**
Nodo XML para este valor.

### toString {#toString--}
```
public String toString()
```

Devuelve la representación en cadena de XmpValue.

**Returns:**
Representación de cadena

### toString {#toString-com.aspose.ms.System.IFormatProvider-}
Devuelve la representación en cadena de XmpValue.

**Returns:**
Representación de cadena

### toStringValue {#toStringValue--}
```
public String toStringValue()
```

Convierte a cadena.

**Returns:**
valor String

### toStructure {#toStructure--}
```
public XmpField [] toStructure()
```

Devuelve el valor XMP como estructura (conjunto de campos).

**Returns:**
matriz de XmpField
