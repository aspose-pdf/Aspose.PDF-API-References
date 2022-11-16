---
title: CharInfoCollection
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 CharInfo 对象集合。
type: docs
weight: 57
url: /zh/java/com.aspose.pdf/charinfocollection/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
java.lang.Iterable
```
public final class CharInfoCollection implements Iterable<CharInfo>
```

表示 CharInfo 对象集合。

--------------------

```
The example demonstrates how to iterate thought all the characters and retrieve the character

 	      //打开文件
 	      Document pdfDocument = new Document(inFile);
 	      //创建 TextFragmentAbsorber 对象来收集页面的所有文本对象
 	      TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber();
 	      //接受所有页面的吸收器
 	      pdfDocument.getPages().get_Item(1).accept(textFragmentAbsorber);
 	      //获取提取的文本片段
 	      TextFragmentCollection textFragmentCollection = textFragmentAbsorber.getTextFragments();


 	      //遍历片段
 	      for (TextFragment textFragment : (```
Iterable
```)textFragmentCollection)
          {
 	          //遍历片段
 	          for (TextSegment textSegment : (```
Iterable
```) textFragment.getSegments())
              {
 	              //遍历字符
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
公共无效添加（CharInfo 项目）
```


Not supported yet.

Collection is read-only, throws exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [CharInfo](../../com.aspose.pdf/charinfo) | CharInfo instance to add. |

### clear() {#clear--}
```
公共无效明确（）
```


Not supported yet.

Collection is read-only. Always throws NotImplementedException.

### contains(CharInfo item) {#contains-com.aspose.pdf.CharInfo-}
```
公共布尔值包含（CharInfo 项目）
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
公共无效复制到（CharInfo[]数组，整数索引）
```


Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [CharInfo\[\]](../../com.aspose.pdf/charinfo) | Array of objects which will be copied. |
| index | int | Starting index from which copying will be started. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
公共布尔等于（对象 arg0）
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSyncRoot() {#getSyncRoot--}
```
公共对象 getSyncRoot()
```


Gets an object that can be used to synchronize access to the collection.

**Returns:**
java.lang.Object - Object for synchronization
### get_Item(int index) {#get-Item-int-}
```
public CharInfo get_Item(int 索引)
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
公共本机 int hashCode()
```




**Returns:**
int
### isReadOnly() {#isReadOnly--}
```
公共布尔 isReadOnly()
```


Gets a value indicating whether collection is read-only

**Returns:**
boolean - boolean value
### isSynchronized() {#isSynchronized--}
```
公共布尔 isSynchronized()
```


Gets a value indicating whether access to the collection is synchronized (thread safe).

**Returns:**
boolean - boolean value
### iterator() {#iterator--}
```
公共 System.Collections.IEnumerator<CharInfo>迭代器()
```


Returns an enumerator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator<com.aspose.pdf.CharInfo> - Enumerator object.
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
公共 System.Collections.IEnumerator iterator_Rename_Namesake()
```


Returns an enumerator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator - Enumerator object.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(CharInfo item) {#remove-com.aspose.pdf.CharInfo-}
```
公共布尔删除（CharInfo 项目）
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
公共整数大小（）
```


Gets the number of  CharInfo  object elements actually contained in the collection.

**Returns:**
int - int value
### toString() {#toString--}
```
公共字符串 toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
公共最终无效等待（）
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
公共最终无效等待（长 arg0，int arg1）
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
