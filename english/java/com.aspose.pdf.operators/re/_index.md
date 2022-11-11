---
title: Re
second_title: Aspose.PDF for Java API Reference
description: Class representing re operator add rectangle to the path.
type: docs
weight: 52
url: /java/com.aspose.pdf.operators/re/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class Re extends Operator
```

Class representing re operator (add rectangle to the path).
## Constructors

| Constructor | Description |
| --- | --- |
| [Re(int index, ICommand command)](#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [Re()](#Re--) | Constructor for extracting goals. |
| [Re(double x, double y, double width, double height)](#Re-double-double-double-double-) | Constructor for writing program. |
## Methods

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | Gets command |
| [getCommandName()](#getCommandName--) | Gets operator name. |
| [getHeight()](#getHeight--) | Height of the rectangle. |
| [getIndex()](#getIndex--) | Get Operator index in page operators list. |
| [getParameters()](#getParameters--) | Gets array of operator parameters. |
| [getWidth()](#getWidth--) | Gets width of the rectangle. |
| [getX()](#getX--) | X coordinate of most left side of rectangle. |
| [getY()](#getY--) | Y coordinate of bottom side of rectangle. |
| [hashCode()](#hashCode--) |  |
| [isTextShowOperator(Operator op)](#isTextShowOperator-com.aspose.pdf.Operator-) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | For internal usage only |
| [setHeight(double value)](#setHeight-double-) | Height of the rectangle. |
| [setIndex(int value)](#setIndex-int-) | Set Operator index in page operators list. |
| [setWidth(double value)](#setWidth-double-) | Sets width of the rectangle. |
| [setX(double value)](#setX-double-) | X coordinate of most left side of rectangle. |
| [setY(double value)](#setY-double-) | Y coordinate of bottom side of rectangle. |
| [toString()](#toString--) | Returns text representation of the operator. |
| [toString(IPdfPrimitive primitive)](#toString-com.aspose.pdf.engine.data.IPdfPrimitive-) | Returns text representation of Pdf primitive (string, array, dictionary etc.) according to PDF specification. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Re(int index, ICommand command) {#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public Re(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### Re() {#Re--}
```
public Re()
```


Constructor for extracting goals.

### Re(double x, double y, double width, double height) {#Re-double-double-double-double-}
```
public Re(double x, double y, double width, double height)
```


Constructor for writing program.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | double | The x-coordinate of the bottom-left corner of the rectangle. |
| y | double | The y-coordinate of the bottom-left corner of the rectangle. |
| width | double | The width of the rectangle. |
| height | double | The height of the rectangle. |

### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts visitor object to process operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |

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
### getCommand() {#getCommand--}
```
public ICommand getCommand()
```


Gets command

**Returns:**
[ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) - ICommand object
### getCommandName() {#getCommandName--}
```
public String getCommandName()
```


Gets operator name.

**Returns:**
java.lang.String - String value
### getHeight() {#getHeight--}
```
public double getHeight()
```


Height of the rectangle.

**Returns:**
double - Height of the rectangle.
### getIndex() {#getIndex--}
```
public int getIndex()
```


Get Operator index in page operators list.

**Returns:**
int - int value
### getParameters() {#getParameters--}
```
public ArrayList<CommandParameter> getParameters()
```


Gets array of operator parameters.

**Returns:**
java.util.ArrayList<com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter> - ArrayList of CommandParameter value
### getWidth() {#getWidth--}
```
public double getWidth()
```


Gets width of the rectangle.

**Returns:**
double - width of the rectangle.
### getX() {#getX--}
```
public double getX()
```


X coordinate of most left side of rectangle.

**Returns:**
double - double value
### getY() {#getY--}
```
public double getY()
```


Y coordinate of bottom side of rectangle.

**Returns:**
double - double value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isTextShowOperator(Operator op) {#isTextShowOperator-com.aspose.pdf.Operator-}
```
public static boolean isTextShowOperator(Operator op)
```


Determines if the operator is operator which responsible for text output (Tj, TJ, etc)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | Operator object |

**Returns:**
boolean - True if this is text output operator
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reset() {#reset--}
```
public void reset()
```


For internal usage only

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Height of the rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Height of the rectangle. |

### setIndex(int value) {#setIndex-int-}
```
public void setIndex(int value)
```


Set Operator index in page operators list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Sets width of the rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | width of the rectangle. |

### setX(double value) {#setX-double-}
```
public void setX(double value)
```


X coordinate of most left side of rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setY(double value) {#setY-double-}
```
public void setY(double value)
```


Y coordinate of bottom side of rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### toString() {#toString--}
```
public String toString()
```


Returns text representation of the operator.

**Returns:**
java.lang.String - Text representation of the operator.
### toString(IPdfPrimitive primitive) {#toString-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public static String toString(IPdfPrimitive primitive)
```


Returns text representation of Pdf primitive (string, array, dictionary etc.) according to PDF specification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| primitive | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) | Primitive |

**Returns:**
java.lang.String - Text represetation of the primitive
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

