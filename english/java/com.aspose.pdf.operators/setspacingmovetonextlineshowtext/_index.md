---
title: SetSpacingMoveToNextLineShowText
second_title: Aspose.PDF for Java API Reference
description: Class representing  operator set word and character spacing move to the next line and show text.
type: docs
weight: 79
url: /java/com.aspose.pdf.operators/setspacingmovetonextlineshowtext/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.TextOperator](../../com.aspose.pdf.operators/textoperator), [com.aspose.pdf.operators.TextShowOperator](../../com.aspose.pdf.operators/textshowoperator)
```
public class SetSpacingMoveToNextLineShowText extends TextShowOperator
```

Class representing " operator (set word and character spacing, move to the next line and show text).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetSpacingMoveToNextLineShowText(int index, ICommand command)](#SetSpacingMoveToNextLineShowText-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [SetSpacingMoveToNextLineShowText(double aw, double ac, String text)](#SetSpacingMoveToNextLineShowText-double-double-java.lang.String-) | Initializes operator. |
| [SetSpacingMoveToNextLineShowText()](#SetSpacingMoveToNextLineShowText--) | Initializes operator. |
## Methods

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAc()](#getAc--) | Get character spacing. |
| [getAw()](#getAw--) | Gets word spacing. |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | Gets command |
| [getCommandName()](#getCommandName--) | Gets operator name. |
| [getIndex()](#getIndex--) | Get Operator index in page operators list. |
| [getParameters()](#getParameters--) | Gets array of operator parameters. |
| [getText()](#getText--) | Gets text of operator. |
| [hashCode()](#hashCode--) |  |
| [isTextShowOperator(Operator op)](#isTextShowOperator-com.aspose.pdf.Operator-) | Determines if the operator is operator which responsible for text output (Tj, TJ, etc) |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | For internal usage only |
| [setIndex(int value)](#setIndex-int-) | Set Operator index in page operators list. |
| [setText(String value)](#setText-java.lang.String-) | Sets text which operator out on the page. |
| [toString()](#toString--) | Translates command and parameters into string representation. |
| [toString(IPdfPrimitive primitive)](#toString-com.aspose.pdf.engine.data.IPdfPrimitive-) | Returns text representation of Pdf primitive (string, array, dictionary etc.) according to PDF specification. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SetSpacingMoveToNextLineShowText(int index, ICommand command) {#SetSpacingMoveToNextLineShowText-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetSpacingMoveToNextLineShowText(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### SetSpacingMoveToNextLineShowText(double aw, double ac, String text) {#SetSpacingMoveToNextLineShowText-double-double-java.lang.String-}
```
public SetSpacingMoveToNextLineShowText(double aw, double ac, String text)
```


Initializes operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aw | double | double value Word spacing. |
| ac | double | double value Character spacing. |
| text | java.lang.String | string Text value. |

### SetSpacingMoveToNextLineShowText() {#SetSpacingMoveToNextLineShowText--}
```
public SetSpacingMoveToNextLineShowText()
```


Initializes operator.

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
### getAc() {#getAc--}
```
public double getAc()
```


Get character spacing.

**Returns:**
double - double value
### getAw() {#getAw--}
```
public double getAw()
```


Gets word spacing.

**Returns:**
double - double value
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
### getText() {#getText--}
```
public String getText()
```


Gets text of operator.

**Returns:**
java.lang.String - String value
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

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Sets text which operator out on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

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

