---
title: "XmpValue"
linktitle: "XmpValue"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente la valeur XMP"
type: docs
weight: 5750
url: /fr/java/com.aspose.pdf/xmpvalue/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpValue

```
public class XmpValue extends Object
```

Représente la valeur XMP

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XmpValue](#XmpValue-java.util.Date-) | Constructeur pour une valeur de date et heure. |
| [XmpValue](#XmpValue-double-) | Constructeur pour une valeur à virgule flottante. |
| [XmpValue](#XmpValue-int-) | Constructeur pour une valeur entière. |
| [XmpValue](#XmpValue-java.lang.Object-) |  |
| [XmpValue](#XmpValue-java.lang.String-) | Constructeur pour une valeur de chaîne. |
| [XmpValue](#XmpValue-java.lang.String-boolean-) | Initialise une nouvelle valeur XMP de chaîne. |
| [XmpValue](#XmpValue-com.aspose.pdf.XmpValue:A-) | Constructeur pour une valeur de tableau. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [isArray](#isArray--) | Renvoie vrai si XmpValue est un tableau. |
| [isDateTime](#isDateTime--) | Renvoie vrai si la valeur est DateTime. |
| [isDouble](#isDouble--) | Renvoie vrai si la valeur est une valeur à virgule flottante. |
| [isField](#isField--) | Renvoie vrai si XmpValue est un champ. |
| [isInteger](#isInteger--) | Renvoie vrai si la valeur est un entier. |
| [isNamedValue](#isNamedValue--) | Renvoie vrai si XmpValue est une valeur nommée. |
| [isNamedValues](#isNamedValues--) | Renvoie vrai si XmpValue représente des valeurs nommées. |
| [isRaw](#isRaw--) | La valeur n'est pas prise en charge/inconnue et le code XML brut est fourni. |
| [isString](#isString--) | Renvoie vrai si la valeur est une chaîne. |
| [isStructure](#isStructure--) | Renvoie vrai si XmpValue représente une structure. |
| [to_](#to_-com.aspose.pdf.XmpValue-) | Convertit XmpValue en tableau. |
| [to_Array](#to_Array-com.aspose.pdf.XmpValue-) | Convertit XmpValue en tableau. |
| [to_Generic](#to_Generic-com.aspose.pdf.XmpValue-) | Obtenir le tableau KeyValuePair |
| [to_KeyValuePair](#to_KeyValuePair-com.aspose.pdf.XmpValue-) | Convertit XmpValue en valeur nommée. |
| [to_String](#to_String-com.aspose.pdf.XmpValue-) | Convertit XmpValue en chaîne. |
| [to_XmpValue](#to_XmpValue-java.util.Date-) | Convertit DateTime en XmpValue. |
| [to_XmpValue](#to_XmpValue-double-) | Convertit double en XmpValue. |
| [to_XmpValue](#to_XmpValue-int-) | Convertit entier en XmpValue. |
| [to_XmpValue](#to_XmpValue-java.lang.Object:A-) | Convertit le tableau en XmpValue. |
| [to_XmpValue](#to_XmpValue-java.lang.String-) | Convertit la chaîne en XmpValue. |
| [toArray](#toArray--) | Renvoie un tableau. |
| [toDateTime](#toDateTime--) | Convertit en date et heure. |
| [toDateTimeOffset](#toDateTimeOffset--) | Convertit la valeur XMP actuelle en une représentation {@link DateTimeOffset}. |
| [toDictionary](#toDictionary--) | Renvoie un dictionnaire contenant des valeurs nommées. |
| [toDouble](#toDouble--) | Convertit en double. |
| [toField](#toField--) | Renvoie la valeur XMP sous forme de champ XMP. |
| [toInteger](#toInteger--) | Convertit en entier. |
| [toNamedValue](#toNamedValue--) | Renvoie la valeur XMP sous forme de valeur nommée. |
| [toNamedValueInternal](#toNamedValueInternal--) | Pour usage interne uniquement |
| [toNamedValues](#toNamedValues--) | Renvoie la valeur XMP sous forme de collection de valeurs nommées. |
| [toNamedValuesInternal](#toNamedValuesInternal--) |  |
| [toRaw](#toRaw--) | Code XML brut pour les valeurs inconnues/non prises en charge. |
| [toString](#toString--) | Renvoie la représentation sous forme de chaîne de XmpValue. |
| [toString](#toString-com.aspose.ms.System.IFormatProvider-) | Renvoie la représentation sous forme de chaîne de XmpValue. |
| [toStringValue](#toStringValue--) | Convertit en chaîne. |
| [toStructure](#toStructure--) | Renvoie la valeur XMP sous forme de structure (ensemble de champs). |

### XmpValue {#XmpValue-java.util.Date-}
Constructeur pour une valeur de date et heure.

### XmpValue {#XmpValue-double-}
```
public XmpValue(double value)
```

Constructeur pour une valeur à virgule flottante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur double. |

### XmpValue {#XmpValue-int-}
```
public XmpValue(int value)
```

Constructeur pour une valeur entière.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur entière. |

### XmpValue {#XmpValue-java.lang.Object-}


### XmpValue {#XmpValue-java.lang.String-}
Constructeur pour une valeur de chaîne.

### XmpValue {#XmpValue-java.lang.String-boolean-}
Initialise une nouvelle valeur XMP de chaîne.

### XmpValue {#XmpValue-com.aspose.pdf.XmpValue:A-}
Constructeur pour une valeur de tableau.

### isArray {#isArray--}
```
public boolean isArray()
```

Renvoie vrai si XmpValue est un tableau.

**Returns:**
valeur booléenne

### isDateTime {#isDateTime--}
```
public boolean isDateTime()
```

Renvoie vrai si la valeur est DateTime.

**Returns:**
valeur booléenne

### isDouble {#isDouble--}
```
public boolean isDouble()
```

Renvoie vrai si la valeur est une valeur à virgule flottante.

**Returns:**
valeur booléenne

### isField {#isField--}
```
public boolean isField()
```

Renvoie vrai si XmpValue est un champ.

**Returns:**
valeur booléenne

### isInteger {#isInteger--}
```
public boolean isInteger()
```

Renvoie vrai si la valeur est un entier.

**Returns:**
valeur booléenne

### isNamedValue {#isNamedValue--}
```
public boolean isNamedValue()
```

Renvoie vrai si XmpValue est une valeur nommée.

**Returns:**
valeur booléenne

### isNamedValues {#isNamedValues--}
```
public boolean isNamedValues()
```

Renvoie vrai si XmpValue représente des valeurs nommées.

**Returns:**
valeur booléenne

### isRaw {#isRaw--}
```
public final boolean isRaw()
```

La valeur n'est pas prise en charge/inconnue et le code XML brut est fourni.

**Returns:**
Vrai si la valeur est renvoyée sous forme de données brutes.

### isString {#isString--}
```
public boolean isString()
```

Renvoie vrai si la valeur est une chaîne.

**Returns:**
valeur booléenne

### isStructure {#isStructure--}
```
public boolean isStructure()
```

Renvoie vrai si XmpValue représente une structure.

**Returns:**
valeur booléenne

### to_ {#to_-com.aspose.pdf.XmpValue-}
Convertit XmpValue en tableau.

### to_Array {#to_Array-com.aspose.pdf.XmpValue-}
Convertit XmpValue en tableau.

### to_Generic {#to_Generic-com.aspose.pdf.XmpValue-}
Obtenir le tableau KeyValuePair

### to_KeyValuePair {#to_KeyValuePair-com.aspose.pdf.XmpValue-}
Convertit XmpValue en valeur nommée.

### to_String {#to_String-com.aspose.pdf.XmpValue-}
Convertit XmpValue en chaîne.

### to_XmpValue {#to_XmpValue-java.util.Date-}
Convertit DateTime en XmpValue.

### to_XmpValue {#to_XmpValue-double-}
```
public static XmpValue to_XmpValue(double value)
```

Convertit double en XmpValue.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur double (Valeur à convertir) |

**Returns:**
Instance XmpValue

### to_XmpValue {#to_XmpValue-int-}
```
public static XmpValue to_XmpValue(int value)
```

Convertit entier en XmpValue.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur int (Valeur à convertir) |

**Returns:**
Instance XmpValue

### to_XmpValue {#to_XmpValue-java.lang.Object:A-}
Convertit le tableau en XmpValue.

### to_XmpValue {#to_XmpValue-java.lang.String-}
Convertit la chaîne en XmpValue.

### toArray {#toArray--}
```
public XmpValue [] toArray()
```

Renvoie un tableau.

**Returns:**
Tableau XmpValue

### toDateTime {#toDateTime--}
```
public Date toDateTime()
```

Convertit en date et heure.

**Returns:**
Instance Date

### toDateTimeOffset {#toDateTimeOffset--}
```
public final com.aspose.ms.System.DateTimeOffset toDateTimeOffset()
```

Convertit la valeur XMP actuelle en une représentation {@link DateTimeOffset}.

**Returns:**
Un {@link DateTimeOffset} qui représente la valeur XMP actuelle.

### toDictionary {#toDictionary--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary< String , XmpValue > toDictionary()
```

Renvoie un dictionnaire contenant des valeurs nommées.

**Returns:**
Dictionnaire

### toDouble {#toDouble--}
```
public double toDouble()
```

Convertit en double.

**Returns:**
valeur double

### toField {#toField--}
```
public XmpField toField()
```

Renvoie la valeur XMP sous forme de champ XMP.

**Returns:**
Instance XmpField

### toInteger {#toInteger--}
```
public int toInteger()
```

Convertit en entier.

**Returns:**
valeur int

### toNamedValue {#toNamedValue--}
```
public HashMap < String , XmpValue > toNamedValue()
```

Renvoie la valeur XMP sous forme de valeur nommée.

**Returns:**
(Valeur nommée) instance HashMap avec clé String et valeur XmpValue

### toNamedValueInternal {#toNamedValueInternal--}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue > toNamedValueInternal()
```

Pour usage interne uniquement

**Returns:**
Pour usage interne uniquement

### toNamedValues {#toNamedValues--}
```
public HashMap < String , XmpValue > toNamedValues()
```

Renvoie la valeur XMP sous forme de collection de valeurs nommées.

**Returns:**
(Valeur de collection nommée) instance HashMap avec clé String et valeur XmpValue

### toNamedValuesInternal {#toNamedValuesInternal--}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >[] toNamedValuesInternal()
```



### toRaw {#toRaw--}
```
public final com.aspose.ms.System.Xml.XmlNode toRaw()
```

Code XML brut pour les valeurs inconnues/non prises en charge.

**Returns:**
Nœud XML pour cette valeur.

### toString {#toString--}
```
public String toString()
```

Renvoie la représentation sous forme de chaîne de XmpValue.

**Returns:**
Représentation sous forme de chaîne

### toString {#toString-com.aspose.ms.System.IFormatProvider-}
Renvoie la représentation sous forme de chaîne de XmpValue.

**Returns:**
Représentation sous forme de chaîne

### toStringValue {#toStringValue--}
```
public String toStringValue()
```

Convertit en chaîne.

**Returns:**
valeur String

### toStructure {#toStructure--}
```
public XmpField [] toStructure()
```

Renvoie la valeur XMP sous forme de structure (ensemble de champs).

**Returns:**
Tableau XmpField
