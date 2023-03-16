---
title: Document.CallBackGetHocr
second_title: Aspose.PDF for Java API Reference
description: The call back procedure for hocr recognize.
type: docs
weight: 11
url: /java/com.aspose.pdf/document.callbackgethocr/
---```
public static interface Document.CallBackGetHocr
```

The call back procedure for hocr recognize.
## Methods

| Method | Description |
| --- | --- |
| [invoke(BufferedImage img)](#invoke-java.awt.image.BufferedImage-) | The call back procedure for hocr recognize. |
### invoke(BufferedImage img) {#invoke-java.awt.image.BufferedImage-}
```
public abstract String invoke(BufferedImage img)
```


The call back procedure for hocr recognize.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| img | java.awt.image.BufferedImage | The hocr image wrapper. |

**Returns:**
java.lang.String - The hocr text.
