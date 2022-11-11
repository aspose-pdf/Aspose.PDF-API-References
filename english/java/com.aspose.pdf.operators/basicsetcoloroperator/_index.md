---
title: BasicSetColorOperator
second_title: Aspose.PDF for Java API Reference
description: Base class for set color operators.
type: docs
weight: 16
url: /java/com.aspose.pdf.operators/basicsetcoloroperator/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.SetColorOperator](../../com.aspose.pdf.operators/setcoloroperator)
```
public abstract class BasicSetColorOperator extends SetColorOperator
```

Base class for set color operators.
## Methods

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor IOperatorSelector which provides operators processing. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getB()](#getB--) | Gets red component of color |
| [getC()](#getC--) | Gets cyan component of CMYK color. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Retirns color specified by the operator. |
| [getColorArray()](#getColorArray--) | Gets array of color components. |
| [getCommand()](#getCommand--) | Gets command |
| [getCommandName()](#getCommandName--) | Gets operator name. |
| [getG()](#getG--) | Gets green component of color |
| [getGrey()](#getGrey--) | Gets black component of gray color. |
| [getIndex()](#getIndex--) | Get Operator index in page operators list. |
| [getK()](#getK--) | Gets black component of CMYK color. |
| [getM()](#getM--) | Gets magenta component of CMYK color. |
| [getParameters()](#getParameters--) | Gets array of operator parameters. |
| [getR()](#getR--) | Gets red component of color |
| [getY()](#getY--) | Gets yellow component of CMYK color. |
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
### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public abstract void accept(IOperatorSelector visitor)
```


Accepts visitor IOperatorSelector which provides operators processing.

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
### getB() {#getB--}
```
public double getB()
```


Gets red component of color

**Returns:**
double - double value
### getC() {#getC--}
```
public double getC()
```


Gets cyan component of CMYK color.

**Returns:**
double - double value
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public abstract Color getColor()
```


Retirns color specified by the operator.

**Returns:**
[Color](../../java.awt/color) - Color specified by operator.
### getColorArray() {#getColorArray--}
```
public double[] getColorArray()
```


Gets array of color components.

**Returns:**
double[] - double array
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
### getG() {#getG--}
```
public double getG()
```


Gets green component of color

**Returns:**
double - double value
### getGrey() {#getGrey--}
```
public double getGrey()
```


Gets black component of gray color.

**Returns:**
double - double value
### getIndex() {#getIndex--}
```
public int getIndex()
```


Get Operator index in page operators list.

**Returns:**
int - int value
### getK() {#getK--}
```
public double getK()
```


Gets black component of CMYK color.

**Returns:**
double - double value
### getM() {#getM--}
```
public double getM()
```


Gets magenta component of CMYK color.

**Returns:**
double - double value
### getParameters() {#getParameters--}
```
public ArrayList<CommandParameter> getParameters()
```


Gets array of operator parameters.

**Returns:**
java.util.ArrayList<com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter> - ArrayList of CommandParameter value
### getR() {#getR--}
```
public double getR()
```


Gets red component of color

**Returns:**
double - double value
### getY() {#getY--}
```
public double getY()
```


Gets yellow component of CMYK color.

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

