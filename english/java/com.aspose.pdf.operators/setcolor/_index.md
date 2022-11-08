---
title: SetColor
second_title: Aspose.PDF for Java API Reference
description: Represents class for sc operator set color for non-stroking operations.
type: docs
weight: 61
url: /java/com.aspose.pdf.operators/setcolor/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.SetColorOperator](../../com.aspose.pdf.operators/setcoloroperator), [com.aspose.pdf.operators.BasicSetColorOperator](../../com.aspose.pdf.operators/basicsetcoloroperator)
```
public class SetColor extends BasicSetColorOperator
```

Represents class for sc operator (set color for non-stroking operations).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetColor()](#SetColor--) | Initializes operator. |
| [SetColor(int index, ICommand command)](#SetColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [SetColor(double g)](#SetColor-double-) | Set color for stroking operators for DeviceGrey, CalGrey and Indexed color spaces. |
| [SetColor(double r, double g, double b)](#SetColor-double-double-double-) | Set color for stroking operator for DeviceRGB, CalRGB, and Lab color spaces |
| [SetColor(double c, double m, double y, double k)](#SetColor-double-double-double-double-) | Set color for non-stroking operator for CMYK color space |
| [SetColor(double[] color)](#SetColor-double---) | Constructor which allows to specify color components. |
## Methods

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getB()](#getB--) | Gets red component of color |
| [getC()](#getC--) | Gets cyan component of CMYK color. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Not supported yet. |
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
| [toString()](#toString--) | Returns string representation of color. |
| [toString(IPdfPrimitive primitive)](#toString-com.aspose.pdf.engine.data.IPdfPrimitive-) | Returns text representation of Pdf primitive (string, array, dictionary etc.) according to PDF specification. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SetColor() {#SetColor--}
```
public SetColor()
```


Initializes operator.

### SetColor(int index, ICommand command) {#SetColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetColor(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### SetColor(double g) {#SetColor-double-}
```
public SetColor(double g)
```


Set color for stroking operators for DeviceGrey, CalGrey and Indexed color spaces.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| g | double | Color value. |

### SetColor(double r, double g, double b) {#SetColor-double-double-double-}
```
public SetColor(double r, double g, double b)
```


Set color for stroking operator for DeviceRGB, CalRGB, and Lab color spaces

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| r | double | Red component. |
| g | double | Green component. |
| b | double | Blue component. |

### SetColor(double c, double m, double y, double k) {#SetColor-double-double-double-double-}
```
public SetColor(double c, double m, double y, double k)
```


Set color for non-stroking operator for CMYK color space

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| c | double | Cyan component. |
| m | double | Magenta component. |
| y | double | Yellow component. |
| k | double | Black component. |

### SetColor(double[] color) {#SetColor-double---}
```
public SetColor(double[] color)
```


Constructor which allows to specify color components.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | double[] | Array of color components. |

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
public Color getColor()
```


Not supported yet.

Returns color specified by the operator.

**Returns:**
[Color](../../java.awt/color) - Operator color.
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


Returns string representation of color.

**Returns:**
java.lang.String - String representation of color.
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

