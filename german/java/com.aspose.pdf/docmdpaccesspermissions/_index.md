---
title: "DocMDPAccessPermissions"
linktitle: "DocMDPAccessPermissions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Die für dieses Dokument gewährten Zugriffsberechtigungen. Gültige Werte sind: 1 - Keine Änderungen am Dokument sind erlaubt; jede Änderung am Dokument macht die Signatur ungültig. 2 -."
type: docs
weight: 1010
url: /de/java/com.aspose.pdf/docmdpaccesspermissions/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < DocMDPAccessPermissions > com.aspose.pdf.DocMDPAccessPermissions, java.lang.Enum < DocMDPAccessPermissions >, com.aspose.pdf.DocMDPAccessPermissions

**All Implemented Interfaces:**
Serializable, Comparable < DocMDPAccessPermissions >

```
public enum DocMDPAccessPermissions extends Enum < DocMDPAccessPermissions >
```

Die Zugriffsberechtigungen, die für dieses Dokument gewährt werden. Gültige Werte sind: 1 - Keine Änderungen am Dokument sind erlaubt; jede Änderung am Dokument macht die Signatur ungültig. 2 - Erlaubte Änderungen sind das Ausfüllen von Formularen, das Instanziieren von Seitenvorlagen und das Signieren; andere Änderungen machen die Signatur ungültig. 3 - Erlaubte Änderungen entsprechen denen von 2, zusätzlich das Erstellen, Löschen und Ändern von Anmerkungen; andere Änderungen machen die Signatur ungültig.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [AnnotationModification](#AnnotationModification) | 3 - Erlaubte Änderungen entsprechen denen von 2, sowie das Erstellen, Löschen und Ändern von Anmerkungen; andere Änderungen machen die Signatur ungültig. |
| [FillingInForms](#FillingInForms) | 2 - Erlaubte Änderungen sind das Ausfüllen von Formularen, das Instanziieren von Seitenvorlagen und das Signieren; andere Änderungen machen die Signatur ungültig. |
| [NoChanges](#NoChanges) | 1 - Keine Änderungen am Dokument sind erlaubt; jede Änderung am Dokument macht die Signatur ungültig. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Gibt die Enum-Konstante dieses Typs mit dem angegebenen Namen zurück. |
| [values](#values--) | Gibt ein Array zurück, das die Konstanten dieses Enum-Typs in der Reihenfolge ihrer Deklaration enthält. |

### AnnotationModification {#AnnotationModification}
```
public static final DocMDPAccessPermissions AnnotationModification
```

3 - Erlaubte Änderungen entsprechen denen von 2, sowie das Erstellen, Löschen und Ändern von Anmerkungen; andere Änderungen machen die Signatur ungültig.

### FillingInForms {#FillingInForms}
```
public static final DocMDPAccessPermissions FillingInForms
```

2 - Erlaubte Änderungen sind das Ausfüllen von Formularen, das Instanziieren von Seitenvorlagen und das Signieren; andere Änderungen machen die Signatur ungültig.

### NoChanges {#NoChanges}
```
public static final DocMDPAccessPermissions NoChanges
```

1 - Keine Änderungen am Dokument sind erlaubt; jede Änderung am Dokument macht die Signatur ungültig.

### getByValue {#getByValue-int-}
```
public static DocMDPAccessPermissions getByValue(int value)
```



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Gibt die Enum-Konstante dieses Typs mit dem angegebenen Namen zurück.

### values {#values--}
```
public static DocMDPAccessPermissions [] values()
```

Gibt ein Array zurück, das die Konstanten dieses Enum-Typs in der Reihenfolge ihrer Deklaration enthält.

**Returns:**
ein Array, das die Konstanten dieses Enum-Typs in der Reihenfolge ihrer Deklaration enthält
