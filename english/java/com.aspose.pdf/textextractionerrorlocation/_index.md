---
title: TextExtractionErrorLocation
second_title: Aspose.PDF for Java API Reference
description: Represents the location in the PDF document where text extraction error has appeared.
type: docs
weight: 369
url: /java/com.aspose.pdf/textextractionerrorlocation/
---
**Inheritance:**
java.lang.Object
```
public final class TextExtractionErrorLocation
```

Represents the location in the PDF document where text extraction error has appeared.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFontUsedKey()](#getFontUsedKey--) | Key (name) of the PDF Font object that is used for showing of the operator that causes text extraction error. |
| [getFormKey()](#getFormKey--) | Key (name) of the PDF Form XObject in which contents stream text extraction error has located. |
| [getObjectType()](#getObjectType--) | Type of the PDF object (Page or xForm) in which contents stream text extraction error has located. |
| [getOperatorIndex()](#getOperatorIndex--) | Index of text showing operator in the contents stream (operator collection) that causes text extraction error. |
| [getOperatorString()](#getOperatorString--) | Text showing operator that causes text extraction error. |
| [getPageNumber()](#getPageNumber--) | Number of the document page where text extraction error has located. |
| [getPath()](#getPath--) | Location of the PDF document where text extraction error has appeared. |
| [getTextStartPoint()](#getTextStartPoint--) | Key (name) of the PDF Font object that is used for showing of the operator that causes text extraction error. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Returns string representation. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFontUsedKey() {#getFontUsedKey--}
```
public String getFontUsedKey()
```


Key (name) of the PDF Font object that is used for showing of the operator that causes text extraction error.

**Returns:**
java.lang.String - String value
### getFormKey() {#getFormKey--}
```
public String getFormKey()
```


Key (name) of the PDF Form XObject in which contents stream text extraction error has located. Not empty if ObjectType == 'xForm'.

**Returns:**
java.lang.String - String value
### getObjectType() {#getObjectType--}
```
public String getObjectType()
```


Type of the PDF object (Page or xForm) in which contents stream text extraction error has located.

**Returns:**
java.lang.String - String value
### getOperatorIndex() {#getOperatorIndex--}
```
public int getOperatorIndex()
```


Index of text showing operator in the contents stream (operator collection) that causes text extraction error.

**Returns:**
int - int value
### getOperatorString() {#getOperatorString--}
```
public String getOperatorString()
```


Text showing operator that causes text extraction error.

**Returns:**
java.lang.String - String value
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Number of the document page where text extraction error has located.

**Returns:**
int - int value
### getPath() {#getPath--}
```
public String getPath()
```


Location of the PDF document where text extraction error has appeared.

**Returns:**
java.lang.String - String value
### getTextStartPoint() {#getTextStartPoint--}
```
public Point getTextStartPoint()
```


Key (name) of the PDF Font object that is used for showing of the operator that causes text extraction error.

**Returns:**
[Point](../../com.aspose.pdf/point) - Point instance
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


Returns string representation.

**Returns:**
java.lang.String - String representation.
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

