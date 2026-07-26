---
title: "CosPdfDictionary"
linktitle: "CosPdfDictionary"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Eine Klasse zum Zugriff auf das Wörterbuch eines Objekts."
type: docs
weight: 20
url: /de/java/com.aspose.pdf.dataeditor/cospdfdictionary/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.dataeditor.CosPdfPrimitive com.aspose.pdf.dataeditor.CosPdfDictionary, com.aspose.pdf.dataeditor.CosPdfPrimitive, com.aspose.pdf.dataeditor.CosPdfDictionary

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, ICosPdfPrimitive >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, ICosPdfPrimitive, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>

```
public class CosPdfDictionary extends CosPdfPrimitive implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , ICosPdfPrimitive >
```

Eine Klasse zum Zugriff auf das Wörterbuch eines Objekts.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CosPdfDictionary](#CosPdfDictionary-com.aspose.pdf.Resources-) | Erstellt ein Wörterbuch aus Ressourcen. @exception ArgumentNullException Die Ressourcen sind null. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Setze ICosPdfPrimitive im Wörterbuch. |
| [add](#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Setzt {@link ICosPdfPrimitive} im Wörterbuch. @exception ArgumentException Wirft eine Ausnahme, wenn Schlüssel/Wert nicht bearbeitet oder entfernt werden können. |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Paar hinzufügen. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Element hinzufügen. |
| [clear](#clear--) | Entfernt alle Elemente aus dem {@link CosPdfDictionary}. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Bestimmt, ob das CosPdfDictionary einen bestimmten Wert enthält. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Gibt true zurück, wenn ein Element enthalten ist. |
| [containsKey](#containsKey-java.lang.String-) | Bestimmt, ob der {@link CosPdfDictionary} ein Element mit dem angegebenen Schlüssel enthält. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Kopiert die Elemente des CosPdfDictionary in ein Array, beginnend an einem bestimmten Array-Index. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | In Array kopieren |
| [createEmptyDictionary](#createEmptyDictionary-com.aspose.pdf.Document-) | Erstellt ein leeres Wörterbuch, das dem Dokument angehängt wird. |
| [createEmptyDictionary](#createEmptyDictionary-com.aspose.pdf.Page-) | Erstellt ein leeres Wörterbuch, das der Seite angehängt wird. |
| [get_Item](#get_Item-java.lang.String-) | Liest oder setzt das Element mit dem angegebenen Schlüssel. |
| [getAllKeys](#getAllKeys--) | Vollständige Sammlung von Schlüsseln. Enthält bearbeitbare und nicht bearbeitbare Schlüssel. |
| [getKeys](#getKeys--) | Sammlung bearbeitbarer Schlüssel. |
| [getValues](#getValues--) | Liefert eine {@link ICollection}, die die Werte im {@link CosPdfDictionary} enthält. |
| [isReadOnly](#isReadOnly--) | Liefert einen Wert, der angibt, ob das {@link CosPdfDictionary} schreibgeschützt ist. |
| [iterator](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Entfernt das erste Vorkommen eines bestimmten Objekts aus dem CosPdfDictionary. |
| [remove](#remove-java.lang.String-) | Entfernt das Element mit dem angegebenen Schlüssel aus dem {@link CosPdfDictionary}. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Element entfernen |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Element nach Schlüssel entfernen. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Liefert oder setzt das Element mit dem angegebenen Schlüssel. @exception ArgumentNullException Der Schlüssel ist null. @exception KeyNotFoundException Die Eigenschaft wurde abgerufen und der Schlüssel wurde nicht gefunden. @exception ArgumentException Wirft eine Ausnahme, wenn der Schlüssel nicht bearbeitet/gesetzt werden kann. |
| [size](#size--) | Liefert die Anzahl der im {@link CosPdfDictionary} enthaltenen Elemente. |
| [toCosPdfDictionary](#toCosPdfDictionary--) | Versucht, diese Instanz in {@link CosPdfDictionary} zu casten. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-) | Für den Zugriff auf einfache Datentypen wie string, name, bool, number. Gibt null für andere Typen zurück. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Versuchen, den Wert zu erhalten |

### CosPdfDictionary {#CosPdfDictionary-com.aspose.pdf.Resources-}
Erstellt ein Wörterbuch aus Ressourcen. @exception ArgumentNullException Die Ressourcen sind null.

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Setze ICosPdfPrimitive im Wörterbuch.

### add {#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Setzt {@link ICosPdfPrimitive} im Wörterbuch. @exception ArgumentException Wirft eine Ausnahme, wenn Schlüssel/Wert nicht bearbeitet oder entfernt werden können.

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Paar hinzufügen.

### addItem {#addItem-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Element hinzufügen.

### clear {#clear--}
```
public final void clear()
```

Entfernt alle Elemente aus dem {@link CosPdfDictionary}.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Bestimmt, ob das CosPdfDictionary einen bestimmten Wert enthält.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Gibt true zurück, wenn ein Element enthalten ist.

### containsKey {#containsKey-java.lang.String-}
Bestimmt, ob der {@link CosPdfDictionary} ein Element mit dem angegebenen Schlüssel enthält.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Kopiert die Elemente des CosPdfDictionary in ein Array, beginnend an einem bestimmten Array-Index.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
In Array kopieren

### createEmptyDictionary {#createEmptyDictionary-com.aspose.pdf.Document-}
Erstellt ein leeres Wörterbuch, das dem Dokument angehängt wird.

### createEmptyDictionary {#createEmptyDictionary-com.aspose.pdf.Page-}
Erstellt ein leeres Wörterbuch, das der Seite angehängt wird.

### get_Item {#get_Item-java.lang.String-}
Liest oder setzt das Element mit dem angegebenen Schlüssel.

### getAllKeys {#getAllKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllKeys()
```

Vollständige Sammlung von Schlüsseln. Enthält bearbeitbare und nicht bearbeitbare Schlüssel.

**Returns:**
Liste von String-Werten

### getKeys {#getKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Sammlung bearbeitbarer Schlüssel.

**Returns:**
Liste von String-Werten

### getValues {#getValues--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< ICosPdfPrimitive > getValues()
```

Liefert eine {@link ICollection}, die die Werte im {@link CosPdfDictionary} enthält.

**Returns:**
Liste von ICosPdfPrimitive-Instanzen

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Liefert einen Wert, der angibt, ob das {@link CosPdfDictionary} schreibgeschützt ist.

**Returns:**
true, wenn das {@link CosPdfDictionary} schreibgeschützt ist; andernfalls false.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , ICosPdfPrimitive >> iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Returns:**
Ein Enumerator, der verwendet werden kann, um durch die Sammlung zu iterieren.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Entfernt das erste Vorkommen eines bestimmten Objekts aus dem CosPdfDictionary.

### remove {#remove-java.lang.String-}
Entfernt das Element mit dem angegebenen Schlüssel aus dem {@link CosPdfDictionary}.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Element entfernen

### removeItemByKey {#removeItemByKey-java.lang.String-}
Element nach Schlüssel entfernen.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Liefert oder setzt das Element mit dem angegebenen Schlüssel. @exception ArgumentNullException Der Schlüssel ist null. @exception KeyNotFoundException Die Eigenschaft wurde abgerufen und der Schlüssel wurde nicht gefunden. @exception ArgumentException Wirft eine Ausnahme, wenn der Schlüssel nicht bearbeitet/gesetzt werden kann.

### size {#size--}
```
public final int size()
```

Liefert die Anzahl der im {@link CosPdfDictionary} enthaltenen Elemente.

**Returns:**
int-Wert

### toCosPdfDictionary {#toCosPdfDictionary--}
```
public CosPdfDictionary toCosPdfDictionary()
```

Versucht, diese Instanz in {@link CosPdfDictionary} zu casten.

**Returns:**
null, wenn die Instanz nicht {@link CosPdfDictionary} ist, sonst {@link CosPdfDictionary}.

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-}
Für den Zugriff auf einfache Datentypen wie string, name, bool, number. Gibt null für andere Typen zurück.

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Versuchen, den Wert zu erhalten
