---
title: ColumnInfo
second_title: Aspose.PDF for Java API Reference
description: This class represents a columns info.
type: docs
weight: 68
url: /java/com.aspose.pdf/columninfo/
---
**Inheritance:**
java.lang.Object
```
public final class ColumnInfo
```

This class represents a columns info.
## Constructors

| Constructor | Description |
| --- | --- |
| [ColumnInfo()](#ColumnInfo--) | Initializes a new instance of the ColumnInfo class. |
## Methods

| Method | Description |
| --- | --- |
| [getColumnWidths()](#getColumnWidths--) | Gets or sets a string that contains the width of columns. |
| [setColumnWidths(String value)](#setColumnWidths-java.lang.String-) | Gets or sets a string that contains the width of columns. |
| [getColumnSpacing()](#getColumnSpacing--) | Gets or sets a string that contains the spacing between columns. |
| [setColumnSpacing(String value)](#setColumnSpacing-java.lang.String-) | Gets or sets a string that contains the spacing between columns. |
| [getColumnCount()](#getColumnCount--) | Gets int value that indicates the number of columns. |
| [setColumnCount(int value)](#setColumnCount-int-) | Sets int value that indicates the number of columns. |
### ColumnInfo() {#ColumnInfo--}
```
public ColumnInfo()
```


Initializes a new instance of the ColumnInfo class.

### getColumnWidths() {#getColumnWidths--}
```
public String getColumnWidths()
```


Gets or sets a string that contains the width of columns. The value of each column should be separated by blank.The default unit is point, but cm, inch and percentage of available width are also supported. For example,"120 2.5cm 1.5inch"

**Returns:**
java.lang.String - String value
### setColumnWidths(String value) {#setColumnWidths-java.lang.String-}
```
public void setColumnWidths(String value)
```


Gets or sets a string that contains the width of columns. The value of each column should be separated by blank.The default unit is point, but cm, inch and percentage of available width are also supported. For example,"120 2.5cm 1.5inch"

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getColumnSpacing() {#getColumnSpacing--}
```
public String getColumnSpacing()
```


Gets or sets a string that contains the spacing between columns. The value of each spacing should be separated by blank. The default unit is point, but cm and inch are also supported.For example,"120 2.5cm 1.5inch".

--------------------

If this property is not set, default value 0 will be used for each spacing.

**Returns:**
java.lang.String - String value
### setColumnSpacing(String value) {#setColumnSpacing-java.lang.String-}
```
public void setColumnSpacing(String value)
```


Gets or sets a string that contains the spacing between columns. The value of each spacing should be separated by blank. The default unit is point, but cm and inch are also supported.For example,"120 2.5cm 1.5inch".

--------------------

If this property is not set, default value 0 will be used for each spacing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getColumnCount() {#getColumnCount--}
```
public int getColumnCount()
```


Gets int value that indicates the number of columns.

**Returns:**
int - column count
### setColumnCount(int value) {#setColumnCount-int-}
```
public void setColumnCount(int value)
```


Sets int value that indicates the number of columns.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | column count |

