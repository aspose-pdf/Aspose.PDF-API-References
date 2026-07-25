---
title: "CharInfoCollection"
linktitle: "CharInfoCollection"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "<p> تمثّل مجموعة كائنات CharInfo. </p> <hr> <pre> يوضح المثال كيفية التكرار عبر جميع الأحرف واسترجاع الحرف //open document Document."
type: docs
weight: 570
url: /ar/java/com.aspose.pdf/charinfocollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CharInfoCollection

**All Implemented Interfaces:**
Iterable < CharInfo >

```
public final class CharInfoCollection extends Object implements Iterable < CharInfo >
```

<p> يمثل مجموعة كائنات CharInfo. </p> <hr> <pre> يوضح المثال كيفية التكرار عبر جميع الأحرف واستخراج الحرف //open document Document pdfDocument = new Document(inFile); //create TextFragmentAbsorber object to collect all the text objects of the page TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber(); //accept the absorber for all the pages pdfDocument.getPages().get_Item(1).accept(textFragmentAbsorber); //get the extracted text fragments TextFragmentCollection textFragmentCollection = textFragmentAbsorber.getTextFragments(); //loop through the fragments for (TextFragment textFragment : ({@code Iterable<TextFragment>})textFragmentCollection) { //loop through the segments for (TextSegment textSegment : ({@code Iterable<TextSegment>}) textFragment.getSegments()) { //loop through the characters {@code for (int i = 1; i <= textSegment.getText().length(); i++)} { CharInfo charInfo = textSegment.getCharacters().get_Item(i); // print character position and rectangle info System.out.println("XIndent : " + charInfo.getPosition().getXIndent()); System.out.println("YIndent : " + charInfo.getPosition().getYIndent()); System.out.println("Width : " + charInfo.getRectangle().getWidth()); System.out.println("Height : " + charInfo.getRectangle().getHeight()); } } } </pre> <hr> <p> يوفر الوصول إلى معلومات تموضع أحرف مقطع النص. </p>

## الطرق

| طريقة | الوصف |
| --- | --- |
| [add](#add-com.aspose.pdf.CharInfo-) | غير مدعوم بعد. المجموعة للقراءة فقط، تُطلق استثناء. |
| [clear](#clear--) | غير مدعوم بعد. المجموعة للقراءة فقط. دائمًا تُطلق NotImplementedException. |
| [contains](#contains-com.aspose.pdf.CharInfo-) | يحدّد ما إذا كانت المجموعة تحتوي على قيمة محددة. |
| [copyTo](#copyTo-com.aspose.pdf.CharInfo:A-int-) | ينسخ المجموعة بالكامل إلى مصفوفة أحادية البعد متوافقة، بدءًا من الفهرس المحدد للمصفوفة الهدف. |
| [get_Item](#get_Item-int-) | يحصل على عنصر CharInfo في الفهرس المحدد 1..n. |
| [getSyncRoot](#getSyncRoot--) | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى المجموعة. |
| [isReadOnly](#isReadOnly--) | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط |
| [isSynchronized](#isSynchronized--) | يحصل على قيمة تشير إلى ما إذا كان الوصول إلى المجموعة مُزامنًا (آمن للخيوط). |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | يعيد عدّادًا للمجموعة بالكامل. |
| [iterator](#iterator--) | يعيد عدّادًا للمجموعة بالكامل. |
| [remove](#remove-com.aspose.pdf.CharInfo-) | غير مدعوم بعد. المجموعة للقراءة فقط، تُطلق استثناء. |
| [size](#size--) | يحصل على عدد عناصر كائن {@code CharInfo} الموجودة فعليًا في المجموعة. |

### add {#add-com.aspose.pdf.CharInfo-}
غير مدعوم بعد. المجموعة للقراءة فقط، تُطلق استثناء.

### clear {#clear--}
```
public void clear()
```

غير مدعوم بعد. المجموعة للقراءة فقط. دائمًا تُطلق NotImplementedException.

### contains {#contains-com.aspose.pdf.CharInfo-}
يحدّد ما إذا كانت المجموعة تحتوي على قيمة محددة.

### copyTo {#copyTo-com.aspose.pdf.CharInfo:A-int-}
ينسخ المجموعة بالكامل إلى مصفوفة أحادية البعد متوافقة، بدءًا من الفهرس المحدد للمصفوفة الهدف.

### get_Item {#get_Item-int-}
```
public CharInfo get_Item(int index)
```

يحصل على عنصر CharInfo في الفهرس المحدد 1..n.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | الفهرس داخل المجموعة. |

**Returns:**
كائن CharInfo.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى المجموعة.

**Returns:**
كائن للمزامنة

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط

**Returns:**
قيمة منطقية

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

يحصل على قيمة تشير إلى ما إذا كان الوصول إلى المجموعة مُزامنًا (آمن للخيوط).

**Returns:**
قيمة منطقية

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

يعيد عدّادًا للمجموعة بالكامل.

**Returns:**
كائن عدّاد.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< CharInfo > iterator()
```

يعيد عدّادًا للمجموعة بالكامل.

**Returns:**
كائن عدّاد.

### remove {#remove-com.aspose.pdf.CharInfo-}
غير مدعوم بعد. المجموعة للقراءة فقط، تُطلق استثناء.

### size {#size--}
```
public int size()
```

يحصل على عدد عناصر كائن {@code CharInfo} الموجودة فعليًا في المجموعة.

**Returns:**
قيمة int
