---
title: "TextExtractionErrorLocation"
linktitle: "TextExtractionErrorLocation"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar platsen i PDF-dokumentet där textutdragningsfelet har uppstått."
type: docs
weight: 5050
url: /sv/java/com.aspose.pdf/textextractionerrorlocation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextExtractionErrorLocation

```
public final class TextExtractionErrorLocation extends Object
```

Representerar platsen i PDF-dokumentet där textutdragningsfelet har uppstått.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFontUsedKey](#getFontUsedKey--) | Nyckel (namn) för PDF-typsnittobjektet som används för att visa operatorn som orsakar fel vid textutdragning. |
| [getFormKey](#getFormKey--) | Nyckel (namn) för PDF Form XObject där fel i textutdragning i innehållsströmmen har placerats. Inte tom om ObjectType == 'xForm'. |
| [getObjectType](#getObjectType--) | Typ av PDF-objektet (Page eller xForm) där fel i textutdragning i innehållsströmmen har placerats. |
| [getOperatorIndex](#getOperatorIndex--) | Index för textvisningsoperatorn i innehållsströmmen (operator-samling) som orsakar fel vid textutdragning. |
| [getOperatorString](#getOperatorString--) | Textvisningsoperator som orsakar fel vid textutdragning. |
| [getPageNumber](#getPageNumber--) | Nummer på dokumentsidan där fel vid textutdragning har placerats. |
| [getPath](#getPath--) | Plats för PDF-dokumentet där fel vid textutdragning har uppstått. |
| [getTextStartPoint](#getTextStartPoint--) | Nyckel (namn) för PDF-typsnittobjektet som används för att visa operatorn som orsakar fel vid textutdragning. |
| [toString](#toString--) | Returnerar strängrepresentation. |

### getFontUsedKey {#getFontUsedKey--}
```
public String getFontUsedKey()
```

Nyckel (namn) för PDF-typsnittobjektet som används för att visa operatorn som orsakar fel vid textutdragning.

**Returns:**
String värde

### getFormKey {#getFormKey--}
```
public String getFormKey()
```

Nyckel (namn) för PDF Form XObject där fel i textutdragning i innehållsströmmen har placerats. Inte tom om ObjectType == 'xForm'.

**Returns:**
String värde

### getObjectType {#getObjectType--}
```
public String getObjectType()
```

Typ av PDF-objektet (Page eller xForm) där fel i textutdragning i innehållsströmmen har placerats.

**Returns:**
String värde

### getOperatorIndex {#getOperatorIndex--}
```
public int getOperatorIndex()
```

Index för textvisningsoperatorn i innehållsströmmen (operator-samling) som orsakar fel vid textutdragning.

**Returns:**
int‑värde

### getOperatorString {#getOperatorString--}
```
public String getOperatorString()
```

Textvisningsoperator som orsakar fel vid textutdragning.

**Returns:**
String värde

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Nummer på dokumentsidan där fel vid textutdragning har placerats.

**Returns:**
int‑värde

### getPath {#getPath--}
```
public String getPath()
```

Plats för PDF-dokumentet där fel vid textutdragning har uppstått.

**Returns:**
String värde

### getTextStartPoint {#getTextStartPoint--}
```
public Point getTextStartPoint()
```

Nyckel (namn) för PDF-typsnittobjektet som används för att visa operatorn som orsakar fel vid textutdragning.

**Returns:**
Point-instans

### toString {#toString--}
```
public String toString()
```

Returnerar strängrepresentation.

**Returns:**
Strängrepresentation.
