---
title: SetDash
second_title: Aspose.PDF for Java API Reference
description: Class representing d operator set line dash pattern.
type: docs
weight: 67
url: /java/com.aspose.pdf.operators/setdash/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class SetDash extends Operator
```

Class representing d operator (set line dash pattern).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetDash(int index, ICommand command)](#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [SetDash(int[] pattern, int phase)](#SetDash-int---int-) | Creates set dash pattern operator. |
## Methods

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromCommand(ICommand command)](#fromCommand-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) |  |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | Gets command |
| [getCommandName()](#getCommandName--) | Gets operator name. |
| [getIndex()](#getIndex--) | Get Operator index in page operators list. |
| [getParameters()](#getParameters--) | Gets array of operator parameters. |
| [getPattern()](#getPattern--) | Dash pattern. |
| [getPhase()](#getPhase--) | Dash phase. |
| [hashCode()](#hashCode--) |  |
| [isTextShowOperator(Operator op)](#isTextShowOperator-com.aspose.pdf.Operator-) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | For internal usage only |
| [setIndex(int value)](#setIndex-int-) | Set Operator index in page operators list. |
| [setPattern(int[] value)](#setPattern-int---) | Dash pattern. |
| [setPhase(int value)](#setPhase-int-) | Dash phase. |
| [toCommand()](#toCommand--) |  |
| [toString()](#toString--) | Gets operator string representation. |
| [toString(IPdfPrimitive primitive)](#toString-com.aspose.pdf.engine.data.IPdfPrimitive-) | Returns text representation of Pdf primitive (string, array, dictionary etc.) according to PDF specification. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SetDash(int index, ICommand command) {#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetDash(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### SetDash(int[] pattern, int phase) {#SetDash-int---int-}
```
public SetDash(int[] pattern, int phase)
```


Creates set dash pattern operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pattern | int[] | Array which defines dash pattern. |
| phase | int | Dash phase. |

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
### fromCommand(ICommand command) {#fromCommand-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public void fromCommand(ICommand command)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) |  |

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
### getPattern() {#getPattern--}
```
public int[] getPattern()
```


Dash pattern. Array's elements shall be numbers that specify the lengths of alternating dashes and gaps. In case of one element array dash and gap lengths are equal.

**Returns:**
int[] - int array
### getPhase() {#getPhase--}
```
public int getPhase()
```


Dash phase. Before beginning to stroke a path, the dash array shall be cycled through, adding up the lengths of dashes and gaps. When the accumulated length equals the value specified by the dash phase, stroking of the path shall begin, and the dash array shall be used cyclically from that point onward.

**Returns:**
int - int value
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

### setPattern(int[] value) {#setPattern-int---}
```
public void setPattern(int[] value)
```


Dash pattern. Array's elements shall be numbers that specify the lengths of alternating dashes and gaps. In case of one element array dash and gap lengths are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | int array |

### setPhase(int value) {#setPhase-int-}
```
public void setPhase(int value)
```


Dash phase. Before beginning to stroke a path, the dash array shall be cycled through, adding up the lengths of dashes and gaps. When the accumulated length equals the value specified by the dash phase, stroking of the path shall begin, and the dash array shall be used cyclically from that point onward.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### toCommand() {#toCommand--}
```
public ICommand toCommand()
```




**Returns:**
[ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand)
### toString() {#toString--}
```
public String toString()
```


Gets operator string representation.

**Returns:**
java.lang.String - [x1 x2] y d, where x1 - dash length, x2 - gap length, y - phase.
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

