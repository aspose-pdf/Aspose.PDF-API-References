---
title: PdfPageEditor
second_title: Aspose.PDF for Java API Reference
description: Represents a class to edit the PDF files page including rotating page zooming page moving position and changing page size.
type: docs
weight: 49
url: /java/com.aspose.pdf.facades/pdfpageeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)
```
public final class PdfPageEditor extends SaveableFacade
```

Represents a class to edit the PDF file's page, including rotating page, zooming page, moving position and changing page size.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfPageEditor()](#PdfPageEditor--) | Constructor for PdfPageEditor class. |
| [PdfPageEditor(Document document)](#PdfPageEditor-com.aspose.pdf.Document-) | Constructor for PdfPageEditor class. |
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
## Methods

| Method | Description |
| --- | --- |
| [applyChanges()](#applyChanges--) | Apply changes made to the document pages. |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Initializes the facade. |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | Initializes the facade. |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | Initializes the facade. |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | Initializes the facade. |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | Initializes the facade. |
| [close()](#close--) | Disposes Document bound with a facade. |
| [dispose()](#dispose--) | Disposes the facade. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Gets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left. |
| [getClass()](#getClass--) |  |
| [getDisplayDuration()](#getDisplayDuration--) | Gets display duration for pages. |
| [getDocument()](#getDocument--) | Gets the document facade is working on. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Gets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left. |
| [getPageBoxSize(int page, String pageBoxName)](#getPageBoxSize-int-java.lang.String-) | Returns size of specified box in document. |
| [getPageRotation(int page)](#getPageRotation-int-) | Returns the rotation of specified page. |
| [getPageRotations()](#getPageRotations--) | Gets the rotation of the pages, A hashtable contains the page number and rotation degree, the key represents the page number, the value of key represents the rotation in degrees. |
| [getPageSize()](#getPageSize--) | Gets the output file's page size. |
| [getPageSize(int page)](#getPageSize-int-) | Returns the page size of the specified page. |
| [getPages()](#getPages--) | Returns total number of pages. |
| [getProcessPages()](#getProcessPages--) | Gets the page numbers to be edited. |
| [getRotation()](#getRotation--) | Gets the rotation of the pages, the rotation must be 0, 90, 180 or 270. |
| [getTransitionDuration()](#getTransitionDuration--) | Gets duration of the transition effect. |
| [getTransitionType()](#getTransitionType--) | Gets transition style to use when moving to this page from another during a presentation. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Gets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom. |
| [getVerticalAlignmentType()](#getVerticalAlignmentType--) | Gets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom. |
| [getZoom()](#getZoom--) | Get zoom coefficient. |
| [hashCode()](#hashCode--) |  |
| [movePosition(float moveX, float moveY)](#movePosition-float-float-) | Moves the origin from (0, 0) to the point that appointted. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | Saves changed document into stream. |
| [save(String outputFile)](#save-java.lang.String-) | Saves changed document into file. |
| [setAlignment(AlignmentType value)](#setAlignment-com.aspose.pdf.facades.AlignmentType-) | Sets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left. |
| [setDisplayDuration(int value)](#setDisplayDuration-int-) | Sets display duration for pages. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Sets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left. |
| [setPageRotations(Map<Integer,Integer> value)](#setPageRotations-java.util.Map-java.lang.Integer-java.lang.Integer--) | Sets the rotation of the pages, A hashtable contains the page number and rotation degree, the key represents the page number, the value of key represents the rotation in degrees. |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.pdf.PageSize-) | Sets the output file's page size. |
| [setProcessPages(int[] value)](#setProcessPages-int---) | Sets the page numbers to be edited. |
| [setRotation(int value)](#setRotation-int-) | Sets the rotation of the pages, the rotation must be 0, 90, 180 or 270. |
| [setTransitionDuration(int value)](#setTransitionDuration-int-) | Sets duration of the transition effect. |
| [setTransitionType(int value)](#setTransitionType-int-) | Sets transition style to use when moving to this page from another during a presentation. |
| [setVerticalAlignment(VerticalAlignmentType value)](#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-) | Sets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom. |
| [setVerticalAlignmentType(int value)](#setVerticalAlignmentType-int-) | Sets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom. |
| [setZoom(float value)](#setZoom-float-) | Sets zoom coefficient. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfPageEditor() {#PdfPageEditor--}
```
public PdfPageEditor()
```


Constructor for PdfPageEditor class.

### PdfPageEditor(Document document) {#PdfPageEditor-com.aspose.pdf.Document-}
```
public PdfPageEditor(Document document)
```


Constructor for PdfPageEditor class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [Document](../../com.aspose.pdf/document) | Document object which should be processed. |

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

### applyChanges() {#applyChanges--}
```
public void applyChanges()
```


Apply changes made to the document pages.

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | The Document object. |

### bindPdf(InputStream srcStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream srcStream)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | The stream of PDF file. |

### bindPdf(InputStream srcStream, String password) {#bindPdf-java.io.InputStream-java.lang.String-}
```
public void bindPdf(InputStream srcStream, String password)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | The stream of PDF file. |
| password | java.lang.String | The password of the PDF document. |

### bindPdf(String srcFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String srcFile)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFile | java.lang.String | The PDF file. |

### bindPdf(String srcFile, String password) {#bindPdf-java.lang.String-java.lang.String-}
```
public void bindPdf(String srcFile, String password)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFile | java.lang.String | The PDF file |
| password | java.lang.String | The password of the PDF document. |

### close() {#close--}
```
public void close()
```


Disposes Document bound with a facade.

### dispose() {#dispose--}
```
public void dispose()
```


Disposes the facade.

This method is obsolete, use close() instead.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignment() {#getAlignment--}
```
public AlignmentType getAlignment()
```


Gets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left.
Use getHorizontalAlignment instead

**Returns:**
[AlignmentType](../../com.aspose.pdf.facades/alignmenttype) - AlignmentType object
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisplayDuration() {#getDisplayDuration--}
```
public int getDisplayDuration()
```


Gets display duration for pages.

**Returns:**
int - int value
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


Gets the document facade is working on.

**Returns:**
[IDocument](../../com.aspose.pdf/idocument) - IDocument element
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Gets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left.

**Returns:**
int - HorizontalAlignment element
### getPageBoxSize(int page, String pageBoxName) {#getPageBoxSize-int-java.lang.String-}
```
public Rectangle getPageBoxSize(int page, String pageBoxName)
```


Returns size of specified box in document.

--------------------

```
The following example demonstrates how to get media box of the 1st page:


 PdfPageEditor editor = new PdfPageEditor();
 editor.bindPdf("sample.pdf");
 Rectangle rect = editor.getBoxSize(1, "media");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | int | Page index. Document pages are numbered from 1. |
| pageBoxName | java.lang.String | Box type name. Valid values are: "art", "bleed", "crop", "media", "trim". |

**Returns:**
[Rectangle](../../java.awt/rectangle) - Rectangle which contains requested box.
### getPageRotation(int page) {#getPageRotation-int-}
```
public int getPageRotation(int page)
```


Returns the rotation of specified page.

--------------------

```
The following example demonstrates how to get page rotation:


 PdfPageEditor editor = new PdfPageEditor();
 editor.bindPdf("sample.pdf");
 int rotation = editor.getPageSize(1);
 System.out.println("Rotation of 1st page : " + rotation + " degrees");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | int | Page index. Document pages are numbered from 1. |

**Returns:**
int - Page rotation in degrees.
### getPageRotations() {#getPageRotations--}
```
public Map<Integer,Integer> getPageRotations()
```


Gets the rotation of the pages, A hashtable contains the page number and rotation degree, the key represents the page number, the value of key represents the rotation in degrees.

**Returns:**
java.util.Map<java.lang.Integer,java.lang.Integer> -  Map  object
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Gets the output file's page size.

**Returns:**
[PageSize](../../com.aspose.pdf/pagesize) - PageSize object
### getPageSize(int page) {#getPageSize-int-}
```
public PageSize getPageSize(int page)
```


Returns the page size of the specified page.

--------------------

```
The following example demonstrates using of GetPageSize method:


 PdfPageEditor editor = new PdfPageEditor();
 editor.bindPdf("sample.pdf");
 PageSize size = editor.getPageSize(1);
 System.out.println("Size of 1st page : " + size.getWidth() + " x " + size.getHeight());
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | int | Page index. Document pages are numbered from 1. |

**Returns:**
[PageSize](../../com.aspose.pdf/pagesize) - Result is instance of PageSize. Use Width and Height properties of the returned object to get page width and height.
### getPages() {#getPages--}
```
public int getPages()
```


Returns total number of pages.

--------------------

```
The following example demonstrates using of GetPages() method:


 PdfPageEditor editor = new PdfPageEditor();
 editor.bindPdf("sample.pdf");
 System.out.println("Document has: " + editor.GetPages());
```

**Returns:**
int - Number of pages.
### getProcessPages() {#getProcessPages--}
```
public int[] getProcessPages()
```


Gets the page numbers to be edited. By default, each page would be edited.

**Returns:**
int[] - array of int values
### getRotation() {#getRotation--}
```
public int getRotation()
```


Gets the rotation of the pages, the rotation must be 0, 90, 180 or 270. Default value is 0.

**Returns:**
int - int value
### getTransitionDuration() {#getTransitionDuration--}
```
public int getTransitionDuration()
```


Gets duration of the transition effect.

**Returns:**
int - int value
### getTransitionType() {#getTransitionType--}
```
public int getTransitionType()
```


Gets transition style to use when moving to this page from another during a presentation.

**Returns:**
int - int value
### getVerticalAlignment() {#getVerticalAlignment--}
```
public VerticalAlignmentType getVerticalAlignment()
```


Gets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom.
Use getVerticalAlignmentType instead

**Returns:**
[VerticalAlignmentType](../../com.aspose.pdf.facades/verticalalignmenttype) - VerticalAlignmentType object
### getVerticalAlignmentType() {#getVerticalAlignmentType--}
```
public int getVerticalAlignmentType()
```


Gets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom.

**Returns:**
int - VerticalAlignmentType element
### getZoom() {#getZoom--}
```
public float getZoom()
```


Get zoom coefficient. Value 1.0 corresponds to 100%. Default value is 1.0.

**Returns:**
float - float value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### movePosition(float moveX, float moveY) {#movePosition-float-float-}
```
public void movePosition(float moveX, float moveY)
```


Moves the origin from (0, 0) to the point that appointted. The origin is left-bottom and the unit is point(1 inch = 72 points).

--------------------

```
PdfPageEditor editor = new PdfPageEditor();
 editor.bindPdf("input.pdf");
 editor.movePosition(-100, 60);
 editor.save("moved.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| moveX | float | X-coordinate. |
| moveY | float | Y-coordinate. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


Saves changed document into stream.

--------------------

```
The following sample demonstrates how to save changed PDF document into stream.


 PdfPageEditor editor = new PdfPageEditor();
 editor.bindPdf("sample.pdf");
 editor.setZoom ( 0.5f);
 editor.save("newdocument.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Stream where changed PDF document will be saved. |

### save(String outputFile) {#save-java.lang.String-}
```
public void save(String outputFile)
```


Saves changed document into file.

--------------------

```
The following sample demonstrates how to save changed PDF document


 PdfPageEditor editor = new PdfPageEditor();
 editor.bindPdf("sample.pdf");
 editor.setZoom ( 0.5f);
 editor.save("newdocument.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | java.lang.String | Path to file where document will be saved. |

### setAlignment(AlignmentType value) {#setAlignment-com.aspose.pdf.facades.AlignmentType-}
```
public void setAlignment(AlignmentType value)
```


Sets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left.
Use setHorizontalAlignment instead

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [AlignmentType](../../com.aspose.pdf.facades/alignmenttype) | AlignmentType value |

### setDisplayDuration(int value) {#setDisplayDuration-int-}
```
public void setDisplayDuration(int value)
```


Sets display duration for pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


Sets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setPageRotations(Map<Integer,Integer> value) {#setPageRotations-java.util.Map-java.lang.Integer-java.lang.Integer--}
```
public void setPageRotations(Map<Integer,Integer> value)
```


Sets the rotation of the pages, A hashtable contains the page number and rotation degree, the key represents the page number, the value of key represents the rotation in degrees.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Map<java.lang.Integer,java.lang.Integer> |  Map  object |

### setPageSize(PageSize value) {#setPageSize-com.aspose.pdf.PageSize-}
```
public void setPageSize(PageSize value)
```


Sets the output file's page size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.pdf/pagesize) | PageSize object |

### setProcessPages(int[] value) {#setProcessPages-int---}
```
public void setProcessPages(int[] value)
```


Sets the page numbers to be edited. By default, each page would be edited.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | array of int values |

### setRotation(int value) {#setRotation-int-}
```
public void setRotation(int value)
```


Sets the rotation of the pages, the rotation must be 0, 90, 180 or 270. Default value is 0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setTransitionDuration(int value) {#setTransitionDuration-int-}
```
public void setTransitionDuration(int value)
```


Sets duration of the transition effect.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setTransitionType(int value) {#setTransitionType-int-}
```
public void setTransitionType(int value)
```


Sets transition style to use when moving to this page from another during a presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setVerticalAlignment(VerticalAlignmentType value) {#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-}
```
public void setVerticalAlignment(VerticalAlignmentType value)
```


Sets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom.
Use setVerticalAlignmentType instead

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VerticalAlignmentType](../../com.aspose.pdf.facades/verticalalignmenttype) | VerticalAlignmentType value |

### setVerticalAlignmentType(int value) {#setVerticalAlignmentType-int-}
```
public void setVerticalAlignmentType(int value)
```


Sets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | VerticalAlignment element |

### setZoom(float value) {#setZoom-float-}
```
public void setZoom(float value)
```


Sets zoom coefficient. Value 1.0 corresponds to 100%. Default value is 1.0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value

--------------------

```
The following example demonstrates how to change zoom of the document pages.


                 PdfPageEditor editor = new PdfPageEditor();
                 editor.bindPdf("sample.pdf");
                 editor.setZoom ( 0.5f);
``` |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

