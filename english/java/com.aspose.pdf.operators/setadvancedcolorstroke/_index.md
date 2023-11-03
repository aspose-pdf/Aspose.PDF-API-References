---
title: SetAdvancedColorStroke
second_title: Aspose.PDF for Java API Reference
description: Class representing SCN operator set color for stroking operations.
type: docs
weight: 57
url: /java/com.aspose.pdf.operators/setadvancedcolorstroke/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.SetColorOperator](../../com.aspose.pdf.operators/setcoloroperator), [com.aspose.pdf.operators.BasicSetColorOperator](../../com.aspose.pdf.operators/basicsetcoloroperator), [com.aspose.pdf.operators.BasicSetColorAndPatternOperator](../../com.aspose.pdf.operators/basicsetcolorandpatternoperator)
```
public class SetAdvancedColorStroke extends BasicSetColorAndPatternOperator
```

Class representing SCN operator (set color for stroking operations).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetAdvancedColorStroke(int index, ICommand command)](#SetAdvancedColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [SetAdvancedColorStroke()](#SetAdvancedColorStroke--) | Initializes operator. |
| [SetAdvancedColorStroke(double g)](#SetAdvancedColorStroke-double-) | Constructor for scn operator |
| [SetAdvancedColorStroke(double g, String patternName)](#SetAdvancedColorStroke-double-java.lang.String-) | Constructor for scn operator. |
| [SetAdvancedColorStroke(double r, double g, double b, String patternName)](#SetAdvancedColorStroke-double-double-double-java.lang.String-) | Constructor for scn operator. |
| [SetAdvancedColorStroke(double c, double m, double y, double k, String patternName)](#SetAdvancedColorStroke-double-double-double-double-java.lang.String-) | Constructor for scn operator. |
| [SetAdvancedColorStroke(double[] colors, String patternName)](#SetAdvancedColorStroke-double---java.lang.String-) | Constructor for scn operator. |
## Methods

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Not supported yet. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
### SetAdvancedColorStroke(int index, ICommand command) {#SetAdvancedColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetAdvancedColorStroke(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### SetAdvancedColorStroke() {#SetAdvancedColorStroke--}
```
public SetAdvancedColorStroke()
```


Initializes operator.

### SetAdvancedColorStroke(double g) {#SetAdvancedColorStroke-double-}
```
public SetAdvancedColorStroke(double g)
```


Constructor for scn operator

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| g | double | double value Gray color value. |

### SetAdvancedColorStroke(double g, String patternName) {#SetAdvancedColorStroke-double-java.lang.String-}
```
public SetAdvancedColorStroke(double g, String patternName)
```


Constructor for scn operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| g | double | Gray color value. |
| patternName | java.lang.String | String value Name of the pattern. |

### SetAdvancedColorStroke(double r, double g, double b, String patternName) {#SetAdvancedColorStroke-double-double-double-java.lang.String-}
```
public SetAdvancedColorStroke(double r, double g, double b, String patternName)
```


Constructor for scn operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| r | double | Red component of the color/ |
| g | double | Green component of the color. |
| b | double | Blue component of the color. |
| patternName | java.lang.String | String object |

### SetAdvancedColorStroke(double c, double m, double y, double k, String patternName) {#SetAdvancedColorStroke-double-double-double-double-java.lang.String-}
```
public SetAdvancedColorStroke(double c, double m, double y, double k, String patternName)
```


Constructor for scn operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| c | double | Cyan component of the color. |
| m | double | Magenta component of the color. |
| y | double | Yellow component of the color. |
| k | double | Black component of the color |
| patternName | java.lang.String | Name of the pattern. |

### SetAdvancedColorStroke(double[] colors, String patternName) {#SetAdvancedColorStroke-double---java.lang.String-}
```
public SetAdvancedColorStroke(double[] colors, String patternName)
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
[Color](../../java.awt/color) - Color specified by operator.
### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts visitor object to process operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |

