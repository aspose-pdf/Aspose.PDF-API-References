---
title: CharInfoCollection
second_title: Aspose.PDF для справки по Java API
description: Представляет коллекцию объектов CharInfo.
type: docs
weight: 57
url: /ru/java/com.aspose.pdf/charinfocollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
java.lang.Iterable
```
public final class CharInfoCollection implements Iterable<CharInfo>
```

Представляет коллекцию объектов CharInfo.

--------------------

```
The example demonstrates how to iterate thought all the characters and retrieve the character

 	      //открыть документ
 	      Document pdfDocument = new Document(inFile);
 	      //создать объект TextFragmentAbsorber для сбора всех текстовых объектов страницы
 	      TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber();
 	      //принять абсорбер для всех страниц
 	      pdfDocument.getPages().get_Item(1).accept(textFragmentAbsorber);
 	      //получить извлеченные текстовые фрагменты
 	      TextFragmentCollection textFragmentCollection = textFragmentAbsorber.getTextFragments();


 	      //цикл по фрагментам
 	      for (TextFragment textFragment : (```
Iterable
```)textFragmentCollection)
          {
 	          //цикл по сегментам
 	          for (TextSegment textSegment : (```
Iterable
```) textFragment.getSegments())
              {
 	              //цикл по символам
                  ```
for (int i = 1; i <= textSegment.getText().length(); i++)
```
                  {

 	                  CharInfo charInfo = textSegment.getCharacters().get_Item(i);

 	                  // print character position and rectangle info

 	                  System.out.println("XIndent : " + charInfo.getPosition().getXIndent());
 	                  System.out.println("YIndent : " + charInfo.getPosition().getYIndent());


 	                  System.out.println("Width : " + charInfo.getRectangle().getWidth());
 	                  System.out.println("Height : " + charInfo.getRectangle().getHeight());

                  }

              }
          }
```

--------------------

Provides access to positioning information of text segment characters.
## Methods

| Method | Description |
| --- | --- |
| [add(CharInfo item)](#add-com.aspose.pdf.CharInfo-) | Not supported yet. |
| [clear()](#clear--) | Not supported yet. |
| [contains(CharInfo item)](#contains-com.aspose.pdf.CharInfo-) | Determines whether the collection contains a specific value. |
| [copyTo(CharInfo[] array, int index)](#copyTo-com.aspose.pdf.CharInfo---int-) | Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSyncRoot()](#getSyncRoot--) | Gets an object that can be used to synchronize access to the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the CharInfo element at the specified index 1..n. |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether collection is read-only |
| [isSynchronized()](#isSynchronized--) | Gets a value indicating whether access to the collection is synchronized (thread safe). |
| [iterator()](#iterator--) | Returns an enumerator for the entire collection. |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) | Returns an enumerator for the entire collection. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(CharInfo item)](#remove-com.aspose.pdf.CharInfo-) | Not supported yet. |
| [size()](#size--) | Gets the number of  CharInfo  object elements actually contained in the collection. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(CharInfo item) {#add-com.aspose.pdf.CharInfo-}
```
public void add (элемент CharInfo)
```


Not supported yet.

Collection is read-only, throws exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [CharInfo](../../com.aspose.pdf/charinfo) | CharInfo instance to add. |

### clear() {#clear--}
```
публичная пустота ясно()
```


Not supported yet.

Collection is read-only. Always throws NotImplementedException.

### contains(CharInfo item) {#contains-com.aspose.pdf.CharInfo-}
```
общественное логическое значение содержит (элемент CharInfo)
```


Determines whether the collection contains a specific value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [CharInfo](../../com.aspose.pdf/charinfo) | The object to locate in the collection |

**Returns:**
boolean - true if item is found in the collection; otherwise, false.
### copyTo(CharInfo[] array, int index) {#copyTo-com.aspose.pdf.CharInfo---int-}
```
public void copyTo(CharInfo[] массив, индекс int)
```


Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [CharInfo\[\]](../../com.aspose.pdf/charinfo) | Array of objects which will be copied. |
| index | int | Starting index from which copying will be started. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
общественное логическое равенство (объект arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
общедоступный окончательный родной класс<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSyncRoot() {#getSyncRoot--}
```
общедоступный объект getSyncRoot()
```


Gets an object that can be used to synchronize access to the collection.

**Returns:**
java.lang.Object - Object for synchronization
### get_Item(int index) {#get-Item-int-}
```
публичный CharInfo get_Item (индекс int)
```


Gets the CharInfo element at the specified index 1..n.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index within the collection. |

**Returns:**
[CharInfo](../../com.aspose.pdf/charinfo) - CharInfo object.
### hashCode() {#hashCode--}
```
общедоступный собственный int hashCode()
```




**Returns:**
int
### isReadOnly() {#isReadOnly--}
```
общественное логическое значение isReadOnly()
```


Gets a value indicating whether collection is read-only

**Returns:**
boolean - boolean value
### isSynchronized() {#isSynchronized--}
```
общественное логическое значение isSynchronized()
```


Gets a value indicating whether access to the collection is synchronized (thread safe).

**Returns:**
boolean - boolean value
### iterator() {#iterator--}
```
общедоступный System.Collections.IEnumerator<CharInfo> итератор()
```


Returns an enumerator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator<com.aspose.pdf.CharInfo> - Enumerator object.
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
общедоступный System.Collections.IEnumerator iterator_Rename_Namesake()
```


Returns an enumerator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator - Enumerator object.
### notify() {#notify--}
```
публичный окончательный родной void notify()
```




### notifyAll() {#notifyAll--}
```
public final родной void notifyAll()
```




### remove(CharInfo item) {#remove-com.aspose.pdf.CharInfo-}
```
public boolean remove (элемент CharInfo)
```


Not supported yet.

Collection is read-only, throws exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [CharInfo](../../com.aspose.pdf/charinfo) | CharInfo instance to remove. |

**Returns:**
boolean - boolean value.
### size() {#size--}
```
общедоступный размер()
```


Gets the number of  CharInfo  object elements actually contained in the collection.

**Returns:**
int - int value
### toString() {#toString--}
```
публичная строка toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
публичный окончательный недействительный ожидание ()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
