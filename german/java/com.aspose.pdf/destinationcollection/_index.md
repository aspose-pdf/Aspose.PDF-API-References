---
title: "DestinationCollection"
linktitle: "DestinationCollection"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse repräsentiert die Sammlung aller Ziele (ein Namensbaum, der Namenszeichenketten zu Zielen abbildet (siehe 12.3.2.3, \"Named Destinations\") und (siehe 7.7.4, \"Name Dictionary\")) in."
type: docs
weight: 960
url: /de/java/com.aspose.pdf/destinationcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.DestinationCollection

**All Implemented Interfaces:**
Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, Object >>

```
public final class DestinationCollection extends Object implements Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object >>
```

Klasse, die die Sammlung aller Ziele (einen Namensbaum, der Namenszeichenketten zu Zielen abbildet (siehe 12.3.2.3, "Named Destinations") und (siehe 7.7.4, "Name Dictionary")) im PDF‑Dokument darstellt.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Fügt das angegebene Element hinzu. |
| [clear](#clear--) | Sammlung ist schreibgeschützt. Wirft immer eine NotSupportedException-Ausnahme. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Bestimmt, ob diese Instanz das Objekt enthält. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Kopiert die Elemente der Sammlung in ein Array, beginnend bei einem bestimmten Array-Index. |
| [get_Item](#get_Item-int-) | Liefert das Zielobjekt nach Index. |
| [getExplicitDestination](#getExplicitDestination-java.lang.String-boolean-) | Gibt das explizite Ziel nach Namen zurück. |
| [getPageNumber](#getPageNumber-java.lang.String-boolean-) | Gibt die Seitennummer des Ziels nach Namen zurück. |
| [indexOf](#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Gibt den Index des Ziels in der Sammlung zurück. |
| [isReadOnly](#isReadOnly--) | Ermittelt einen Wert, der angibt, ob die Sammlung schreibgeschützt ist. |
| [iterator](#iterator--) | Gibt den Enumerator zurück. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Entfernt das angegebene Element. |
| [size](#size--) | Liefert die Anzahl der in der Sammlung enthaltenen Elemente. |

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Fügt das angegebene Element hinzu.

### clear {#clear--}
```
public void clear()
```

Sammlung ist schreibgeschützt. Wirft immer eine NotSupportedException-Ausnahme.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Bestimmt, ob diese Instanz das Objekt enthält.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Kopiert die Elemente der Sammlung in ein Array, beginnend bei einem bestimmten Array-Index.

### get_Item {#get_Item-int-}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object > get_Item(int index)
```

Liefert das Zielobjekt nach Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Der Index des abzurufenden Ziels. |

**Returns:**
Ziel.

### getExplicitDestination {#getExplicitDestination-java.lang.String-boolean-}
Gibt das explizite Ziel nach Namen zurück.

### getPageNumber {#getPageNumber-java.lang.String-boolean-}
Gibt die Seitennummer des Ziels nach Namen zurück.

### indexOf {#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Gibt den Index des Ziels in der Sammlung zurück.

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Ermittelt einen Wert, der angibt, ob die Sammlung schreibgeschützt ist.

**Returns:**
boolescher Wert

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object >> iterator()
```

Gibt den Enumerator zurück.

**Returns:**
Der Enumerator.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Entfernt das angegebene Element.

### size {#size--}
```
public int size()
```

Liefert die Anzahl der in der Sammlung enthaltenen Elemente.

**Returns:**
int-Wert
