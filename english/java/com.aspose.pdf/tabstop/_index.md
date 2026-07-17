---
title: TabStop
linktitle: TabStop
second_title: Aspose.PDF for Java API Reference
description: Represents a custom Tab stop position in a paragraph.
type: docs
weight: 4840
url: /java/com.aspose.pdf/tabstop/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TabStop

```
public class TabStop extends Object
```

Represents a custom Tab stop position in a paragraph.

## Constructors

| Constructor | Description |
| --- | --- |
| [TabStop](#TabStop--) | Initializes a new instance of the {@code TabStop} class. |
| [TabStop](#TabStop-float-) | Initializes a new instance of the {@code TabStop} class with specified position. |

## Methods

| Method | Description |
| --- | --- |
| [getAlignmentType](#getAlignmentType--) | Gets or sets a {@code AlignmentType} enum that indicates the tab tab alignment type. |
| [getLeaderType](#getLeaderType--) | Gets or sets a {@code TabLeaderType} enum that indicates the tab leader type. |
| [getPosition](#getPosition--) | Gets or sets a float value that indicates the tab stop position. |
| [isReadOnly](#isReadOnly--) | Gets value indicating that this {@code TabStop} instance is already attached to {@code TextFragment} and became readonly |
| [setAlignmentType](#setAlignmentType-int-) | Gets or sets a {@code AlignmentType} enum that indicates the tab tab alignment type. |
| [setLeaderType](#setLeaderType-int-) | Gets or sets a {@code TabLeaderType} enum that indicates the tab leader type. |
| [setPosition](#setPosition-float-) | Sets a float value that indicates the tab stop position. |

### TabStop {#TabStop--}
```
public TabStop()
```

Initializes a new instance of the {@code TabStop} class.

### TabStop {#TabStop-float-}
```
public TabStop(float position)
```

Initializes a new instance of the {@code TabStop} class with specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position |  | The position of the tab stop. |

### getAlignmentType {#getAlignmentType--}
```
public int getAlignmentType()
```

Gets or sets a {@code AlignmentType} enum that indicates the tab tab alignment type.

**Returns:**
TabAlignmentType element @see TabAlignmentType

### getLeaderType {#getLeaderType--}
```
public int getLeaderType()
```

Gets or sets a {@code TabLeaderType} enum that indicates the tab leader type.

**Returns:**
TabLeaderType element @see TabLeaderType

### getPosition {#getPosition--}
```
public float getPosition()
```

Gets or sets a float value that indicates the tab stop position.

**Returns:**
float value

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Gets value indicating that this {@code TabStop} instance is already attached to {@code TextFragment} and became readonly

**Returns:**
boolean value

### setAlignmentType {#setAlignmentType-int-}
```
public void setAlignmentType(int value)
```

Gets or sets a {@code AlignmentType} enum that indicates the tab tab alignment type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | TabAlignmentType element @see TabAlignmentType |

### setLeaderType {#setLeaderType-int-}
```
public void setLeaderType(int value)
```

Gets or sets a {@code TabLeaderType} enum that indicates the tab leader type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | TabLeaderType element @see TabLeaderType |

### setPosition {#setPosition-float-}
```
public void setPosition(float value)
```

Sets a float value that indicates the tab stop position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |
