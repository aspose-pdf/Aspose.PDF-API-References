---
title: "CollectionField"
linktitle: "CollectionField"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en fältklass för dokumentsamlingens schema."
type: docs
weight: 620
url: /sv/java/com.aspose.pdf/collectionfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CollectionField

```
public class CollectionField extends Object
```

Representerar en fältklass för dokumentsamlingens schema.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getE](#getE--) | Hämtar en flagga som indikerar om den interaktiva PDF‑processorn ska tillhandahålla stöd för att redigera fältvärdet. Standardvärde: false |
| [getFiledType](#getFiledType--) | Hämtar typen av ett fältvärde i en schemasamling. Detta fält beskriver värdetypen som motsvarar {@code Subtype}({@link #getSubtype}/{@link #setSubtype(int)}). |
| [getN](#getN--) | Hämtar det textuella fältnamnet som ska visas för användaren av den interaktiva PDF‑processorn |
| [getO](#getO--) | Hämtar den relativa ordningen för fältnamnet i användargränssnittet. Fält ska sorteras av den interaktiva PDF‑processorn i stigande ordning. |
| [getSubtype](#getSubtype--) | Hämtar undertypen för ett fältvärde i en schemasamling. Undertypen för samlingsfältet eller filrelaterat fält som denna ordbok beskriver. Denna post identifierar datatypen som ska lagras i fältet. |
| [getV](#getV--) | Hämtar den initiala synligheten för fältet i användargränssnittet. Standardvärde: true. |

### getE {#getE--}
```
public final boolean getE()
```

Hämtar en flagga som indikerar om den interaktiva PDF‑processorn ska tillhandahålla stöd för att redigera fältvärdet. Standardvärde: false

**Returns:**
booleskt värde

### getFiledType {#getFiledType--}
```
public final int getFiledType()
```

Hämtar typen av ett fältvärde i en schemasamling. Detta fält beskriver värdetypen som motsvarar {@code Subtype}({@link #getSubtype}/{@link #setSubtype(int)}).

**Returns:**
FieldValueType element

### getN {#getN--}
```
public final String getN()
```

Hämtar det textuella fältnamnet som ska visas för användaren av den interaktiva PDF‑processorn

**Returns:**
String värde

### getO {#getO--}
```
public final Integer [] getO()
```

Hämtar den relativa ordningen för fältnamnet i användargränssnittet. Fält ska sorteras av den interaktiva PDF‑processorn i stigande ordning.

**Returns:**
array av Integer

### getSubtype {#getSubtype--}
```
public final int getSubtype()
```

Hämtar undertypen för ett fältvärde i en schemasamling. Undertypen för samlingsfältet eller filrelaterat fält som denna ordbok beskriver. Denna post identifierar datatypen som ska lagras i fältet.

**Returns:**
CollectionFieldSubtype element

### getV {#getV--}
```
public final boolean getV()
```

Hämtar den initiala synligheten för fältet i användargränssnittet. Standardvärde: true.

**Returns:**
booleskt värde
