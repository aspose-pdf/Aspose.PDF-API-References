---
title: "XmpValue"
linktitle: "XmpValue"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta il valore XMP."
type: docs
weight: 5750
url: /it/java/com.aspose.pdf/xmpvalue/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpValue

```
public class XmpValue extends Object
```

Rappresenta il valore XMP.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XmpValue](#XmpValue-java.util.Date-) | Costruttore per valore di data e ora. |
| [XmpValue](#XmpValue-double-) | Costruttore per valore a virgola mobile. |
| [XmpValue](#XmpValue-int-) | Costruttore per valore intero. |
| [XmpValue](#XmpValue-java.lang.Object-) |  |
| [XmpValue](#XmpValue-java.lang.String-) | Costruttore per valore stringa. |
| [XmpValue](#XmpValue-java.lang.String-boolean-) | Inizializza un nuovo valore XMP stringa. |
| [XmpValue](#XmpValue-com.aspose.pdf.XmpValue:A-) | Costruttore per valore array. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isArray](#isArray--) | Restituisce true se XmpValue è un array. |
| [isDateTime](#isDateTime--) | Restituisce true se il valore è DateTime. |
| [isDouble](#isDouble--) | Restituisce true se il valore è un numero a virgola mobile. |
| [isField](#isField--) | Restituisce true se XmpValue è un campo. |
| [isInteger](#isInteger--) | Restituisce true se il valore è intero. |
| [isNamedValue](#isNamedValue--) | Restituisce true se XmpValue è un valore nominato. |
| [isNamedValues](#isNamedValues--) | Restituisce true se XmpValue rappresenta valori nominati. |
| [isRaw](#isRaw--) | Il valore non è supportato/sconosciuto e viene fornito il codice XML grezzo. |
| [isString](#isString--) | Restituisce true se il valore è una stringa. |
| [isStructure](#isStructure--) | Restituisce true se XmpValue rappresenta una struttura. |
| [to_](#to_-com.aspose.pdf.XmpValue-) | Converte XmpValue in un array. |
| [to_Array](#to_Array-com.aspose.pdf.XmpValue-) | Converte XmpValue in un array. |
| [to_Generic](#to_Generic-com.aspose.pdf.XmpValue-) | Ottieni l'array KeyValuePair |
| [to_KeyValuePair](#to_KeyValuePair-com.aspose.pdf.XmpValue-) | Converte XmpValue in un valore nominato. |
| [to_String](#to_String-com.aspose.pdf.XmpValue-) | Converte XmpValue in una stringa. |
| [to_XmpValue](#to_XmpValue-java.util.Date-) | Converte DateTime in XmpValue. |
| [to_XmpValue](#to_XmpValue-double-) | Converte double in XmpValue. |
| [to_XmpValue](#to_XmpValue-int-) | Converte intero in XmpValue. |
| [to_XmpValue](#to_XmpValue-java.lang.Object:A-) | Converte array in XmpValue. |
| [to_XmpValue](#to_XmpValue-java.lang.String-) | Converte stringa in XmpValue. |
| [toArray](#toArray--) | Restituisce un array. |
| [toDateTime](#toDateTime--) | Converte in data e ora. |
| [toDateTimeOffset](#toDateTimeOffset--) | Converte il valore XMP corrente in una rappresentazione {@link DateTimeOffset}. |
| [toDictionary](#toDictionary--) | Restituisce un dizionario che contiene valori denominati. |
| [toDouble](#toDouble--) | Converte in double. |
| [toField](#toField--) | Restituisce il valore XMP come campo XMP. |
| [toInteger](#toInteger--) | Converte in integer. |
| [toNamedValue](#toNamedValue--) | Restituisce il valore XMP come valore denominato. |
| [toNamedValueInternal](#toNamedValueInternal--) | Solo per uso interno |
| [toNamedValues](#toNamedValues--) | Restituisce il valore XMP come raccolta di valori denominati. |
| [toNamedValuesInternal](#toNamedValuesInternal--) |  |
| [toRaw](#toRaw--) | Codice XML grezzo per valori sconosciuti/non supportati. |
| [toString](#toString--) | Restituisce la rappresentazione stringa di XmpValue. |
| [toString](#toString-com.aspose.ms.System.IFormatProvider-) | Restituisce la rappresentazione stringa di XmpValue. |
| [toStringValue](#toStringValue--) | Converte in stringa. |
| [toStructure](#toStructure--) | Restituisce il valore XMP come struttura (insieme di campi). |

### XmpValue {#XmpValue-java.util.Date-}
Costruttore per valore di data e ora.

### XmpValue {#XmpValue-double-}
```
public XmpValue(double value)
```

Costruttore per valore a virgola mobile.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Valore double. |

### XmpValue {#XmpValue-int-}
```
public XmpValue(int value)
```

Costruttore per valore intero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Valore integer. |

### XmpValue {#XmpValue-java.lang.Object-}


### XmpValue {#XmpValue-java.lang.String-}
Costruttore per valore stringa.

### XmpValue {#XmpValue-java.lang.String-boolean-}
Inizializza un nuovo valore XMP stringa.

### XmpValue {#XmpValue-com.aspose.pdf.XmpValue:A-}
Costruttore per valore array.

### isArray {#isArray--}
```
public boolean isArray()
```

Restituisce true se XmpValue è un array.

**Returns:**
valore booleano

### isDateTime {#isDateTime--}
```
public boolean isDateTime()
```

Restituisce true se il valore è DateTime.

**Returns:**
valore booleano

### isDouble {#isDouble--}
```
public boolean isDouble()
```

Restituisce true se il valore è un numero a virgola mobile.

**Returns:**
valore booleano

### isField {#isField--}
```
public boolean isField()
```

Restituisce true se XmpValue è un campo.

**Returns:**
valore booleano

### isInteger {#isInteger--}
```
public boolean isInteger()
```

Restituisce true se il valore è intero.

**Returns:**
valore booleano

### isNamedValue {#isNamedValue--}
```
public boolean isNamedValue()
```

Restituisce true se XmpValue è un valore nominato.

**Returns:**
valore booleano

### isNamedValues {#isNamedValues--}
```
public boolean isNamedValues()
```

Restituisce true se XmpValue rappresenta valori nominati.

**Returns:**
valore booleano

### isRaw {#isRaw--}
```
public final boolean isRaw()
```

Il valore non è supportato/sconosciuto e viene fornito il codice XML grezzo.

**Returns:**
Vero se il valore è restituito come dati grezzi.

### isString {#isString--}
```
public boolean isString()
```

Restituisce true se il valore è una stringa.

**Returns:**
valore booleano

### isStructure {#isStructure--}
```
public boolean isStructure()
```

Restituisce true se XmpValue rappresenta una struttura.

**Returns:**
valore booleano

### to_ {#to_-com.aspose.pdf.XmpValue-}
Converte XmpValue in un array.

### to_Array {#to_Array-com.aspose.pdf.XmpValue-}
Converte XmpValue in un array.

### to_Generic {#to_Generic-com.aspose.pdf.XmpValue-}
Ottieni l'array KeyValuePair

### to_KeyValuePair {#to_KeyValuePair-com.aspose.pdf.XmpValue-}
Converte XmpValue in un valore nominato.

### to_String {#to_String-com.aspose.pdf.XmpValue-}
Converte XmpValue in una stringa.

### to_XmpValue {#to_XmpValue-java.util.Date-}
Converte DateTime in XmpValue.

### to_XmpValue {#to_XmpValue-double-}
```
public static XmpValue to_XmpValue(double value)
```

Converte double in XmpValue.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double (Valore da convertire) |

**Returns:**
istanza XmpValue

### to_XmpValue {#to_XmpValue-int-}
```
public static XmpValue to_XmpValue(int value)
```

Converte intero in XmpValue.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int (Valore da convertire) |

**Returns:**
istanza XmpValue

### to_XmpValue {#to_XmpValue-java.lang.Object:A-}
Converte array in XmpValue.

### to_XmpValue {#to_XmpValue-java.lang.String-}
Converte stringa in XmpValue.

### toArray {#toArray--}
```
public XmpValue [] toArray()
```

Restituisce un array.

**Returns:**
array XmpValue

### toDateTime {#toDateTime--}
```
public Date toDateTime()
```

Converte in data e ora.

**Returns:**
istanza Date

### toDateTimeOffset {#toDateTimeOffset--}
```
public final com.aspose.ms.System.DateTimeOffset toDateTimeOffset()
```

Converte il valore XMP corrente in una rappresentazione {@link DateTimeOffset}.

**Returns:**
Un {@link DateTimeOffset} che rappresenta il valore XMP corrente.

### toDictionary {#toDictionary--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary< String , XmpValue > toDictionary()
```

Restituisce un dizionario che contiene valori denominati.

**Returns:**
Dizionario

### toDouble {#toDouble--}
```
public double toDouble()
```

Converte in double.

**Returns:**
valore double

### toField {#toField--}
```
public XmpField toField()
```

Restituisce il valore XMP come campo XMP.

**Returns:**
Istanza XmpField

### toInteger {#toInteger--}
```
public int toInteger()
```

Converte in integer.

**Returns:**
valore int

### toNamedValue {#toNamedValue--}
```
public HashMap < String , XmpValue > toNamedValue()
```

Restituisce il valore XMP come valore denominato.

**Returns:**
(Valore denominato) istanza HashMap con chiave String e valore XmpValue

### toNamedValueInternal {#toNamedValueInternal--}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue > toNamedValueInternal()
```

Solo per uso interno

**Returns:**
Solo per uso interno

### toNamedValues {#toNamedValues--}
```
public HashMap < String , XmpValue > toNamedValues()
```

Restituisce il valore XMP come raccolta di valori denominati.

**Returns:**
(Valore di collezione denominato) istanza HashMap con chiave String e valore XmpValue

### toNamedValuesInternal {#toNamedValuesInternal--}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >[] toNamedValuesInternal()
```



### toRaw {#toRaw--}
```
public final com.aspose.ms.System.Xml.XmlNode toRaw()
```

Codice XML grezzo per valori sconosciuti/non supportati.

**Returns:**
Nodo XML per questo valore.

### toString {#toString--}
```
public String toString()
```

Restituisce la rappresentazione stringa di XmpValue.

**Returns:**
Rappresentazione della stringa

### toString {#toString-com.aspose.ms.System.IFormatProvider-}
Restituisce la rappresentazione stringa di XmpValue.

**Returns:**
Rappresentazione della stringa

### toStringValue {#toStringValue--}
```
public String toStringValue()
```

Converte in stringa.

**Returns:**
valore String

### toStructure {#toStructure--}
```
public XmpField [] toStructure()
```

Restituisce il valore XMP come struttura (insieme di campi).

**Returns:**
array XmpField
