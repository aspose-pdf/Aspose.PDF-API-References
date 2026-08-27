---
title: "LightweightOperatorCollection"
linktitle: "LightweightOperatorCollection"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Leichte Operatorensammlung. Vorgesehen für Szenarien, in denen der zugrunde liegende Inhaltsstrom nicht angehängt ist und nur eine Operatorensammlung als Ergebnis benötigt wird."
type: docs
weight: 2700
url: /de/java/com.aspose.pdf/lightweightoperatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection com.aspose.pdf.LightweightOperatorCollection, com.aspose.pdf.BaseOperatorCollection, com.aspose.pdf.LightweightOperatorCollection

**All Implemented Interfaces:**
Iterable < Operator >

```
public class LightweightOperatorCollection extends BaseOperatorCollection
```

Leichte Operatorensammlung. Vorgesehen für Szenarien, in denen der zugrunde liegende Inhaltsstrom nicht angehängt ist und nur eine Operatorensammlung als Ergebnis benötigt wird.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [LightweightOperatorCollection](#LightweightOperatorCollection--) | Objekt initialisieren |
| [LightweightOperatorCollection](#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-) | Objekt initialisieren |
| [LightweightOperatorCollection](#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-) | Objekt initialisieren |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add](#add-com.aspose.pdf.Operator-) | Operator hinzufügen |
| [addRange](#addRange-com.aspose.pdf.LightweightOperatorCollection-) | LightweightOperatorCollection hinzufügen |
| [cancelUpdate](#cancelUpdate--) | Bricht das letzte Update ab. Diese Methode kann aufgerufen werden, wenn die Änderung keine Inhaltsaktualisierung auslösen soll. |
| [clear](#clear--) | Leert die Sammlung. |
| [contains](#contains-com.aspose.pdf.Operator-) | Prüft, ob das Element in der Sammlung ist. |
| [deleteUnrestricted](#deleteUnrestricted-int-) | internes Löschen Unrestrictedelement |
| [get_Item](#get_Item-int-) | <p> Holt den Operator nach seinem Index. </p> <hr> <pre> Beispiel demonstriert, wie man den Operator des Seiteninhalts nach Index erhält. Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [getUnrestricted](#getUnrestricted-int-) | Für interne Verwendung getUnrestricted-Operator |
| [insert](#insert-int-com.aspose.pdf.Operator-) | Operator einfügen |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | Gibt an, ob die Sammlung auf schnelle Textextraktion beschränkt ist. |
| [isReadOnly](#isReadOnly--) | Ermittelt einen Wert, der angibt, ob die Sammlung schreibgeschützt ist. |
| [iterator](#iterator--) | Iterator zurückgeben |
| [remove](#remove-com.aspose.pdf.Operator-) | Entfernt den Operator aus der Sammlung. |
| [resumeUpdate](#resumeUpdate--) | Setzt die Dokumentaktualisierung fort. Aktualisiert den Inhaltsstream, falls ausstehende Änderungen vorhanden sind. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | Setzt den Operator nach seinem Index. <hr> <pre> Beispiel demonstriert, wie man den Operator des Seiteninhalts nach Index erhält. Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [size](#size--) | Anzahl der Operatoren |
| [suppressUpdate](#suppressUpdate--) | Unterdrückt das Aktualisieren von Inhaltsdaten. Der Inhalts-Stream wird nicht aktualisiert, bis ResumeUpdate aufgerufen wird. |
| [toList](#toList--) | Gibt die Operatorenliste zurück. |
| [updateData](#updateData--) | intern |

### LightweightOperatorCollection {#LightweightOperatorCollection--}
```
public LightweightOperatorCollection()
```

Objekt initialisieren

### LightweightOperatorCollection {#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-}
Objekt initialisieren

### LightweightOperatorCollection {#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-}
Objekt initialisieren

### add {#add-com.aspose.pdf.Operator-}
Operator hinzufügen

### addRange {#addRange-com.aspose.pdf.LightweightOperatorCollection-}
LightweightOperatorCollection hinzufügen

### cancelUpdate {#cancelUpdate--}
```
public void cancelUpdate()
```

Bricht das letzte Update ab. Diese Methode kann aufgerufen werden, wenn die Änderung keine Inhaltsaktualisierung auslösen soll.

### clear {#clear--}
```
public void clear()
```

Leert die Sammlung.

### contains {#contains-com.aspose.pdf.Operator-}
Prüft, ob das Element in der Sammlung ist.

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```

internes Löschen Unrestrictedelement

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | int-Wert |

### get_Item {#get_Item-int-}
```
public Operator get_Item(int index)
```

<p> Holt den Operator nach seinem Index. </p> <hr> <pre> Beispiel demonstriert, wie man den Operator des Seiteninhalts nach Index erhält. Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Index des Operators. Die Nummerierung beginnt bei 1. |

**Returns:**
Operator vom angegebenen Index

### getUnrestricted {#getUnrestricted-int-}
```
public Operator getUnrestricted(int index)
```

Für interne Verwendung getUnrestricted-Operator

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | int-Wert |

**Returns:**
Operatorobjekt

### insert {#insert-int-com.aspose.pdf.Operator-}
Operator einfügen

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public boolean isFastTextExtractionMode()
```

Gibt an, ob die Sammlung auf schnelle Textextraktion beschränkt ist.

**Returns:**
boolescher Wert

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Ermittelt einen Wert, der angibt, ob die Sammlung schreibgeschützt ist.

**Returns:**
boolescher Wert

### iterator {#iterator--}
```
public Iterator < Operator > iterator()
```

Iterator zurückgeben

**Returns:**
{@code IGenericEnumerator<Operator>} Objekt

### remove {#remove-com.aspose.pdf.Operator-}
Entfernt den Operator aus der Sammlung.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

Setzt die Dokumentaktualisierung fort. Aktualisiert den Inhaltsstream, falls ausstehende Änderungen vorhanden sind.

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
Setzt den Operator nach seinem Index. <hr> <pre> Beispiel demonstriert, wie man den Operator des Seiteninhalts nach Index erhält. Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre>

### size {#size--}
```
public int size()
```

Anzahl der Operatoren

**Returns:**
int-Wert

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Unterdrückt das Aktualisieren von Inhaltsdaten. Der Inhalts-Stream wird nicht aktualisiert, bis ResumeUpdate aufgerufen wird.

### toList {#toList--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

Gibt die Operatorenliste zurück.

**Returns:**
Operatorliste.

### updateData {#updateData--}
```
public void updateData()
```

intern
