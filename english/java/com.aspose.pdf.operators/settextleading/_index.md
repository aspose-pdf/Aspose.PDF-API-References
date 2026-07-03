---
title: SetTextLeading
second_title: Aspose.PDF for Java API Reference
description: Class represenging TL operator (set text leading).
type: docs
weight: 740
url: /java/com.aspose.pdf.operators/settextleading/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.operators.TextStateOperator, com.aspose.pdf.operators.SetTextLeading

```
public class SetTextLeading extends TextStateOperator
```

Class represenging TL operator (set text leading).

## Constructors

| Constructor | Description |
| --- | --- |
| [SetTextLeading](#SetTextLeading-double-) | Constructor for text leadign operator. |
| [SetTextLeading](#SetTextLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextLeading-) |  |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getLeading](#getLeading--) | Gets the text leading. |
| [setLeading](#setLeading-double-) | Sets the text leading. |
| [toString](#toString--) | Produces text code of operator. |

### SetTextLeading {#SetTextLeading-double-}
```
public SetTextLeading(double leading)
```

Constructor for text leadign operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| leading |  | Text leading. |

### SetTextLeading {#SetTextLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextLeading-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepts visitor object to process operator.

### getLeading {#getLeading--}
```
public double getLeading()
```

Gets the text leading.

**Returns:**
double value

### setLeading {#setLeading-double-}
```
public void setLeading(double value)
```

Sets the text leading.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### toString {#toString--}
```
public String toString()
```

Produces text code of operator.

**Returns:**
Text representation of operator.
