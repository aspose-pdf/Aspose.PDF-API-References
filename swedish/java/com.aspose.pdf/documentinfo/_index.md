---
title: "DocumentInfo"
linktitle: "DocumentInfo"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar metadata för PDF-dokument."
type: docs
weight: 1160
url: /sv/java/com.aspose.pdf/documentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.Generic.Dictionary< String , String > com.aspose.pdf.DocumentInfo, com.aspose.ms.System.Collections.Generic.Dictionary< String , String >, com.aspose.pdf.DocumentInfo

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, String >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>

```
public final class DocumentInfo extends com.aspose.ms.System.Collections.Generic.Dictionary< String , String >
```

Representerar metadata för PDF-dokument.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [DocumentInfo](#DocumentInfo-com.aspose.pdf.IDocument-) | Initiera DocumentInfo-instans. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addItem](#addItem-java.lang.String-java.lang.String-) | Lägger till ett element med den angivna nyckeln och värdet i samlingen. |
| [clear](#clear--) | Rensar dokumentinformationen. |
| [clearCustomData](#clearCustomData--) | Rensar endast anpassade data, lämnar alla andra fördefinierade värden (Title, Author, etc.). |
| [get_Item](#get_Item-java.lang.String-) | Hämtar värdet som är associerat med den angivna nyckeln. |
| [getAuthor](#getAuthor--) | Hämtar dokumentets författare. |
| [getCreationDate](#getCreationDate--) | Hämtar datumet för dokumentets skapande. |
| [getCreationTimeZone](#getCreationTimeZone--) | Tidszon för skapandedatum i millisekunder. |
| [getCreator](#getCreator--) | Hämtar dokumentets skapare. |
| [getKeywords](#getKeywords--) | Hämtar dokumentets nyckelord. |
| [getModDate](#getModDate--) | Hämtar datumet för dokumentets ändring. |
| [getModTimeZone](#getModTimeZone--) | Tidszon för ändringsdatum. |
| [getProducer](#getProducer--) | Hämtar dokumentets producent. |
| [getSubject](#getSubject--) | Hämtar dokumentets ämne. |
| [getTitle](#getTitle--) | Hämtar dokumentets titel. |
| [getTrapped](#getTrapped--) | Hämtar flaggan för fångst. |
| [isPredefinedKey](#isPredefinedKey-java.lang.String-) | Bestämmer om nyckeln är fördefinierad (Title, Author, etc.), inte anpassad. |
| [remove](#remove-java.lang.String-) | Tar bort elementet med den angivna nyckeln från samlingen. |
| [set_Item](#set_Item-java.lang.String-java.lang.String-) | Ställer in värdet som är associerat med den angivna nyckeln. |
| [setAuthor](#setAuthor-java.lang.String-) | Ställer in dokumentets författare. |
| [setCreationDate](#setCreationDate-java.util.Date-) | Ställer in datumet för dokumentets skapande. |
| [setCreationTimeZone](#setCreationTimeZone-double-) | Tidszon för skapandedatum i millisekunder. |
| [setCreator](#setCreator-java.lang.String-) | Ställer in dokumentets skapare. |
| [setKeywords](#setKeywords-java.lang.String-) | Ställ in dokumentets nyckelord. |
| [setModDate](#setModDate-java.util.Date-) | Ställer in datumet för dokumentets ändring. |
| [setModTimeZone](#setModTimeZone-double-) | Tidszon för ändringsdatum. |
| [setProducer](#setProducer-java.lang.String-) | Anger dokumentets producent. |
| [setSubject](#setSubject-java.lang.String-) | Anger dokumentets ämne. |
| [setTitle](#setTitle-java.lang.String-) | Anger dokumentets titel. |
| [setTrapped](#setTrapped-java.lang.String-) | Anger den fångade flaggan. |

### DocumentInfo {#DocumentInfo-com.aspose.pdf.IDocument-}
Initiera DocumentInfo-instans.

### addItem {#addItem-java.lang.String-java.lang.String-}
Lägger till ett element med den angivna nyckeln och värdet i samlingen.

### clear {#clear--}
```
public void clear()
```

Rensar dokumentinformationen.

### clearCustomData {#clearCustomData--}
```
public void clearCustomData()
```

Rensar endast anpassade data, lämnar alla andra fördefinierade värden (Title, Author, etc.).

### get_Item {#get_Item-java.lang.String-}
Hämtar värdet som är associerat med den angivna nyckeln.

### getAuthor {#getAuthor--}
```
public String getAuthor()
```

Hämtar dokumentets författare.

**Returns:**
String värde

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

Hämtar datumet för dokumentets skapande.

**Returns:**
Date-objekt

### getCreationTimeZone {#getCreationTimeZone--}
```
public double getCreationTimeZone()
```

Tidszon för skapandedatum i millisekunder.

**Returns:**
double-värde

### getCreator {#getCreator--}
```
public String getCreator()
```

Hämtar dokumentets skapare.

**Returns:**
String värde

### getKeywords {#getKeywords--}
```
public String getKeywords()
```

Hämtar dokumentets nyckelord.

**Returns:**
String värde

### getModDate {#getModDate--}
```
public Date getModDate()
```

Hämtar datumet för dokumentets ändring.

**Returns:**
Date-objekt

### getModTimeZone {#getModTimeZone--}
```
public double getModTimeZone()
```

Tidszon för ändringsdatum.

**Returns:**
double-värde

### getProducer {#getProducer--}
```
public String getProducer()
```

Hämtar dokumentets producent.

**Returns:**
String värde

### getSubject {#getSubject--}
```
public String getSubject()
```

Hämtar dokumentets ämne.

**Returns:**
String värde

### getTitle {#getTitle--}
```
public String getTitle()
```

Hämtar dokumentets titel.

**Returns:**
String värde

### getTrapped {#getTrapped--}
```
public String getTrapped()
```

Hämtar flaggan för fångst.

**Returns:**
String värde

### isPredefinedKey {#isPredefinedKey-java.lang.String-}
Bestämmer om nyckeln är fördefinierad (Title, Author, etc.), inte anpassad.

### remove {#remove-java.lang.String-}
Tar bort elementet med den angivna nyckeln från samlingen.

### set_Item {#set_Item-java.lang.String-java.lang.String-}
Ställer in värdet som är associerat med den angivna nyckeln.

### setAuthor {#setAuthor-java.lang.String-}
Ställer in dokumentets författare.

### setCreationDate {#setCreationDate-java.util.Date-}
Ställer in datumet för dokumentets skapande.

### setCreationTimeZone {#setCreationTimeZone-double-}
```
public void setCreationTimeZone(double value)
```

Tidszon för skapandedatum i millisekunder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | i millisekunder |

### setCreator {#setCreator-java.lang.String-}
Ställer in dokumentets skapare.

### setKeywords {#setKeywords-java.lang.String-}
Ställ in dokumentets nyckelord.

### setModDate {#setModDate-java.util.Date-}
Ställer in datumet för dokumentets ändring.

### setModTimeZone {#setModTimeZone-double-}
```
public void setModTimeZone(double value)
```

Tidszon för ändringsdatum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setProducer {#setProducer-java.lang.String-}
Anger dokumentets producent.

### setSubject {#setSubject-java.lang.String-}
Anger dokumentets ämne.

### setTitle {#setTitle-java.lang.String-}
Anger dokumentets titel.

### setTrapped {#setTrapped-java.lang.String-}
Anger den fångade flaggan.
