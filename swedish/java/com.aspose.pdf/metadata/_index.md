---
title: "Metadata"
linktitle: "Metadata"
second_title: "Aspose.PDF för Java API-referens"
description: "Tillhandahåller åtkomst till XMP-metadataström."
type: docs
weight: 3050
url: /sv/java/com.aspose.pdf/metadata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Metadata

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XmpValue >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>

```
public final class Metadata extends Object implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpValue >
```

Tillhandahåller åtkomst till XMP-metadataström.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Lägger till ett par med nyckel och värde i ordboken. |
| [addItem](#addItem-java.lang.String-java.lang.Object-) | Lägger till värde i metadata. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-) | Lägger till pdf-extension i metadata. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | Lägger till värde i metadata. |
| [clear](#clear--) | Rensar metadata. |
| [contains](#contains-java.lang.String-) | Kontrollerar om nyckeln finns i metadata. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Kontrollerar om angivet nyckel‑värde‑par finns i ordboken. |
| [containsKey](#containsKey-java.lang.String-) | Bestämmer om denna ordbok innehåller angiven nyckel. |
| [copyTo](#copyTo-com.aspose.ms.System.Array-int-) | Kopierar element från samlingen till en array. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Kopierar element från samlingen till en array. |
| [get_Item](#get_Item-java.lang.String-) | Hämtar data från metadata. |
| [getExtensionFields_Internal](#getExtensionFields_Internal--) | Endast för internt bruk. Hämtar ordboken för tilläggsfält. |
| [getExtensionFields](#getExtensionFields--) | <p> Hämtar ordboken för tilläggsfält. </p> |
| [getItem](#getItem-java.lang.String-) | Hämtar data från metadata. |
| [getKeys](#getKeys--) | Hämtar samling av metadata-nycklar. |
| [getNamespaceUriByPrefix](#getNamespaceUriByPrefix-java.lang.String-) | Returnerar namnrymdens URI för prefix. |
| [getPrefixByNamespaceUri](#getPrefixByNamespaceUri-java.lang.String-) | Returnerar prefix för namnrymdens URI. |
| [getSyncRoot](#getSyncRoot--) | Hämtar samlingens synkroniseringsobjekt. |
| [getValues](#getValues--) | Hämtar värden i metadata. |
| [isFixedSize](#isFixedSize--) | Kontrollerar om samlingen har fast storlek. |
| [isReadOnly](#isReadOnly--) | Kontrollerar om samlingen är skrivskyddad. |
| [isSynchronized](#isSynchronized--) | Kontrollerar om samlingen är synkroniserad. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) |  |
| [iterator](#iterator--) | Returnerar ordboksenumerator. |
| [iteratorIE](#iteratorIE--) | Hämtar enumerator för samlingen. |
| [registerNamespaceUri](#registerNamespaceUri-java.lang.String-java.lang.String-) | Registrerar namnrymdens URI. |
| [registerNamespaceUri](#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-) | Registrerar namnrymdens URI. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Tar bort nyckel/värde-par från samlingen. |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Tar bort post från metadata. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XmpValue-) | Ställer in data från metadata. |
| [setItem](#setItem-java.lang.String-com.aspose.pdf.XmpValue-) | Ställer in data från metadata. |
| [size](#size--) | Hämtar antalet element i samlingen. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Försöker hitta nyckel i ordboken och hämtar värdet om det finns. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue:A-) | Försöker hitta nyckel i ordboken och hämtar värdet om det finns. |

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Lägger till ett par med nyckel och värde i ordboken.

### addItem {#addItem-java.lang.String-java.lang.Object-}
Lägger till värde i metadata.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-}
Lägger till pdf-extension i metadata.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
Lägger till värde i metadata.

### clear {#clear--}
```
public void clear()
```

Rensar metadata.

### contains {#contains-java.lang.String-}
Kontrollerar om nyckeln finns i metadata.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Kontrollerar om angivet nyckel‑värde‑par finns i ordboken.

### containsKey {#containsKey-java.lang.String-}
Bestämmer om denna ordbok innehåller angiven nyckel.

### copyTo {#copyTo-com.aspose.ms.System.Array-int-}
Kopierar element från samlingen till en array.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Kopierar element från samlingen till en array.

### get_Item {#get_Item-java.lang.String-}
Hämtar data från metadata.

### getExtensionFields_Internal {#getExtensionFields_Internal--}
```
public com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpPdfAExtensionSchema > getExtensionFields_Internal()
```

Endast för internt bruk. Hämtar ordboken för tilläggsfält.

**Returns:**
intern objekt

### getExtensionFields {#getExtensionFields--}
```
public Hashtable < String , XmpPdfAExtensionSchema > getExtensionFields()
```

<p> Hämtar ordboken för tilläggsfält. </p>

**Returns:**
{@code Hashtable<String, XmpPdfAExtensionSchema>} objekt

### getItem {#getItem-java.lang.String-}
Hämtar data från metadata.

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Hämtar samling av metadata-nycklar.

**Returns:**
ICollection-objekt

### getNamespaceUriByPrefix {#getNamespaceUriByPrefix-java.lang.String-}
Returnerar namnrymdens URI för prefix.

### getPrefixByNamespaceUri {#getPrefixByNamespaceUri-java.lang.String-}
Returnerar prefix för namnrymdens URI.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Hämtar samlingens synkroniseringsobjekt.

**Returns:**
Objekt för synkronisering

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XmpValue > getValues()
```

Hämtar värden i metadata.

**Returns:**
ICollection-objekt

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

Kontrollerar om samlingen har fast storlek.

**Returns:**
booleskt värde

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Kontrollerar om samlingen är skrivskyddad.

**Returns:**
booleskt värde

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Kontrollerar om samlingen är synkroniserad.

**Returns:**
booleskt värde

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```



### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iterator()
```

Returnerar ordboksenumerator.

**Returns:**
Enumerator.

### iteratorIE {#iteratorIE--}
```
public Iterator <com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iteratorIE()
```

Hämtar enumerator för samlingen.

**Returns:**
IEnumerator-objekt @see IEnumerator

### registerNamespaceUri {#registerNamespaceUri-java.lang.String-java.lang.String-}
Registrerar namnrymdens URI.

### registerNamespaceUri {#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-}
Registrerar namnrymdens URI.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Tar bort nyckel/värde-par från samlingen.

### removeItemByKey {#removeItemByKey-java.lang.String-}
Tar bort post från metadata.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XmpValue-}
Ställer in data från metadata.

### setItem {#setItem-java.lang.String-com.aspose.pdf.XmpValue-}
Ställer in data från metadata.

### size {#size--}
```
public int size()
```

Hämtar antalet element i samlingen.

**Returns:**
int‑värde

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Försöker hitta nyckel i ordboken och hämtar värdet om det finns.

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue:A-}
Försöker hitta nyckel i ordboken och hämtar värdet om det finns.
