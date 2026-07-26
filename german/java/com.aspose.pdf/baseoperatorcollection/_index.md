---
title: "BaseOperatorCollection"
linktitle: "BaseOperatorCollection"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt die Basisklasse für eine Operatorensammlung dar."
type: docs
weight: 270
url: /de/java/com.aspose.pdf/baseoperatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection

**All Implemented Interfaces:**
Iterable < Operator >

```
public abstract class BaseOperatorCollection extends Object implements Iterable < Operator >
```

Stellt die Basisklasse für eine Operatorensammlung dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BaseOperatorCollection](#BaseOperatorCollection--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add](#add-com.aspose.pdf.Operator-) | Fügt einen neuen Operator zur Sammlung hinzu. |
| [cancelUpdate](#cancelUpdate--) | Bricht das letzte Update ab. Diese Methode kann aufgerufen werden, wenn die Änderung keine Inhaltsaktualisierung auslösen soll. |
| [clear](#clear--) | Leert die Sammlung. |
| [contains](#contains-com.aspose.pdf.Operator-) | Prüft, ob das Element in der Sammlung ist. |
| [deleteUnrestricted](#deleteUnrestricted-int-) | intern |
| [get_Item](#get_Item-int-) | Liefert den Operator anhand seines Index. |
| [getUnrestricted](#getUnrestricted-int-) | Nur für den internen Gebrauch. |
| [insert](#insert-int-com.aspose.pdf.Operator-) | Fügt den Operator in die Sammlung ein. |
| [isEmpty](#isEmpty--) | Gibt TRUE zurück, wenn die Sammlung leer ist. |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | Gibt an, ob die Sammlung auf schnelle Textextraktion beschränkt ist. |
| [isReadOnly](#isReadOnly--) | Gibt true zurück, wenn die Sammlung schreibgeschützt ist. |
| [iterator](#iterator--) | Gibt einen Enumerator für die Sammlung zurück |
| [remove](#remove-com.aspose.pdf.Operator-) | Entfernt den Operator aus der Sammlung. |
| [resumeUpdate](#resumeUpdate--) | Setzt die Dokumentaktualisierung fort. Aktualisiert den Inhaltsstream, falls ausstehende Änderungen vorhanden sind. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | Setzt den Operator anhand seines Index. |
| [size](#size--) | Ermittelt die Anzahl der Operatoren in der Sammlung. |
| [suppressUpdate](#suppressUpdate--) | Unterdrückt das Aktualisieren von Inhaltsdaten. Der Inhalts-Stream wird nicht aktualisiert, bis ResumeUpdate aufgerufen wird. |
| [toList](#toList--) | Gibt die Opetator-Liste zurück. |
| [updateData](#updateData--) | intern |

### BaseOperatorCollection {#BaseOperatorCollection--}
```
public BaseOperatorCollection()
```



### add {#add-com.aspose.pdf.Operator-}
Fügt einen neuen Operator zur Sammlung hinzu.

### cancelUpdate {#cancelUpdate--}
```
public abstract void cancelUpdate()
```

Bricht das letzte Update ab. Diese Methode kann aufgerufen werden, wenn die Änderung keine Inhaltsaktualisierung auslösen soll.

### clear {#clear--}
```
public abstract void clear()
```

Leert die Sammlung.

### contains {#contains-com.aspose.pdf.Operator-}
Prüft, ob das Element in der Sammlung ist.

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public abstract void deleteUnrestricted(int index)
```

intern

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | int-Wert |

### get_Item {#get_Item-int-}
```
public abstract Operator get_Item(int index)
```

Liefert den Operator anhand seines Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Index des Operators. Die Nummerierung beginnt bei 1. |

**Returns:**
Operator vom angegebenen Index

### getUnrestricted {#getUnrestricted-int-}
```
public abstract Operator getUnrestricted(int index)
```

Nur für den internen Gebrauch.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | int-Wert |

**Returns:**
Operatorobjekt

### insert {#insert-int-com.aspose.pdf.Operator-}
Fügt den Operator in die Sammlung ein.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Gibt TRUE zurück, wenn die Sammlung leer ist.

**Returns:**
boolescher Wert

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public abstract boolean isFastTextExtractionMode()
```

Gibt an, ob die Sammlung auf schnelle Textextraktion beschränkt ist.

**Returns:**
boolescher Wert

### isReadOnly {#isReadOnly--}
```
public abstract boolean isReadOnly()
```

Gibt true zurück, wenn die Sammlung schreibgeschützt ist.

**Returns:**
boolescher Wert

### iterator {#iterator--}
```
public abstract Iterator < Operator > iterator()
```

Gibt einen Enumerator für die Sammlung zurück

**Returns:**
Sammlungsenumerator

### remove {#remove-com.aspose.pdf.Operator-}
Entfernt den Operator aus der Sammlung.

### resumeUpdate {#resumeUpdate--}
```
public abstract void resumeUpdate()
```

Setzt die Dokumentaktualisierung fort. Aktualisiert den Inhaltsstream, falls ausstehende Änderungen vorhanden sind.

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
Setzt den Operator anhand seines Index.

### size {#size--}
```
public abstract int size()
```

Ermittelt die Anzahl der Operatoren in der Sammlung.

**Returns:**
Ganzzahlwert

### suppressUpdate {#suppressUpdate--}
```
public abstract void suppressUpdate()
```

Unterdrückt das Aktualisieren von Inhaltsdaten. Der Inhalts-Stream wird nicht aktualisiert, bis ResumeUpdate aufgerufen wird.

### toList {#toList--}
```
public abstract com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

Gibt die Opetator-Liste zurück.

**Returns:**
Opetator-Liste.

### updateData {#updateData--}
```
public abstract void updateData()
```

intern
