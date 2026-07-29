---
title: "CharInfoCollection"
linktitle: "CharInfoCollection"
second_title: "Aspose.PDF for Java API 参考"
description: "<p> 表示 CharInfo 对象的集合。 </p> <hr> <pre> 示例演示如何遍历所有字符并检索字符 //open document Document."
type: docs
weight: 570
url: /zh/java/com.aspose.pdf/charinfocollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CharInfoCollection

**All Implemented Interfaces:**
可迭代 < CharInfo >

```
public final class CharInfoCollection extends Object implements Iterable < CharInfo >
```

<p> 表示 CharInfo 对象集合。 </p> <hr> <pre> The example demonstrates how to iterate thought all the characters and retrieve the character //open document Document pdfDocument = new Document(inFile); //create TextFragmentAbsorber object to collect all the text objects of the page TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber(); //accept the absorber for all the pages pdfDocument.getPages().get_Item(1).accept(textFragmentAbsorber); //get the extracted text fragments TextFragmentCollection textFragmentCollection = textFragmentAbsorber.getTextFragments(); //loop through the fragments for (TextFragment textFragment : ({@code Iterable<TextFragment>})textFragmentCollection) { //loop through the segments for (TextSegment textSegment : ({@code Iterable<TextSegment>}) textFragment.getSegments()) { //loop through the characters {@code for (int i = 1; i <= textSegment.getText().length(); i++)} { CharInfo charInfo = textSegment.getCharacters().get_Item(i); // print character position and rectangle info System.out.println("XIndent : " + charInfo.getPosition().getXIndent()); System.out.println("YIndent : " + charInfo.getPosition().getYIndent()); System.out.println("Width : " + charInfo.getRectangle().getWidth()); System.out.println("Height : " + charInfo.getRectangle().getHeight()); } } } </pre> <hr> <p> 提供对文本段字符定位信息的访问。 </p>

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.pdf.CharInfo-) | 尚未支持。集合为只读，会抛出异常。 |
| [clear](#clear--) | 尚未支持。集合为只读。始终抛出 NotImplementedException。 |
| [contains](#contains-com.aspose.pdf.CharInfo-) | 确定集合是否包含特定值。 |
| [copyTo](#copyTo-com.aspose.pdf.CharInfo:A-int-) | 将整个集合复制到兼容的一维数组中，从目标数组的指定索引开始。 |
| [get_Item](#get_Item-int-) | 获取指定索引 1..n 处的 CharInfo 元素。 |
| [getSyncRoot](#getSyncRoot--) | 获取可用于同步访问集合的对象。 |
| [isReadOnly](#isReadOnly--) | 获取指示集合是否为只读的值 |
| [isSynchronized](#isSynchronized--) | 获取指示对集合的访问是否已同步（线程安全）的值。 |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | 返回整个集合的枚举器。 |
| [iterator](#iterator--) | 返回整个集合的枚举器。 |
| [remove](#remove-com.aspose.pdf.CharInfo-) | 尚未支持。集合为只读，会抛出异常。 |
| [size](#size--) | 获取集合中实际包含的 {@code CharInfo} 对象元素的数量。 |

### add {#add-com.aspose.pdf.CharInfo-}
尚未支持。集合为只读，会抛出异常。

### clear {#clear--}
```
public void clear()
```

尚未支持。集合为只读。始终抛出 NotImplementedException。

### contains {#contains-com.aspose.pdf.CharInfo-}
确定集合是否包含特定值。

### copyTo {#copyTo-com.aspose.pdf.CharInfo:A-int-}
将整个集合复制到兼容的一维数组中，从目标数组的指定索引开始。

### get_Item {#get_Item-int-}
```
public CharInfo get_Item(int index)
```

获取指定索引 1..n 处的 CharInfo 元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 集合中的索引。 |

**Returns:**
CharInfo 对象。

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

获取可用于同步访问集合的对象。

**Returns:**
用于同步的对象

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

获取指示集合是否为只读的值

**Returns:**
布尔值

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

获取指示对集合的访问是否已同步（线程安全）的值。

**Returns:**
布尔值

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

返回整个集合的枚举器。

**Returns:**
Enumerator 对象。

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< CharInfo > iterator()
```

返回整个集合的枚举器。

**Returns:**
Enumerator 对象。

### remove {#remove-com.aspose.pdf.CharInfo-}
尚未支持。集合为只读，会抛出异常。

### size {#size--}
```
public int size()
```

获取集合中实际包含的 {@code CharInfo} 对象元素的数量。

**Returns:**
int 值
