---
title: CurveTo1
second_title: Aspose.PDF for Java API Reference
description: Class representing v operator append curve to path initial point replicated.
type: docs
weight: 25
url: /java/com.aspose.pdf.operators/curveto1/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class CurveTo1 extends Operator
```

Class representing v operator (append curve to path, initial point replicated).
## Constructors

| Constructor | Description |
| --- | --- |
| [CurveTo1(int index, ICommand command)](#CurveTo1-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [CurveTo1(double x2, double y2, double x3, double y3)](#CurveTo1-double-double-double-double-) | Initializes curve operator. |
## Methods

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts operator selector. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | Gets command |
| [getCommandName()](#getCommandName--) | Gets operator name. |
| [getIndex()](#getIndex--) | Get Operator index in page operators list. |
| [getParameters()](#getParameters--) | Gets array of operator parameters. |
| [getPoints()](#getPoints--) | Points of the curve. |
| [hashCode()](#hashCode--) |  |
| [isTextShowOperator(Operator op)](#isTextShowOperator-com.aspose.pdf.Operator-) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | For internal usage only |
| [setIndex(int value)](#setIndex-int-) | Set Operator index in page operators list. |
| [toString()](#toString--) | Translates command and parameters into string representation. |
| [toString(IPdfPrimitive primitive)](#toString-com.aspose.pdf.engine.data.IPdfPrimitive-) | Returns text representation of Pdf primitive (string, array, dictionary etc.) according to PDF specification. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurveTo1(int index, ICommand command) {#CurveTo1-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public CurveTo1(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### CurveTo1(double x2, double y2, double x3, double y3) {#CurveTo1-double-double-double-double-}
```
public CurveTo1(double x2, double y2, double x3, double y3)
```


Initializes curve operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x2 | double | Abscissa of second point. |
| y2 | double | Ordinate of second point. |
| x3 | double | Abscissa of third point. |
| y3 | double | Ordinate of third point. |

### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts operator selector.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object |

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
### getPoints() {#getPoints--}
```
public Point[] getPoints()
```


Points of the curve.

**Returns:**
com.aspose.pdf.Point[] - array of Point instances
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

### setIndex(int value) {#setIndex-int-}
```
public void setIndex(int value)
```


Set Operator index in page operators list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### toString() {#toString--}
```
public String toString()
```


Translates command and parameters into string representation.

**Returns:**
java.lang.String - Operator text
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

