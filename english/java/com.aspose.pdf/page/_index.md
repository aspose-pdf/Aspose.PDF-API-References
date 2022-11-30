---
title: Page
second_title: Aspose.PDF for Java API Reference
description: Class representing page of PDF document.
type: docs
weight: 257
url: /java/com.aspose.pdf/page/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable, com.aspose.pdf.ISupportsMemoryCleanup
```
public final class Page implements System.IDisposable, Closeable, ISupportsMemoryCleanup
```

Class representing page of PDF document.
## Methods

| Method | Description |
| --- | --- |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts  AnnotationSelector  visitor object that provides functionality to work with annotations. |
| [accept(ImagePlacementAbsorber visitor)](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | Accepts  ImagePlacementAbsorber  visitor object that provides functionality to work with image placement objects. |
| [accept(TextAbsorber visitor)](#accept-com.aspose.pdf.TextAbsorber-) | Accepts  TextAbsorber  visitor object that provides functionality to work with text objects. |
| [accept(TextFragmentAbsorber visitor)](#accept-com.aspose.pdf.TextFragmentAbsorber-) | Accepts  TextFragmentAbsorber  visitor object that provides functionality to work with text objects. |
| [addImage(InputStream imageStream, Rectangle imageRect)](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-) | Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [addImage(InputStream stream, Rectangle rectangle, CompositingParameters compositingParameters)](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-) | Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [addImage(InputStream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, boolean saveImageProportions)](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-) | Adds searchable image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [addImage(String imagePath, Rectangle rectangle)](#addImage-java.lang.String-com.aspose.pdf.Rectangle-) | Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [addImage(String hocr, InputStream imageStream, Rectangle imageRect)](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-) | Adds searchable image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [addStamp(Stamp stamp)](#addStamp-com.aspose.pdf.Stamp-) | Put stamp into page. |
| [asByteArray(Resolution resolution)](#asByteArray-com.aspose.pdf.devices.Resolution-) | Converts current page as BMP bitmap and than returns array of bytes. |
| [asXml()](#asXml--) | Converts current page as xml in utf8 encoding. |
| [calculateContentBBox()](#calculateContentBBox--) | Calculates bbox value - rectangle containing contents without visible margins. |
| [clearContents()](#clearContents--) | For internal usage only |
| [close()](#close--) | Closes all resources used by this document. |
| [convertToPNGMemoryStream()](#convertToPNGMemoryStream--) | Convert page to PNG for DSR, OMR, OCR image stream. |
| [deleteUnusedResources(System.Collections.Generic.Dictionary<Integer,Integer> usageTable)](#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.Integer-java.lang.Integer--) |  |
| [dispose()](#dispose--) | Frees up memory |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillUsedObjectsTable(System.Collections.Generic.Dictionary<Integer,Integer> usageTable, IPdfDictionary CommonResources)](#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.Integer-java.lang.Integer--com.aspose.pdf.engine.data.IPdfDictionary-) |  |
| [findReferences(OperatorCollection contents, String name)](#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | Returns list of operators which uses resource with specified name. |
| [findReferences(String name)](#findReferences-java.lang.String-) | Find references |
| [flatten()](#flatten--) | Removes all static fields located on the page and place their values instead. |
| [freeMemory()](#freeMemory--) | Clears cached data |
| [getActions()](#getActions--) | Gets collection of page properties. |
| [getAnnotations()](#getAnnotations--) | Gets collection of page annotations. |
| [getArtBox()](#getArtBox--) | Gets art box of the page. |
| [getArtifacts()](#getArtifacts--) | Gets collection of artifacts on the page. |
| [getBackground()](#getBackground--) | Gets the background color of the page. |
| [getBackgroundImage()](#getBackgroundImage--) | Gets or sets background image for page (for generator only, not filled in when reading document). |
| [getBleedBox()](#getBleedBox--) | Gets bleed box of the page. |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | Gets color type of the pages based on information getting from operators SetColor, images and forms. |
| [getContents()](#getContents--) | Gets collection of operators in the content stream of the page. |
| [getContentsAppender()](#getContentsAppender--) | Gets current contents appender. |
| [getCropBox()](#getCropBox--) | Gets crop box of the page. |
| [getDocument()](#getDocument--) | Get document |
| [getDuration()](#getDuration--) | Gets page display duration. |
| [getEnginePage()](#getEnginePage--) | For Internal usage only |
| [getFieldsInTabOrder()](#getFieldsInTabOrder--) | Gets list of Field object in Tab order on this page. |
| [getFooter()](#getFooter--) | Gets page Footer. |
| [getGroup()](#getGroup--) | Gets a group attributes class specifying the attributes of the page's page group for use in the transparent imaging model. |
| [getHeader()](#getHeader--) | Gets page header. |
| [getLayers()](#getLayers--) | Gets layers collection. |
| [getMediaBox()](#getMediaBox--) | Gets media box of the page. |
| [getNoteLineStyle()](#getNoteLineStyle--) | Gets the line style for notes. |
| [getNotifications()](#getNotifications--) | Returns notifications about inside operations with page content. |
| [getNumber()](#getNumber--) | Get number of the page. |
| [getOnBeforePageGenerate()](#getOnBeforePageGenerate--) | Event for customize header and footer. |
| [getPageInfo()](#getPageInfo--) | Gets the page info. |
| [getPageRect(boolean considerRotation)](#getPageRect-boolean-) | Returns rectangle of the page according to its CropBox (or MediaBox if CropBox null). |
| [getParagraphs()](#getParagraphs--) | Gets the paragraphs. |
| [getRect()](#getRect--) | Returns rectangle of the page according to its CropBox and MediaBox; For get: page crop box is returned if specified, otherwise page media box is returned. |
| [getRect_Rename_Namesake()](#getRect-Rename-Namesake--) | Returns rectangle of the page according to its CropBox and MediaBox; |
| [getResources()](#getResources--) | Gets page resources. |
| [getRotate()](#getRotate--) | Gets rotation of the page. |
| [getRotationMatrix()](#getRotationMatrix--) | Gets transfomation matrix for the page. |
| [getTabOrder()](#getTabOrder--) | Gets tab order of the page. |
| [getTocInfo()](#getTocInfo--) | Gets table of contents info. |
| [getTrimBox()](#getTrimBox--) | Gets trim box of the page. |
| [getUserUnit()](#getUserUnit--) | Gets or sets UserUnit value. |
| [getWatermark()](#getWatermark--) | Gets the watermark of the page. |
| [hashCode()](#hashCode--) |  |
| [intToRotation(int rotation)](#intToRotation-int-) | Translates integer value into corresponding rotation enumeration member. |
| [isAddParagraphsAfterLast()](#isAddParagraphsAfterLast--) | Gets or sets the addition of paragraphs after the last paragraph of the page |
| [isBlank(double fillThresholdFactor)](#isBlank-double-) | Gets the flag whether page is blank or not. |
| [makeGrayscale()](#makeGrayscale--) | Converts the page to grayscale. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeObjectReferences(OperatorCollection contents, String name)](#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | Remove object references |
| [removeObjectReferences(String name)](#removeObjectReferences-java.lang.String-) | Remove references to XObject from page contents (i.e. all Do operators which use name of object). |
| [rotationToInt(int rotation)](#rotationToInt-int-) | Translates rotation enumeration member into integer value. |
| [sendTo(PageDevice device, OutputStream output)](#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-) | Sends page to process with given page device. |
| [sendTo(PageDevice device, String outputFileName)](#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-) | Sends page to process with given page device. |
| [setAddParagraphsAfterLast(boolean value)](#setAddParagraphsAfterLast-boolean-) | Gets or sets the addition of paragraphs after the last paragraph of the page |
| [setArtBox(Rectangle value)](#setArtBox-com.aspose.pdf.Rectangle-) | Sets art box of the page. |
| [setBackground(Color value)](#setBackground-com.aspose.pdf.Color-) | Sets the background color of the page. |
| [setBackground(Color value)](#setBackground-java.awt.Color-) | Sets the background color of the page. |
| [setBackgroundImage(Image value)](#setBackgroundImage-com.aspose.pdf.Image-) | Gets or sets background image for page (for generator only, not filled in when reading document). |
| [setBleedBox(Rectangle value)](#setBleedBox-com.aspose.pdf.Rectangle-) | Sets bleed box of the page. |
| [setCropBox(Rectangle value)](#setCropBox-com.aspose.pdf.Rectangle-) | Sets crop box of the page. |
| [setDuration(double value)](#setDuration-double-) | Sets page display duration. |
| [setEnginePage(IPage enginePage)](#setEnginePage-com.aspose.pdf.engine.commondata.IPage-) | For Internal usage only |
| [setFooter(HeaderFooter value)](#setFooter-com.aspose.pdf.HeaderFooter-) | Sets page Footer. |
| [setGroup(Group value)](#setGroup-com.aspose.pdf.Group-) | Sets a group attributes class specifying the attributes of the page's page group for use in the transparent imaging model. |
| [setHeader(HeaderFooter value)](#setHeader-com.aspose.pdf.HeaderFooter-) | Sets page header. |
| [setLayers(ArrayList<Layer> value)](#setLayers-java.util.ArrayList-com.aspose.pdf.Layer--) | Sets layers collection. |
| [setLayersInternal(System.Collections.Generic.List<Layer> value)](#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.Layer--) | Sets layers collection. |
| [setMediaBox(Rectangle value)](#setMediaBox-com.aspose.pdf.Rectangle-) | Sets media box of the page. |
| [setNoteLineStyle(GraphInfo value)](#setNoteLineStyle-com.aspose.pdf.GraphInfo-) | Sets the line style for notes. |
| [setPageInfo(PageInfo value)](#setPageInfo-com.aspose.pdf.PageInfo-) | Sets the page info. |
| [setPageSize(double width, double height)](#setPageSize-double-double-) | Sets page size for page. |
| [setParagraphs(Paragraphs value)](#setParagraphs-com.aspose.pdf.Paragraphs-) | Sets the paragraphs. |
| [setRect(Rectangle value)](#setRect-com.aspose.pdf.Rectangle-) | Gets or sets rectangle of the page. |
| [setRotate(int value)](#setRotate-int-) | Sets rotation of the page. |
| [setTabOrder(int value)](#setTabOrder-int-) | Sets tab order of the page. |
| [setTocInfo(TocInfo value)](#setTocInfo-com.aspose.pdf.TocInfo-) | Sets table of contents info. |
| [setTransition(IPdfDictionary transition)](#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-) | Set transition |
| [setTrimBox(Rectangle value)](#setTrimBox-com.aspose.pdf.Rectangle-) | Sets trim box of the page. |
| [setUserUnit(double value)](#setUserUnit-double-) | Gets or sets UserUnit value. |
| [setWatermark(Watermark value)](#setWatermark-com.aspose.pdf.Watermark-) | Sets the watermark of the page. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts  AnnotationSelector  visitor object that provides functionality to work with annotations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Annotation selector sobject. |

### accept(ImagePlacementAbsorber visitor) {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
```
public void accept(ImagePlacementAbsorber visitor)
```


Accepts  ImagePlacementAbsorber  visitor object that provides functionality to work with image placement objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [ImagePlacementAbsorber](../../com.aspose.pdf/imageplacementabsorber) | Image placement absorber object. |

### accept(TextAbsorber visitor) {#accept-com.aspose.pdf.TextAbsorber-}
```
public void accept(TextAbsorber visitor)
```


Accepts  TextAbsorber  visitor object that provides functionality to work with text objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [TextAbsorber](../../com.aspose.pdf/textabsorber) | Text absorber object. |

### accept(TextFragmentAbsorber visitor) {#accept-com.aspose.pdf.TextFragmentAbsorber-}
```
public void accept(TextFragmentAbsorber visitor)
```


Accepts  TextFragmentAbsorber  visitor object that provides functionality to work with text objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber) | Text absorber object. |

### addImage(InputStream imageStream, Rectangle imageRect) {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-}
```
public void addImage(InputStream imageStream, Rectangle imageRect)
```


Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | java.io.InputStream | The stream of the image. |
| imageRect | [Rectangle](../../com.aspose.pdf/rectangle) | The position of the image. |

### addImage(InputStream stream, Rectangle rectangle, CompositingParameters compositingParameters) {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-}
```
public void addImage(InputStream stream, Rectangle rectangle, CompositingParameters compositingParameters)
```


Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream of the image. |
| rectangle | [Rectangle](../../com.aspose.pdf/rectangle) | The position of the image. |
| compositingParameters | [CompositingParameters](../../com.aspose.pdf/compositingparameters) | The compositing parameters. |

### addImage(InputStream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, boolean saveImageProportions) {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-}
```
public void addImage(InputStream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, boolean saveImageProportions)
```


Adds searchable image onto the page and locates it in the middle of specified rectangle saving image's proportion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | java.io.InputStream | InputStream object |
| imageRect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle object |
| imageWidth | int | int value |
| imageHeight | int | int value |
| saveImageProportions | boolean | boolean value |

### addImage(String imagePath, Rectangle rectangle) {#addImage-java.lang.String-com.aspose.pdf.Rectangle-}
```
public void addImage(String imagePath, Rectangle rectangle)
```


Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imagePath | java.lang.String | The path to image. |
| rectangle | [Rectangle](../../com.aspose.pdf/rectangle) | The position of the image. |

### addImage(String hocr, InputStream imageStream, Rectangle imageRect) {#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-}
```
public void addImage(String hocr, InputStream imageStream, Rectangle imageRect)
```


Adds searchable image onto the page and locates it in the middle of specified rectangle saving image's proportion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hocr | java.lang.String | The hocr of the image. |
| imageStream | java.io.InputStream | The stream of the image. |
| imageRect | [Rectangle](../../com.aspose.pdf/rectangle) | The position of the image. |

### addStamp(Stamp stamp) {#addStamp-com.aspose.pdf.Stamp-}
```
public void addStamp(Stamp stamp)
```


Put stamp into page. Stamp can be page number, image or simple text, e.g. some logo.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stamp | [Stamp](../../com.aspose.pdf/stamp) | Stamp to add on the page. Each stamp has its coordinates and corresponding properties regarding to the kind of stamp, i.e. image or text value. |

### asByteArray(Resolution resolution) {#asByteArray-com.aspose.pdf.devices.Resolution-}
```
public byte[] asByteArray(Resolution resolution)
```


Converts current page as BMP bitmap and than returns array of bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | The resolution. |

**Returns:**
byte[] - Converted array of image bytes.
### asXml() {#asXml--}
```
public String asXml()
```


Converts current page as xml in utf8 encoding.

**Returns:**
java.lang.String - Converted xml string.
### calculateContentBBox() {#calculateContentBBox--}
```
public Rectangle calculateContentBBox()
```


Calculates bbox value - rectangle containing contents without visible margins.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Bbox value - rectangle containing contents without visible margins
### clearContents() {#clearContents--}
```
public void clearContents()
```


For internal usage only

### close() {#close--}
```
public void close()
```


Closes all resources used by this document.

### convertToPNGMemoryStream() {#convertToPNGMemoryStream--}
```
public byte[] convertToPNGMemoryStream()
```


Convert page to PNG for DSR, OMR, OCR image stream.

**Returns:**
byte[] - Image stream in byte[] array.
### deleteUnusedResources(System.Collections.Generic.Dictionary<Integer,Integer> usageTable) {#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.Integer-java.lang.Integer--}
```
public void deleteUnusedResources(System.Collections.Generic.Dictionary<Integer,Integer> usageTable)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| usageTable | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.Integer> |  |

### dispose() {#dispose--}
```
public void dispose()
```


Frees up memory

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
### fillUsedObjectsTable(System.Collections.Generic.Dictionary<Integer,Integer> usageTable, IPdfDictionary CommonResources) {#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.Integer-java.lang.Integer--com.aspose.pdf.engine.data.IPdfDictionary-}
```
public void fillUsedObjectsTable(System.Collections.Generic.Dictionary<Integer,Integer> usageTable, IPdfDictionary CommonResources)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| usageTable | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.Integer> |  |
| CommonResources | [IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) |  |

### findReferences(OperatorCollection contents, String name) {#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
```
public static List<Object> findReferences(OperatorCollection contents, String name)
```


Returns list of operators which uses resource with specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contents | [OperatorCollection](../../com.aspose.pdf/operatorcollection) | OperatorCollection value |
| name | java.lang.String | String value |

**Returns:**
java.util.List<java.lang.Object> - List of Object
### findReferences(String name) {#findReferences-java.lang.String-}
```
public List<Object> findReferences(String name)
```


Find references

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | String value |

**Returns:**
java.util.List<java.lang.Object> -  List  object
### flatten() {#flatten--}
```
public void flatten()
```


Removes all static fields located on the page and place their values instead.

### freeMemory() {#freeMemory--}
```
public void freeMemory()
```


Clears cached data

### getActions() {#getActions--}
```
public PageActionCollection getActions()
```


Gets collection of page properties.

**Returns:**
[PageActionCollection](../../com.aspose.pdf/pageactioncollection) - PageActionCollection value
### getAnnotations() {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```


Gets collection of page annotations.  Annotations 

**Returns:**
[AnnotationCollection](../../com.aspose.pdf/annotationcollection) - AnnotationCollection value
### getArtBox() {#getArtBox--}
```
public Rectangle getArtBox()
```


Gets art box of the page.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle value

--------------------

```
Example demonstrates how to get art box of the page:


 Document document = new Document("sample.pdf");
 Rectangle artBox = document.getPages().get(1).getArtBox();
```
### getArtifacts() {#getArtifacts--}
```
public ArtifactCollection getArtifacts()
```


Gets collection of artifacts on the page.

**Returns:**
[ArtifactCollection](../../com.aspose.pdf/artifactcollection) - ArtifactCollection value
### getBackground() {#getBackground--}
```
public Color getBackground()
```


Gets the background color of the page.

**Returns:**
[Color](../../java.awt/color) - Color value
### getBackgroundImage() {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```


Gets or sets background image for page (for generator only, not filled in when reading document).

**Returns:**
[Image](../../com.aspose.pdf/image) - Image instance
### getBleedBox() {#getBleedBox--}
```
public Rectangle getBleedBox()
```


Gets bleed box of the page.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle value

--------------------

```
Example demonstrates how to get bleed box of the page:


 Document document = new Document("sample.pdf");
 Rectangle bleedBox = document.getPages().get(1).getBleedBox();
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorType() {#getColorType--}
```
public int getColorType()
```


Gets color type of the pages based on information getting from operators SetColor, images and forms.

**Returns:**
int - ColorType element
### getContents() {#getContents--}
```
public OperatorCollection getContents()
```


Gets collection of operators in the content stream of the page.  OperatorCollection 

**Returns:**
[OperatorCollection](../../com.aspose.pdf/operatorcollection) - OperatorCollection object

--------------------

```
Example is demonstrates how to scan operators stream of page.


 Document document = new Document("sample.pdf");
 Operators contents = document.getPages().get_Item(1).getContents();
 for(Operator op : ```
(Iterable)
```contents)
 {
     System.out.println(op);
 }
```
### getContentsAppender() {#getContentsAppender--}
```
public ContentsAppender getContentsAppender()
```


Gets current contents appender.  ContentsAppender 

**Returns:**
[ContentsAppender](../../com.aspose.pdf/contentsappender) - ContentsAppender value
### getCropBox() {#getCropBox--}
```
public Rectangle getCropBox()
```


Gets crop box of the page.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle value

--------------------

```
Example demonstrates how to get crop box of the page:


 Document document = new Document("sample.pdf");
 Rectangle cropBox = document.getPages().get_Item(1).getCropBox();
```
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


Get document

**Returns:**
[IDocument](../../com.aspose.pdf/idocument) - IDocument object
### getDuration() {#getDuration--}
```
public double getDuration()
```


Gets page display duration. This is time in seconds that page shall be displayed during presentation. Returs -1 if duration is not defined.

--------------------

Example demonstrates how to get page duration

Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); int pageRect = page.getDuration();

**Returns:**
double - double value
### getEnginePage() {#getEnginePage--}
```
public IPage getEnginePage()
```


For Internal usage only

**Returns:**
[IPage](../../com.aspose.pdf.engine.commondata/ipage) - internal instance
### getFieldsInTabOrder() {#getFieldsInTabOrder--}
```
public List<Field> getFieldsInTabOrder()
```


Gets list of Field object in Tab order on this page.

**Returns:**
java.util.List<com.aspose.pdf.Field> - List of field objects
### getFooter() {#getFooter--}
```
public HeaderFooter getFooter()
```


Gets page Footer.

**Returns:**
[HeaderFooter](../../com.aspose.pdf/headerfooter) - The page Footer.
### getGroup() {#getGroup--}
```
public Group getGroup()
```


Gets a group attributes class specifying the attributes of the page's page group for use in the transparent imaging model.

**Returns:**
[Group](../../com.aspose.pdf/group) - Group value
### getHeader() {#getHeader--}
```
public HeaderFooter getHeader()
```


Gets page header.

**Returns:**
[HeaderFooter](../../com.aspose.pdf/headerfooter) - The page header.
### getLayers() {#getLayers--}
```
public List<Layer> getLayers()
```


Gets layers collection.

**Returns:**
java.util.List<com.aspose.pdf.Layer> - Value: The layers collection.
### getMediaBox() {#getMediaBox--}
```
public Rectangle getMediaBox()
```


Gets media box of the page.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle value

--------------------

```
Example demonstrates how to get media box of the page:


 Document document = new Document("sample.pdf");
 Rectangle mediaBox = document.getPages().get(1).getMediaBox();
```
### getNoteLineStyle() {#getNoteLineStyle--}
```
public GraphInfo getNoteLineStyle()
```


Gets the line style for notes.(for generator only, not filled in when reading document)

**Returns:**
[GraphInfo](../../com.aspose.pdf/graphinfo) - GraphInfo value
### getNotifications() {#getNotifications--}
```
public String getNotifications()
```


Returns notifications about inside operations with page content. (Only notifications about paragraph events in text adding scenarios are supported now.)

**Returns:**
java.lang.String - String representing notifications about inside operations with page content.
### getNumber() {#getNumber--}
```
public final int getNumber()
```


Get number of the page.

**Returns:**
int - int value
### getOnBeforePageGenerate() {#getOnBeforePageGenerate--}
```
public PdfEvent<Page.BeforePageGenerate> getOnBeforePageGenerate()
```


Event for customize header and footer.

**Returns:**
[PdfEvent](../../com.aspose.pdf/pdfevent) -  PdfEvent instance 
### getPageInfo() {#getPageInfo--}
```
public PageInfo getPageInfo()
```


Gets the page info.(for generator only, not filled in when reading document).

**Returns:**
[PageInfo](../../com.aspose.pdf/pageinfo) - The page info.
### getPageRect(boolean considerRotation) {#getPageRect-boolean-}
```
public Rectangle getPageRect(boolean considerRotation)
```


Returns rectangle of the page according to its CropBox (or MediaBox if CropBox null).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| considerRotation | boolean | If true then rotation of the page will be considered in rect calculation. |

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle of the page.
### getParagraphs() {#getParagraphs--}
```
public Paragraphs getParagraphs()
```


Gets the paragraphs.

**Returns:**
[Paragraphs](../../com.aspose.pdf/paragraphs) - The paragraphs.
### getRect() {#getRect--}
```
public Rectangle getRect()
```


Returns rectangle of the page according to its CropBox and MediaBox; For get: page crop box is returned if specified, otherwise page media box is returned. For set: page media box always set.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle value

--------------------

```
Example demonstrates how to get page rectangle:

 Document document = new Document("sample.pdf");
 Page page = document.getPages().get(1);
 Rectangle pageRect = page.getRect();
```
### getRect_Rename_Namesake() {#getRect-Rename-Namesake--}
```
public Rectangle getRect_Rename_Namesake()
```


Returns rectangle of the page according to its CropBox and MediaBox;

Internal

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle value

--------------------

```
Example demonstrates how to get page rectangle:

 Document document = new Document("sample.pdf");
 Page page = document.getPages().get(1);
 Rectangle pageRect = page.getRect();
```
### getResources() {#getResources--}
```
public Resources getResources()
```


Gets page resources. Resources object contains collections of images, forms and fonts.  Resources 

**Returns:**
[Resources](../../com.aspose.pdf/resources) - Resources value

--------------------

```
Example demonstrates scan through page images:


 Document document = new Document("sample.pdf");
 DocumentActions actions = document.getActions();
 Resources resources = document.getPages().get(1).getResources();
 for(XImage image : ```
(Ierable)resources
```.getImages())
 {
   System.out.println(image.getWidth() + ":" + image.getHeight());
 }
```
### getRotate() {#getRotate--}
```
public int getRotate()
```


Gets rotation of the page.

**Returns:**
int - Rotation element

--------------------

```
Example demonstrates how to determine page rotation.


 Document document = new Document("sample.pdf");
 System.out.println(document.getPages().get(1).getRotate());
```
### getRotationMatrix() {#getRotationMatrix--}
```
public Matrix getRotationMatrix()
```


Gets transfomation matrix for the page.

**Returns:**
[Matrix](../../com.aspose.pdf/matrix) - Matrix value
### getTabOrder() {#getTabOrder--}
```
public int getTabOrder()
```


Gets tab order of the page. Possible values: Row, Column. Default, Manual

**Returns:**
int - TabOrder value
### getTocInfo() {#getTocInfo--}
```
public TocInfo getTocInfo()
```


Gets table of contents info.

**Returns:**
[TocInfo](../../com.aspose.pdf/tocinfo) - The table of contents info - default null. If it set this page will contain table of contents.
### getTrimBox() {#getTrimBox--}
```
public Rectangle getTrimBox()
```


Gets trim box of the page.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle value

--------------------

```
Example demonstrates how to get trim box of the page:


 Document document = new Document("sample.pdf");
 Rectangle trimBox = document.getPages().get(1).getTrimBox();
```
### getUserUnit() {#getUserUnit--}
```
public final double getUserUnit()
```


Gets or sets UserUnit value. A positive number giving the size of default user space units, in multiples of 1 \\u0432\\u0403\\u201e 72 inch. Default value is 1. Please set zero or negative value in order to clear this entry in page.

**Returns:**
double - double value
### getWatermark() {#getWatermark--}
```
public Watermark getWatermark()
```


Gets the watermark of the page.

**Returns:**
[Watermark](../../com.aspose.pdf/watermark) - Watermark value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### intToRotation(int rotation) {#intToRotation-int-}
```
public static int intToRotation(int rotation)
```


Translates integer value into corresponding rotation enumeration member.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rotation | int | Integer value to convert |

**Returns:**
int - Rotation enumeration member
### isAddParagraphsAfterLast() {#isAddParagraphsAfterLast--}
```
public final boolean isAddParagraphsAfterLast()
```


Gets or sets the addition of paragraphs after the last paragraph of the page

Value: Value indicates whether paragraphs will be added after the last paragraph of the page. Paragraphs will be added after the last paragraph of the page if value is true.

**Returns:**
boolean - boolean value
### isBlank(double fillThresholdFactor) {#isBlank-double-}
```
public boolean isBlank(double fillThresholdFactor)
```


Gets the flag whether page is blank or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fillThresholdFactor | double | The fill threshold value that manages the sensitivity of detection. Should be equal or greater than 0.01. |

**Returns:**
boolean - boolean value True - if page is blank; otherwise, false.
### makeGrayscale() {#makeGrayscale--}
```
public final void makeGrayscale()
```


Converts the page to grayscale.

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeObjectReferences(OperatorCollection contents, String name) {#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
```
public static void removeObjectReferences(OperatorCollection contents, String name)
```


Remove object references

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contents | [OperatorCollection](../../com.aspose.pdf/operatorcollection) | OperatorCollection object |
| name | java.lang.String | value |

### removeObjectReferences(String name) {#removeObjectReferences-java.lang.String-}
```
public void removeObjectReferences(String name)
```


Remove references to XObject from page contents (i.e. all Do operators which use name of object).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | String value |

### rotationToInt(int rotation) {#rotationToInt-int-}
```
public static int rotationToInt(int rotation)
```


Translates rotation enumeration member into integer value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rotation | int | Rotation enumeratioom member. |

**Returns:**
int - Corresponding integer value
### sendTo(PageDevice device, OutputStream output) {#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-}
```
public void sendTo(PageDevice device, OutputStream output)
```


Sends page to process with given page device.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| device | [PageDevice](../../com.aspose.pdf.devices/pagedevice) | The device to process page. |
| output | java.io.OutputStream | Result stream which is used with device to save its output. |

### sendTo(PageDevice device, String outputFileName) {#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-}
```
public void sendTo(PageDevice device, String outputFileName)
```


Sends page to process with given page device.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| device | [PageDevice](../../com.aspose.pdf.devices/pagedevice) | The device to process page. |
| outputFileName | java.lang.String | File which is used with device to save its output. |

### setAddParagraphsAfterLast(boolean value) {#setAddParagraphsAfterLast-boolean-}
```
public final void setAddParagraphsAfterLast(boolean value)
```


Gets or sets the addition of paragraphs after the last paragraph of the page

Value: Value indicates whether paragraphs will be added after the last paragraph of the page. Paragraphs will be added after the last paragraph of the page if value is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setArtBox(Rectangle value) {#setArtBox-com.aspose.pdf.Rectangle-}
```
public void setArtBox(Rectangle value)
```


Sets art box of the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle value |

### setBackground(Color value) {#setBackground-com.aspose.pdf.Color-}
```
public void setBackground(Color value)
```


Sets the background color of the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Color object |

### setBackground(Color value) {#setBackground-java.awt.Color-}
```
public void setBackground(Color value)
```


Sets the background color of the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color | Color object |

### setBackgroundImage(Image value) {#setBackgroundImage-com.aspose.pdf.Image-}
```
public final void setBackgroundImage(Image value)
```


Gets or sets background image for page (for generator only, not filled in when reading document).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Image](../../com.aspose.pdf/image) | Image instance |

### setBleedBox(Rectangle value) {#setBleedBox-com.aspose.pdf.Rectangle-}
```
public void setBleedBox(Rectangle value)
```


Sets bleed box of the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle value |

### setCropBox(Rectangle value) {#setCropBox-com.aspose.pdf.Rectangle-}
```
public void setCropBox(Rectangle value)
```


Sets crop box of the page.

--------------------

```
Example demonstrates how to get crop box of the page:


 Document document = new Document("sample.pdf");
 document.getPages().get_Item(1).setCropBox(new Rectangle(0d,0d,100d,100d));
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle object |

### setDuration(double value) {#setDuration-double-}
```
public void setDuration(double value)
```


Sets page display duration. This is time in seconds that page shall be displayed during presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | page display duration. |

### setEnginePage(IPage enginePage) {#setEnginePage-com.aspose.pdf.engine.commondata.IPage-}
```
public void setEnginePage(IPage enginePage)
```


For Internal usage only

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| enginePage | [IPage](../../com.aspose.pdf.engine.commondata/ipage) | internal instance |

### setFooter(HeaderFooter value) {#setFooter-com.aspose.pdf.HeaderFooter-}
```
public void setFooter(HeaderFooter value)
```


Sets page Footer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HeaderFooter](../../com.aspose.pdf/headerfooter) | The page Footer. |

### setGroup(Group value) {#setGroup-com.aspose.pdf.Group-}
```
public void setGroup(Group value)
```


Sets a group attributes class specifying the attributes of the page's page group for use in the transparent imaging model.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Group](../../com.aspose.pdf/group) | Group value |

### setHeader(HeaderFooter value) {#setHeader-com.aspose.pdf.HeaderFooter-}
```
public void setHeader(HeaderFooter value)
```


Sets page header.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HeaderFooter](../../com.aspose.pdf/headerfooter) | The page header. |

### setLayers(ArrayList<Layer> value) {#setLayers-java.util.ArrayList-com.aspose.pdf.Layer--}
```
public void setLayers(ArrayList<Layer> value)
```


Sets layers collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.ArrayList<com.aspose.pdf.Layer> | : The layers collection. |

### setLayersInternal(System.Collections.Generic.List<Layer> value) {#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.Layer--}
```
public void setLayersInternal(System.Collections.Generic.List<Layer> value)
```


Sets layers collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Layer> | : The layers collection. |

### setMediaBox(Rectangle value) {#setMediaBox-com.aspose.pdf.Rectangle-}
```
public void setMediaBox(Rectangle value)
```


Sets media box of the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle |

### setNoteLineStyle(GraphInfo value) {#setNoteLineStyle-com.aspose.pdf.GraphInfo-}
```
public void setNoteLineStyle(GraphInfo value)
```


Sets the line style for notes.(for generator only, not filled in when reading document)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [GraphInfo](../../com.aspose.pdf/graphinfo) | : GraphInfo value |

### setPageInfo(PageInfo value) {#setPageInfo-com.aspose.pdf.PageInfo-}
```
public void setPageInfo(PageInfo value)
```


Sets the page info.(for generator only, not filled in when reading document).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PageInfo](../../com.aspose.pdf/pageinfo) | The page info. |

### setPageSize(double width, double height) {#setPageSize-double-double-}
```
public void setPageSize(double width, double height)
```


Sets page size for page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | double | Page width. |
| height | double | Page size. |

### setParagraphs(Paragraphs value) {#setParagraphs-com.aspose.pdf.Paragraphs-}
```
public void setParagraphs(Paragraphs value)
```


Sets the paragraphs.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Paragraphs](../../com.aspose.pdf/paragraphs) | Paragraphs value |

### setRect(Rectangle value) {#setRect-com.aspose.pdf.Rectangle-}
```
public void setRect(Rectangle value)
```


Gets or sets rectangle of the page. For get: page crop box is returned if specified, otherwise page media box is returned. For set: page media box always set. is returned. Please note that this property don't consider page rotation. To get page rectangle considering rotation please use ActualRect.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle object |

### setRotate(int value) {#setRotate-int-}
```
public void setRotate(int value)
```


Sets rotation of the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | Rotation element |

### setTabOrder(int value) {#setTabOrder-int-}
```
public void setTabOrder(int value)
```


Sets tab order of the page. Possible values: Row, Column. Default, Manual

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | TabOrder object |

### setTocInfo(TocInfo value) {#setTocInfo-com.aspose.pdf.TocInfo-}
```
public void setTocInfo(TocInfo value)
```


Sets table of contents info.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TocInfo](../../com.aspose.pdf/tocinfo) | The table of contents info - default null. If it set this page will contain table of contents. |

### setTransition(IPdfDictionary transition) {#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-}
```
public void setTransition(IPdfDictionary transition)
```


Set transition

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| transition | [IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) | IPdfDictionary object |

### setTrimBox(Rectangle value) {#setTrimBox-com.aspose.pdf.Rectangle-}
```
public void setTrimBox(Rectangle value)
```


Sets trim box of the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle value |

### setUserUnit(double value) {#setUserUnit-double-}
```
public final void setUserUnit(double value)
```


Gets or sets UserUnit value. A positive number giving the size of default user space units, in multiples of 1 \\u0432\\u0403\\u201e 72 inch. Default value is 1. Please set zero or negative value in order to clear this entry in page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setWatermark(Watermark value) {#setWatermark-com.aspose.pdf.Watermark-}
```
public void setWatermark(Watermark value)
```


Sets the watermark of the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Watermark](../../com.aspose.pdf/watermark) | Watermark object |

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

