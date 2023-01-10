---
title: Position
second_title: Aspose.PDF for Java API Reference
description: Represents a position object
type: docs
weight: 292
url: /java/com.aspose.pdf/position/
---
**Inheritance:**
java.lang.Object
```
public final class Position
```

Represents a position object
## Constructors

| Constructor | Description |
| --- | --- |
| [Position(double xIndent, double yIndent)](#Position-double-double-) | Initializes a new instance of  Position  class |
## Methods

| Method | Description |
| --- | --- |
| [getXIndent()](#getXIndent--) | Gets the X coordinate of the object |
| [setXIndent(double value)](#setXIndent-double-) | Sets the X coordinate of the object |
| [getYIndent()](#getYIndent--) | Gets the Y coordinate of the object |
| [setYIndent(double value)](#setYIndent-double-) | Sets the Y coordinate of the object |
| [toString()](#toString--) | Gets string representation for the current  Position  object. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified object is equal to the current  Position  object. |
| [hashCode()](#hashCode--) | Returns a hash code value for the object. |
### Position(double xIndent, double yIndent) {#Position-double-double-}
```
public Position(double xIndent, double yIndent)
```


Initializes a new instance of  Position  class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xIndent | double | X coordinate value. |
| yIndent | double | Y coordinate value. |

### getXIndent() {#getXIndent--}
```
public double getXIndent()
```


Gets the X coordinate of the object

**Returns:**
double - double value
### setXIndent(double value) {#setXIndent-double-}
```
public void setXIndent(double value)
```


Sets the X coordinate of the object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getYIndent() {#getYIndent--}
```
public double getYIndent()
```


Gets the Y coordinate of the object

**Returns:**
double - double value
### setYIndent(double value) {#setYIndent-double-}
```
public void setYIndent(double value)
```


Sets the Y coordinate of the object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### toString() {#toString--}
```
public String toString()
```


Gets string representation for the current  Position  object.

**Returns:**
java.lang.String - String representration of the Position object.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified object is equal to the current  Position  object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Object that is checked for equality. |

**Returns:**
boolean - True in case objects are equal.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code value for the object. This method is supported for the benefit of hash tables such as those provided by java.util.HashMap.

The general contract of  hashCode  is:

 *  Whenever it is invoked on the same object more than once during an execution of a Java application, the  hashCode  method must consistently return the same integer, provided no information used in  equals  comparisons on the object is modified. This integer need not remain consistent from one execution of an application to another execution of the same application.
 *  If two objects are equal according to the  equals(Object)  method, then calling the  hashCode  method on each of the two objects must produce the same integer result.
 *  It is *not* required that if two objects are unequal according to the java.lang.Object\#equals(java.lang.Object)\#equals(java.lang.Object) method, then calling the  hashCode  method on each of the two objects must produce distinct integer results. However, the programmer should be aware that producing distinct integer results for unequal objects may improve the performance of hash tables.

As much as is reasonably practical, the hashCode method defined by class  Object  does return distinct integers for distinct objects. (This is typically implemented by converting the internal address of the object into an integer, but this implementation technique is not required by the JavaTM programming language.)

**Returns:**
int - a hash code value for this object.
