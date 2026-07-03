---
title: Page
second_title: Aspose.PDF for Java API Reference
description: Class representing page of PDF document.
type: docs
weight: 3310
url: /java/com.aspose.pdf/page/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Page

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer, Closeable, AutoCloseable

```
public final class Page extends Object implements com.aspose.ms.System.IDisposable, Closeable , com.aspose.pdf.engine.IOperatorContainer
```

Class representing page of PDF document.

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts {@code AnnotationSelector} visitor object that provides functionality to work with annotations. |
| [accept](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | Accepts {@code ImagePlacementAbsorber} visitor object that provides functionality to work with image placement objects. |
| [accept](#accept-com.aspose.pdf.TextAbsorber-) | Accepts {@code TextAbsorber} visitor object that provides functionality to work with text objects. |
| [accept](#accept-com.aspose.pdf.TextFragmentAbsorber-) | Accepts {@code TextFragmentAbsorber} visitor object that provides functionality to work with text objects. |
| [addGraphics](#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-) | Adds graphics to the page. Works faster than adding elements one by one with GraphicElement#addOnPage(Page) method. |
| [addGraphics](#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-com.aspose.pdf.Rectangle-) | Adds graphics to the page. Works faster than adding elements one by one with GraphicElement#addOnPage(Page) method. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-) | Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-) | Adds searchable image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-com.aspose.pdf.Rectangle-) | Adds searchable image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-) | Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-) | Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-boolean-) | Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [addImage](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-) | Adds searchable image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [addImage](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-) | Adds searchable image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [addImage](#addImage-java.lang.String-com.aspose.pdf.Rectangle-) | Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [addStamp](#addStamp-com.aspose.pdf.Stamp-) | Put stamp into page. Stamp can be page number, image or simple text, e.g. some logo. |
| [asByteArray](#asByteArray-com.aspose.pdf.devices.Resolution-) | Converts current page as BMP bitmap and than returns array of bytes. |
| [asXml](#asXml--) | Converts current page as xml in utf8 encoding. |
| [calculateContentBBox](#calculateContentBBox--) | Calculates bbox value - rectangle containing contents without visible margins. |
| [clearContents](#clearContents--) | For internal usage only |
| [close](#close--) | Closes all resources used by this document. |
| [convertToPNGMemoryStream](#convertToPNGMemoryStream--) | Convert page to PNG for DSR, OMR, OCR image stream. |
| [deleteGraphics](#deleteGraphics-com.aspose.pdf.vector.GraphicElementCollection-) | Deletes graphics from the page. Works faster than deleting elements one by one with {@link GraphicElement#remove} method. |
| [deleteUnusedResources](#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-) |  |
| [dispose](#dispose--) | Frees up memory This method is obsolete, use close() instead. |
| [fillUsedObjectsTable](#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.engine.data.IPdfDictionary-) |  |
| [findReferences](#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | Returns list of operators which uses resource with specified name. |
| [findReferences](#findReferences-java.lang.String-) | <p> Find references </p> |
| [flatten](#flatten--) | Removes all static fields located on the page and place their values instead. |
| [freeMemory](#freeMemory--) | Clears cached data |
| [getActions](#getActions--) | Gets collection of page properties. |
| [getAnnotations](#getAnnotations--) | Gets collection of page annotations. {@code Annotations} |
| [getArtBox](#getArtBox--) | <p> Gets art box of the page. </p> |
| [getArtifacts](#getArtifacts--) | Gets collection of artifacts on the page. |
| [getBackground](#getBackground--) | Gets the background color of the page. |
| [getBackgroundImage](#getBackgroundImage--) | Gets or sets background image for page (for generator only, not filled in when reading document). |
| [getBleedBox](#getBleedBox--) | <p> Gets bleed box of the page. </p> |
| [getColorType](#getColorType--) | Gets color type of the pages based on information getting from operators SetColor, images and forms. |
| [getContents](#getContents--) | <p> Gets collection of operators in the content stream of the page. {@code OperatorCollection} </p> |
| [getContentsAppender](#getContentsAppender--) | Gets current contents appender. {@code ContentsAppender} |
| [getCropBox](#getCropBox--) | <p> Gets crop box of the page. </p> |
| [getDocument](#getDocument--) | Get document |
| [getDuration](#getDuration--) | <p> Gets page display duration. This is time in seconds that page shall be displayed during presentation. Returns -1 if duration is not defined. </p> <hr> Example demonstrates how to get page duration <p> Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); int pageRect = page.getDuration(); </p> |
| [getEnginePage](#getEnginePage--) | For Internal usage only |
| [getFieldsInTabOrder](#getFieldsInTabOrder--) | Gets list of Field object in Tab order on this page. |
| [getFooter](#getFooter--) | Gets page Footer. |
| [getGroup](#getGroup--) | Gets a group attributes class specifying the attributes of the page's page group for use in the transparent imaging model. |
| [getHeader](#getHeader--) | Gets page header. |
| [getLayers](#getLayers--) | Gets layers collection. |
| [getMediaBox](#getMediaBox--) | <p> Gets media box of the page. </p> |
| [getNoteLineStyle](#getNoteLineStyle--) | Gets the line style for notes.(for generator only, not filled in when reading document) |
| [getNotifications](#getNotifications--) | Returns notifications about inside operations with page content. (Only notifications about paragraph events in text adding scenarios are supported now.) |
| [getNumber](#getNumber--) | Get number of the page. |
| [getOnBeforePageGenerate](#getOnBeforePageGenerate--) | Event for customize header and footer. |
| [getPageInfo](#getPageInfo--) | Gets the page info.(for generator only, not filled in when reading document). |
| [getPageRect](#getPageRect-boolean-) | Returns rectangle of the page according to its CropBox (or MediaBox if CropBox null). |
| [getParagraphs](#getParagraphs--) | Gets the paragraphs. |
| [getRect_Rename_Namesake](#getRect_Rename_Namesake--) | <p> Returns rectangle of the page according to its CropBox and MediaBox; </p> Internal |
| [getRect](#getRect--) | <p> Returns rectangle of the page according to its CropBox and MediaBox; For get: page crop box is returned if specified, otherwise page media box is returned. For set: page media box always set. </p> |
| [getResources](#getResources--) | Retrieves the resources associated with the page. |
| [getResourcesField](#getResourcesField--) | <p> Gets page resources. Resources object contains collections of images, forms and fonts. {@code Resources} </p> |
| [getRotate](#getRotate--) | <p> Gets rotation of the page. </p> |
| [getRotationMatrix](#getRotationMatrix--) | Gets transformation matrix for the page. |
| [getTabOrder](#getTabOrder--) | Gets tab order of the page. Possible values: Row, Column. Default, Manual |
| [getTocInfo](#getTocInfo--) | Gets table of contents info. |
| [getTrimBox](#getTrimBox--) | <p> Gets trim box of the page. </p> |
| [getUserUnit](#getUserUnit--) | Gets or sets UserUnit value. A positive number giving the size of default user space units, in multiples of 1 / 72 inch. Default value is 1. Please set zero or negative value in order to clear this entry in page. |
| [getWatermark](#getWatermark--) | Gets the watermark of the page. |
| [hasVectorGraphics](#hasVectorGraphics--) | Detect of the presence of vector graphics, if it is present on the page. |
| [intToRotation](#intToRotation-int-) | Translates integer value into corresponding rotation enumeration member. |
| [isAddParagraphsAfterLast](#isAddParagraphsAfterLast--) | Gets or sets the addition of paragraphs after the last paragraph of the page Value: Value indicates whether paragraphs will be added after the last paragraph of the page. Paragraphs will be added after the last paragraph of the page if value is true. |
| [isBlank](#isBlank-double-) | Gets the flag whether page is blank or not. |
| [isBlank](#isBlank-double-boolean-) | Gets the flag whether page is blank or not. |
| [makeGrayscale](#makeGrayscale--) | Converts the page to grayscale. |
| [mergeLayers](#mergeLayers-java.lang.String-) | Merges all layers on the page into a single layer with the specified new layer name. |
| [mergeLayers](#mergeLayers-java.lang.String-java.lang.String-) | Merges all layers on the page into a single layer with the specified new layer name and optional content group Id. |
| [removeObjectReferences](#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | Remove object references |
| [removeObjectReferences](#removeObjectReferences-java.lang.String-) | Remove references to XObject from page contents (i.e. all Do operators which use name of object). |
| [resize](#resize-com.aspose.pdf.PageSize-) | Resizes the page. |
| [rotationToInt](#rotationToInt-com.aspose.pdf.Rotation-) | Translates rotation enumeration member into integer value. |
| [sendTo](#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-) | Sends page to process with given page device. |
| [sendTo](#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-) | Sends page to process with given page device. |
| [setAddParagraphsAfterLast](#setAddParagraphsAfterLast-boolean-) | Gets or sets the addition of paragraphs after the last paragraph of the page Value: Value indicates whether paragraphs will be added after the last paragraph of the page. Paragraphs will be added after the last paragraph of the page if value is true. |
| [setArtBox](#setArtBox-com.aspose.pdf.Rectangle-) | Sets art box of the page. |
| [setBackground](#setBackground-java.awt.Color-) | Sets the background color of the page. |
| [setBackground](#setBackground-com.aspose.pdf.Color-) | Sets the background color of the page. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | Gets or sets background image for page (for generator only, not filled in when reading document). |
| [setBleedBox](#setBleedBox-com.aspose.pdf.Rectangle-) | Sets bleed box of the page. |
| [setCropBox](#setCropBox-com.aspose.pdf.Rectangle-) | <p> Sets crop box of the page. </p> <hr> <pre> Example demonstrates how to get crop box of the page: Document document = new Document("sample.pdf"); document.getPages().get_Item(1).setCropBox(new Rectangle(0d,0d,100d,100d)); </pre> |
| [setDuration](#setDuration-double-) | Sets page display duration. This is time in seconds that page shall be displayed during presentation. Returns -1 if duration is not defined. |
| [setEnginePage](#setEnginePage-com.aspose.pdf.engine.commondata.IPage-) | For Internal usage only |
| [setFooter](#setFooter-com.aspose.pdf.HeaderFooter-) | Sets page Footer. |
| [setGroup](#setGroup-com.aspose.pdf.Group-) | Sets a group attributes class specifying the attributes of the page's page group for use in the transparent imaging model. |
| [setHeader](#setHeader-com.aspose.pdf.HeaderFooter-) | Sets page header. |
| [setLayers](#setLayers-java.util.ArrayList-) | Sets layers collection. |
| [setLayersInternal](#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-) | Sets layers collection. |
| [setMediaBox](#setMediaBox-com.aspose.pdf.Rectangle-) | Sets media box of the page. |
| [setNoteLineStyle](#setNoteLineStyle-com.aspose.pdf.GraphInfo-) | Sets the line style for notes.(for generator only, not filled in when reading document) |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Sets the page info.(for generator only, not filled in when reading document). |
| [setPageSize](#setPageSize-double-double-) | Sets page size for page. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | Sets the paragraphs. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | Gets or sets rectangle of the page. For get: page crop box is returned if specified, otherwise page media box is returned. For set: page media box always set. is returned. Please note that this property don't consider page rotation. To get page rectangle considering rotation please use ActualRect. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | Sets rotation of the page. |
| [setTabOrder](#setTabOrder-int-) | Sets tab order of the page. Possible values: Row, Column. Default, Manual |
| [setTocInfo](#setTocInfo-com.aspose.pdf.TocInfo-) | Sets table of contents info. |
| [setTransition](#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-) | Set transition |
| [setTrimBox](#setTrimBox-com.aspose.pdf.Rectangle-) | Sets trim box of the page. |
| [setUserUnit](#setUserUnit-double-) | Gets or sets UserUnit value. A positive number giving the size of default user space units, in multiples of 1 / 72 inch. Default value is 1. Please set zero or negative value in order to clear this entry in page. |
| [setWatermark](#setWatermark-com.aspose.pdf.Watermark-) | Sets the watermark of the page. |
| [trySaveVectorGraphics](#trySaveVectorGraphics-java.lang.String-) | Tries to save vector graphics if they are present on the page. The save format is SVG. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepts {@code AnnotationSelector} visitor object that provides functionality to work with annotations.

### accept {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
Accepts {@code ImagePlacementAbsorber} visitor object that provides functionality to work with image placement objects.

### accept {#accept-com.aspose.pdf.TextAbsorber-}
Accepts {@code TextAbsorber} visitor object that provides functionality to work with text objects.

### accept {#accept-com.aspose.pdf.TextFragmentAbsorber-}
Accepts {@code TextFragmentAbsorber} visitor object that provides functionality to work with text objects.

### addGraphics {#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-}
Adds graphics to the page. Works faster than adding elements one by one with GraphicElement#addOnPage(Page) method.

### addGraphics {#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-com.aspose.pdf.Rectangle-}
Adds graphics to the page. Works faster than adding elements one by one with GraphicElement#addOnPage(Page) method.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-}
Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-}
Adds searchable image onto the page and locates it in the middle of specified rectangle saving image's proportion.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-com.aspose.pdf.Rectangle-}
Adds searchable image onto the page and locates it in the middle of specified rectangle saving image's proportion.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-}
Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-}
Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-boolean-}
Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion.

### addImage {#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-}
Adds searchable image onto the page and locates it in the middle of specified rectangle saving image's proportion.

### addImage {#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-}
Adds searchable image onto the page and locates it in the middle of specified rectangle saving image's proportion.

### addImage {#addImage-java.lang.String-com.aspose.pdf.Rectangle-}
Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion.

### addStamp {#addStamp-com.aspose.pdf.Stamp-}
Put stamp into page. Stamp can be page number, image or simple text, e.g. some logo.

### asByteArray {#asByteArray-com.aspose.pdf.devices.Resolution-}
Converts current page as BMP bitmap and than returns array of bytes.

### asXml {#asXml--}
```
public String asXml()
```

Converts current page as xml in utf8 encoding.

**Returns:**
Converted xml string.

### calculateContentBBox {#calculateContentBBox--}
```
public Rectangle calculateContentBBox()
```

Calculates bbox value - rectangle containing contents without visible margins.

**Returns:**
Bbox value - rectangle containing contents without visible margins

### clearContents {#clearContents--}
```
public void clearContents()
```

For internal usage only

### close {#close--}
```
public void close()
```

Closes all resources used by this document.

### convertToPNGMemoryStream {#convertToPNGMemoryStream--}
```
public byte[] convertToPNGMemoryStream()
```

Convert page to PNG for DSR, OMR, OCR image stream.

**Returns:**
Image stream in byte[] array.

### deleteGraphics {#deleteGraphics-com.aspose.pdf.vector.GraphicElementCollection-}
Deletes graphics from the page. Works faster than deleting elements one by one with {@link GraphicElement#remove} method.

### deleteUnusedResources {#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-}


### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Frees up memory This method is obsolete, use close() instead.

### fillUsedObjectsTable {#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.engine.data.IPdfDictionary-}


### findReferences {#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
Returns list of operators which uses resource with specified name.

### findReferences {#findReferences-java.lang.String-}
<p> Find references </p>

### flatten {#flatten--}
```
public void flatten()
```

Removes all static fields located on the page and place their values instead.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Clears cached data

### getActions {#getActions--}
```
public PageActionCollection getActions()
```

Gets collection of page properties.

**Returns:**
PageActionCollection value

### getAnnotations {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```

Gets collection of page annotations. {@code Annotations}

**Returns:**
AnnotationCollection value

### getArtBox {#getArtBox--}
```
public Rectangle getArtBox()
```

<p> Gets art box of the page. </p>

**Returns:**
Rectangle value <hr> <pre> Example demonstrates how to get art box of the page: Document document = new Document("sample.pdf"); Rectangle artBox = document.getPages().get(1).getArtBox(); </pre>

### getArtifacts {#getArtifacts--}
```
public ArtifactCollection getArtifacts()
```

Gets collection of artifacts on the page.

**Returns:**
ArtifactCollection value

### getBackground {#getBackground--}
```
public Color getBackground()
```

Gets the background color of the page.

**Returns:**
Color value

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

Gets or sets background image for page (for generator only, not filled in when reading document).

**Returns:**
Image instance

### getBleedBox {#getBleedBox--}
```
public Rectangle getBleedBox()
```

<p> Gets bleed box of the page. </p>

**Returns:**
Rectangle value <hr> <pre> Example demonstrates how to get bleed box of the page: Document document = new Document("sample.pdf"); Rectangle bleedBox = document.getPages().get(1).getBleedBox(); </pre>

### getColorType {#getColorType--}
```
public ColorType getColorType()
```

Gets color type of the pages based on information getting from operators SetColor, images and forms.

**Returns:**
ColorType element @see ColorType

### getContents {#getContents--}
```
public OperatorCollection getContents()
```

<p> Gets collection of operators in the content stream of the page. {@code OperatorCollection} </p>

**Returns:**
OperatorCollection object <hr> <pre> Example is demonstrates how to scan operators stream of page. Document document = new Document("sample.pdf"); Operators contents = document.getPages().get_Item(1).getContents(); for(Operator op : {@code (Iterable<Operator>)}contents) { System.out.println(op); } </pre>

### getContentsAppender {#getContentsAppender--}
```
public ContentsAppender getContentsAppender()
```

Gets current contents appender. {@code ContentsAppender}

**Returns:**
ContentsAppender value

### getCropBox {#getCropBox--}
```
public Rectangle getCropBox()
```

<p> Gets crop box of the page. </p>

**Returns:**
Rectangle value <hr> <pre> Example demonstrates how to get crop box of the page: Document document = new Document("sample.pdf"); Rectangle cropBox = document.getPages().get_Item(1).getCropBox(); </pre>

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Get document

**Returns:**
IDocument object

### getDuration {#getDuration--}
```
public double getDuration()
```

<p> Gets page display duration. This is time in seconds that page shall be displayed during presentation. Returns -1 if duration is not defined. </p> <hr> Example demonstrates how to get page duration <p> Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); int pageRect = page.getDuration(); </p>

**Returns:**
double value

### getEnginePage {#getEnginePage--}
```
public com.aspose.pdf.engine.commondata.IPage getEnginePage()
```

For Internal usage only

**Returns:**
internal instance

### getFieldsInTabOrder {#getFieldsInTabOrder--}
```
public List < Field > getFieldsInTabOrder()
```

Gets list of Field object in Tab order on this page.

**Returns:**
List of field objects

### getFooter {#getFooter--}
```
public HeaderFooter getFooter()
```

Gets page Footer.

**Returns:**
The page Footer.

### getGroup {#getGroup--}
```
public Group getGroup()
```

Gets a group attributes class specifying the attributes of the page's page group for use in the transparent imaging model.

**Returns:**
Group value

### getHeader {#getHeader--}
```
public HeaderFooter getHeader()
```

Gets page header.

**Returns:**
The page header.

### getLayers {#getLayers--}
```
public List < Layer > getLayers()
```

Gets layers collection.

**Returns:**
Value: The layers' collection.

### getMediaBox {#getMediaBox--}
```
public Rectangle getMediaBox()
```

<p> Gets media box of the page. </p>

**Returns:**
Rectangle value <hr> <pre> Example demonstrates how to get media box of the page: Document document = new Document("sample.pdf"); Rectangle mediaBox = document.getPages().get(1).getMediaBox(); </pre>

### getNoteLineStyle {#getNoteLineStyle--}
```
public GraphInfo getNoteLineStyle()
```

Gets the line style for notes.(for generator only, not filled in when reading document)

**Returns:**
GraphInfo value

### getNotifications {#getNotifications--}
```
public String getNotifications()
```

Returns notifications about inside operations with page content. (Only notifications about paragraph events in text adding scenarios are supported now.)

**Returns:**
String representing notifications about inside operations with page content.

### getNumber {#getNumber--}
```
public final int getNumber()
```

Get number of the page.

**Returns:**
int value

### getOnBeforePageGenerate {#getOnBeforePageGenerate--}
```
public PdfEvent < Page.BeforePageGenerate > getOnBeforePageGenerate()
```

Event for customize header and footer.

**Returns:**
{@code PdfEvent<BeforePageGenerate> instance}

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Gets the page info.(for generator only, not filled in when reading document).

**Returns:**
The page info.

### getPageRect {#getPageRect-boolean-}
```
public Rectangle getPageRect(boolean considerRotation)
```

Returns rectangle of the page according to its CropBox (or MediaBox if CropBox null).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| considerRotation |  | If true then rotation of the page will be considered in rect calculation. |

**Returns:**
Rectangle of the page.

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

Gets the paragraphs.

**Returns:**
The paragraphs.

### getRect_Rename_Namesake {#getRect_Rename_Namesake--}
```
public Rectangle getRect_Rename_Namesake()
```

<p> Returns rectangle of the page according to its CropBox and MediaBox; </p> Internal

**Returns:**
Rectangle value <hr> <pre> Example demonstrates how to get page rectangle: Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); Rectangle pageRect = page.getRect(); </pre>

### getRect {#getRect--}
```
public Rectangle getRect()
```

<p> Returns rectangle of the page according to its CropBox and MediaBox; For get: page crop box is returned if specified, otherwise page media box is returned. For set: page media box always set. </p>

**Returns:**
Rectangle value <hr> <pre> Example demonstrates how to get page rectangle: Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); Rectangle pageRect = page.getRect(); </pre>

### getResources {#getResources--}
```
public final Resources getResources()
```

Retrieves the resources associated with the page.

**Returns:**
A {@code Resources}({@link #getResources()}) object representing the resources of the page.

### getResourcesField {#getResourcesField--}
```
public Resources getResourcesField()
```

<p> Gets page resources. Resources object contains collections of images, forms and fonts. {@code Resources} </p>

**Returns:**
Resources value <hr> <pre> Example demonstrates scan through page images: Document document = new Document("sample.pdf"); DocumentActions actions = document.getActions(); Resources resources = document.getPages().get(1).getResources(); for(XImage image : {@code (Iterable<XImage>)resources}.getImages()) { System.out.println(image.getWidth() + ":" + image.getHeight()); } </pre>

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

<p> Gets rotation of the page. </p>

**Returns:**
Rotation element <hr> <pre> Example demonstrates how to determine page rotation. Document document = new Document("sample.pdf"); System.out.println(document.getPages().get(1).getRotate()); </pre> @see Rotation

### getRotationMatrix {#getRotationMatrix--}
```
public Matrix getRotationMatrix()
```

Gets transformation matrix for the page.

**Returns:**
Matrix value

### getTabOrder {#getTabOrder--}
```
public int getTabOrder()
```

Gets tab order of the page. Possible values: Row, Column. Default, Manual

**Returns:**
TabOrder value @see TabOrder

### getTocInfo {#getTocInfo--}
```
public TocInfo getTocInfo()
```

Gets table of contents info.

**Returns:**
The table of contents info - default null. If it set this page will contain table of contents.

### getTrimBox {#getTrimBox--}
```
public Rectangle getTrimBox()
```

<p> Gets trim box of the page. </p>

**Returns:**
Rectangle value <hr> <pre> Example demonstrates how to get trim box of the page: Document document = new Document("sample.pdf"); Rectangle trimBox = document.getPages().get(1).getTrimBox(); </pre>

### getUserUnit {#getUserUnit--}
```
public final double getUserUnit()
```

Gets or sets UserUnit value. A positive number giving the size of default user space units, in multiples of 1 / 72 inch. Default value is 1. Please set zero or negative value in order to clear this entry in page.

**Returns:**
double value

### getWatermark {#getWatermark--}
```
public Watermark getWatermark()
```

Gets the watermark of the page.

**Returns:**
Watermark value

### hasVectorGraphics {#hasVectorGraphics--}
```
public final boolean hasVectorGraphics()
```

Detect of the presence of vector graphics, if it is present on the page.

**Returns:**
True if the page contains path construction operators; otherwise, False.

### intToRotation {#intToRotation-int-}
```
public static Rotation intToRotation(int rotation)
```

Translates integer value into corresponding rotation enumeration member.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rotation |  | Integer value to convert |

**Returns:**
Rotation enumeration member @see Rotation

### isAddParagraphsAfterLast {#isAddParagraphsAfterLast--}
```
public final boolean isAddParagraphsAfterLast()
```

Gets or sets the addition of paragraphs after the last paragraph of the page Value: Value indicates whether paragraphs will be added after the last paragraph of the page. Paragraphs will be added after the last paragraph of the page if value is true.

**Returns:**
boolean value

### isBlank {#isBlank-double-}
```
public boolean isBlank(double fillThresholdFactor)
```

Gets the flag whether page is blank or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fillThresholdFactor |  | The fill threshold value that manages the sensitivity of detection. Should be in range [0..1). To determine whether a page is empty or not, the ratio of the filled space to the total space of the page is calculated. This ratio is compared with the fillThresholdFactor parameter and if it is less, the page is considered empty. |

**Returns:**
boolean value True - if page is blank; otherwise, false.

### isBlank {#isBlank-double-boolean-}
```
public boolean isBlank(double fillThresholdFactor, boolean parseWhiteContent)
```

Gets the flag whether page is blank or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fillThresholdFactor |  | The fill threshold value that manages the sensitivity of detection. Should be equal or greater than 0.01. |
| parseWhiteContent |  | True for complete page scanning with white contend analyzing, False (default) - fast algorithm, where white graphics is counted as not blank page. |

**Returns:**
boolean value True - if page is blank; otherwise, false.

### makeGrayscale {#makeGrayscale--}
```
public final void makeGrayscale()
```

Converts the page to grayscale.

### mergeLayers {#mergeLayers-java.lang.String-}
Merges all layers on the page into a single layer with the specified new layer name.

### mergeLayers {#mergeLayers-java.lang.String-java.lang.String-}
Merges all layers on the page into a single layer with the specified new layer name and optional content group Id.

### removeObjectReferences {#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
Remove object references

### removeObjectReferences {#removeObjectReferences-java.lang.String-}
Remove references to XObject from page contents (i.e. all Do operators which use name of object).

### resize {#resize-com.aspose.pdf.PageSize-}
Resizes the page.

### rotationToInt {#rotationToInt-com.aspose.pdf.Rotation-}
Translates rotation enumeration member into integer value.

### sendTo {#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-}
Sends page to process with given page device.

### sendTo {#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-}
Sends page to process with given page device.

### setAddParagraphsAfterLast {#setAddParagraphsAfterLast-boolean-}
```
public final void setAddParagraphsAfterLast(boolean value)
```

Gets or sets the addition of paragraphs after the last paragraph of the page Value: Value indicates whether paragraphs will be added after the last paragraph of the page. Paragraphs will be added after the last paragraph of the page if value is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setArtBox {#setArtBox-com.aspose.pdf.Rectangle-}
Sets art box of the page.

### setBackground {#setBackground-java.awt.Color-}
Sets the background color of the page.

### setBackground {#setBackground-com.aspose.pdf.Color-}
Sets the background color of the page.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
Gets or sets background image for page (for generator only, not filled in when reading document).

### setBleedBox {#setBleedBox-com.aspose.pdf.Rectangle-}
Sets bleed box of the page.

### setCropBox {#setCropBox-com.aspose.pdf.Rectangle-}
<p> Sets crop box of the page. </p> <hr> <pre> Example demonstrates how to get crop box of the page: Document document = new Document("sample.pdf"); document.getPages().get_Item(1).setCropBox(new Rectangle(0d,0d,100d,100d)); </pre>

### setDuration {#setDuration-double-}
```
public void setDuration(double value)
```

Sets page display duration. This is time in seconds that page shall be displayed during presentation. Returns -1 if duration is not defined.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | page display duration. |

### setEnginePage {#setEnginePage-com.aspose.pdf.engine.commondata.IPage-}
For Internal usage only

### setFooter {#setFooter-com.aspose.pdf.HeaderFooter-}
Sets page Footer.

### setGroup {#setGroup-com.aspose.pdf.Group-}
Sets a group attributes class specifying the attributes of the page's page group for use in the transparent imaging model.

### setHeader {#setHeader-com.aspose.pdf.HeaderFooter-}
Sets page header.

### setLayers {#setLayers-java.util.ArrayList-}
Sets layers collection.

### setLayersInternal {#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-}
Sets layers collection.

### setMediaBox {#setMediaBox-com.aspose.pdf.Rectangle-}
Sets media box of the page.

### setNoteLineStyle {#setNoteLineStyle-com.aspose.pdf.GraphInfo-}
Sets the line style for notes.(for generator only, not filled in when reading document)

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Sets the page info.(for generator only, not filled in when reading document).

### setPageSize {#setPageSize-double-double-}
```
public void setPageSize(double width, double height)
```

Sets page size for page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width |  | Page width. |
| height |  | Page size. |

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
Sets the paragraphs.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
Gets or sets rectangle of the page. For get: page crop box is returned if specified, otherwise page media box is returned. For set: page media box always set. is returned. Please note that this property don't consider page rotation. To get page rectangle considering rotation please use ActualRect.

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
Sets rotation of the page.

### setTabOrder {#setTabOrder-int-}
```
public void setTabOrder(int value)
```

Sets tab order of the page. Possible values: Row, Column. Default, Manual

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | TabOrder object @see TabOrder |

### setTocInfo {#setTocInfo-com.aspose.pdf.TocInfo-}
Sets table of contents info.

### setTransition {#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-}
Set transition

### setTrimBox {#setTrimBox-com.aspose.pdf.Rectangle-}
Sets trim box of the page.

### setUserUnit {#setUserUnit-double-}
```
public final void setUserUnit(double value)
```

Gets or sets UserUnit value. A positive number giving the size of default user space units, in multiples of 1 / 72 inch. Default value is 1. Please set zero or negative value in order to clear this entry in page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setWatermark {#setWatermark-com.aspose.pdf.Watermark-}
Sets the watermark of the page.

### trySaveVectorGraphics {#trySaveVectorGraphics-java.lang.String-}
Tries to save vector graphics if they are present on the page. The save format is SVG.
