---
title: TextExtractionError
second_title: Aspose.PDF for Java API Reference
description: Describes the text extraction error has appeared in the PDF document.
type: docs
weight: 369
url: /java/com.aspose.pdf/textextractionerror/
---
**Inheritance:**
java.lang.Object
```
public final class TextExtractionError
```

Describes the text extraction error has appeared in the PDF document.
## Methods

| Method | Description |
| --- | --- |
| [getSummary()](#getSummary--) | Brief description of the error. |
| [getDescription()](#getDescription--) | Expanded description of the error. |
| [getLocation()](#getLocation--) | Location of the error. |
| [getFontKey()](#getFontKey--) | Key (PDF name) of the Font object that is used for showing text that causes extraction error. |
| [getFontName()](#getFontName--) | Readable (internal) name of the Font object that is used for showing text that causes extraction error. |
| [getExtractedText()](#getExtractedText--) | Text that was actually extracted. |
| [toString()](#toString--) | Returns string representation. |
### getSummary() {#getSummary--}
```
public String getSummary()
```


Brief description of the error.

**Returns:**
java.lang.String - String value
### getDescription() {#getDescription--}
```
public String getDescription()
```


Expanded description of the error.

**Returns:**
java.lang.String - String value
### getLocation() {#getLocation--}
```
public TextExtractionErrorLocation getLocation()
```


Location of the error.

**Returns:**
[TextExtractionErrorLocation](../../com.aspose.pdf/textextractionerrorlocation) - TextExtractionErrorLocation instance
### getFontKey() {#getFontKey--}
```
public String getFontKey()
```


Key (PDF name) of the Font object that is used for showing text that causes extraction error.

**Returns:**
java.lang.String - String value
### getFontName() {#getFontName--}
```
public String getFontName()
```


Readable (internal) name of the Font object that is used for showing text that causes extraction error.

**Returns:**
java.lang.String - String value
### getExtractedText() {#getExtractedText--}
```
public String getExtractedText()
```


Text that was actually extracted.

**Returns:**
java.lang.String - String value
### toString() {#toString--}
```
public String toString()
```


Returns string representation.

**Returns:**
java.lang.String - String representation
