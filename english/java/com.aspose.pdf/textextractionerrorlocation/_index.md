---
title: TextExtractionErrorLocation
second_title: Aspose.PDF for Java API Reference
description: Represents the location in the PDF document where text extraction error has appeared.
type: docs
weight: 370
url: /java/com.aspose.pdf/textextractionerrorlocation/
---
**Inheritance:**
java.lang.Object
```
public final class TextExtractionErrorLocation
```

Represents the location in the PDF document where text extraction error has appeared.
## Methods

| Method | Description |
| --- | --- |
| [getPath()](#getPath--) | Location of the PDF document where text extraction error has appeared. |
| [getPageNumber()](#getPageNumber--) | Number of the document page where text extraction error has located. |
| [getObjectType()](#getObjectType--) | Type of the PDF object (Page or xForm) in which contents stream text extraction error has located. |
| [getFormKey()](#getFormKey--) | Key (name) of the PDF Form XObject in which contents stream text extraction error has located. |
| [getOperatorIndex()](#getOperatorIndex--) | Index of text showing operator in the contents stream (operator collection) that causes text extraction error. |
| [getOperatorString()](#getOperatorString--) | Text showing operator that causes text extraction error. |
| [getFontUsedKey()](#getFontUsedKey--) | Key (name) of the PDF Font object that is used for showing of the operator that causes text extraction error. |
| [getTextStartPoint()](#getTextStartPoint--) | Key (name) of the PDF Font object that is used for showing of the operator that causes text extraction error. |
| [toString()](#toString--) | Returns string representation. |
### getPath() {#getPath--}
```
public String getPath()
```


Location of the PDF document where text extraction error has appeared.

**Returns:**
java.lang.String - String value
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Number of the document page where text extraction error has located.

**Returns:**
int - int value
### getObjectType() {#getObjectType--}
```
public String getObjectType()
```


Type of the PDF object (Page or xForm) in which contents stream text extraction error has located.

**Returns:**
java.lang.String - String value
### getFormKey() {#getFormKey--}
```
public String getFormKey()
```


Key (name) of the PDF Form XObject in which contents stream text extraction error has located. Not empty if ObjectType == 'xForm'.

**Returns:**
java.lang.String - String value
### getOperatorIndex() {#getOperatorIndex--}
```
public int getOperatorIndex()
```


Index of text showing operator in the contents stream (operator collection) that causes text extraction error.

**Returns:**
int - int value
### getOperatorString() {#getOperatorString--}
```
public String getOperatorString()
```


Text showing operator that causes text extraction error.

**Returns:**
java.lang.String - String value
### getFontUsedKey() {#getFontUsedKey--}
```
public String getFontUsedKey()
```


Key (name) of the PDF Font object that is used for showing of the operator that causes text extraction error.

**Returns:**
java.lang.String - String value
### getTextStartPoint() {#getTextStartPoint--}
```
public Point getTextStartPoint()
```


Key (name) of the PDF Font object that is used for showing of the operator that causes text extraction error.

**Returns:**
[Point](../../com.aspose.pdf/point) - Point instance
### toString() {#toString--}
```
public String toString()
```


Returns string representation.

**Returns:**
java.lang.String - String representation.
