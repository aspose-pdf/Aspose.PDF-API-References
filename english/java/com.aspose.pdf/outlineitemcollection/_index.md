---
title: OutlineItemCollection
second_title: Aspose.PDF for Java API Reference
description: Represents outline entry in outline hierarchy of PDF document.
type: docs
weight: 3270
url: /java/com.aspose.pdf/outlineitemcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Outlines com.aspose.pdf.OutlineItemCollection, com.aspose.pdf.Outlines, com.aspose.pdf.OutlineItemCollection

**All Implemented Interfaces:**
Iterable < OutlineItemCollection >

```
public final class OutlineItemCollection extends Outlines
```

Represents outline entry in outline hierarchy of PDF document.

## Constructors

| Constructor | Description |
| --- | --- |
| [OutlineItemCollection](#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-) | Initializes new instance of this class using internal engine outline entry object. |
| [OutlineItemCollection](#OutlineItemCollection-com.aspose.pdf.OutlineCollection-) | Initializes outline item instance using root hierarchy object. |

## Methods

| Method | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.OutlineItemCollection-) | Adds outline item to collection. |
| [clear](#clear--) | Clears all items from the collection. |
| [contains](#contains-com.aspose.pdf.OutlineItemCollection-) | Not supported yet. Always throws NotImplementedException |
| [copyTo](#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-) | Copies the outline entries to an System.Array, starting at a particular System.Array index. |
| [delete](#delete--) | Deletes this outline item from the document outline hierarchy. |
| [delete](#delete-java.lang.String-) | Deletes this outline item from the document outline hierarchy. |
| [get_Item](#get_Item-int-) | Gets outline item from the collection using index. |
| [getAction](#getAction--) | Gets the action for this outline item. |
| [getBold](#getBold--) | Gets bold flag for the title text of this outline item |
| [getColor](#getColor--) | Gets the color for the title text of this outline item. |
| [getDestination](#getDestination--) | Gets the destination for this outline item. |
| [getEngineDict](#getEngineDict--) | Internal only |
| [getEngineObj](#getEngineObj--) | Internal only |
| [getFirst](#getFirst--) | Gets the outline item representing the first top-level item in the outline hierarchy. |
| [getItalic](#getItalic--) | Gets an italic flag for the title text of this outline item |
| [getLast](#getLast--) | Gets the outline item representing the last top-level item in the outline hierarchy. |
| [getLevel](#getLevel--) | Gets hierarchy level of outline item. |
| [getNext](#getNext--) | Gets the outline item representing next item relatively this item in the outline hierarchy. |
| [getOpen](#getOpen--) | Get open status (true/false) for outline item. |
| [getParent](#getParent--) | Gets the parent object of this outline item in the outline hierarchy. |
| [getPrev](#getPrev--) | Gets the outline item representing previous item relatively this item in the outline hierarchy. |
| [getSyncRoot](#getSyncRoot--) | Gets the object that can be used to synchronize access to this collection. |
| [getTitle](#getTitle--) | Gets the title for this outline item. |
| [getVisibleCount](#getVisibleCount--) | Gets the total number of outline items at all levels in the document outline hierarchy. |
| [hasNext](#hasNext--) | Check if outline item representing next item relatively this item in the outline hierarchy. |
| [insert](#insert-int-com.aspose.pdf.OutlineItemCollection-) | Inserts the outline item into collection at the specified place. |
| [isReadOnly](#isReadOnly--) | Gets a value indicating whether the collection is read-only. |
| [isSynchronized](#isSynchronized--) | Gets the value indicating whether access to this collection is synchronized (thread safe). |
| [iterator](#iterator--) | Returns an enumerator that iterates through the collection. |
| [next](#next--) |  |
| [remove](#remove-int-) | Remove item by index. |
| [remove](#remove-com.aspose.pdf.OutlineItemCollection-) | Not supported yet. Always throws NotImplementedException |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | Sets the action for this outline item. |
| [setBold](#setBold-boolean-) | Sets bold flag for the title text of this outline item |
| [setColor](#setColor-java.awt.Color-) | Sets the color for the title text of this outline item. |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | Sets the destination for this outline item. |
| [setItalic](#setItalic-boolean-) | Sets italic flag for the title text of this outline item |
| [setOpen](#setOpen-boolean-) | Sets open status (true/false) for outline item. |
| [setTitle](#setTitle-java.lang.String-) | Sets the title for this outline item. |
| [size](#size--) | Count of collection items. Please dont confuse with VisibleCount: VisibleCount gets number of visible outline item on all levels. |

### OutlineItemCollection {#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-}
Initializes new instance of this class using internal engine outline entry object.

### OutlineItemCollection {#OutlineItemCollection-com.aspose.pdf.OutlineCollection-}
Initializes outline item instance using root hierarchy object.

### add {#add-com.aspose.pdf.OutlineItemCollection-}
Adds outline item to collection.

### clear {#clear--}
```
public void clear()
```

Clears all items from the collection.

### contains {#contains-com.aspose.pdf.OutlineItemCollection-}
Not supported yet. Always throws NotImplementedException

### copyTo {#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-}
Copies the outline entries to an System.Array, starting at a particular System.Array index.

### delete {#delete--}
```
public void delete()
```

Deletes this outline item from the document outline hierarchy.

### delete {#delete-java.lang.String-}
Deletes this outline item from the document outline hierarchy.

### get_Item {#get_Item-int-}
```
public OutlineItemCollection get_Item(int index)
```

Gets outline item from the collection using index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Index within the collection. |

**Returns:**
OutlineItemCollection object.

### getAction {#getAction--}
```
public PdfAction getAction()
```

Gets the action for this outline item.

**Returns:**
PdfAction value

### getBold {#getBold--}
```
public boolean getBold()
```

Gets bold flag for the title text of this outline item

**Returns:**
boolean value

### getColor {#getColor--}
```
public Color getColor()
```

Gets the color for the title text of this outline item.

**Returns:**
Color value

### getDestination {#getDestination--}
```
public IAppointment getDestination()
```

Gets the destination for this outline item.

**Returns:**
IAppointment value

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

Internal only

**Returns:**
IPdfDictionary object

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Internal only

**Returns:**
IPdfObject object

### getFirst {#getFirst--}
```
public OutlineItemCollection getFirst()
```

Gets the outline item representing the first top-level item in the outline hierarchy.

**Returns:**
OutlineItemCollection value

### getItalic {#getItalic--}
```
public boolean getItalic()
```

Gets an italic flag for the title text of this outline item

**Returns:**
boolean value

### getLast {#getLast--}
```
public OutlineItemCollection getLast()
```

Gets the outline item representing the last top-level item in the outline hierarchy.

**Returns:**
OutlineItemCollection value

### getLevel {#getLevel--}
```
public int getLevel()
```

Gets hierarchy level of outline item.

**Returns:**
int value

### getNext {#getNext--}
```
public OutlineItemCollection getNext()
```

Gets the outline item representing next item relatively this item in the outline hierarchy.

**Returns:**
OutlineItemCollection value

### getOpen {#getOpen--}
```
public boolean getOpen()
```

Get open status (true/false) for outline item.

**Returns:**
boolean value

### getParent {#getParent--}
```
public Outlines getParent()
```

Gets the parent object of this outline item in the outline hierarchy.

**Returns:**
Object value

### getPrev {#getPrev--}
```
public OutlineItemCollection getPrev()
```

Gets the outline item representing previous item relatively this item in the outline hierarchy.

**Returns:**
OutlineItemCollection value

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Gets the object that can be used to synchronize access to this collection.

**Returns:**
Object value

### getTitle {#getTitle--}
```
public String getTitle()
```

Gets the title for this outline item.

**Returns:**
String value

### getVisibleCount {#getVisibleCount--}
```
public int getVisibleCount()
```

Gets the total number of outline items at all levels in the document outline hierarchy.

**Returns:**
int value

### hasNext {#hasNext--}
```
public final boolean hasNext()
```

Check if outline item representing next item relatively this item in the outline hierarchy.

**Returns:**
boolean value

### insert {#insert-int-com.aspose.pdf.OutlineItemCollection-}
Inserts the outline item into collection at the specified place.

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Gets a value indicating whether the collection is read-only.

**Returns:**
boolean value

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Gets the value indicating whether access to this collection is synchronized (thread safe).

**Returns:**
boolean value

### iterator {#iterator--}
```
public Iterator < OutlineItemCollection > iterator()
```

Returns an enumerator that iterates through the collection.

**Returns:**
An System.Collections.IEnumerator object that can be used to iterate through the collection.

### next {#next--}
```
public OutlineItemCollection next()
```



### remove {#remove-int-}
```
public final void remove(int index)
```

Remove item by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Index of item to be deleted. |

### remove {#remove-com.aspose.pdf.OutlineItemCollection-}
Not supported yet. Always throws NotImplementedException

### setAction {#setAction-com.aspose.pdf.PdfAction-}
Sets the action for this outline item.

### setBold {#setBold-boolean-}
```
public void setBold(boolean value)
```

Sets bold flag for the title text of this outline item

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setColor {#setColor-java.awt.Color-}
Sets the color for the title text of this outline item.

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
Sets the destination for this outline item.

### setItalic {#setItalic-boolean-}
```
public void setItalic(boolean value)
```

Sets italic flag for the title text of this outline item

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Sets open status (true/false) for outline item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setTitle {#setTitle-java.lang.String-}
Sets the title for this outline item.

### size {#size--}
```
public int size()
```

Count of collection items. Please dont confuse with VisibleCount: VisibleCount gets number of visible outline item on all levels.

**Returns:**
int value
