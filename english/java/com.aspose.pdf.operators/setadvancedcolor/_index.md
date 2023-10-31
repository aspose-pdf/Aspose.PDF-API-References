---
title: SetAdvancedColor
second_title: Aspose.PDF for Java API Reference
description: Class representing scn operator set color for non-stroking operations.
type: docs
weight: 56
url: /java/com.aspose.pdf.operators/setadvancedcolor/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.SetColorOperator](../../com.aspose.pdf.operators/setcoloroperator), [com.aspose.pdf.operators.BasicSetColorOperator](../../com.aspose.pdf.operators/basicsetcoloroperator), [com.aspose.pdf.operators.BasicSetColorAndPatternOperator](../../com.aspose.pdf.operators/basicsetcolorandpatternoperator)
```
public class SetAdvancedColor extends BasicSetColorAndPatternOperator
```

Class representing scn operator (set color for non-stroking operations).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetAdvancedColor(int index, ICommand command)](#SetAdvancedColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [SetAdvancedColor()](#SetAdvancedColor--) | Initializes operator. |
| [SetAdvancedColor(double g, String patternName)](#SetAdvancedColor-double-java.lang.String-) | Constructor for scn operator. |
| [SetAdvancedColor(double g)](#SetAdvancedColor-double-) | Constructor for scn operator |
| [SetAdvancedColor(double r, double g, double b, String patternName)](#SetAdvancedColor-double-double-double-java.lang.String-) | Constructor for scn operator. |
| [SetAdvancedColor(double c, double m, double y, double k, String patternName)](#SetAdvancedColor-double-double-double-double-java.lang.String-) | Constructor for scn operator. |
| [SetAdvancedColor(String patternName)](#SetAdvancedColor-java.lang.String-) | Constructor for scn operator. |
| [SetAdvancedColor(double[] colors, String patternName)](#SetAdvancedColor-double---java.lang.String-) | Constructor for scn operator. |
## Methods

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Not supported yet. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
### SetAdvancedColor(int index, ICommand command) {#SetAdvancedColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetAdvancedColor(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### SetAdvancedColor() {#SetAdvancedColor--}
```
public SetAdvancedColor()
```


Initializes operator.

### SetAdvancedColor(double g, String patternName) {#SetAdvancedColor-double-java.lang.String-}
```
public SetAdvancedColor(double g, String patternName)
```


Constructor for scn operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| g | double | Color value. |
| patternName | java.lang.String | Pattern name. |

### SetAdvancedColor(double g) {#SetAdvancedColor-double-}
```
public SetAdvancedColor(double g)
```


Constructor for scn operator

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| g | double | Color value. |

### SetAdvancedColor(double r, double g, double b, String patternName) {#SetAdvancedColor-double-double-double-java.lang.String-}
```
public SetAdvancedColor(double r, double g, double b, String patternName)
```


Constructor for scn operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| r | double | Red component of the color. |
| g | double | Green component of the color. |
| b | double | Blue component of the color. |
| patternName | java.lang.String | Pattern name. |

### SetAdvancedColor(double c, double m, double y, double k, String patternName) {#SetAdvancedColor-double-double-double-double-java.lang.String-}
```
public SetAdvancedColor(double c, double m, double y, double k, String patternName)
```


Constructor for scn operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| c | double | Cyan component of the color. |
| m | double | Magenta component of the color. |
| y | double | Yellow component of the color. |
| k | double | Black component of the color. |
| patternName | java.lang.String | String object Pattern name. |

### SetAdvancedColor(String patternName) {#SetAdvancedColor-java.lang.String-}
```
public SetAdvancedColor(String patternName)
```


Constructor for scn operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| patternName | java.lang.String | Pattern name. |

### SetAdvancedColor(double[] colors, String patternName) {#SetAdvancedColor-double---java.lang.String-}
```
public SetAdvancedColor(double[] colors, String patternName)
```


Constructor for scn operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colors | double[] | Color array. |
| patternName | java.lang.String | Pattern name. |

### getColor() {#getColor--}
```
public Color getColor()
```


Not supported yet.

Returns color specified by operator.

**Returns:**
[Color](../../java.awt/color) - Color set by operator.
### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts visitor object to process operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |

