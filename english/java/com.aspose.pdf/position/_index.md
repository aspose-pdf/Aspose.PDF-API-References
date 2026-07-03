---
title: Position
second_title: Aspose.PDF for Java API Reference
description: Represents a position object
type: docs
weight: 3940
url: /java/com.aspose.pdf/position/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Position

```
public final class Position extends Object
```

Represents a position object

## Constructors

| Constructor | Description |
| --- | --- |
| [Position](#Position-double-double-) | Initializes a new instance of {@code Position} class |

## Methods

| Method | Description |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Determines whether the specified object is equal to the current {@code Position} object. |
| [getXIndent](#getXIndent--) | Gets the X coordinate of the object |
| [getYIndent](#getYIndent--) | Gets the Y coordinate of the object |
| [hashCode](#hashCode--) | Returns a hash code value for the object. This method is supported for the benefit of hash tables such as those provided by {@link java.util.HashMap}. <p> The general contract of {@code hashCode} is: <ul> <li>Whenever it is invoked on the same object more than once during an execution of a Java application, the {@code hashCode} method must consistently return the same integer, provided no information used in {@code equals} comparisons on the object is modified. This integer need not remain consistent from one execution of an application to another execution of the same application. <li>If two objects are equal according to the {@code equals(Object)} method, then calling the {@code hashCode} method on each of the two objects must produce the same integer result. <li>It is <em>not</em> required that if two objects are unequal according to the {@link java.lang.Object#equals(java.lang.Object)} method, then calling the {@code hashCode} method on each of the two objects must produce distinct integer results. However, the programmer should be aware that producing distinct integer results for unequal objects may improve the performance of hash tables. </ul> <p> As much as is reasonably practical, the hashCode method defined by class {@code Object} does return distinct integers for distinct objects. (This is typically implemented by converting the internal address of the object into an integer, but this implementation technique is not required by the Java<span style="font-size:70%"><sup>TM</sup></span> programming language.) |
| [setXIndent](#setXIndent-double-) | Sets the X coordinate of the object |
| [setYIndent](#setYIndent-double-) | Sets the Y coordinate of the object |
| [toString](#toString--) | Gets string representation for the current {@code Position} object. |

### Position {#Position-double-double-}
```
public Position(double xIndent, double yIndent)
```

Initializes a new instance of {@code Position} class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xIndent |  | X coordinate value. |
| yIndent |  | Y coordinate value. |

### equals {#equals-java.lang.Object-}
Determines whether the specified object is equal to the current {@code Position} object.

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

Gets the X coordinate of the object

**Returns:**
double value

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

Gets the Y coordinate of the object

**Returns:**
double value

### hashCode {#hashCode--}
```
public int hashCode()
```

Returns a hash code value for the object. This method is supported for the benefit of hash tables such as those provided by {@link java.util.HashMap}. <p> The general contract of {@code hashCode} is: <ul> <li>Whenever it is invoked on the same object more than once during an execution of a Java application, the {@code hashCode} method must consistently return the same integer, provided no information used in {@code equals} comparisons on the object is modified. This integer need not remain consistent from one execution of an application to another execution of the same application. <li>If two objects are equal according to the {@code equals(Object)} method, then calling the {@code hashCode} method on each of the two objects must produce the same integer result. <li>It is <em>not</em> required that if two objects are unequal according to the {@link java.lang.Object#equals(java.lang.Object)} method, then calling the {@code hashCode} method on each of the two objects must produce distinct integer results. However, the programmer should be aware that producing distinct integer results for unequal objects may improve the performance of hash tables. </ul> <p> As much as is reasonably practical, the hashCode method defined by class {@code Object} does return distinct integers for distinct objects. (This is typically implemented by converting the internal address of the object into an integer, but this implementation technique is not required by the Java<span style="font-size:70%"><sup>TM</sup></span> programming language.)

**Returns:**
a hash code value for this object. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

Sets the X coordinate of the object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

Sets the Y coordinate of the object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### toString {#toString--}
```
public String toString()
```

Gets string representation for the current {@code Position} object.

**Returns:**
String representration of the Position object.
