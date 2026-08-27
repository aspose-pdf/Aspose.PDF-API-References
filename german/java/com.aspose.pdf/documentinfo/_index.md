---
title: "DocumentInfo"
linktitle: "DocumentInfo"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt Metainformationen eines PDF-Dokuments dar."
type: docs
weight: 1160
url: /de/java/com.aspose.pdf/documentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.Generic.Dictionary< String , String > com.aspose.pdf.DocumentInfo, com.aspose.ms.System.Collections.Generic.Dictionary< String , String >, com.aspose.pdf.DocumentInfo

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, String >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>

```
public final class DocumentInfo extends com.aspose.ms.System.Collections.Generic.Dictionary< String , String >
```

Stellt Metainformationen eines PDF-Dokuments dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DocumentInfo](#DocumentInfo-com.aspose.pdf.IDocument-) | Initialisiere die DocumentInfo-Instanz. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addItem](#addItem-java.lang.String-java.lang.String-) | Fügt ein Element mit dem angegebenen Schlüssel und Wert in die Sammlung ein. |
| [clear](#clear--) | Löscht die Dokumentinformationen. |
| [clearCustomData](#clearCustomData--) | Löscht nur benutzerdefinierte Daten und lässt alle anderen vordefinierten Werte (Titel, Autor usw.) unverändert. |
| [get_Item](#get_Item-java.lang.String-) | Gibt den mit dem angegebenen Schlüssel verknüpften Wert zurück. |
| [getAuthor](#getAuthor--) | Gibt den Dokumentautor zurück. |
| [getCreationDate](#getCreationDate--) | Gibt das Erstellungsdatum des Dokuments zurück. |
| [getCreationTimeZone](#getCreationTimeZone--) | Zeitzone des Erstellungsdatums in Millisekunden. |
| [getCreator](#getCreator--) | Gibt den Dokumentersteller zurück. |
| [getKeywords](#getKeywords--) | Gibt die Schlüsselwörter des Dokuments zurück. |
| [getModDate](#getModDate--) | Gibt das Änderungsdatum des Dokuments zurück. |
| [getModTimeZone](#getModTimeZone--) | Zeitzone des Änderungsdatums. |
| [getProducer](#getProducer--) | Gibt den Dokumenthersteller zurück. |
| [getSubject](#getSubject--) | Gibt den Betreff des Dokuments zurück. |
| [getTitle](#getTitle--) | Gibt den Dokumenttitel zurück. |
| [getTrapped](#getTrapped--) | Gibt das 'trapped'-Flag zurück. |
| [isPredefinedKey](#isPredefinedKey-java.lang.String-) | Bestimmt, ob der Schlüssel vordefiniert ist (Titel, Autor usw.) und nicht benutzerdefiniert. |
| [remove](#remove-java.lang.String-) | Entfernt das Element mit dem angegebenen Schlüssel aus der Sammlung. |
| [set_Item](#set_Item-java.lang.String-java.lang.String-) | Setzt den mit dem angegebenen Schlüssel verknüpften Wert. |
| [setAuthor](#setAuthor-java.lang.String-) | Setzt den Dokumentautor. |
| [setCreationDate](#setCreationDate-java.util.Date-) | Setzt das Erstellungsdatum des Dokuments. |
| [setCreationTimeZone](#setCreationTimeZone-double-) | Zeitzone des Erstellungsdatums in Millisekunden. |
| [setCreator](#setCreator-java.lang.String-) | Setzt den Dokumentersteller. |
| [setKeywords](#setKeywords-java.lang.String-) | Setzt die Schlüsselwörter des Dokuments. |
| [setModDate](#setModDate-java.util.Date-) | Setzt das Änderungsdatum des Dokuments. |
| [setModTimeZone](#setModTimeZone-double-) | Zeitzone des Änderungsdatums. |
| [setProducer](#setProducer-java.lang.String-) | Legt den Dokumenthersteller fest. |
| [setSubject](#setSubject-java.lang.String-) | Legt den Betreff des Dokuments fest. |
| [setTitle](#setTitle-java.lang.String-) | Legt den Dokumenttitel fest. |
| [setTrapped](#setTrapped-java.lang.String-) | Legt das Trapped-Flag fest. |

### DocumentInfo {#DocumentInfo-com.aspose.pdf.IDocument-}
Initialisiere die DocumentInfo-Instanz.

### addItem {#addItem-java.lang.String-java.lang.String-}
Fügt ein Element mit dem angegebenen Schlüssel und Wert in die Sammlung ein.

### clear {#clear--}
```
public void clear()
```

Löscht die Dokumentinformationen.

### clearCustomData {#clearCustomData--}
```
public void clearCustomData()
```

Löscht nur benutzerdefinierte Daten und lässt alle anderen vordefinierten Werte (Titel, Autor usw.) unverändert.

### get_Item {#get_Item-java.lang.String-}
Gibt den mit dem angegebenen Schlüssel verknüpften Wert zurück.

### getAuthor {#getAuthor--}
```
public String getAuthor()
```

Gibt den Dokumentautor zurück.

**Returns:**
String Wert

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

Gibt das Erstellungsdatum des Dokuments zurück.

**Returns:**
Date-Objekt

### getCreationTimeZone {#getCreationTimeZone--}
```
public double getCreationTimeZone()
```

Zeitzone des Erstellungsdatums in Millisekunden.

**Returns:**
double-Wert

### getCreator {#getCreator--}
```
public String getCreator()
```

Gibt den Dokumentersteller zurück.

**Returns:**
String Wert

### getKeywords {#getKeywords--}
```
public String getKeywords()
```

Gibt die Schlüsselwörter des Dokuments zurück.

**Returns:**
String Wert

### getModDate {#getModDate--}
```
public Date getModDate()
```

Gibt das Änderungsdatum des Dokuments zurück.

**Returns:**
Date-Objekt

### getModTimeZone {#getModTimeZone--}
```
public double getModTimeZone()
```

Zeitzone des Änderungsdatums.

**Returns:**
double-Wert

### getProducer {#getProducer--}
```
public String getProducer()
```

Gibt den Dokumenthersteller zurück.

**Returns:**
String Wert

### getSubject {#getSubject--}
```
public String getSubject()
```

Gibt den Betreff des Dokuments zurück.

**Returns:**
String Wert

### getTitle {#getTitle--}
```
public String getTitle()
```

Gibt den Dokumenttitel zurück.

**Returns:**
String Wert

### getTrapped {#getTrapped--}
```
public String getTrapped()
```

Gibt das 'trapped'-Flag zurück.

**Returns:**
String Wert

### isPredefinedKey {#isPredefinedKey-java.lang.String-}
Bestimmt, ob der Schlüssel vordefiniert ist (Titel, Autor usw.) und nicht benutzerdefiniert.

### remove {#remove-java.lang.String-}
Entfernt das Element mit dem angegebenen Schlüssel aus der Sammlung.

### set_Item {#set_Item-java.lang.String-java.lang.String-}
Setzt den mit dem angegebenen Schlüssel verknüpften Wert.

### setAuthor {#setAuthor-java.lang.String-}
Setzt den Dokumentautor.

### setCreationDate {#setCreationDate-java.util.Date-}
Setzt das Erstellungsdatum des Dokuments.

### setCreationTimeZone {#setCreationTimeZone-double-}
```
public void setCreationTimeZone(double value)
```

Zeitzone des Erstellungsdatums in Millisekunden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | in Millisekunden |

### setCreator {#setCreator-java.lang.String-}
Setzt den Dokumentersteller.

### setKeywords {#setKeywords-java.lang.String-}
Setzt die Schlüsselwörter des Dokuments.

### setModDate {#setModDate-java.util.Date-}
Setzt das Änderungsdatum des Dokuments.

### setModTimeZone {#setModTimeZone-double-}
```
public void setModTimeZone(double value)
```

Zeitzone des Änderungsdatums.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setProducer {#setProducer-java.lang.String-}
Legt den Dokumenthersteller fest.

### setSubject {#setSubject-java.lang.String-}
Legt den Betreff des Dokuments fest.

### setTitle {#setTitle-java.lang.String-}
Legt den Dokumenttitel fest.

### setTrapped {#setTrapped-java.lang.String-}
Legt das Trapped-Flag fest.
