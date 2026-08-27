---
title: "Metadata"
linktitle: "Metadata"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt Zugriff auf den XMP-Metadaten-Stream bereit."
type: docs
weight: 3050
url: /de/java/com.aspose.pdf/metadata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Metadata

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XmpValue >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>

```
public final class Metadata extends Object implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpValue >
```

Stellt Zugriff auf den XMP-Metadaten-Stream bereit.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Fügt ein Paar mit Schlüssel und Wert zum Wörterbuch hinzu. |
| [addItem](#addItem-java.lang.String-java.lang.Object-) | Fügt einen Wert zu den Metadaten hinzu. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-) | Fügt die PDF-Erweiterung zu den Metadaten hinzu. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | Fügt einen Wert zu den Metadaten hinzu. |
| [clear](#clear--) | Löscht die Metadaten. |
| [contains](#contains-java.lang.String-) | Überprüft, ob der Schlüssel in den Metadaten enthalten ist. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Überprüft, ob das angegebene Schlüssel-Wert-Paar im Wörterbuch enthalten ist. |
| [containsKey](#containsKey-java.lang.String-) | Ermittelt, ob dieses Wörterbuch den angegebenen Schlüssel enthält. |
| [copyTo](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert Elemente der Sammlung in ein Array. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Kopiert Elemente der Sammlung in ein Array. |
| [get_Item](#get_Item-java.lang.String-) | Liest Daten aus den Metadaten. |
| [getExtensionFields_Internal](#getExtensionFields_Internal--) | Nur für den internen Gebrauch. Gibt das Wörterbuch der Erweiterungsfelder zurück. |
| [getExtensionFields](#getExtensionFields--) | <p> Gibt das Wörterbuch der Erweiterungsfelder zurück. </p> |
| [getItem](#getItem-java.lang.String-) | Liest Daten aus den Metadaten. |
| [getKeys](#getKeys--) | Gibt die Sammlung von Metadaten-Schlüsseln zurück. |
| [getNamespaceUriByPrefix](#getNamespaceUriByPrefix-java.lang.String-) | Gibt den Namespace-URI anhand des Präfixes zurück. |
| [getPrefixByNamespaceUri](#getPrefixByNamespaceUri-java.lang.String-) | Gibt das Präfix anhand des Namespace-URI zurück. |
| [getSyncRoot](#getSyncRoot--) | Gibt das Synchronisationsobjekt der Sammlung zurück. |
| [getValues](#getValues--) | Gibt die Werte in den Metadaten zurück. |
| [isFixedSize](#isFixedSize--) | Überprüft, ob die Sammlung eine feste Größe hat. |
| [isReadOnly](#isReadOnly--) | Überprüft, ob die Sammlung schreibgeschützt ist. |
| [isSynchronized](#isSynchronized--) | Überprüft, ob die Sammlung synchronisiert ist. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) |  |
| [iterator](#iterator--) | Gibt den Wörterbuch-Enumerator zurück. |
| [iteratorIE](#iteratorIE--) | Gibt den Enumerator der Sammlung zurück. |
| [registerNamespaceUri](#registerNamespaceUri-java.lang.String-java.lang.String-) | Registriert den Namespace-URI. |
| [registerNamespaceUri](#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-) | Registriert den Namespace-URI. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Entfernt das Schlüssel/Wert-Paar aus der Sammlung. |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Entfernt den Eintrag aus den Metadaten. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XmpValue-) | Setzt Daten aus Metadaten. |
| [setItem](#setItem-java.lang.String-com.aspose.pdf.XmpValue-) | Setzt Daten aus Metadaten. |
| [size](#size--) | Ermittelt die Anzahl der Elemente in der Sammlung. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Versucht, den Schlüssel im Wörterbuch zu finden und ruft den Wert ab, wenn er gefunden wird. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue:A-) | Versucht, den Schlüssel im Wörterbuch zu finden und ruft den Wert ab, wenn er gefunden wird. |

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Fügt ein Paar mit Schlüssel und Wert zum Wörterbuch hinzu.

### addItem {#addItem-java.lang.String-java.lang.Object-}
Fügt einen Wert zu den Metadaten hinzu.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-}
Fügt die PDF-Erweiterung zu den Metadaten hinzu.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
Fügt einen Wert zu den Metadaten hinzu.

### clear {#clear--}
```
public void clear()
```

Löscht die Metadaten.

### contains {#contains-java.lang.String-}
Überprüft, ob der Schlüssel in den Metadaten enthalten ist.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Überprüft, ob das angegebene Schlüssel-Wert-Paar im Wörterbuch enthalten ist.

### containsKey {#containsKey-java.lang.String-}
Ermittelt, ob dieses Wörterbuch den angegebenen Schlüssel enthält.

### copyTo {#copyTo-com.aspose.ms.System.Array-int-}
Kopiert Elemente der Sammlung in ein Array.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Kopiert Elemente der Sammlung in ein Array.

### get_Item {#get_Item-java.lang.String-}
Liest Daten aus den Metadaten.

### getExtensionFields_Internal {#getExtensionFields_Internal--}
```
public com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpPdfAExtensionSchema > getExtensionFields_Internal()
```

Nur für den internen Gebrauch. Gibt das Wörterbuch der Erweiterungsfelder zurück.

**Returns:**
internes Objekt

### getExtensionFields {#getExtensionFields--}
```
public Hashtable < String , XmpPdfAExtensionSchema > getExtensionFields()
```

<p> Gibt das Wörterbuch der Erweiterungsfelder zurück. </p>

**Returns:**
{@code Hashtable<String, XmpPdfAExtensionSchema>} Objekt

### getItem {#getItem-java.lang.String-}
Liest Daten aus den Metadaten.

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Gibt die Sammlung von Metadaten-Schlüsseln zurück.

**Returns:**
ICollection Objekt

### getNamespaceUriByPrefix {#getNamespaceUriByPrefix-java.lang.String-}
Gibt den Namespace-URI anhand des Präfixes zurück.

### getPrefixByNamespaceUri {#getPrefixByNamespaceUri-java.lang.String-}
Gibt das Präfix anhand des Namespace-URI zurück.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Gibt das Synchronisationsobjekt der Sammlung zurück.

**Returns:**
Objekt für Synchronisation

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XmpValue > getValues()
```

Gibt die Werte in den Metadaten zurück.

**Returns:**
ICollection Objekt

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

Überprüft, ob die Sammlung eine feste Größe hat.

**Returns:**
boolescher Wert

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Überprüft, ob die Sammlung schreibgeschützt ist.

**Returns:**
boolescher Wert

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Überprüft, ob die Sammlung synchronisiert ist.

**Returns:**
boolescher Wert

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```



### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iterator()
```

Gibt den Wörterbuch-Enumerator zurück.

**Returns:**
Enumerator.

### iteratorIE {#iteratorIE--}
```
public Iterator <com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iteratorIE()
```

Gibt den Enumerator der Sammlung zurück.

**Returns:**
IEnumerator Objekt @see IEnumerator

### registerNamespaceUri {#registerNamespaceUri-java.lang.String-java.lang.String-}
Registriert den Namespace-URI.

### registerNamespaceUri {#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-}
Registriert den Namespace-URI.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Entfernt das Schlüssel/Wert-Paar aus der Sammlung.

### removeItemByKey {#removeItemByKey-java.lang.String-}
Entfernt den Eintrag aus den Metadaten.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XmpValue-}
Setzt Daten aus Metadaten.

### setItem {#setItem-java.lang.String-com.aspose.pdf.XmpValue-}
Setzt Daten aus Metadaten.

### size {#size--}
```
public int size()
```

Ermittelt die Anzahl der Elemente in der Sammlung.

**Returns:**
int-Wert

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Versucht, den Schlüssel im Wörterbuch zu finden und ruft den Wert ab, wenn er gefunden wird.

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue:A-}
Versucht, den Schlüssel im Wörterbuch zu finden und ruft den Wert ab, wenn er gefunden wird.
