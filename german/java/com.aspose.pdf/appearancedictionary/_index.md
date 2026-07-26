---
title: "AppearanceDictionary"
linktitle: "AppearanceDictionary"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Annotationsaussehens-Wörterbuch, das angibt, wie die Annotation visuell auf der Seite dargestellt werden soll."
type: docs
weight: 150
url: /de/java/com.aspose.pdf/appearancedictionary/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AppearanceDictionary

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XForm >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>

```
public final class AppearanceDictionary extends Object implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XForm >
```

Annotationsaussehens-Wörterbuch, das angibt, wie die Annotation visuell auf der Seite dargestellt werden soll.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add](#add-java.lang.Object-java.lang.Object-) | Fügt ein Element mit dem angegebenen Schlüssel und Wert hinzu. |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Fügt ein Paar mit Schlüssel und Wert zum Wörterbuch hinzu. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XForm-) | Fügt ein X-Formular für den angegebenen Schlüssel hinzu. |
| [clear](#clear--) | Entfernt alle Elemente aus dem Wörterbuch. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Überprüft, ob das angegebene Schlüssel-Wert-Paar im Wörterbuch enthalten ist. |
| [containsKey](#containsKey-java.lang.String-) | Ermittelt, ob dieses Wörterbuch den angegebenen Schlüssel enthält. |
| [copyTo](#copyTo-com.aspose.pdf.XForm:A-int-) | / * / * Gibt ein IDictionaryEnumerator-Objekt für das Wörterbuch zurück. / * / * / * |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Kopiert die Elemente der ICollection in ein Array, beginnend an einem bestimmten Array-Index. |
| [get_Item](#get_Item-java.lang.String-) | Stellt eine bequeme Form zum Abrufen von appearance streams dar. |
| [getDict](#getDict--) | Erhält das pdf-Wörterbuch |
| [getKeys_](#getKeys_--) | Gets keys of the dictionary. If appearance dictionary has subditionaries, then {@code Keys} contains (N\ | R\ | D).state-Werte, wobei N - normale Darstellung, R - Roll-over-Darstellung, D - gedrückte Darstellung und state - der Name des Zustands ist (z. B. An, Aus für Kontrollkästchen). |
| [getKeys](#getKeys--) | Gets keys of the dictionary. If appearance dictionary has subditionaries, then {@code Keys} contains (N\ | R\ | D).state-Werte, wobei N - normale Darstellung, R - Roll-over-Darstellung, D - gedrückte Darstellung und state - der Name des Zustands ist (z. B. An, Aus für Kontrollkästchen). |
| [getSyncRoot](#getSyncRoot--) | Erhält ein Objekt, das verwendet werden kann, um den Zugriff auf das Wörterbuch zu synchronisieren. |
| [getValues_](#getValues_--) | Erhält die Liste der Wörterbuchwerte. Die Ergebnis-Sammlung enthält die Liste der XForm-Objekte. |
| [getValues](#getValues--) | Erhält die Liste der Wörterbuchwerte. Die Ergebnis-Sammlung enthält die Liste der XForm-Objekte. |
| [isFixedSize](#isFixedSize--) | Erhält einen Wert, der angibt, ob das Wörterbuch eine feste Größe hat. |
| [isReadOnly](#isReadOnly--) | Erhält einen Wert, der angibt, ob das Wörterbuch schreibgeschützt ist. |
| [isSynchronized](#isSynchronized--) | Erhält einen Wert, der angibt, ob der Zugriff auf das Wörterbuch synchronisiert ist (Thread-sicher). |
| [iterator__Rename_Namesake](#iterator__Rename_Namesake--) | Enumerator für die Sammlung. |
| [iterator](#iterator--) | Gibt ein IDictionaryEnumerator-Objekt für das Wörterbuch zurück. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Entfernt das Schlüssel/Wert-Paar aus der Sammlung. |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Entfernt den Schlüssel aus dem Wörterbuch. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XForm-) |  |
| [size](#size--) | Erhält die Anzahl der im Wörterbuch enthaltenen Elemente. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Versucht, den Schlüssel im Wörterbuch zu finden und ruft den Wert ab, wenn er gefunden wird. |

### add {#add-java.lang.Object-java.lang.Object-}
Fügt ein Element mit dem angegebenen Schlüssel und Wert hinzu.

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Fügt ein Paar mit Schlüssel und Wert zum Wörterbuch hinzu.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XForm-}
Fügt ein X-Formular für den angegebenen Schlüssel hinzu.

### clear {#clear--}
```
public void clear()
```

Entfernt alle Elemente aus dem Wörterbuch.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Überprüft, ob das angegebene Schlüssel-Wert-Paar im Wörterbuch enthalten ist.

### containsKey {#containsKey-java.lang.String-}
Ermittelt, ob dieses Wörterbuch den angegebenen Schlüssel enthält.

### copyTo {#copyTo-com.aspose.pdf.XForm:A-int-}
/ * / * Gibt ein IDictionaryEnumerator-Objekt für das Wörterbuch zurück. / * / * / *

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Kopiert die Elemente der ICollection in ein Array, beginnend an einem bestimmten Array-Index.

### get_Item {#get_Item-java.lang.String-}
Stellt eine bequeme Form zum Abrufen von appearance streams dar.

### getDict {#getDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getDict()
```

Erhält das pdf-Wörterbuch

**Returns:**
IPdfDictionary-Objekt

### getKeys_ {#getKeys_--}
```
public List < String > getKeys_()
```

Erhält die Schlüssel des Wörterbuchs. Wenn das Appearance-Wörterbuch Unterwörterbücher hat, dann enthält {@code Keys} (N|R|D).state-Werte, wobei N - normale Darstellung, R - Roll-over-Darstellung, D - gedrückte Darstellung und state - der Name des Zustands ist (z. B. An, Aus für Kontrollkästchen).

**Returns:**
Liste von String-Werten

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Erhält die Schlüssel des Wörterbuchs. Wenn das Appearance-Wörterbuch Unterwörterbücher hat, dann enthält {@code Keys} (N|R|D).state-Werte, wobei N - normale Darstellung, R - Roll-over-Darstellung, D - gedrückte Darstellung und state - der Name des Zustands ist (z. B. An, Aus für Kontrollkästchen).

**Returns:**
Liste von String-Werten

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Erhält ein Objekt, das verwendet werden kann, um den Zugriff auf das Wörterbuch zu synchronisieren.

**Returns:**
Objekt für Synchronisation

### getValues_ {#getValues_--}
```
public List < XForm > getValues_()
```

Erhält die Liste der Wörterbuchwerte. Die Ergebnis-Sammlung enthält die Liste der XForm-Objekte.

**Returns:**
Liste der XForm-Werte

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XForm > getValues()
```

Erhält die Liste der Wörterbuchwerte. Die Ergebnis-Sammlung enthält die Liste der XForm-Objekte.

**Returns:**
Liste der XForm-Werte

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

Erhält einen Wert, der angibt, ob das Wörterbuch eine feste Größe hat.

**Returns:**
boolescher Wert

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Erhält einen Wert, der angibt, ob das Wörterbuch schreibgeschützt ist.

**Returns:**
boolescher Wert

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Erhält einen Wert, der angibt, ob der Zugriff auf das Wörterbuch synchronisiert ist (Thread-sicher).

**Returns:**
boolescher Wert

### iterator__Rename_Namesake {#iterator__Rename_Namesake--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XForm >> iterator__Rename_Namesake()
```

Enumerator für die Sammlung.

**Returns:**
Enumerator der Sammlungs‑Elemente.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XForm >> iterator()
```

Gibt ein IDictionaryEnumerator-Objekt für das Wörterbuch zurück.

**Returns:**
Enumerator des Wörterbuchs.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Entfernt das Schlüssel/Wert-Paar aus der Sammlung.

### removeItemByKey {#removeItemByKey-java.lang.String-}
Entfernt den Schlüssel aus dem Wörterbuch.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XForm-}


### size {#size--}
```
public int size()
```

Erhält die Anzahl der im Wörterbuch enthaltenen Elemente.

**Returns:**
int-Wert

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Versucht, den Schlüssel im Wörterbuch zu finden und ruft den Wert ab, wenn er gefunden wird.
