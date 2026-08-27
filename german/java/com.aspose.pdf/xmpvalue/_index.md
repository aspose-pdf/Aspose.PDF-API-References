---
title: "XmpValue"
linktitle: "XmpValue"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt XMP‑Wert dar"
type: docs
weight: 5750
url: /de/java/com.aspose.pdf/xmpvalue/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpValue

```
public class XmpValue extends Object
```

Stellt XMP‑Wert dar

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XmpValue](#XmpValue-java.util.Date-) | Konstruktor für Datum-Uhrzeit-Wert. |
| [XmpValue](#XmpValue-double-) | Konstruktor für Gleitkommawert. |
| [XmpValue](#XmpValue-int-) | Konstruktor für Ganzzahlwert. |
| [XmpValue](#XmpValue-java.lang.Object-) |  |
| [XmpValue](#XmpValue-java.lang.String-) | Konstruktor für Zeichenkettenwert. |
| [XmpValue](#XmpValue-java.lang.String-boolean-) | Initialisiert neuen Zeichenketten‑XMP‑Wert. |
| [XmpValue](#XmpValue-com.aspose.pdf.XmpValue:A-) | Konstruktor für Array‑Wert. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isArray](#isArray--) | Gibt true zurück, wenn XmpValue ein Array ist. |
| [isDateTime](#isDateTime--) | Gibt true zurück, wenn der Wert ein DateTime ist. |
| [isDouble](#isDouble--) | Gibt true zurück, wenn der Wert ein Gleitkommawert ist. |
| [isField](#isField--) | Gibt true zurück, wenn XmpValue ein Feld ist. |
| [isInteger](#isInteger--) | Gibt true zurück, wenn der Wert eine Ganzzahl ist. |
| [isNamedValue](#isNamedValue--) | Gibt true zurück, wenn XmpValue ein benannter Wert ist. |
| [isNamedValues](#isNamedValues--) | Gibt true zurück, wenn XmpValue benannte Werte darstellt. |
| [isRaw](#isRaw--) | Wert wird nicht unterstützt/unbekannt und roher XML‑Code wird bereitgestellt. |
| [isString](#isString--) | Gibt true zurück, wenn der Wert eine Zeichenkette ist. |
| [isStructure](#isStructure--) | Gibt true zurück, wenn XmpValue eine Struktur darstellt. |
| [to_](#to_-com.aspose.pdf.XmpValue-) | Konvertiert XmpValue in ein Array. |
| [to_Array](#to_Array-com.aspose.pdf.XmpValue-) | Konvertiert XmpValue zu einem Array. |
| [to_Generic](#to_Generic-com.aspose.pdf.XmpValue-) | Hole KeyValuePair‑Array |
| [to_KeyValuePair](#to_KeyValuePair-com.aspose.pdf.XmpValue-) | Konvertiert XmpValue in einen benannten Wert. |
| [to_String](#to_String-com.aspose.pdf.XmpValue-) | Konvertiert XmpValue in eine Zeichenkette. |
| [to_XmpValue](#to_XmpValue-java.util.Date-) | Konvertiert DateTime in XmpValue. |
| [to_XmpValue](#to_XmpValue-double-) | Konvertiert double in XmpValue. |
| [to_XmpValue](#to_XmpValue-int-) | Konvertiert integer in XmpValue. |
| [to_XmpValue](#to_XmpValue-java.lang.Object:A-) | Konvertiert Array zu XmpValue. |
| [to_XmpValue](#to_XmpValue-java.lang.String-) | Konvertiert Zeichenkette zu XmpValue. |
| [toArray](#toArray--) | Gibt ein Array zurück. |
| [toDateTime](#toDateTime--) | Konvertiert zu Datum und Uhrzeit. |
| [toDateTimeOffset](#toDateTimeOffset--) | Konvertiert den aktuellen XMP-Wert in eine {@link DateTimeOffset}-Darstellung. |
| [toDictionary](#toDictionary--) | Gibt ein Wörterbuch zurück, das benannte Werte enthält. |
| [toDouble](#toDouble--) | Konvertiert zu double. |
| [toField](#toField--) | Gibt den XMP-Wert als XMP-Feld zurück. |
| [toInteger](#toInteger--) | Konvertiert zu integer. |
| [toNamedValue](#toNamedValue--) | Gibt den XMP-Wert als benannten Wert zurück. |
| [toNamedValueInternal](#toNamedValueInternal--) | Nur für den internen Gebrauch |
| [toNamedValues](#toNamedValues--) | Gibt den XMP-Wert als Sammlung benannter Werte zurück. |
| [toNamedValuesInternal](#toNamedValuesInternal--) |  |
| [toRaw](#toRaw--) | Roh-XML-Code für unbekannte/nicht unterstützte Werte. |
| [toString](#toString--) | Gibt die String-Darstellung von XmpValue zurück. |
| [toString](#toString-com.aspose.ms.System.IFormatProvider-) | Gibt die String-Darstellung von XmpValue zurück. |
| [toStringValue](#toStringValue--) | Konvertiert in einen String. |
| [toStructure](#toStructure--) | Gibt den XMP-Wert als Struktur (Menge von Feldern) zurück. |

### XmpValue {#XmpValue-java.util.Date-}
Konstruktor für Datum-Uhrzeit-Wert.

### XmpValue {#XmpValue-double-}
```
public XmpValue(double value)
```

Konstruktor für Gleitkommawert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Double-Wert. |

### XmpValue {#XmpValue-int-}
```
public XmpValue(int value)
```

Konstruktor für Ganzzahlwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Integer-Wert. |

### XmpValue {#XmpValue-java.lang.Object-}


### XmpValue {#XmpValue-java.lang.String-}
Konstruktor für Zeichenkettenwert.

### XmpValue {#XmpValue-java.lang.String-boolean-}
Initialisiert neuen Zeichenketten‑XMP‑Wert.

### XmpValue {#XmpValue-com.aspose.pdf.XmpValue:A-}
Konstruktor für Array‑Wert.

### isArray {#isArray--}
```
public boolean isArray()
```

Gibt true zurück, wenn XmpValue ein Array ist.

**Returns:**
boolescher Wert

### isDateTime {#isDateTime--}
```
public boolean isDateTime()
```

Gibt true zurück, wenn der Wert ein DateTime ist.

**Returns:**
boolescher Wert

### isDouble {#isDouble--}
```
public boolean isDouble()
```

Gibt true zurück, wenn der Wert ein Gleitkommawert ist.

**Returns:**
boolescher Wert

### isField {#isField--}
```
public boolean isField()
```

Gibt true zurück, wenn XmpValue ein Feld ist.

**Returns:**
boolescher Wert

### isInteger {#isInteger--}
```
public boolean isInteger()
```

Gibt true zurück, wenn der Wert eine Ganzzahl ist.

**Returns:**
boolescher Wert

### isNamedValue {#isNamedValue--}
```
public boolean isNamedValue()
```

Gibt true zurück, wenn XmpValue ein benannter Wert ist.

**Returns:**
boolescher Wert

### isNamedValues {#isNamedValues--}
```
public boolean isNamedValues()
```

Gibt true zurück, wenn XmpValue benannte Werte darstellt.

**Returns:**
boolescher Wert

### isRaw {#isRaw--}
```
public final boolean isRaw()
```

Wert wird nicht unterstützt/unbekannt und roher XML‑Code wird bereitgestellt.

**Returns:**
Wahr, wenn der Wert als Rohdaten zurückgegeben wird.

### isString {#isString--}
```
public boolean isString()
```

Gibt true zurück, wenn der Wert eine Zeichenkette ist.

**Returns:**
boolescher Wert

### isStructure {#isStructure--}
```
public boolean isStructure()
```

Gibt true zurück, wenn XmpValue eine Struktur darstellt.

**Returns:**
boolescher Wert

### to_ {#to_-com.aspose.pdf.XmpValue-}
Konvertiert XmpValue in ein Array.

### to_Array {#to_Array-com.aspose.pdf.XmpValue-}
Konvertiert XmpValue zu einem Array.

### to_Generic {#to_Generic-com.aspose.pdf.XmpValue-}
Hole KeyValuePair‑Array

### to_KeyValuePair {#to_KeyValuePair-com.aspose.pdf.XmpValue-}
Konvertiert XmpValue in einen benannten Wert.

### to_String {#to_String-com.aspose.pdf.XmpValue-}
Konvertiert XmpValue in eine Zeichenkette.

### to_XmpValue {#to_XmpValue-java.util.Date-}
Konvertiert DateTime in XmpValue.

### to_XmpValue {#to_XmpValue-double-}
```
public static XmpValue to_XmpValue(double value)
```

Konvertiert double in XmpValue.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert (zu konvertierender Wert) |

**Returns:**
XmpValue-Instanz

### to_XmpValue {#to_XmpValue-int-}
```
public static XmpValue to_XmpValue(int value)
```

Konvertiert integer in XmpValue.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert (zu konvertierender Wert) |

**Returns:**
XmpValue-Instanz

### to_XmpValue {#to_XmpValue-java.lang.Object:A-}
Konvertiert Array zu XmpValue.

### to_XmpValue {#to_XmpValue-java.lang.String-}
Konvertiert Zeichenkette zu XmpValue.

### toArray {#toArray--}
```
public XmpValue [] toArray()
```

Gibt ein Array zurück.

**Returns:**
XmpValue-Array

### toDateTime {#toDateTime--}
```
public Date toDateTime()
```

Konvertiert zu Datum und Uhrzeit.

**Returns:**
Datum-Instanz

### toDateTimeOffset {#toDateTimeOffset--}
```
public final com.aspose.ms.System.DateTimeOffset toDateTimeOffset()
```

Konvertiert den aktuellen XMP-Wert in eine {@link DateTimeOffset}-Darstellung.

**Returns:**
Ein {@link DateTimeOffset}, das den aktuellen XMP-Wert darstellt.

### toDictionary {#toDictionary--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary< String , XmpValue > toDictionary()
```

Gibt ein Wörterbuch zurück, das benannte Werte enthält.

**Returns:**
Wörterbuch

### toDouble {#toDouble--}
```
public double toDouble()
```

Konvertiert zu double.

**Returns:**
double-Wert

### toField {#toField--}
```
public XmpField toField()
```

Gibt den XMP-Wert als XMP-Feld zurück.

**Returns:**
XmpField Instanz

### toInteger {#toInteger--}
```
public int toInteger()
```

Konvertiert zu integer.

**Returns:**
int-Wert

### toNamedValue {#toNamedValue--}
```
public HashMap < String , XmpValue > toNamedValue()
```

Gibt den XMP-Wert als benannten Wert zurück.

**Returns:**
(Benannter Wert) HashMap-Instanz mit String-Schlüssel und XmpValue-Wert

### toNamedValueInternal {#toNamedValueInternal--}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue > toNamedValueInternal()
```

Nur für den internen Gebrauch

**Returns:**
Nur für den internen Gebrauch

### toNamedValues {#toNamedValues--}
```
public HashMap < String , XmpValue > toNamedValues()
```

Gibt den XMP-Wert als Sammlung benannter Werte zurück.

**Returns:**
(Benannte Sammlung) HashMap-Instanz mit String-Schlüssel und XmpValue-Wert

### toNamedValuesInternal {#toNamedValuesInternal--}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >[] toNamedValuesInternal()
```



### toRaw {#toRaw--}
```
public final com.aspose.ms.System.Xml.XmlNode toRaw()
```

Roh-XML-Code für unbekannte/nicht unterstützte Werte.

**Returns:**
XML-Knoten für diesen Wert.

### toString {#toString--}
```
public String toString()
```

Gibt die String-Darstellung von XmpValue zurück.

**Returns:**
String-Darstellung

### toString {#toString-com.aspose.ms.System.IFormatProvider-}
Gibt die String-Darstellung von XmpValue zurück.

**Returns:**
String-Darstellung

### toStringValue {#toStringValue--}
```
public String toStringValue()
```

Konvertiert in einen String.

**Returns:**
String Wert

### toStructure {#toStructure--}
```
public XmpField [] toStructure()
```

Gibt den XMP-Wert als Struktur (Menge von Feldern) zurück.

**Returns:**
XmpField-Array
