---
title: Operator.SetDash
second_title: Aspose.PDF for Java API Reference
description: Class representing d operator set line dash pattern.
type: docs
weight: 64
url: /java/com.aspose.pdf/operator.setdash/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public static class Operator.SetDash extends Operator
```

Class representing d operator (set line dash pattern).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetDash(int[] pattern, int phase)](#SetDash-int---int-) | Creates set dash pattern operator. |
## Methods

| Method | Description |
| --- | --- |
| [getPattern()](#getPattern--) | Dash pattern. |
| [setPattern(int[] value)](#setPattern-int---) |  |
| [getPhase()](#getPhase--) | Dash phase. |
| [setPhase(int value)](#setPhase-int-) |  |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Gets operator string representation. |
### SetDash(int[] pattern, int phase) {#SetDash-int---int-}
```
public SetDash(int[] pattern, int phase)
```


Creates set dash pattern operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pattern | int[] | Array which defines dash pattern. |
| phase | int |  |

### getPattern() {#getPattern--}
```
public int[] getPattern()
```


Dash pattern. Array\\ufffds elements shall be numbers that specify the lengths of alternating dashes and gaps. In case of one element array dash and gap lengths are equal.

**Returns:**
int[]
### setPattern(int[] value) {#setPattern-int---}
```
public void setPattern(int[] value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### getPhase() {#getPhase--}
```
public int getPhase()
```


Dash phase. Before beginning to stroke a path, the dash array shall be cycled through, adding up the lengths of dashes and gaps. When the accumulated length equals the value specified by the dash phase, stroking of the path shall begin, and the dash array shall be used cyclically from that point onward.

**Returns:**
int
### setPhase(int value) {#setPhase-int-}
```
public void setPhase(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts visitor object to process operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |

### toString() {#toString--}
```
public String toString()
```


Gets operator string representation.

**Returns:**
java.lang.String - [x1 x2] y d, where x1 - dash length, x2 - gap length, y - phase.
