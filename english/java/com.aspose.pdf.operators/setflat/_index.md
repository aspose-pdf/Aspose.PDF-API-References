---
title: SetFlat
second_title: Aspose.PDF for Java API Reference
description: Class representing i operator (set flatness toleracne).
type: docs
weight: 620
url: /java/com.aspose.pdf.operators/setflat/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetFlat, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetFlat

```
public class SetFlat extends Operator
```

Class representing i operator (set flatness toleracne).

## Constructors

| Constructor | Description |
| --- | --- |
| [SetFlat](#SetFlat-double-) | Initializes operator. |
| [SetFlat](#SetFlat-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetFlatnessTolerance-) | Constructor for operator class. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts a visitor object to process operator. |
| [getFlatness](#getFlatness--) | Gets the flatness. |
| [setFlatness](#setFlatness-double-) | Sets the flatness. |
| [toCommand](#toCommand--) | For internal usage only! |

### SetFlat {#SetFlat-double-}
```
public SetFlat(double flatness)
```

Initializes operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flatness |  | The value of flatness. |

### SetFlat {#SetFlat-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetFlatnessTolerance-}
Constructor for operator class.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepts a visitor object to process operator.

### getFlatness {#getFlatness--}
```
public double getFlatness()
```

Gets the flatness.

**Returns:**
double value

### setFlatness {#setFlatness-double-}
```
public void setFlatness(double value)
```

Sets the flatness.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

For internal usage only!

**Returns:**
ICommand value ICommand object
