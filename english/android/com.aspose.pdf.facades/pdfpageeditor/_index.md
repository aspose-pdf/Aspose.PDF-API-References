---
title: PdfPageEditor
second_title: Aspose.PDF for Java API Reference
description: Represents a class to edit the PDF files page including rotating page zooming page moving position and changing page size.
type: docs
weight: 43
url: /java/com.aspose.pdf.facades/pdfpageeditor/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)
```
public final class PdfPageEditor extends SaveableFacade
```

Represents a class to edit the PDF file's page, including rotating page, zooming page, moving position and changing page size.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfPageEditor()](#PdfPageEditor--) |  |
| [PdfPageEditor(Document document)](#PdfPageEditor-com.aspose.pdf.Document-) |  |
## Fields

| Field | Description |
| --- | --- |
| [SPLITVOUT](#SPLITVOUT) | Out Vertical Split |
| [SPLITHOUT](#SPLITHOUT) | Out Horizontal Split |
| [SPLITVIN](#SPLITVIN) | In Vertical Split |
| [SPLITHIN](#SPLITHIN) | IN Horizontal Split |
| [BLINDV](#BLINDV) | Vertical Blinds |
| [BLINDH](#BLINDH) | Vertical Blinds |
| [INBOX](#INBOX) | Inward Box |
| [OUTBOX](#OUTBOX) | Outward Box |
| [LRWIPE](#LRWIPE) | Left-Right Wipe |
| [RLWIPE](#RLWIPE) | Right-Left Wipe |
| [BTWIPE](#BTWIPE) | Bottom-Top Wipe |
| [TBWIPE](#TBWIPE) | Top-Bottom Wipe |
| [DISSOLVE](#DISSOLVE) | Dissolve |
| [LRGLITTER](#LRGLITTER) | Left-Right Glitter |
| [TBGLITTER](#TBGLITTER) | Top-Bottom Glitter |
| [DGLITTER](#DGLITTER) | Diagonal Glitter |
## Methods

| Method | Description |
| --- | --- |
| [getTransitionDuration()](#getTransitionDuration--) | Gets duration of the transition effect. |
| [setTransitionDuration(int value)](#setTransitionDuration-int-) | Sets duration of the transition effect. |
| [getTransitionType()](#getTransitionType--) | Gets transition style to use when moving to this page from another during a presentation. |
| [setTransitionType(int value)](#setTransitionType-int-) | Sets transition style to use when moving to this page from another during a presentation. |
| [getDisplayDuration()](#getDisplayDuration--) | Gets display duration for pages. |
| [setDisplayDuration(int value)](#setDisplayDuration-int-) | Sets display duration for pages. |
| [getPages_Rename_Namesake()](#getPages-Rename-Namesake--) | Gets the page numbers to be edited. |
| [setPages(int[] value)](#setPages-int---) | Sets the page numbers to be edited. |
| [getRotation()](#getRotation--) | Gets the rotation of the pages, the rotation must be 0, 90, 180 or 270. |
| [setRotation(int value)](#setRotation-int-) | Sets the rotation of the pages, the rotation must be 0, 90, 180 or 270. |
| [getPageRotations()](#getPageRotations--) | Gets the rotation of the pages, A hashtable contains the page number and rotation degree, the key represents the page number, the value of key represents the rotation in degrees. |
| [setPageRotations(Map value)](#setPageRotations-java.util.Map-) | Sets the rotation of the pages, A hashtable contains the page number and rotation degree, the key represents the page number, the value of key represents the rotation in degrees. |
| [getZoom()](#getZoom--) | Get zoom coefficient. |
| [setZoom(float value)](#setZoom-float-) | Sets zoom coefficient. |
| [getPageSize()](#getPageSize--) | Gets the output file's page size. |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.pdf.facades.PageSize-) | Sets the output file's page size. |
| [getAlignment()](#getAlignment--) | Gets or sets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left. |
| [setAlignment(AlignmentType value)](#setAlignment-com.aspose.pdf.facades.AlignmentType-) | Sets or sets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Gets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Sets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Gets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom. |
| [setVerticalAlignment(VerticalAlignmentType value)](#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-) | Sets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom. |
| [getVerticalAlignmentType()](#getVerticalAlignmentType--) | Gets or Sets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom. |
| [setVerticalAlignmentType(int value)](#setVerticalAlignmentType-int-) | Sets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom. |
| [movePosition(float moveX, float moveY)](#movePosition-float-float-) | Moves the origin from (0, 0) to the point that appointted. |
| [getPages()](#getPages--) | Returns total number of pages. |
| [getPageSize(int page)](#getPageSize-int-) | Returns the page size of the specified page. |
| [getPageRotation(int page)](#getPageRotation-int-) | Returns the rotation of specified page. |
| [getPageBoxSize(int page, String pageBoxName)](#getPageBoxSize-int-java.lang.String-) | Returns size of specified box in document. |
| [save(String outputFile)](#save-java.lang.String-) | Saves changed document into file. |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | Saves changed document into stream. |
| [applyChanges()](#applyChanges--) | Apply changes made to the document pages. |
### PdfPageEditor() {#PdfPageEditor--}
```
public PdfPageEditor()
```




### PdfPageEditor(Document document) {#PdfPageEditor-com.aspose.pdf.Document-}
```
public PdfPageEditor(Document document)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [Document](../../com.aspose.pdf/document) |  |

### SPLITVOUT {#SPLITVOUT}
```
public static final int SPLITVOUT
```


Out Vertical Split

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

### SPLITHIN {#SPLITHIN}
```
public static final int SPLITHIN
```


IN Horizontal Split

### BLINDV {#BLINDV}
```
public static final int BLINDV
```


Vertical Blinds

### BLINDH {#BLINDH}
```
public static final int BLINDH
```


Vertical Blinds

### INBOX {#INBOX}
```
public static final int INBOX
```


Inward Box

### OUTBOX {#OUTBOX}
```
public static final int OUTBOX
```


Outward Box

### LRWIPE {#LRWIPE}
```
public static final int LRWIPE
```


Left-Right Wipe

### RLWIPE {#RLWIPE}
```
public static final int RLWIPE
```


Right-Left Wipe

### BTWIPE {#BTWIPE}
```
public static final int BTWIPE
```


Bottom-Top Wipe

### TBWIPE {#TBWIPE}
```
public static final int TBWIPE
```


Top-Bottom Wipe

### DISSOLVE {#DISSOLVE}
```
public static final int DISSOLVE
```


Dissolve

### LRGLITTER {#LRGLITTER}
```
public static final int LRGLITTER
```


Left-Right Glitter

### TBGLITTER {#TBGLITTER}
```
public static final int TBGLITTER
```


Top-Bottom Glitter

### DGLITTER {#DGLITTER}
```
public static final int DGLITTER
```


Diagonal Glitter

### getTransitionDuration() {#getTransitionDuration--}
```
public int getTransitionDuration()
```


Gets duration of the transition effect.

**Returns:**
int
### setTransitionDuration(int value) {#setTransitionDuration-int-}
```
public void setTransitionDuration(int value)
```


Sets duration of the transition effect.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTransitionType() {#getTransitionType--}
```
public int getTransitionType()
```


Gets transition style to use when moving to this page from another during a presentation.

**Returns:**
int
### setTransitionType(int value) {#setTransitionType-int-}
```
public void setTransitionType(int value)
```


Sets transition style to use when moving to this page from another during a presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDisplayDuration() {#getDisplayDuration--}
```
public int getDisplayDuration()
```


Gets display duration for pages.

**Returns:**
int
### setDisplayDuration(int value) {#setDisplayDuration-int-}
```
public void setDisplayDuration(int value)
```


Sets display duration for pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPages_Rename_Namesake() {#getPages-Rename-Namesake--}
```
public int[] getPages_Rename_Namesake()
```


Gets the page numbers to be edited. By default, each page would be edited.

**Returns:**
int[]
### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


Sets the page numbers to be edited. By default, each page would be edited.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### getRotation() {#getRotation--}
```
public int getRotation()
```


Gets the rotation of the pages, the rotation must be 0, 90, 180 or 270. Default value is 0.

**Returns:**
int
### setRotation(int value) {#setRotation-int-}
```
public void setRotation(int value)
```


Sets the rotation of the pages, the rotation must be 0, 90, 180 or 270. Default value is 0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPageRotations() {#getPageRotations--}
```
public Map getPageRotations()
```


Gets the rotation of the pages, A hashtable contains the page number and rotation degree, the key represents the page number, the value of key represents the rotation in degrees.

**Returns:**
java.util.Map
### setPageRotations(Map value) {#setPageRotations-java.util.Map-}
```
public void setPageRotations(Map value)
```


Sets the rotation of the pages, A hashtable contains the page number and rotation degree, the key represents the page number, the value of key represents the rotation in degrees.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Map |  |

### getZoom() {#getZoom--}
```
public float getZoom()
```


Get zoom coefficient. Value 1.0 corresponds to 100%. Default value is 1.0.

**Returns:**
float
### setZoom(float value) {#setZoom-float-}
```
public void setZoom(float value)
```


Sets zoom coefficient. Value 1.0 corresponds to 100%. Default value is 1.0.

--------------------

> ```
> The following example demonstrates how to change zoom of the document pages.
>  
>  PdfPageEditor editor = new PdfPageEditor();
>  editor.bindPdf("sample.pdf");
>  editor.setZoom ( 0.5f);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Gets the output file's page size.

**Returns:**
[PageSize](../../com.aspose.pdf.facades/pagesize)
### setPageSize(PageSize value) {#setPageSize-com.aspose.pdf.facades.PageSize-}
```
public void setPageSize(PageSize value)
```


Sets the output file's page size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.pdf.facades/pagesize) |  |

### getAlignment() {#getAlignment--}
```
public AlignmentType getAlignment()
```


Gets or sets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left.
Use getHorizontalAlignment instead

**Returns:**
[AlignmentType](../../com.aspose.pdf.facades/alignmenttype)
### setAlignment(AlignmentType value) {#setAlignment-com.aspose.pdf.facades.AlignmentType-}
```
public void setAlignment(AlignmentType value)
```


Sets or sets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left.
Use setHorizontalAlignment instead

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [AlignmentType](../../com.aspose.pdf.facades/alignmenttype) |  |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Gets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left.

**Returns:**
int
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


Sets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public VerticalAlignmentType getVerticalAlignment()
```


Gets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom.
Use getVerticalAlignmentType instead

**Returns:**
[VerticalAlignmentType](../../com.aspose.pdf.facades/verticalalignmenttype)
### setVerticalAlignment(VerticalAlignmentType value) {#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-}
```
public void setVerticalAlignment(VerticalAlignmentType value)
```


Sets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom.
Use setVerticalAlignmentType instead

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VerticalAlignmentType](../../com.aspose.pdf.facades/verticalalignmenttype) |  |

### getVerticalAlignmentType() {#getVerticalAlignmentType--}
```
public int getVerticalAlignmentType()
```


Gets or Sets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom.

**Returns:**
int
### setVerticalAlignmentType(int value) {#setVerticalAlignmentType-int-}
```
public void setVerticalAlignmentType(int value)
```


Sets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### movePosition(float moveX, float moveY) {#movePosition-float-float-}
```
public void movePosition(float moveX, float moveY)
```


Moves the origin from (0, 0) to the point that appointted. The origin is left-bottom and the unit is point(1 inch = 72 points).

--------------------

> ```
> PdfPageEditor editor = new PdfPageEditor();
>  editor.bindPdf("input.pdf");
>  editor.movePosition(-100, 60);
>  editor.save("moved.pdf");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| moveX | float | X-coordinate. |
| moveY | float | Y-coordinate. |

### getPages() {#getPages--}
```
public int getPages()
```


Returns total number of pages.

--------------------

> ```
> The following example demonstrates using of GetPages() method:
>  
>  PdfPageEditor editor = new PdfPageEditor();
>  editor.bindPdf("sample.pdf");
>  System.out.println("Document has: " + editor.GetPages());
> ```

**Returns:**
int
### getPageSize(int page) {#getPageSize-int-}
```
public PageSize getPageSize(int page)
```


Returns the page size of the specified page.

--------------------

> ```
> The following example demonstrates using of GetPageSize method: 
>  
>  PdfPageEditor editor = new PdfPageEditor();
>  editor.bindPdf("sample.pdf");
>  PageSize size = editor.getPageSize(1);
>  System.out.println("Size of 1st page : " + size.Width + " x " + size.Height);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | int | Page index. Document pages are numbered from 1. |

**Returns:**
[PageSize](../../com.aspose.pdf.facades/pagesize) - Result is instance of PageSize. Use Width and Height properties of the returned object to get page width and height.
### getPageRotation(int page) {#getPageRotation-int-}
```
public int getPageRotation(int page)
```


Returns the rotation of specified page.

--------------------

> ```
> The following example demonstrates how to get page rotation:
>  
>  PdfPageEditor editor = new PdfPageEditor();
>  editor.bindPdf("sample.pdf");
>  int rotation = editor.GetPageSize(1);
>  System.out.println("Rotation of 1st page : " + rotation + " degrees");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | int | Page index. Document pages are numbered from 1. |

**Returns:**
int - Page rotation in degrees.
### getPageBoxSize(int page, String pageBoxName) {#getPageBoxSize-int-java.lang.String-}
```
public Rect getPageBoxSize(int page, String pageBoxName)
```


Returns size of specified box in document.

--------------------

> ```
> The following example demonstrates how to get media box of the 1st page:
>  
>  PdfPageEditor editor = new PdfPageEditor();
>  editor.bindPdf("sample.pdf");
>  Rectangle rect = editor.getBoxSize(1, "media");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | int | Page index. Document pages are numbered from 1. |
| pageBoxName | java.lang.String | Box type name. Valid values are: "art", "bleed", "crop", "media", "trim". |

**Returns:**
android.graphics.Rect - Rectangle which contains requested box.
### save(String outputFile) {#save-java.lang.String-}
```
public void save(String outputFile)
```


Saves changed document into file.

--------------------

> ```
> The following sample demonstrates how to save changed PDF document
>  
>  PdfPageEditor editor = new PdfPageEditor();
>  editor.bindPdf("sample.pdf");
>  editor.setZoom ( 0.5f);
>  editor.save("newdocument.pdf");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | Path to file where document will be saved. |

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


Saves changed document into stream.

--------------------

> ```
> The following sample demonstrates how to save changed PDF document into stream.
>  
>  PdfPageEditor editor = new PdfPageEditor();
>  editor.bindPdf("sample.pdf");
>  editor.setZoom ( 0.5f);
>  editor.save("newdocument.pdf");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Stream where changed PDF document will be saved. |

### applyChanges() {#applyChanges--}
```
public void applyChanges()
```


Apply changes made to the document pages.

