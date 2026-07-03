---
title: PdfPageEditor
second_title: Aspose.PDF for Java API Reference
description: Represents a class to edit the PDF file's page, including rotating page, zooming page, moving position and changing page size.
type: docs
weight: 570
url: /java/com.aspose.pdf.facades/pdfpageeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfPageEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfPageEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfPageEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfPageEditor extends SaveableFacade
```

Represents a class to edit the PDF file's page, including rotating page, zooming page, moving position and changing page size.

## Fields

| Field | Description |
| --- | --- |
| [BLINDH](#BLINDH) | Vertical Blinds |
| [BLINDV](#BLINDV) | Vertical Blinds |
| [BTWIPE](#BTWIPE) | Bottom-Top Wipe |
| [DGLITTER](#DGLITTER) | Diagonal Glitter |
| [DISSOLVE](#DISSOLVE) | The old page dissolves |
| [INBOX](#INBOX) | Inward Box |
| [LRGLITTER](#LRGLITTER) | Left-Right Glitter |
| [LRWIPE](#LRWIPE) | Left-Right Wipe |
| [OUTBOX](#OUTBOX) | Outward Box |
| [RLWIPE](#RLWIPE) | Right-Left Wipe |
| [SPLITHIN](#SPLITHIN) | IN Horizontal Split |
| [SPLITHOUT](#SPLITHOUT) | Out Horizontal Split |
| [SPLITVIN](#SPLITVIN) | In Vertical Split |
| [SPLITVOUT](#SPLITVOUT) | Out Vertical Split |
| [TBGLITTER](#TBGLITTER) | Top-Bottom Glitter |
| [TBWIPE](#TBWIPE) | Top-Bottom Wipe |

## Constructors

| Constructor | Description |
| --- | --- |
| [PdfPageEditor](#PdfPageEditor--) | Constructor for PdfPageEditor class. |
| [PdfPageEditor](#PdfPageEditor-com.aspose.pdf.Document-) | Constructor for PdfPageEditor class. |

## Methods

| Method | Description |
| --- | --- |
| [applyChanges](#applyChanges--) | Apply changes made to the document pages. |
| [getAlignment](#getAlignment--) | Gets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left. Use getHorizontalAlignment instead |
| [getDisplayDuration](#getDisplayDuration--) | Gets display duration for pages. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Gets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left. |
| [getPageBoxSize](#getPageBoxSize-int-java.lang.String-) | <p> Returns size of specified box in document. </p> <hr> <pre> The following example demonstrates how to get media box of the 1st page: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); Rectangle rect = editor.getBoxSize(1, "media"); </pre> |
| [getPageRectangle](#getPageRectangle-com.aspose.pdf.Page-) | Return page size of the page. |
| [getPageRotation](#getPageRotation-int-) | <p> Returns the rotation of specified page. </p> <hr> <pre> The following example demonstrates how to get page rotation: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); int rotation = editor.getPageSize(1); System.out.println("Rotation of 1st page : " + rotation + " degrees"); </pre> |
| [getPageRotations](#getPageRotations--) | <p> Gets the rotation of the pages, A hashtable contains the page number and rotation degree, the key represents the page number, the value of key represents the rotation in degrees. </p> |
| [getPages](#getPages--) | <p> Returns total number of pages. </p> <hr> <pre> The following example demonstrates using of GetPages() method: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); System.out.println("Document has: " + editor.GetPages()); </pre> |
| [getPageSize](#getPageSize--) | Gets the output file's page size. |
| [getPageSize](#getPageSize-int-) | <p> Returns the page size of the specified page. </p> <hr> <pre> The following example demonstrates using of GetPageSize method: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); PageSize size = editor.getPageSize(1); System.out.println("Size of 1st page : " + size.getWidth() + " x " + size.getHeight()); </pre> |
| [getProcessPages](#getProcessPages--) | Gets the page numbers to be edited. By default, each page would be edited. |
| [getRotation](#getRotation--) | Gets the rotation of the pages, the rotation must be 0, 90, 180 or 270. Default value is 0. |
| [getTransitionDuration](#getTransitionDuration--) | Gets duration of the transition effect. |
| [getTransitionType](#getTransitionType--) | Gets transition style to use when moving to this page from another during a presentation. |
| [getVerticalAlignment](#getVerticalAlignment--) | Gets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom. Use getVerticalAlignmentType instead |
| [getVerticalAlignmentType](#getVerticalAlignmentType--) | Gets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom. |
| [getZoom](#getZoom--) | Get zoom coefficient. Value 1.0 corresponds to 100%. Default value is 1.0. |
| [isBoxDefined](#isBoxDefined-com.aspose.pdf.Page-java.lang.String-) | Check is the box is defined on the page. |
| [movePosition](#movePosition-float-float-) | <p> Moves the origin from (0, 0) to the point that appointted. The origin is left-bottom and the unit is point(1 inch = 72 points). </p> <hr> <pre> PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("input.pdf"); editor.movePosition(-100, 60); editor.save("moved.pdf"); </pre> |
| [save](#save-java.io.OutputStream-) | <p> Saves changed document into stream. </p> <hr> <pre> The following sample demonstrates how to save changed PDF document into stream. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre> |
| [save](#save-java.lang.String-) | <p> Saves changed document into file. </p> <hr> <pre> The following sample demonstrates how to save changed PDF document PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre> |
| [setAlignment](#setAlignment-com.aspose.pdf.facades.AlignmentType-) | Sets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left. Use setHorizontalAlignment instead |
| [setDisplayDuration](#setDisplayDuration-int-) | Sets display duration for pages. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Sets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left. |
| [setPageRotations](#setPageRotations-java.util.Map-) | Sets the rotation of the pages, A hashtable contains the page number and rotation degree, the key represents the page number, the value of key represents the rotation in degrees. |
| [setPageSize](#setPageSize-com.aspose.pdf.PageSize-) | Sets the output file's page size. |
| [setProcessPages](#setProcessPages-int:A-) | Sets the page numbers to be edited. By default, each page would be edited. |
| [setRotation](#setRotation-int-) | Sets the rotation of the pages, the rotation must be 0, 90, 180 or 270. Default value is 0. |
| [setTransitionDuration](#setTransitionDuration-int-) | Sets duration of the transition effect. |
| [setTransitionType](#setTransitionType-int-) | Sets transition style to use when moving to this page from another during a presentation. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-) | Sets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom. Use setVerticalAlignmentType instead |
| [setVerticalAlignmentType](#setVerticalAlignmentType-com.aspose.pdf.VerticalAlignment-) | Sets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom. |
| [setZoom](#setZoom-float-) | <p> Sets zoom coefficient. Value 1.0 corresponds to 100%. Default value is 1.0. </p> |

### BLINDH {#BLINDH}
```
public static final int BLINDH
```

Vertical Blinds

### BLINDV {#BLINDV}
```
public static final int BLINDV
```

Vertical Blinds

### BTWIPE {#BTWIPE}
```
public static final int BTWIPE
```

Bottom-Top Wipe

### DGLITTER {#DGLITTER}
```
public static final int DGLITTER
```

Diagonal Glitter

### DISSOLVE {#DISSOLVE}
```
public static final int DISSOLVE
```

The old page dissolves

### INBOX {#INBOX}
```
public static final int INBOX
```

Inward Box

### LRGLITTER {#LRGLITTER}
```
public static final int LRGLITTER
```

Left-Right Glitter

### LRWIPE {#LRWIPE}
```
public static final int LRWIPE
```

Left-Right Wipe

### OUTBOX {#OUTBOX}
```
public static final int OUTBOX
```

Outward Box

### RLWIPE {#RLWIPE}
```
public static final int RLWIPE
```

Right-Left Wipe

### SPLITHIN {#SPLITHIN}
```
public static final int SPLITHIN
```

IN Horizontal Split

### SPLITHOUT {#SPLITHOUT}
```
public static final int SPLITHOUT
```

Out Horizontal Split

### SPLITVIN {#SPLITVIN}
```
public static final int SPLITVIN
```

In Vertical Split

### SPLITVOUT {#SPLITVOUT}
```
public static final int SPLITVOUT
```

Out Vertical Split

### TBGLITTER {#TBGLITTER}
```
public static final int TBGLITTER
```

Top-Bottom Glitter

### TBWIPE {#TBWIPE}
```
public static final int TBWIPE
```

Top-Bottom Wipe

### PdfPageEditor {#PdfPageEditor--}
```
public PdfPageEditor()
```

Constructor for PdfPageEditor class.

### PdfPageEditor {#PdfPageEditor-com.aspose.pdf.Document-}
Constructor for PdfPageEditor class.

### applyChanges {#applyChanges--}
```
public void applyChanges()
```

Apply changes made to the document pages.

### getAlignment {#getAlignment--}
```
@Deprecated public AlignmentType getAlignment()
```

Gets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left. Use getHorizontalAlignment instead

**Returns:**
AlignmentType object @see HorizontalAlignment

### getDisplayDuration {#getDisplayDuration--}
```
public int getDisplayDuration()
```

Gets display duration for pages.

**Returns:**
int value

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Gets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left.

**Returns:**
HorizontalAlignment element @see HorizontalAlignment

### getPageBoxSize {#getPageBoxSize-int-java.lang.String-}
<p> Returns size of specified box in document. </p> <hr> <pre> The following example demonstrates how to get media box of the 1st page: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); Rectangle rect = editor.getBoxSize(1, "media"); </pre>

### getPageRectangle {#getPageRectangle-com.aspose.pdf.Page-}
Return page size of the page.

### getPageRotation {#getPageRotation-int-}
```
public int getPageRotation(int page)
```

<p> Returns the rotation of specified page. </p> <hr> <pre> The following example demonstrates how to get page rotation: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); int rotation = editor.getPageSize(1); System.out.println("Rotation of 1st page : " + rotation + " degrees"); </pre>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page |  | Page index. Document pages are numbered from 1. |

**Returns:**
Page rotation in degrees.

### getPageRotations {#getPageRotations--}
```
public Map < Integer , Integer > getPageRotations()
```

<p> Gets the rotation of the pages, A hashtable contains the page number and rotation degree, the key represents the page number, the value of key represents the rotation in degrees. </p>

**Returns:**
{@code Map<Integer, Integer>} object

### getPages {#getPages--}
```
public int getPages()
```

<p> Returns total number of pages. </p> <hr> <pre> The following example demonstrates using of GetPages() method: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); System.out.println("Document has: " + editor.GetPages()); </pre>

**Returns:**
Number of pages.

### getPageSize {#getPageSize--}
```
public PageSize getPageSize()
```

Gets the output file's page size.

**Returns:**
PageSize object

### getPageSize {#getPageSize-int-}
```
public PageSize getPageSize(int page)
```

<p> Returns the page size of the specified page. </p> <hr> <pre> The following example demonstrates using of GetPageSize method: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); PageSize size = editor.getPageSize(1); System.out.println("Size of 1st page : " + size.getWidth() + " x " + size.getHeight()); </pre>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page |  | Page index. Document pages are numbered from 1. |

**Returns:**
Result is instance of PageSize. Use Width and Height properties of the returned object to get page width and height.

### getProcessPages {#getProcessPages--}
```
public int[] getProcessPages()
```

Gets the page numbers to be edited. By default, each page would be edited.

**Returns:**
array of int values

### getRotation {#getRotation--}
```
public int getRotation()
```

Gets the rotation of the pages, the rotation must be 0, 90, 180 or 270. Default value is 0.

**Returns:**
int value

### getTransitionDuration {#getTransitionDuration--}
```
public int getTransitionDuration()
```

Gets duration of the transition effect.

**Returns:**
int value

### getTransitionType {#getTransitionType--}
```
public int getTransitionType()
```

Gets transition style to use when moving to this page from another during a presentation.

**Returns:**
int value

### getVerticalAlignment {#getVerticalAlignment--}
```
@Deprecated public VerticalAlignmentType getVerticalAlignment()
```

Gets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom. Use getVerticalAlignmentType instead

**Returns:**
VerticalAlignmentType object

### getVerticalAlignmentType {#getVerticalAlignmentType--}
```
public VerticalAlignment getVerticalAlignmentType()
```

Gets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom.

**Returns:**
VerticalAlignmentType element @see VerticalAlignmentType

### getZoom {#getZoom--}
```
public float getZoom()
```

Get zoom coefficient. Value 1.0 corresponds to 100%. Default value is 1.0.

**Returns:**
float value

### isBoxDefined {#isBoxDefined-com.aspose.pdf.Page-java.lang.String-}
Check is the box is defined on the page.

### movePosition {#movePosition-float-float-}
```
public void movePosition(float moveX, float moveY)
```

<p> Moves the origin from (0, 0) to the point that appointted. The origin is left-bottom and the unit is point(1 inch = 72 points). </p> <hr> <pre> PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("input.pdf"); editor.movePosition(-100, 60); editor.save("moved.pdf"); </pre>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| moveX |  | X-coordinate. |
| moveY |  | Y-coordinate. |

### save {#save-java.io.OutputStream-}
<p> Saves changed document into stream. </p> <hr> <pre> The following sample demonstrates how to save changed PDF document into stream. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre>

### save {#save-java.lang.String-}
<p> Saves changed document into file. </p> <hr> <pre> The following sample demonstrates how to save changed PDF document PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre>

### setAlignment {#setAlignment-com.aspose.pdf.facades.AlignmentType-}
Sets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left. Use setHorizontalAlignment instead

### setDisplayDuration {#setDisplayDuration-int-}
```
public void setDisplayDuration(int value)
```

Sets display duration for pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Sets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left.

### setPageRotations {#setPageRotations-java.util.Map-}
Sets the rotation of the pages, A hashtable contains the page number and rotation degree, the key represents the page number, the value of key represents the rotation in degrees.

### setPageSize {#setPageSize-com.aspose.pdf.PageSize-}
Sets the output file's page size.

### setProcessPages {#setProcessPages-int:A-}
```
public void setProcessPages(int[] value)
```

Sets the page numbers to be edited. By default, each page would be edited.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | array of int values |

### setRotation {#setRotation-int-}
```
public void setRotation(int value)
```

Sets the rotation of the pages, the rotation must be 0, 90, 180 or 270. Default value is 0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setTransitionDuration {#setTransitionDuration-int-}
```
public void setTransitionDuration(int value)
```

Sets duration of the transition effect.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setTransitionType {#setTransitionType-int-}
```
public void setTransitionType(int value)
```

Sets transition style to use when moving to this page from another during a presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-}
Sets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom. Use setVerticalAlignmentType instead

### setVerticalAlignmentType {#setVerticalAlignmentType-com.aspose.pdf.VerticalAlignment-}
Sets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom.

### setZoom {#setZoom-float-}
```
public void setZoom(float value)
```

<p> Sets zoom coefficient. Value 1.0 corresponds to 100%. Default value is 1.0. </p>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value <hr> <pre> The following example demonstrates how to change zoom of the document pages. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); </pre> |
