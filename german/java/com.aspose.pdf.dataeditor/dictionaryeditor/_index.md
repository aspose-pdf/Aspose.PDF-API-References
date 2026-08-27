---
title: "DictionaryEditor"
linktitle: "DictionaryEditor"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Eine Klasse zum Zugriff auf das Baum‑Wörterbuch eines Dokuments (Dokumenten‑Wörterbuch, Seiten‑Wörterbuch, Ressourcen‑Wörterbuch)."
type: docs
weight: 70
url: /de/java/com.aspose.pdf.dataeditor/dictionaryeditor/
---
**Inheritance:**
java.lang.Object, java.util.Dictionary <K,V> java.util.Hashtable < String , ICosPdfPrimitive > com.aspose.pdf.dataeditor.DictionaryEditor, java.util.Dictionary <K,V>, java.util.Hashtable < String , ICosPdfPrimitive > com.aspose.pdf.dataeditor.DictionaryEditor, java.util.Hashtable < String , ICosPdfPrimitive >, com.aspose.pdf.dataeditor.DictionaryEditor

**All Implemented Interfaces:**
Serializable, Cloneable, Map < String, ICosPdfPrimitive >

```
public class DictionaryEditor extends Hashtable < String , ICosPdfPrimitive >
```

Eine Klasse zum Zugriff auf das Baum‑Wörterbuch eines Dokuments (Dokumenten‑Wörterbuch, Seiten‑Wörterbuch, Ressourcen‑Wörterbuch).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Document-) |  |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Page-) |  |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Resources-) | @exception ArgumentNullException Die Ressourcen sind null. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Setze ICosPdfPrimitive im Wörterbuch. |
| [add](#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Setze {@link ICosPdfPrimitive} im Wörterbuch. |
| [clear](#clear--) | Entfernt alle Elemente aus dem {@link DictionaryEditor}. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Bestimmt, ob der DictionaryEditor einen bestimmten Wert enthält. |
| [containsKey](#containsKey-java.lang.String-) | Bestimmt, ob {@link DictionaryEditor} ein Element mit dem angegebenen Schlüssel enthält. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Kopiert die Elemente des DictionaryEditor in ein Array, beginnend bei einem bestimmten Array-Index. |
| [get_Item](#get_Item-java.lang.String-) | Liest oder setzt das Element mit dem angegebenen Schlüssel. |
| [getAllKeys](#getAllKeys--) | Vollständige Sammlung von Schlüsseln. Enthält bearbeitbare und nicht bearbeitbare Schlüssel. |
| [getKeys](#getKeys--) | Sammlung bearbeitbarer Schlüssel. |
| [getValues](#getValues--) | Liefert ein {@link ICollection}, das die Werte im {@link DictionaryEditor} enthält. |
| [isReadOnly](#isReadOnly--) | Liefert einen Wert, der angibt, ob {@link DictionaryEditor} schreibgeschützt ist. |
| [iterator](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Entfernt das erste Vorkommen eines bestimmten Objekts aus dem DictionaryEditor. |
| [remove](#remove-java.lang.String-) | Entfernt das Element mit dem angegebenen Schlüssel aus dem {@link DictionaryEditor}. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Liest oder setzt das Element mit dem angegebenen Schlüssel. |
| [size](#size--) | Liefert die Anzahl der im {@link DictionaryEditor} enthaltenen Elemente. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-) | Für den Zugriff auf einfache Datentypen wie string, name, bool, number. Gibt null für andere Typen zurück. |

### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Document-}


### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Page-}


### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Resources-}
@exception ArgumentNullException Die Ressourcen sind null.

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Setze ICosPdfPrimitive im Wörterbuch.

### add {#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Setze {@link ICosPdfPrimitive} im Wörterbuch.

### clear {#clear--}
```
public final void clear()
```

Entfernt alle Elemente aus dem {@link DictionaryEditor}.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Bestimmt, ob der DictionaryEditor einen bestimmten Wert enthält.

### containsKey {#containsKey-java.lang.String-}
Bestimmt, ob {@link DictionaryEditor} ein Element mit dem angegebenen Schlüssel enthält.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Kopiert die Elemente des DictionaryEditor in ein Array, beginnend bei einem bestimmten Array-Index.

### get_Item {#get_Item-java.lang.String-}
Liest oder setzt das Element mit dem angegebenen Schlüssel.

### getAllKeys {#getAllKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllKeys()
```

Vollständige Sammlung von Schlüsseln. Enthält bearbeitbare und nicht bearbeitbare Schlüssel.

**Returns:**
Iterable einer String-Instanz

### getKeys {#getKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Sammlung bearbeitbarer Schlüssel.

**Returns:**
Iterable einer String-Instanz

### getValues {#getValues--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< ICosPdfPrimitive > getValues()
```

Liefert ein {@link ICollection}, das die Werte im {@link DictionaryEditor} enthält.

**Returns:**
Iterable einer ICosPdfPrimitive-Instanz

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Liefert einen Wert, der angibt, ob {@link DictionaryEditor} schreibgeschützt ist.

**Returns:**
true, wenn {@link DictionaryEditor} schreibgeschützt ist; andernfalls false.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , ICosPdfPrimitive >> iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Returns:**
Ein Enumerator, der verwendet werden kann, um durch die Sammlung zu iterieren.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Entfernt das erste Vorkommen eines bestimmten Objekts aus dem DictionaryEditor.

### remove {#remove-java.lang.String-}
Entfernt das Element mit dem angegebenen Schlüssel aus dem {@link DictionaryEditor}.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Liest oder setzt das Element mit dem angegebenen Schlüssel.

### size {#size--}
```
public final int size()
```

Liefert die Anzahl der im {@link DictionaryEditor} enthaltenen Elemente.

**Returns:**
int-Wert

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-}
Für den Zugriff auf einfache Datentypen wie string, name, bool, number. Gibt null für andere Typen zurück.
