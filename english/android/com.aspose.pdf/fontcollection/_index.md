---
title: FontCollection
second_title: Aspose.PDF for Java API Reference
description: Represents font collection.
type: docs
weight: 112
url: /java/com.aspose.pdf/fontcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.ICollection
```
public final class FontCollection implements System.Collections.ICollection
```

Represents font collection.

--------------------

> ```
> The example demonstrates how to make all font declared on page as embedded.
>   
>  // Open document
>  Document doc = new Document(@"D:\Tests\input.pdf");
>  // ensure all fonts declared on page resources are embedded
>  // note that if fonts are declared on form resources they are not accessible from page resources
>  fore(com.aspsoe.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts())
>  {
>      if(!font.isEmbedded())
>          font.isEmbedded(true);
>  }
>  doc.save(@"D:\Tests\input.pdf");
> ```

--------------------

Font collections represented by  FontCollection  class are used in several scenarios. For example, in resources with  Resources.Fonts  property.
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | Gets the number of  Font  object elements actually contained in the collection. |
| [getSyncRoot()](#getSyncRoot--) | Gets an object that can be used to synchronize access to the collection. |
| [isSynchronized()](#isSynchronized--) | Gets a value indicating whether access to the collection is synchronized (thread safe). |
| [iterator()](#iterator--) | Returns an enumerator for the entire collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array |
| [add(Font newFont, String[] resName)](#add-com.aspose.pdf.Font-java.lang.String---) | Adds new font to font resources and returns automatically assigned name of font resource. |
| [add(Font fragment)](#add-com.aspose.pdf.Font-) | Adds the font element at the specified index. |
| [get_Item(int index)](#get-Item-int-) | Gets the font element at the specified index. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Gets font from the collection by font name. |
| [contains(String name)](#contains-java.lang.String-) | Checks if font exists in font collection. |
| [add(String resName, IPdfObject newFont)](#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-) | Add new font to font collection. |
| [add(String resName, String baseFontName)](#add-java.lang.String-java.lang.String-) | Adds to font resources new font entry with specified base font name. |
### size() {#size--}
```
public int size()
```


Gets the number of  Font  object elements actually contained in the collection.

**Returns:**
int
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Gets an object that can be used to synchronize access to the collection.

**Returns:**
java.lang.Object
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Gets a value indicating whether access to the collection is synchronized (thread safe).

**Returns:**
boolean
### iterator() {#iterator--}
```
public System.Collections.IEnumerator iterator()
```


Returns an enumerator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public void copyTo(System.Array array, int index)
```


Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array |  |
| index | int |  |

### add(Font newFont, String[] resName) {#add-com.aspose.pdf.Font-java.lang.String---}
```
public void add(Font newFont, String[] resName)
```


Adds new font to font resources and returns automatically assigned name of font resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newFont | [Font](../../com.aspose.pdf/font) | Font. |
| resName | java.lang.String[] | The automatically assigned resource item name. |

### add(Font fragment) {#add-com.aspose.pdf.Font-}
```
public void add(Font fragment)
```


Adds the font element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fragment | [Font](../../com.aspose.pdf/font) | Font object |

### get_Item(int index) {#get-Item-int-}
```
public Font get_Item(int index)
```


Gets the font element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[Font](../../com.aspose.pdf/font) - 
### get_Item(String name) {#get-Item-java.lang.String-}
```
public Font get_Item(String name)
```


Gets font from the collection by font name. Exception is thrown if font was not found.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the font. |

**Returns:**
[Font](../../com.aspose.pdf/font) - Found font.
### contains(String name) {#contains-java.lang.String-}
```
public boolean contains(String name)
```


Checks if font exists in font collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Font name. |

**Returns:**
boolean
### add(String resName, IPdfObject newFont) {#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-}
```
public void add(String resName, IPdfObject newFont)
```


Add new font to font collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resName | java.lang.String |  |
| newFont | [IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) |  |

### add(String resName, String baseFontName) {#add-java.lang.String-java.lang.String-}
```
public void add(String resName, String baseFontName)
```


Adds to font resources new font entry with specified base font name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resName | java.lang.String |  |
| baseFontName | java.lang.String |  |

