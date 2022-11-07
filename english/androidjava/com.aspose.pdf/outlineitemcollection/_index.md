---
title: OutlineItemCollection
second_title: Aspose.PDF for Java API Reference
description: Represents outline entry in outline hierarchy of PDF document.
type: docs
weight: 192
url: /java/com.aspose.pdf/outlineitemcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class OutlineItemCollection implements Iterable
```

Represents outline entry in outline hierarchy of PDF document.
## Constructors

| Constructor | Description |
| --- | --- |
| [OutlineItemCollection(IPdfObject outline)](#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-) | Initializes new instance of this class using internal engine outline entry object. |
| [OutlineItemCollection(OutlineCollection outlines)](#OutlineItemCollection-com.aspose.pdf.OutlineCollection-) | Initializes outline item instance using root hierarchy object. |
## Fields

| Field | Description |
| --- | --- |
| [document](#document) | For internal usage only. |
## Methods

| Method | Description |
| --- | --- |
| [getEngineDict()](#getEngineDict--) | Internal only |
| [getEngineObj()](#getEngineObj--) | Internal only |
| [getTitle()](#getTitle--) | Gets the title for this outline item. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Sets the title for this outline item. |
| [getDestination()](#getDestination--) | Gets the destination for this outline item. |
| [setDestination(IAppointment value)](#setDestination-com.aspose.pdf.IAppointment-) | Sets the destination for this outline item. |
| [getAction()](#getAction--) | Gets the action for this outline item. |
| [setAction(PdfAction value)](#setAction-com.aspose.pdf.PdfAction-) | Sets the action for this outline item. |
| [getColor()](#getColor--) | Gets the color for the title text of this outline item. |
| [setColor(Color value)](#setColor-com.aspose.pdf.java.awt.Color-) | Sets the color for the title text of this outline item. |
| [getItalic()](#getItalic--) | Gets italic flag for the title text of this outline item |
| [setItalic(boolean value)](#setItalic-boolean-) | Sets italic flag for the title text of this outline item |
| [getBold()](#getBold--) | Gets bold flag for the title text of this outline item |
| [setBold(boolean value)](#setBold-boolean-) | Sets bold flag for the title text of this outline item |
| [getFirst()](#getFirst--) | Gets the outline item representing the first top-level item in the outline hierarchy. |
| [getLast()](#getLast--) | Gets the outline item representing the last top-level item in the outline hierarchy. |
| [getPrev()](#getPrev--) | Gets the outline item representing previous item relatively this item in the outline hierarchy. |
| [getNext()](#getNext--) | Gets the outline item representing next item relatively this item in the outline hierarchy. |
| [getParent()](#getParent--) | Gets the parent object of this outline item in the outline hierarchy. |
| [size()](#size--) | Gets the total number of outline items at all levels in the document outline hierarchy. |
| [isSynchronized()](#isSynchronized--) | Gets the value indicating whether access to this collection is synchronized (thread safe). |
| [getSyncRoot()](#getSyncRoot--) | Gets the object that can be used to synchronize access to this collection. |
| [getOpen()](#getOpen--) | Get open status (true/false) for outline item. |
| [setOpen(boolean value)](#setOpen-boolean-) | Sets open status (true/false) for outline item. |
| [delete()](#delete--) | Deletes this outline item from the document outline hierarchy. |
| [delete(String name)](#delete-java.lang.String-) | Deletes outline entry with specified name from the document outline hierarchy. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [add(OutlineItemCollection outline)](#add-com.aspose.pdf.OutlineItemCollection-) | Adds outline item to collection. |
| [insert(int index, OutlineItemCollection outline)](#insert-int-com.aspose.pdf.OutlineItemCollection-) | Inserts the outline item into collection at the specified place. |
| [get_Item(int index)](#get-Item-int-) | Gets outline item from the collection using index. |
| [getLevel()](#getLevel--) | Gets hierarchy level of outline item. |
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

### document {#document}
```
public IPdfDocument document
```


For internal usage only.

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
### getTitle() {#getTitle--}
```
public String getTitle()
```


Gets the title for this outline item.

**Returns:**
java.lang.String - String value
### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Sets the title for this outline item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getDestination() {#getDestination--}
```
public IAppointment getDestination()
```


Gets the destination for this outline item.

**Returns:**
[IAppointment](../../com.aspose.pdf/iappointment) - IAppointment value
### setDestination(IAppointment value) {#setDestination-com.aspose.pdf.IAppointment-}
```
public void setDestination(IAppointment value)
```


Sets the destination for this outline item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAppointment](../../com.aspose.pdf/iappointment) | IAppointment value |

### getAction() {#getAction--}
```
public PdfAction getAction()
```


Gets the action for this outline item.

**Returns:**
[PdfAction](../../com.aspose.pdf/pdfaction) - PdfAction value
### setAction(PdfAction value) {#setAction-com.aspose.pdf.PdfAction-}
```
public void setAction(PdfAction value)
```


Sets the action for this outline item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | PdfAction value |

### getColor() {#getColor--}
```
public Color getColor()
```


Gets the color for the title text of this outline item.

**Returns:**
[Color](../../com.aspose.pdf.java.awt/color) - Color value
### setColor(Color value) {#setColor-com.aspose.pdf.java.awt.Color-}
```
public void setColor(Color value)
```


Sets the color for the title text of this outline item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf.java.awt/color) | Color object |

### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Gets italic flag for the title text of this outline item

**Returns:**
boolean - boolean value
### setItalic(boolean value) {#setItalic-boolean-}
```
public void setItalic(boolean value)
```


Sets italic flag for the title text of this outline item

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getBold() {#getBold--}
```
public boolean getBold()
```


Gets bold flag for the title text of this outline item

**Returns:**
boolean - boolean value
### setBold(boolean value) {#setBold-boolean-}
```
public void setBold(boolean value)
```


Sets bold flag for the title text of this outline item

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getFirst() {#getFirst--}
```
public OutlineItemCollection getFirst()
```


Gets the outline item representing the first top-level item in the outline hierarchy.

**Returns:**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) - OutlineItemCollection value
### getLast() {#getLast--}
```
public OutlineItemCollection getLast()
```


Gets the outline item representing the last top-level item in the outline hierarchy.

**Returns:**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) - OutlineItemCollection value
### getPrev() {#getPrev--}
```
public OutlineItemCollection getPrev()
```


Gets the outline item representing previous item relatively this item in the outline hierarchy.

**Returns:**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) - OutlineItemCollection value
### getNext() {#getNext--}
```
public OutlineItemCollection getNext()
```


Gets the outline item representing next item relatively this item in the outline hierarchy.

**Returns:**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) - OutlineItemCollection value
### getParent() {#getParent--}
```
public Object getParent()
```


Gets the parent object of this outline item in the outline hierarchy.

**Returns:**
java.lang.Object - Object value
### size() {#size--}
```
public int size()
```


Gets the total number of outline items at all levels in the document outline hierarchy.

**Returns:**
int - int value
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Gets the value indicating whether access to this collection is synchronized (thread safe).

**Returns:**
boolean - boolean value
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Gets the object that can be used to synchronize access to this collection.

**Returns:**
java.lang.Object - Object value
### getOpen() {#getOpen--}
```
public boolean getOpen()
```


Get open status (true/false) for outline item.

**Returns:**
boolean - boolean value
### setOpen(boolean value) {#setOpen-boolean-}
```
public void setOpen(boolean value)
```


Sets open status (true/false) for outline item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

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

### iterator() {#iterator--}
```
public System.Collections.IEnumerator iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator - An System.Collections.IEnumerator object that can be used to iterate through the collection.
### add(OutlineItemCollection outline) {#add-com.aspose.pdf.OutlineItemCollection-}
```
public void add(OutlineItemCollection outline)
```


Adds outline item to collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outline | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | The outline item to be added. |

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
### getLevel() {#getLevel--}
```
public int getLevel()
```


Gets hierarchy level of outline item.

**Returns:**
int - int value
