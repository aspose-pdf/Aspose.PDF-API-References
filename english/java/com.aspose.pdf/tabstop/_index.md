---
title: TabStop
second_title: Aspose.PDF for Java API Reference
description: Represents a custom Tab stop position in a paragraph.
type: docs
weight: 353
url: /java/com.aspose.pdf/tabstop/
---
**Inheritance:**
java.lang.Object
```
public class TabStop
```

Represents a custom Tab stop position in a paragraph.
## Constructors

| Constructor | Description |
| --- | --- |
| [TabStop()](#TabStop--) | Initializes a new instance of the  TabStop  class. |
| [TabStop(float position)](#TabStop-float-) | Initializes a new instance of the  TabStop  class with specified position. |
## Methods

| Method | Description |
| --- | --- |
| [getPosition()](#getPosition--) | Gets or sets a float value that indicates the tab stop position. |
| [setPosition(float value)](#setPosition-float-) | Sets a float value that indicates the tab stop position. |
| [getLeaderType()](#getLeaderType--) | Gets or sets a  TabLeaderType  enum that indicates the tab leader type. |
| [setLeaderType(int value)](#setLeaderType-int-) | Gets or sets a  TabLeaderType  enum that indicates the tab leader type. |
| [getAlignmentType()](#getAlignmentType--) | Gets or sets a  AlignmentType  enum that indicates the tab tab alignment type. |
| [setAlignmentType(int value)](#setAlignmentType-int-) | Gets or sets a  AlignmentType  enum that indicates the tab tab alignment type. |
| [isReadOnly()](#isReadOnly--) | Gets value indicating that this  TabStop  instance is already attached to  TextFragment  and became readonly |
### TabStop() {#TabStop--}
```
public TabStop()
```


Initializes a new instance of the  TabStop  class.

### TabStop(float position) {#TabStop-float-}
```
public TabStop(float position)
```


Initializes a new instance of the  TabStop  class with specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | float | The position of the tab stop. |

### getPosition() {#getPosition--}
```
public float getPosition()
```


Gets or sets a float value that indicates the tab stop position.

**Returns:**
float - float value
### setPosition(float value) {#setPosition-float-}
```
public void setPosition(float value)
```


Sets a float value that indicates the tab stop position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### getLeaderType() {#getLeaderType--}
```
public int getLeaderType()
```


Gets or sets a  TabLeaderType  enum that indicates the tab leader type.

**Returns:**
int - TabLeaderType element
### setLeaderType(int value) {#setLeaderType-int-}
```
public void setLeaderType(int value)
```


Gets or sets a  TabLeaderType  enum that indicates the tab leader type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | TabLeaderType element |

### getAlignmentType() {#getAlignmentType--}
```
public int getAlignmentType()
```


Gets or sets a  AlignmentType  enum that indicates the tab tab alignment type.

**Returns:**
int - TabAlignmentType element
### setAlignmentType(int value) {#setAlignmentType-int-}
```
public void setAlignmentType(int value)
```


Gets or sets a  AlignmentType  enum that indicates the tab tab alignment type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | TabAlignmentType element |

### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Gets value indicating that this  TabStop  instance is already attached to  TextFragment  and became readonly

**Returns:**
boolean - boolean value
