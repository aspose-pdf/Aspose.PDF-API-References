---
title: "AppearanceDictionary"
linktitle: "AppearanceDictionary"
second_title: "Aspose.PDF för Java API-referens"
description: "Annoteringsutseendedictionary som specificerar hur annoteringen ska visas visuellt på sidan."
type: docs
weight: 150
url: /sv/java/com.aspose.pdf/appearancedictionary/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AppearanceDictionary

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XForm >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>

```
public final class AppearanceDictionary extends Object implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XForm >
```

Annoteringsutseendedictionary som specificerar hur annoteringen ska visas visuellt på sidan.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add-java.lang.Object-java.lang.Object-) | Lägger till ett element med den angivna nyckeln och värdet. |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Lägger till ett par med nyckel och värde i ordboken. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XForm-) | Lägg till X-form för angiven nyckel. |
| [clear](#clear--) | Tar bort alla element från ordboken. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Kontrollerar om angivet nyckel‑värde‑par finns i ordboken. |
| [containsKey](#containsKey-java.lang.String-) | Bestämmer om denna ordbok innehåller angiven nyckel. |
| [copyTo](#copyTo-com.aspose.pdf.XForm:A-int-) | / * / * Returnerar ett IDictionaryEnumerator-objekt för ordboken. / * / * / * |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Kopierar elementen i ICollection till en Array, med start vid ett specifikt Array-index. |
| [get_Item](#get_Item-java.lang.String-) | Representerar ett bekvämt sätt att hämta utseendeströmmar. |
| [getDict](#getDict--) | Hämtar pdf-ordbok |
| [getKeys_](#getKeys_--) | Gets keys of the dictionary. If appearance dictionary has subditionaries, then {@code Keys} contains (N\ | R\ | D).state-värden, där N - normal utseende, R - rollover-utseende, D - nedtryckt utseende och state - namnet på tillståndet (t.ex. På, Av för kryssrutor). |
| [getKeys](#getKeys--) | Gets keys of the dictionary. If appearance dictionary has subditionaries, then {@code Keys} contains (N\ | R\ | D).state-värden, där N - normal utseende, R - rollover-utseende, D - nedtryckt utseende och state - namnet på tillståndet (t.ex. På, Av för kryssrutor). |
| [getSyncRoot](#getSyncRoot--) | Hämtar ett objekt som kan användas för att synkronisera åtkomst till ordboken. |
| [getValues_](#getValues_--) | Hämtar listan över ordbokens värden. Resultatsamlingen innehåller listan över XForm-objekt. |
| [getValues](#getValues--) | Hämtar listan över ordbokens värden. Resultatsamlingen innehåller listan över XForm-objekt. |
| [isFixedSize](#isFixedSize--) | Hämtar ett värde som indikerar om ordboken har en fast storlek. |
| [isReadOnly](#isReadOnly--) | Hämtar ett värde som indikerar om ordboken är skrivskyddad. |
| [isSynchronized](#isSynchronized--) | Hämtar ett värde som indikerar om åtkomst till ordboken är synkroniserad (trådsäker). |
| [iterator__Rename_Namesake](#iterator__Rename_Namesake--) | Enumerator för samlingen. |
| [iterator](#iterator--) | Returnerar ett IDictionaryEnumerator-objekt för ordboken. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Tar bort nyckel/värde-par från samlingen. |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Tar bort nyckel från ordboken. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XForm-) |  |
| [size](#size--) | Hämtar antalet element som finns i ordboken. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Försöker hitta nyckel i ordboken och hämtar värdet om det finns. |

### add {#add-java.lang.Object-java.lang.Object-}
Lägger till ett element med den angivna nyckeln och värdet.

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Lägger till ett par med nyckel och värde i ordboken.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XForm-}
Lägg till X-form för angiven nyckel.

### clear {#clear--}
```
public void clear()
```

Tar bort alla element från ordboken.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Kontrollerar om angivet nyckel‑värde‑par finns i ordboken.

### containsKey {#containsKey-java.lang.String-}
Bestämmer om denna ordbok innehåller angiven nyckel.

### copyTo {#copyTo-com.aspose.pdf.XForm:A-int-}
/ * / * Returnerar ett IDictionaryEnumerator-objekt för ordboken. / * / * / *

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Kopierar elementen i ICollection till en Array, med start vid ett specifikt Array-index.

### get_Item {#get_Item-java.lang.String-}
Representerar ett bekvämt sätt att hämta utseendeströmmar.

### getDict {#getDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getDict()
```

Hämtar pdf-ordbok

**Returns:**
IPdfDictionary‑objekt

### getKeys_ {#getKeys_--}
```
public List < String > getKeys_()
```

Hämtar nycklarna i ordboken. Om utseendeordboken har underordböcker, innehåller {@code Keys} (N|R|D).state-värden, där N - normal utseende, R - rollover-utseende, D - nedtryckt utseende och state - namnet på tillståndet (t.ex. På, Av för kryssrutor).

**Returns:**
Lista med String-värden

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Hämtar nycklarna i ordboken. Om utseendeordboken har underordböcker, innehåller {@code Keys} (N|R|D).state-värden, där N - normal utseende, R - rollover-utseende, D - nedtryckt utseende och state - namnet på tillståndet (t.ex. På, Av för kryssrutor).

**Returns:**
Lista med String-värden

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Hämtar ett objekt som kan användas för att synkronisera åtkomst till ordboken.

**Returns:**
Objekt för synkronisering

### getValues_ {#getValues_--}
```
public List < XForm > getValues_()
```

Hämtar listan över ordbokens värden. Resultatsamlingen innehåller listan över XForm-objekt.

**Returns:**
Lista med XForm-värden

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XForm > getValues()
```

Hämtar listan över ordbokens värden. Resultatsamlingen innehåller listan över XForm-objekt.

**Returns:**
Lista med XForm-värden

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

Hämtar ett värde som indikerar om ordboken har en fast storlek.

**Returns:**
booleskt värde

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Hämtar ett värde som indikerar om ordboken är skrivskyddad.

**Returns:**
booleskt värde

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Hämtar ett värde som indikerar om åtkomst till ordboken är synkroniserad (trådsäker).

**Returns:**
booleskt värde

### iterator__Rename_Namesake {#iterator__Rename_Namesake--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XForm >> iterator__Rename_Namesake()
```

Enumerator för samlingen.

**Returns:**
enumerator för samlingens objekt.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XForm >> iterator()
```

Returnerar ett IDictionaryEnumerator-objekt för ordboken.

**Returns:**
Enumerator för ordboken.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Tar bort nyckel/värde-par från samlingen.

### removeItemByKey {#removeItemByKey-java.lang.String-}
Tar bort nyckel från ordboken.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XForm-}


### size {#size--}
```
public int size()
```

Hämtar antalet element som finns i ordboken.

**Returns:**
int‑värde

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Försöker hitta nyckel i ordboken och hämtar värdet om det finns.
