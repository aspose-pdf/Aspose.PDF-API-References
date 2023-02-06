---
title: FitBExplicitDestination
second_title: Aspose.PDF for Java API Reference
description: Represents explicit destination that displays the page with its contents magnified just enough to fit its bounding box entirely within the window both horizontally and vertically.
type: docs
weight: 122
url: /java/com.aspose.pdf/fitbexplicitdestination/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.ExplicitDestination](../../com.aspose.pdf/explicitdestination)
```
public final class FitBExplicitDestination extends ExplicitDestination
```

Represents explicit destination that displays the page with its contents magnified just enough to fit its bounding box entirely within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the bounding box within the window in the other dimension.
## Constructors

| Constructor | Description |
| --- | --- |
| [FitBExplicitDestination(Page page)](#FitBExplicitDestination-com.aspose.pdf.Page-) | Creates the instance and initializes it by DOM page object. |
| [FitBExplicitDestination(Document document, int pageNumber)](#FitBExplicitDestination-com.aspose.pdf.Document-int-) | Creates remote explicit destination. |
| [FitBExplicitDestination(int pageNumber)](#FitBExplicitDestination-int-) | Creates remote explicit destination. |
## Methods

| Method | Description |
| --- | --- |
| [toString()](#toString--) | Converts the object state into string value. |
### FitBExplicitDestination(Page page) {#FitBExplicitDestination-com.aspose.pdf.Page-}
```
public FitBExplicitDestination(Page page)
```


Creates the instance and initializes it by DOM page object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | DOM page object. |

### FitBExplicitDestination(Document document, int pageNumber) {#FitBExplicitDestination-com.aspose.pdf.Document-int-}
```
public FitBExplicitDestination(Document document, int pageNumber)
```


Creates remote explicit destination.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [Document](../../com.aspose.pdf/document) | The parent document that contains this object. |
| pageNumber | int | The destination page number of remote document. |

### FitBExplicitDestination(int pageNumber) {#FitBExplicitDestination-int-}
```
public FitBExplicitDestination(int pageNumber)
```


Creates remote explicit destination.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The destination page number of remote document. |

### toString() {#toString--}
```
public String toString()
```


Converts the object state into string value. Example: "1 FitB".

**Returns:**
java.lang.String - String value representing object state.
