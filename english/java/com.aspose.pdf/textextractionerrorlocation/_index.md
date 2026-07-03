---
title: TextExtractionErrorLocation
second_title: Aspose.PDF for Java API Reference
description: Represents the location in the PDF document where text extraction error has appeared.
type: docs
weight: 5050
url: /java/com.aspose.pdf/textextractionerrorlocation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextExtractionErrorLocation

```
public final class TextExtractionErrorLocation extends Object
```

Represents the location in the PDF document where text extraction error has appeared.

## Methods

| Method | Description |
| --- | --- |
| [getFontUsedKey](#getFontUsedKey--) | Key (name) of the PDF Font object that is used for showing of the operator that causes text extraction error. |
| [getFormKey](#getFormKey--) | Key (name) of the PDF Form XObject in which contents stream text extraction error has located. Not empty if ObjectType == 'xForm'. |
| [getObjectType](#getObjectType--) | Type of the PDF object (Page or xForm) in which contents stream text extraction error has located. |
| [getOperatorIndex](#getOperatorIndex--) | Index of text showing operator in the contents stream (operator collection) that causes text extraction error. |
| [getOperatorString](#getOperatorString--) | Text showing operator that causes text extraction error. |
| [getPageNumber](#getPageNumber--) | Number of the document page where text extraction error has located. |
| [getPath](#getPath--) | Location of the PDF document where text extraction error has appeared. |
| [getTextStartPoint](#getTextStartPoint--) | Key (name) of the PDF Font object that is used for showing of the operator that causes text extraction error. |
| [toString](#toString--) | Returns string representation. |

### getFontUsedKey {#getFontUsedKey--}
```
public String getFontUsedKey()
```

Key (name) of the PDF Font object that is used for showing of the operator that causes text extraction error.

**Returns:**
String value

### getFormKey {#getFormKey--}
```
public String getFormKey()
```

Key (name) of the PDF Form XObject in which contents stream text extraction error has located. Not empty if ObjectType == 'xForm'.

**Returns:**
String value

### getObjectType {#getObjectType--}
```
public String getObjectType()
```

Type of the PDF object (Page or xForm) in which contents stream text extraction error has located.

**Returns:**
String value

### getOperatorIndex {#getOperatorIndex--}
```
public int getOperatorIndex()
```

Index of text showing operator in the contents stream (operator collection) that causes text extraction error.

**Returns:**
int value

### getOperatorString {#getOperatorString--}
```
public String getOperatorString()
```

Text showing operator that causes text extraction error.

**Returns:**
String value

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Number of the document page where text extraction error has located.

**Returns:**
int value

### getPath {#getPath--}
```
public String getPath()
```

Location of the PDF document where text extraction error has appeared.

**Returns:**
String value

### getTextStartPoint {#getTextStartPoint--}
```
public Point getTextStartPoint()
```

Key (name) of the PDF Font object that is used for showing of the operator that causes text extraction error.

**Returns:**
Point instance

### toString {#toString--}
```
public String toString()
```

Returns string representation.

**Returns:**
String representation.
