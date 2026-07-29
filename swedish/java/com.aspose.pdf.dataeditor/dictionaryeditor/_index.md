---
title: "DictionaryEditor"
linktitle: "DictionaryEditor"
second_title: "Aspose.PDF för Java API-referens"
description: "En klass för åtkomst till ett dokuments träd-ordbok (dokumentordbok, sidordbok, resurserordbok)."
type: docs
weight: 70
url: /sv/java/com.aspose.pdf.dataeditor/dictionaryeditor/
---
**Inheritance:**
java.lang.Object, java.util.Dictionary <K,V> java.util.Hashtable < String , ICosPdfPrimitive > com.aspose.pdf.dataeditor.DictionaryEditor, java.util.Dictionary <K,V>, java.util.Hashtable < String , ICosPdfPrimitive > com.aspose.pdf.dataeditor.DictionaryEditor, java.util.Hashtable < String , ICosPdfPrimitive >, com.aspose.pdf.dataeditor.DictionaryEditor

**All Implemented Interfaces:**
Serializable, Cloneable, Map < String, ICosPdfPrimitive >

```
public class DictionaryEditor extends Hashtable < String , ICosPdfPrimitive >
```

En klass för åtkomst till ett dokuments träd-ordbok (dokumentordbok, sidordbok, resurserordbok).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Document-) |  |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Page-) |  |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Resources-) | @exception ArgumentNullException Resurserna är null. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Ange ICosPdfPrimitive till ordbok. |
| [add](#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Ange {@link ICosPdfPrimitive} till ordbok. |
| [clear](#clear--) | Tar bort alla objekt från {@link DictionaryEditor}. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Bestämmer om DictionaryEditor innehåller ett specifikt värde. |
| [containsKey](#containsKey-java.lang.String-) | Bestämmer om {@link DictionaryEditor} innehåller ett element med den angivna nyckeln. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Kopierar elementen i DictionaryEditor till en Array, med start vid ett specifikt Array-index. |
| [get_Item](#get_Item-java.lang.String-) | Hämtar eller anger elementet med den angivna nyckeln. |
| [getAllKeys](#getAllKeys--) | Fullständig samling av nycklar. Innehåller redigerbara och icke-redigerbara nycklar. |
| [getKeys](#getKeys--) | Samling av redigerbara nycklar. |
| [getValues](#getValues--) | Hämtar en {@link ICollection} som innehåller värdena i {@link DictionaryEditor}. |
| [isReadOnly](#isReadOnly--) | Hämtar ett värde som indikerar om {@link DictionaryEditor} är skrivskyddad. |
| [iterator](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Tar bort den första förekomsten av ett specifikt objekt från DictionaryEditor. |
| [remove](#remove-java.lang.String-) | Tar bort elementet med den angivna nyckeln från {@link DictionaryEditor}. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Hämtar eller anger elementet med den angivna nyckeln. |
| [size](#size--) | Hämtar antalet element som finns i {@link DictionaryEditor}. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-) | För åtkomst till enkla datatyper som string, name, bool, number. Returnerar null för andra typer. |

### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Document-}


### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Page-}


### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Resources-}
@exception ArgumentNullException Resurserna är null.

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Ange ICosPdfPrimitive till ordbok.

### add {#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Ange {@link ICosPdfPrimitive} till ordbok.

### clear {#clear--}
```
public final void clear()
```

Tar bort alla objekt från {@link DictionaryEditor}.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Bestämmer om DictionaryEditor innehåller ett specifikt värde.

### containsKey {#containsKey-java.lang.String-}
Bestämmer om {@link DictionaryEditor} innehåller ett element med den angivna nyckeln.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Kopierar elementen i DictionaryEditor till en Array, med start vid ett specifikt Array-index.

### get_Item {#get_Item-java.lang.String-}
Hämtar eller anger elementet med den angivna nyckeln.

### getAllKeys {#getAllKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllKeys()
```

Fullständig samling av nycklar. Innehåller redigerbara och icke-redigerbara nycklar.

**Returns:**
Itererbar av String-instans

### getKeys {#getKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Samling av redigerbara nycklar.

**Returns:**
Itererbar av String-instans

### getValues {#getValues--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< ICosPdfPrimitive > getValues()
```

Hämtar en {@link ICollection} som innehåller värdena i {@link DictionaryEditor}.

**Returns:**
Itererbar av ICosPdfPrimitive-instans

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Hämtar ett värde som indikerar om {@link DictionaryEditor} är skrivskyddad.

**Returns:**
true om {@link DictionaryEditor} är skrivskyddad; annars false.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , ICosPdfPrimitive >> iterator()
```

Returnerar en enumerator som itererar genom samlingen.

**Returns:**
En enumerator som kan användas för att iterera genom samlingen.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Tar bort den första förekomsten av ett specifikt objekt från DictionaryEditor.

### remove {#remove-java.lang.String-}
Tar bort elementet med den angivna nyckeln från {@link DictionaryEditor}.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Hämtar eller anger elementet med den angivna nyckeln.

### size {#size--}
```
public final int size()
```

Hämtar antalet element som finns i {@link DictionaryEditor}.

**Returns:**
int‑värde

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-}
För åtkomst till enkla datatyper som string, name, bool, number. Returnerar null för andra typer.
