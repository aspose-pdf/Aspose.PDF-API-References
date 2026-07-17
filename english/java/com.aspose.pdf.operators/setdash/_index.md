---
title: SetDash
linktitle: SetDash
second_title: Aspose.PDF for Java API Reference
description: Class representing d operator (set line dash pattern).
type: docs
weight: 610
url: /java/com.aspose.pdf.operators/setdash/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetDash, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetDash

```
public class SetDash extends Operator
```

Class representing d operator (set line dash pattern).

## Constructors

| Constructor | Description |
| --- | --- |
| [SetDash](#SetDash-int:A-int-) | Creates set dash pattern operator. |
| [SetDash](#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineDashPattern-) | Constructor for operator class. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getPattern](#getPattern--) | Dash pattern. Array's elements shall be numbers that specify the lengths of alternating dashes and gaps. In case of one element array dash and gap lengths are equal. |
| [getPhase](#getPhase--) | Dash phase. Before beginning to stroke a path, the dash array shall be cycled through, adding up the lengths of dashes and gaps. When the accumulated length equals the value specified by the dash phase, stroking of the path shall begin, and the dash array shall be used cyclically from that point onward. |
| [setPattern](#setPattern-int:A-) | Dash pattern. Array's elements shall be numbers that specify the lengths of alternating dashes and gaps. In case of one element array dash and gap lengths are equal. |
| [setPhase](#setPhase-int-) | Dash phase. Before beginning to stroke a path, the dash array shall be cycled through, adding up the lengths of dashes and gaps. When the accumulated length equals the value specified by the dash phase, stroking of the path shall begin, and the dash array shall be used cyclically from that point onward. |
| [toCommand](#toCommand--) | For internal usage only! |
| [toString](#toString--) | Gets operator string representation. |

### SetDash {#SetDash-int:A-int-}
```
public SetDash(int[] pattern, int phase)
```

Creates set dash pattern operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pattern |  | Array which defines dash pattern. |
| phase |  | Dash phase. |

### SetDash {#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineDashPattern-}
Constructor for operator class.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepts visitor object to process operator.

### getPattern {#getPattern--}
```
public int[] getPattern()
```

Dash pattern. Array's elements shall be numbers that specify the lengths of alternating dashes and gaps. In case of one element array dash and gap lengths are equal.

**Returns:**
int array

### getPhase {#getPhase--}
```
public int getPhase()
```

Dash phase. Before beginning to stroke a path, the dash array shall be cycled through, adding up the lengths of dashes and gaps. When the accumulated length equals the value specified by the dash phase, stroking of the path shall begin, and the dash array shall be used cyclically from that point onward.

**Returns:**
int value

### setPattern {#setPattern-int:A-}
```
public void setPattern(int[] value)
```

Dash pattern. Array's elements shall be numbers that specify the lengths of alternating dashes and gaps. In case of one element array dash and gap lengths are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int array |

### setPhase {#setPhase-int-}
```
public void setPhase(int value)
```

Dash phase. Before beginning to stroke a path, the dash array shall be cycled through, adding up the lengths of dashes and gaps. When the accumulated length equals the value specified by the dash phase, stroking of the path shall begin, and the dash array shall be used cyclically from that point onward.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

For internal usage only!

**Returns:**
ICommand value ICommand object

### toString {#toString--}
```
public String toString()
```

Gets operator string representation.

**Returns:**
[x1 x2] y d, where x1 - dash length, x2 - gap length, y - phase.
