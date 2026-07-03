---
title: GraphicalPdfComparer
linktitle: GraphicalPdfComparer
second_title: Aspose.PDF for Java API Reference
description: Represents a class for graphically comparing PDF documents. Should be used to search for small changes, mainly of a graphical nature. To compare text content changes, use other.
type: docs
weight: 10
url: /java/com.aspose.pdf.comparison.graphicalcomparison/graphicalpdfcomparer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.graphicalcomparison.GraphicalPdfComparer

```
public class GraphicalPdfComparer extends Object
```

Represents a class for graphically comparing PDF documents. Should be used to search for small changes, mainly of a graphical nature. To compare text content changes, use other PDF comparison classes.

## Constructors

| Constructor | Description |
| --- | --- |
| [GraphicalPdfComparer](#GraphicalPdfComparer--) | Creates an instance of {@link GraphicalPdfComparer} class. |

## Methods

| Method | Description |
| --- | --- |
| [compareDocumentsToImages](#compareDocumentsToImages-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-) | Compares documents graphically. |
| [compareDocumentsToPdf](#compareDocumentsToPdf-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-) | Compares documents graphically. The comparison result is placed in a PDF document. |
| [comparePagesToImage](#comparePagesToImage-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-) | Compares pages graphically. The comparison result is placed in a image. |
| [comparePagesToPdf](#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-com.aspose.pdf.Document-) | Compares pages graphically. The comparison result is placed in a PDF document. |
| [comparePagesToPdf](#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-) | Compares pages graphically. The comparison result is placed in a PDF document. |
| [getColor](#getColor--) | Gets and sets the change flag color. The default color is red. |
| [getDifference](#getDifference-com.aspose.pdf.Page-com.aspose.pdf.Page-) | Gets differences between pages images. The result contains an image of the first page compared and an array of differences. |
| [getResolution](#getResolution--) | Gets and sets the resolution of the resulting images. The default value is 150dpi. |
| [getThreshold](#getThreshold--) | Gets and sets the threshold value in percentage. This value allows you to ignore small changes if they are not significant to you. The default value is 0%. |
| [setColor](#setColor-com.aspose.pdf.Color-) | Gets and sets the change flag color. The default color is red. |
| [setResolution](#setResolution-com.aspose.pdf.devices.Resolution-) | Gets and sets the resolution of the resulting images. The default value is 150dpi. |
| [setThreshold](#setThreshold-double-) | Gets and sets the threshold value in percentage. This value allows you to ignore small changes if they are not significant to you. The default value is 0%. |

### GraphicalPdfComparer {#GraphicalPdfComparer--}
```
public GraphicalPdfComparer()
```

Creates an instance of {@link GraphicalPdfComparer} class.

### compareDocumentsToImages {#compareDocumentsToImages-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-}
Compares documents graphically.

### compareDocumentsToPdf {#compareDocumentsToPdf-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-}
Compares documents graphically. The comparison result is placed in a PDF document.

### comparePagesToImage {#comparePagesToImage-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-}
Compares pages graphically. The comparison result is placed in a image.

### comparePagesToPdf {#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-com.aspose.pdf.Document-}
Compares pages graphically. The comparison result is placed in a PDF document.

### comparePagesToPdf {#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-}
Compares pages graphically. The comparison result is placed in a PDF document.

### getColor {#getColor--}
```
public final Color getColor()
```

Gets and sets the change flag color. The default color is red.

**Returns:**
Color instance

### getDifference {#getDifference-com.aspose.pdf.Page-com.aspose.pdf.Page-}
Gets differences between pages images. The result contains an image of the first page compared and an array of differences.

### getResolution {#getResolution--}
```
public final Resolution getResolution()
```

Gets and sets the resolution of the resulting images. The default value is 150dpi.

**Returns:**
Resolution instance

### getThreshold {#getThreshold--}
```
public final double getThreshold()
```

Gets and sets the threshold value in percentage. This value allows you to ignore small changes if they are not significant to you. The default value is 0%.

**Returns:**
double value

### setColor {#setColor-com.aspose.pdf.Color-}
Gets and sets the change flag color. The default color is red.

### setResolution {#setResolution-com.aspose.pdf.devices.Resolution-}
Gets and sets the resolution of the resulting images. The default value is 150dpi.

### setThreshold {#setThreshold-double-}
```
public final void setThreshold(double value)
```

Gets and sets the threshold value in percentage. This value allows you to ignore small changes if they are not significant to you. The default value is 0%.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |
