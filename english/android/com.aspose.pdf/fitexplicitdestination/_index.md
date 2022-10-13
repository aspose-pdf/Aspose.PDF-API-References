---
title: FitExplicitDestination
second_title: Aspose.PDF for Java API Reference
description: Represents explicit destination that displays the page with its contents magnified just enough to fit the entire page within the window both horizontally and vertically.
type: docs
weight: 105
url: /java/com.aspose.pdf/fitexplicitdestination/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.ExplicitDestination](../../com.aspose.pdf/explicitdestination)
```
public final class FitExplicitDestination extends ExplicitDestination
```

Represents explicit destination that displays the page with its contents magnified just enough to fit the entire page within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the page within the window in the other dimension.
## Constructors

| Constructor | Description |
| --- | --- |
| [FitExplicitDestination(Page page)](#FitExplicitDestination-com.aspose.pdf.Page-) | Creates local explicit destination. |
| [FitExplicitDestination(Document document, int pageNumber)](#FitExplicitDestination-com.aspose.pdf.Document-int-) | Creates remote explicit destination. |
| [FitExplicitDestination(int pageNumber)](#FitExplicitDestination-int-) | Creates remote explicit destination. |
## Methods

| Method | Description |
| --- | --- |
| [toString()](#toString--) | Converts the object state into string value. |
### FitExplicitDestination(Page page) {#FitExplicitDestination-com.aspose.pdf.Page-}
```
public FitExplicitDestination(Page page)
```


Creates local explicit destination.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The destination page object. |

### FitExplicitDestination(Document document, int pageNumber) {#FitExplicitDestination-com.aspose.pdf.Document-int-}
```
public FitExplicitDestination(Document document, int pageNumber)
```


Creates remote explicit destination.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [Document](../../com.aspose.pdf/document) | The Aspose.Pdf.Document object. |
| pageNumber | int | The destination page number. |

### FitExplicitDestination(int pageNumber) {#FitExplicitDestination-int-}
```
public FitExplicitDestination(int pageNumber)
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


Converts the object state into string value. Example: "1 Fit".

**Returns:**
java.lang.String - String value representing object state.
