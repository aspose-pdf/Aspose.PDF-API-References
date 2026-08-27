---
title: "XmpValue"
linktitle: "XmpValue"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar XMP-värde"
type: docs
weight: 5750
url: /sv/java/com.aspose.pdf/xmpvalue/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpValue

```
public class XmpValue extends Object
```

Representerar XMP-värde

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [XmpValue](#XmpValue-java.util.Date-) | Konstruktor för datum‑tidsvärde. |
| [XmpValue](#XmpValue-double-) | Konstruktor för flyttal‑värde. |
| [XmpValue](#XmpValue-int-) | Konstruktor för heltalsvärde. |
| [XmpValue](#XmpValue-java.lang.Object-) |  |
| [XmpValue](#XmpValue-java.lang.String-) | Konstruktor för strängvärde. |
| [XmpValue](#XmpValue-java.lang.String-boolean-) | Initierar nytt sträng‑XMP‑värde. |
| [XmpValue](#XmpValue-com.aspose.pdf.XmpValue:A-) | Konstruktor för array‑värde. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isArray](#isArray--) | Returnerar true om XmpValue är en array. |
| [isDateTime](#isDateTime--) | Returnerar true om värdet är DateTime. |
| [isDouble](#isDouble--) | Returnerar true om värdet är ett flyttal. |
| [isField](#isField--) | Returnerar true om XmpValue är ett fält. |
| [isInteger](#isInteger--) | Returnerar true om värdet är ett heltal. |
| [isNamedValue](#isNamedValue--) | Returnerar true om XmpValue är ett namngivet värde. |
| [isNamedValues](#isNamedValues--) | Returnerar true om XmpValue representerar namngivna värden. |
| [isRaw](#isRaw--) | Värdet stöds inte/är okänt och rå XML‑kod tillhandahålls. |
| [isString](#isString--) | Returnerar true om värdet är en sträng. |
| [isStructure](#isStructure--) | Returnerar true om XmpValue representerar en struktur. |
| [to_](#to_-com.aspose.pdf.XmpValue-) | Konverterar XmpValue till en array. |
| [to_Array](#to_Array-com.aspose.pdf.XmpValue-) | Konverterar XmpValue till en array. |
| [to_Generic](#to_Generic-com.aspose.pdf.XmpValue-) | Hämta KeyValuePair‑array |
| [to_KeyValuePair](#to_KeyValuePair-com.aspose.pdf.XmpValue-) | Konverterar XmpValue till ett namngivet värde. |
| [to_String](#to_String-com.aspose.pdf.XmpValue-) | Konverterar XmpValue till en sträng. |
| [to_XmpValue](#to_XmpValue-java.util.Date-) | Konverterar DateTime till XmpValue. |
| [to_XmpValue](#to_XmpValue-double-) | Konverterar double till XmpValue. |
| [to_XmpValue](#to_XmpValue-int-) | Konverterar heltal till XmpValue. |
| [to_XmpValue](#to_XmpValue-java.lang.Object:A-) | Konverterar array till XmpValue. |
| [to_XmpValue](#to_XmpValue-java.lang.String-) | Konverterar sträng till XmpValue. |
| [toArray](#toArray--) | Returnerar array. |
| [toDateTime](#toDateTime--) | Konverterar till datumtid. |
| [toDateTimeOffset](#toDateTimeOffset--) | Konverterar det aktuella XMP‑värdet till en {@link DateTimeOffset}-representation. |
| [toDictionary](#toDictionary--) | Returnerar en ordbok som innehåller namngivna värden. |
| [toDouble](#toDouble--) | Konverterar till double. |
| [toField](#toField--) | Returnerar XMP‑värdet som XMP‑fält. |
| [toInteger](#toInteger--) | Konverterar till heltal. |
| [toNamedValue](#toNamedValue--) | Returnerar XMP‑värdet som ett namngivet värde. |
| [toNamedValueInternal](#toNamedValueInternal--) | Endast för intern användning |
| [toNamedValues](#toNamedValues--) | Returnerar XMP‑värdet som en samling av namngivna värden. |
| [toNamedValuesInternal](#toNamedValuesInternal--) |  |
| [toRaw](#toRaw--) | Rå XML‑kod för okända/ej stödda värden. |
| [toString](#toString--) | Returnerar strängrepresentation av XmpValue. |
| [toString](#toString-com.aspose.ms.System.IFormatProvider-) | Returnerar strängrepresentation av XmpValue. |
| [toStringValue](#toStringValue--) | Konverterar till sträng. |
| [toStructure](#toStructure--) | Returnerar XMP‑värdet som en struktur (uppsättning av fält). |

### XmpValue {#XmpValue-java.util.Date-}
Konstruktor för datum‑tidsvärde.

### XmpValue {#XmpValue-double-}
```
public XmpValue(double value)
```

Konstruktor för flyttal‑värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | Double‑värde. |

### XmpValue {#XmpValue-int-}
```
public XmpValue(int value)
```

Konstruktor för heltalsvärde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | Heltalsvärde. |

### XmpValue {#XmpValue-java.lang.Object-}


### XmpValue {#XmpValue-java.lang.String-}
Konstruktor för strängvärde.

### XmpValue {#XmpValue-java.lang.String-boolean-}
Initierar nytt sträng‑XMP‑värde.

### XmpValue {#XmpValue-com.aspose.pdf.XmpValue:A-}
Konstruktor för array‑värde.

### isArray {#isArray--}
```
public boolean isArray()
```

Returnerar true om XmpValue är en array.

**Returns:**
booleskt värde

### isDateTime {#isDateTime--}
```
public boolean isDateTime()
```

Returnerar true om värdet är DateTime.

**Returns:**
booleskt värde

### isDouble {#isDouble--}
```
public boolean isDouble()
```

Returnerar true om värdet är ett flyttal.

**Returns:**
booleskt värde

### isField {#isField--}
```
public boolean isField()
```

Returnerar true om XmpValue är ett fält.

**Returns:**
booleskt värde

### isInteger {#isInteger--}
```
public boolean isInteger()
```

Returnerar true om värdet är ett heltal.

**Returns:**
booleskt värde

### isNamedValue {#isNamedValue--}
```
public boolean isNamedValue()
```

Returnerar true om XmpValue är ett namngivet värde.

**Returns:**
booleskt värde

### isNamedValues {#isNamedValues--}
```
public boolean isNamedValues()
```

Returnerar true om XmpValue representerar namngivna värden.

**Returns:**
booleskt värde

### isRaw {#isRaw--}
```
public final boolean isRaw()
```

Värdet stöds inte/är okänt och rå XML‑kod tillhandahålls.

**Returns:**
Sant om värdet returneras som rådata.

### isString {#isString--}
```
public boolean isString()
```

Returnerar true om värdet är en sträng.

**Returns:**
booleskt värde

### isStructure {#isStructure--}
```
public boolean isStructure()
```

Returnerar true om XmpValue representerar en struktur.

**Returns:**
booleskt värde

### to_ {#to_-com.aspose.pdf.XmpValue-}
Konverterar XmpValue till en array.

### to_Array {#to_Array-com.aspose.pdf.XmpValue-}
Konverterar XmpValue till en array.

### to_Generic {#to_Generic-com.aspose.pdf.XmpValue-}
Hämta KeyValuePair‑array

### to_KeyValuePair {#to_KeyValuePair-com.aspose.pdf.XmpValue-}
Konverterar XmpValue till ett namngivet värde.

### to_String {#to_String-com.aspose.pdf.XmpValue-}
Konverterar XmpValue till en sträng.

### to_XmpValue {#to_XmpValue-java.util.Date-}
Konverterar DateTime till XmpValue.

### to_XmpValue {#to_XmpValue-double-}
```
public static XmpValue to_XmpValue(double value)
```

Konverterar double till XmpValue.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double‑värde (Värde att konvertera) |

**Returns:**
XmpValue‑instans

### to_XmpValue {#to_XmpValue-int-}
```
public static XmpValue to_XmpValue(int value)
```

Konverterar heltal till XmpValue.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde (Värde att konvertera) |

**Returns:**
XmpValue‑instans

### to_XmpValue {#to_XmpValue-java.lang.Object:A-}
Konverterar array till XmpValue.

### to_XmpValue {#to_XmpValue-java.lang.String-}
Konverterar sträng till XmpValue.

### toArray {#toArray--}
```
public XmpValue [] toArray()
```

Returnerar array.

**Returns:**
XmpValue‑array

### toDateTime {#toDateTime--}
```
public Date toDateTime()
```

Konverterar till datumtid.

**Returns:**
Datum‑instans

### toDateTimeOffset {#toDateTimeOffset--}
```
public final com.aspose.ms.System.DateTimeOffset toDateTimeOffset()
```

Konverterar det aktuella XMP‑värdet till en {@link DateTimeOffset}-representation.

**Returns:**
En {@link DateTimeOffset} som representerar det aktuella XMP‑värdet.

### toDictionary {#toDictionary--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary< String , XmpValue > toDictionary()
```

Returnerar en ordbok som innehåller namngivna värden.

**Returns:**
Ordbok

### toDouble {#toDouble--}
```
public double toDouble()
```

Konverterar till double.

**Returns:**
double-värde

### toField {#toField--}
```
public XmpField toField()
```

Returnerar XMP‑värdet som XMP‑fält.

**Returns:**
XmpField instans

### toInteger {#toInteger--}
```
public int toInteger()
```

Konverterar till heltal.

**Returns:**
int‑värde

### toNamedValue {#toNamedValue--}
```
public HashMap < String , XmpValue > toNamedValue()
```

Returnerar XMP‑värdet som ett namngivet värde.

**Returns:**
(Namngivet värde) HashMap‑instans med String‑nyckel och XmpValue‑värde

### toNamedValueInternal {#toNamedValueInternal--}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue > toNamedValueInternal()
```

Endast för intern användning

**Returns:**
Endast för intern användning

### toNamedValues {#toNamedValues--}
```
public HashMap < String , XmpValue > toNamedValues()
```

Returnerar XMP‑värdet som en samling av namngivna värden.

**Returns:**
(Namngiven samlingsvärde) HashMap‑instans med String‑nyckel och XmpValue‑värde

### toNamedValuesInternal {#toNamedValuesInternal--}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >[] toNamedValuesInternal()
```



### toRaw {#toRaw--}
```
public final com.aspose.ms.System.Xml.XmlNode toRaw()
```

Rå XML‑kod för okända/ej stödda värden.

**Returns:**
XML‑nod för detta värde.

### toString {#toString--}
```
public String toString()
```

Returnerar strängrepresentation av XmpValue.

**Returns:**
Strängrepresentation

### toString {#toString-com.aspose.ms.System.IFormatProvider-}
Returnerar strängrepresentation av XmpValue.

**Returns:**
Strängrepresentation

### toStringValue {#toStringValue--}
```
public String toStringValue()
```

Konverterar till sträng.

**Returns:**
String värde

### toStructure {#toStructure--}
```
public XmpField [] toStructure()
```

Returnerar XMP‑värdet som en struktur (uppsättning av fält).

**Returns:**
XmpField‑array
