---
title: OutlineItemCollection
second_title: Aspose.PDF for Java API Reference
description: Represents outline entry in outline hierarchy of PDF document.
type: docs
weight: 240
url: /java/com.aspose.pdf/outlineitemcollection/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Outlines](../../com.aspose.pdf/outlines)
```
public final class OutlineItemCollection extends Outlines
```

Represents outline entry in outline hierarchy of PDF document.
## Constructors

| Constructor | Description |
| --- | --- |
| [OutlineItemCollection(IPdfObject outline)](#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-) | Initializes new instance of this class using internal engine outline entry object. |
| [OutlineItemCollection(OutlineCollection outlines)](#OutlineItemCollection-com.aspose.pdf.OutlineCollection-) | Initializes outline item instance using root hierarchy object. |
## Methods

| Method | Description |
| --- | --- |
| [add(OutlineItemCollection outline)](#add-com.aspose.pdf.OutlineItemCollection-) | Adds outline item to collection. |
| [clear()](#clear--) | Clears all items from the collection. |
| [contains(OutlineItemCollection item)](#contains-com.aspose.pdf.OutlineItemCollection-) | Not supported yet. |
| [copyTo(OutlineItemCollection[] array, int index)](#copyTo-com.aspose.pdf.OutlineItemCollection---int-) | Copies the outline entries to an System.Array, starting at a particular System.Array index. |
| [delete()](#delete--) | Deletes this outline item from the document outline hierarchy. |
| [delete(String name)](#delete-java.lang.String-) | Deletes outline entry with specified name from the document outline hierarchy. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Gets the action for this outline item. |
| [getBold()](#getBold--) | Gets bold flag for the title text of this outline item |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Gets the color for the title text of this outline item. |
| [getDestination()](#getDestination--) | Gets the destination for this outline item. |
| [getEngineDict()](#getEngineDict--) | Internal only |
| [getEngineObj()](#getEngineObj--) | Internal only |
| [getFirst()](#getFirst--) | Gets the outline item representing the first top-level item in the outline hierarchy. |
| [getItalic()](#getItalic--) | Gets italic flag for the title text of this outline item |
| [getLast()](#getLast--) | Gets the outline item representing the last top-level item in the outline hierarchy. |
| [getLevel()](#getLevel--) | Gets hierarchy level of outline item. |
| [getNext()](#getNext--) | Gets the outline item representing next item relatively this item in the outline hierarchy. |
| [getOpen()](#getOpen--) | Get open status (true/false) for outline item. |
| [getParent()](#getParent--) | Gets the parent object of this outline item in the outline hierarchy. |
| [getPrev()](#getPrev--) | Gets the outline item representing previous item relatively this item in the outline hierarchy. |
| [getSyncRoot()](#getSyncRoot--) | Gets the object that can be used to synchronize access to this collection. |
| [getTitle()](#getTitle--) | Gets the title for this outline item. |
| [getVisibleCount()](#getVisibleCount--) | Gets the total number of outline items at all levels in the document outline hierarchy. |
| [get_Item(int index)](#get-Item-int-) | Gets outline item from the collection using index. |
| [hasNext()](#hasNext--) | Check if outline item representing next item relatively this item in the outline hierarchy. |
| [hashCode()](#hashCode--) |  |
| [insert(int index, OutlineItemCollection outline)](#insert-int-com.aspose.pdf.OutlineItemCollection-) | Inserts the outline item into collection at the specified place. |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether the collection is read-only. |
| [isSynchronized()](#isSynchronized--) | Gets the value indicating whether access to this collection is synchronized (thread safe). |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) |  |
| [next()](#next--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(OutlineItemCollection item)](#remove-com.aspose.pdf.OutlineItemCollection-) | Not supported yet. |
| [remove(int index)](#remove-int-) | Remove item by index. |
| [setAction(PdfAction value)](#setAction-com.aspose.pdf.PdfAction-) | Sets the action for this outline item. |
| [setBold(boolean value)](#setBold-boolean-) | Sets bold flag for the title text of this outline item |
| [setColor(Color value)](#setColor-java.awt.Color-) | Sets the color for the title text of this outline item. |
| [setDestination(IAppointment value)](#setDestination-com.aspose.pdf.IAppointment-) | Sets the destination for this outline item. |
| [setItalic(boolean value)](#setItalic-boolean-) | Sets italic flag for the title text of this outline item |
| [setOpen(boolean value)](#setOpen-boolean-) | Sets open status (true/false) for outline item. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Sets the title for this outline item. |
| [size()](#size--) | Count of collection items. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OutlineItemCollection(IPdfObject outline) {#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-}
```
public OutlineItemCollection(IPdfObject outline)
```


Initializes new instance of this class using internal engine outline entry object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outline | [IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) | Internal engine object of outline entry. |

### OutlineItemCollection(OutlineCollection outlines) {#OutlineItemCollection-com.aspose.pdf.OutlineCollection-}
```
public OutlineItemCollection(OutlineCollection outlines)
```


Initializes outline item instance using root hierarchy object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outlines | [OutlineCollection](../../com.aspose.pdf/outlinecollection) | Outlune collection. |

### add(OutlineItemCollection outline) {#add-com.aspose.pdf.OutlineItemCollection-}
```
public void add(OutlineItemCollection outline)
```


Adds outline item to collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outline | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | The outline item to be added. |

### clear() {#clear--}
```
public void clear()
```


Clears all items from the collection.

### contains(OutlineItemCollection item) {#contains-com.aspose.pdf.OutlineItemCollection-}
```
public boolean contains(OutlineItemCollection item)
```


Not supported yet.

Always throws NotImplementedException

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | The object to locate in the collection |

**Returns:**
boolean - boolean value True - if item found; otherwise, false.
### copyTo(OutlineItemCollection[] array, int index) {#copyTo-com.aspose.pdf.OutlineItemCollection---int-}
```
public void copyTo(OutlineItemCollection[] array, int index)
```


Copies the outline entries to an System.Array, starting at a particular System.Array index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [OutlineItemCollection\[\]](../../com.aspose.pdf/outlineitemcollection) | The one-dimensional System.Array that is the destination. Must have zero-based indexing. |
| index | int | The zero-based index in array at which copying begins. |

### delete() {#delete--}
```
public void delete()
```


Deletes this outline item from the document outline hierarchy.

### delete(String name) {#delete-java.lang.String-}
```
public void delete(String name)
```


Deletes outline entry with specified name from the document outline hierarchy.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Title of outline entry will be deleted. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAction() {#getAction--}
```
public PdfAction getAction()
```


Gets the action for this outline item.

**Returns:**
[PdfAction](../../com.aspose.pdf/pdfaction) - PdfAction value
### getBold() {#getBold--}
```
public boolean getBold()
```


Gets bold flag for the title text of this outline item

**Returns:**
boolean - boolean value
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```


Gets the color for the title text of this outline item.

**Returns:**
[Color](../../java.awt/color) - Color value
### getDestination() {#getDestination--}
```
public IAppointment getDestination()
```


Gets the destination for this outline item.

**Returns:**
[IAppointment](../../com.aspose.pdf/iappointment) - IAppointment value
### getEngineDict() {#getEngineDict--}
```
public IPdfDictionary getEngineDict()
```


Internal only

**Returns:**
[IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) - IPdfDictionary object
### getEngineObj() {#getEngineObj--}
```
public IPdfObject getEngineObj()
```


Internal only

**Returns:**
[IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) - IPdfObject object
### getFirst() {#getFirst--}
```
public OutlineItemCollection getFirst()
```


Gets the outline item representing the first top-level item in the outline hierarchy.

**Returns:**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) - OutlineItemCollection value
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Gets italic flag for the title text of this outline item

**Returns:**
boolean - boolean value
### getLast() {#getLast--}
```
public OutlineItemCollection getLast()
```


Gets the outline item representing the last top-level item in the outline hierarchy.

**Returns:**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) - OutlineItemCollection value
### getLevel() {#getLevel--}
```
public int getLevel()
```


Gets hierarchy level of outline item.

**Returns:**
int - int value
### getNext() {#getNext--}
```
public OutlineItemCollection getNext()
```


Gets the outline item representing next item relatively this item in the outline hierarchy.

**Returns:**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) - OutlineItemCollection value
### getOpen() {#getOpen--}
```
public boolean getOpen()
```


Get open status (true/false) for outline item.

**Returns:**
boolean - boolean value
### getParent() {#getParent--}
```
public Outlines getParent()
```


Gets the parent object of this outline item in the outline hierarchy.

**Returns:**
[Outlines](../../com.aspose.pdf/outlines) - Object value
### getPrev() {#getPrev--}
```
public OutlineItemCollection getPrev()
```


Gets the outline item representing previous item relatively this item in the outline hierarchy.

**Returns:**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) - OutlineItemCollection value
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Gets the object that can be used to synchronize access to this collection.

**Returns:**
java.lang.Object - Object value
### getTitle() {#getTitle--}
```
public String getTitle()
```


Gets the title for this outline item.

**Returns:**
java.lang.String - String value
### getVisibleCount() {#getVisibleCount--}
```
public int getVisibleCount()
```


Gets the total number of outline items at all levels in the document outline hierarchy.

**Returns:**
int - int value
### get_Item(int index) {#get-Item-int-}
```
public OutlineItemCollection get_Item(int index)
```


Gets outline item from the collection using index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index within the collection. |

**Returns:**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) - OutlineItemCollection object.
### hasNext() {#hasNext--}
```
public final boolean hasNext()
```


Check if outline item representing next item relatively this item in the outline hierarchy.

**Returns:**
boolean - boolean value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### insert(int index, OutlineItemCollection outline) {#insert-int-com.aspose.pdf.OutlineItemCollection-}
```
public void insert(int index, OutlineItemCollection outline)
```


Inserts the outline item into collection at the specified place.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index specifying place for inserting. |
| outline | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | The outline item should be inserted. |

### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Gets a value indicating whether the collection is read-only.

**Returns:**
boolean - boolean value
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Gets the value indicating whether access to this collection is synchronized (thread safe).

**Returns:**
boolean - boolean value
### iterator() {#iterator--}
```
public Iterator<OutlineItemCollection> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
java.util.Iterator<com.aspose.pdf.OutlineItemCollection> - An System.Collections.IEnumerator object that can be used to iterate through the collection.
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public final System.Collections.IEnumerator iterator_Rename_Namesake()
```




**Returns:**
com.aspose.ms.System.Collections.IEnumerator
### next() {#next--}
```
public OutlineItemCollection next()
```




**Returns:**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(OutlineItemCollection item) {#remove-com.aspose.pdf.OutlineItemCollection-}
```
public boolean remove(OutlineItemCollection item)
```


Not supported yet.

Always throws NotImplementedException

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | OutlineItemCollection instance |

**Returns:**
boolean - boolean value True - if item removed; otherwise, false.
### remove(int index) {#remove-int-}
```
public final void remove(int index)
```


Remove item by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of item to be deleted. |

### setAction(PdfAction value) {#setAction-com.aspose.pdf.PdfAction-}
```
public void setAction(PdfAction value)
```


Sets the action for this outline item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | PdfAction value |

### setBold(boolean value) {#setBold-boolean-}
```
public void setBold(boolean value)
```


Sets bold flag for the title text of this outline item

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setColor(Color value) {#setColor-java.awt.Color-}
```
public void setColor(Color value)
```


Sets the color for the title text of this outline item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color | Color object |

### setDestination(IAppointment value) {#setDestination-com.aspose.pdf.IAppointment-}
```
public void setDestination(IAppointment value)
```


Sets the destination for this outline item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAppointment](../../com.aspose.pdf/iappointment) | IAppointment value |

### setItalic(boolean value) {#setItalic-boolean-}
```
public void setItalic(boolean value)
```


Sets italic flag for the title text of this outline item

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setOpen(boolean value) {#setOpen-boolean-}
```
public void setOpen(boolean value)
```


Sets open status (true/false) for outline item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Sets the title for this outline item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### size() {#size--}
```
public int size()
```


Count of collection items. Please dont confuse with VisibleCount: VisibleCount gets number of visible outline item on all levels.

**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
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

