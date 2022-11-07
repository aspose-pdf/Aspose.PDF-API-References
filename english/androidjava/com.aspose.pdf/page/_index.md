---
title: Page
second_title: Aspose.PDF for Java API Reference
description: Class representing page of PDF document.
type: docs
weight: 208
url: /java/com.aspose.pdf/page/
---
**Inheritance:**
java.lang.Object
```
public final class Page
```

Class representing page of PDF document.
## Constructors

| Constructor | Description |
| --- | --- |
| [Page(IPage page)](#Page-com.aspose.pdf.engine.commondata.IPage-) |  |
## Fields

| Field | Description |
| --- | --- |
| [OnBeforePageGenerate](#OnBeforePageGenerate) |  |
| [EnginePage](#EnginePage) |  |
## Methods

| Method | Description |
| --- | --- |
| [getTocInfo()](#getTocInfo--) | The table of contents info. |
| [setTocInfo(TocInfo value)](#setTocInfo-com.aspose.pdf.TocInfo-) |  |
| [getHeader()](#getHeader--) | The page header. |
| [setHeader(HeaderFooter value)](#setHeader-com.aspose.pdf.HeaderFooter-) |  |
| [getFooter()](#getFooter--) | The page header. |
| [setFooter(HeaderFooter value)](#setFooter-com.aspose.pdf.HeaderFooter-) |  |
| [getParagraphs()](#getParagraphs--) | Gets the paragraphs. |
| [setParagraphs(Paragraphs value)](#setParagraphs-com.aspose.pdf.Paragraphs-) |  |
| [getPageInfo()](#getPageInfo--) | Gets the page info. |
| [setPageInfo(PageInfo value)](#setPageInfo-com.aspose.pdf.PageInfo-) | Sets the page info. |
| [getDocument()](#getDocument--) |  |
| [getRect()](#getRect--) | Gets or sets rectangle of the page. |
| [getRect_Rename_Namesake()](#getRect-Rename-Namesake--) | Gets or sets rectangle of the page. |
| [setRect(Rectangle value)](#setRect-com.aspose.pdf.Rectangle-) |  |
| [getColorType()](#getColorType--) | Sets color type of the pages based on information getting from operators SetColor and images. |
| [getPageRect(boolean considerRotation)](#getPageRect-boolean-) | Returns rectangle of the page. |
| [getTabOrder()](#getTabOrder--) | Gets or sets tab order of the page. |
| [setTabOrder(int value)](#setTabOrder-int-) |  |
| [getDuration()](#getDuration--) | Gets of set page display duration. |
| [setDuration(double value)](#setDuration-double-) |  |
| [getContents()](#getContents--) | Gets collection of operators in the content stream of the page. |
| [getGroup()](#getGroup--) | Gets a group attributes class specifying the attributes of the page\\ufffds page group for use in the transparent imaging model. |
| [setGroup(Group value)](#setGroup-com.aspose.pdf.Group-) | Sets a group attributes class specifying the attributes of the page\\ufffds page group for use in the transparent imaging model. |
| [getAnnotations()](#getAnnotations--) | Gets collection of page annotations. |
| [getResources()](#getResources--) | Gets page resources. |
| [getRotate()](#getRotate--) | Gets rotation of the page. |
| [setRotate(int value)](#setRotate-int-) | Sets rotation of the page. |
| [getTrimBox()](#getTrimBox--) | Gets or sets trim box of the page. |
| [setTrimBox(Rectangle value)](#setTrimBox-com.aspose.pdf.Rectangle-) | Sets trim box of the page. |
| [getArtBox()](#getArtBox--) | Gets art box of the page. |
| [setArtBox(Rectangle value)](#setArtBox-com.aspose.pdf.Rectangle-) | Sets art box of the page. |
| [getBleedBox()](#getBleedBox--) | Gets bleed box of the page. |
| [setBleedBox(Rectangle value)](#setBleedBox-com.aspose.pdf.Rectangle-) | Sets bleed box of the page. |
| [getCropBox()](#getCropBox--) | Gets crop box of the page. |
| [setCropBox(Rectangle value)](#setCropBox-com.aspose.pdf.Rectangle-) | Sets crop box of the page. |
| [getMediaBox()](#getMediaBox--) | Gets media box of the page. |
| [setMediaBox(Rectangle value)](#setMediaBox-com.aspose.pdf.Rectangle-) | Sets media box of the page. |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts  AnnotationSelector  visitor object that provides functionality to work with annotations. |
| [rotationToInt(int rotation)](#rotationToInt-int-) | Translates rotation enumeration member into integer value. |
| [intToRotation(int rotation)](#intToRotation-int-) | Translates integer value into corresponding rotation enumeration member. |
| [addStamp(Stamp stamp)](#addStamp-com.aspose.pdf.Stamp-) | Put stamp into page. |
| [addImageInternal(System.IO.Stream imageStream, Rectangle imageRect)](#addImageInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.Rectangle-) | Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [addImage(InputStream imageStream, Rectangle imageRect)](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-) | Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [addImageInternal(String hocr, System.IO.Stream imageStream, Rectangle imageRect)](#addImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-com.aspose.pdf.Rectangle-) | Adds searchable image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [addImage(String hocr, InputStream imageStream, Rectangle imageRect)](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-) | Adds searchable image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [addImage(InputStream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, boolean saveImageProportions)](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-) |  |
| [addImage(String imagePath, Rectangle rectangle)](#addImage-java.lang.String-com.aspose.pdf.Rectangle-) | Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [addImage(System.IO.Stream stream, Rectangle rectangle, CompositingParameters compositingParameters)](#addImage-com.aspose.ms.System.IO.Stream-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-) | Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [flatten()](#flatten--) | Removes all fields located on the page and place their values instead. |
| [accept(TextFragmentAbsorber visitor)](#accept-com.aspose.pdf.TextFragmentAbsorber-) | Accepts  TextFragmentAbsorber  visitor object that provides functionality to work with text objects. |
| [accept(ImagePlacementAbsorber visitor)](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | Accepts  ImagePlacementAbsorber  visitor object that provides functionality to work with image placement objects. |
| [accept(TextAbsorber visitor)](#accept-com.aspose.pdf.TextAbsorber-) | Accepts  TextAbsorber  visitor object that provides functionality to work with text objects. |
| [setPageSize(double width, double height)](#setPageSize-double-double-) | Sets page size for page. |
| [setTransition(IPdfDictionary transition)](#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-) |  |
| [getNumber()](#getNumber--) | Get number of the page. |
| [getRotationMatrix()](#getRotationMatrix--) | Gets transfomation matrix for the page. |
| [getContentsAppender()](#getContentsAppender--) | Gets current contents appender. |
| [getBackground()](#getBackground--) | Gets the background color of the page. |
| [setBackground(Color value)](#setBackground-com.aspose.pdf.java.awt.Color-) | Sets the background color of the page. |
| [getWatermark()](#getWatermark--) | Gets the watermark of the page. |
| [setWatermark(Watermark value)](#setWatermark-com.aspose.pdf.Watermark-) | Sets the watermark of the page. |
| [removeObjectReferences(String name)](#removeObjectReferences-java.lang.String-) | Remove references to XObject from page contents (i.e. all Do operators which use name of object). |
| [removeObjectReferences(OperatorCollection contents, String name)](#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) |  |
| [findReferences(String name)](#findReferences-java.lang.String-) |  |
| [findReferences(OperatorCollection contents, String name)](#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | Returns list of operators which uses resource with specified name. |
| [clearContents()](#clearContents--) |  |
| [getArtifacts()](#getArtifacts--) | Gets collection of artifacts on the page. |
| [getActions()](#getActions--) | Gets collection of page properties. |
| [makeGrayscale()](#makeGrayscale--) | Converts images on page as grayscaled. |
| [freeMemory()](#freeMemory--) | Clears cached data |
### Page(IPage page) {#Page-com.aspose.pdf.engine.commondata.IPage-}
```
public Page(IPage page)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [IPage](../../com.aspose.pdf.engine.commondata/ipage) |  |

### OnBeforePageGenerate {#OnBeforePageGenerate}
```
public final Event<Page.BeforePageGenerate> OnBeforePageGenerate
```


### EnginePage {#EnginePage}
```
public IPage EnginePage
```


### getTocInfo() {#getTocInfo--}
```
public TocInfo getTocInfo()
```


The table of contents info.

**Returns:**
[TocInfo](../../com.aspose.pdf/tocinfo) - The table of contents info - default null. If it set this page will contain table of contents.
### setTocInfo(TocInfo value) {#setTocInfo-com.aspose.pdf.TocInfo-}
```
public void setTocInfo(TocInfo value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TocInfo](../../com.aspose.pdf/tocinfo) |  |

### getHeader() {#getHeader--}
```
public HeaderFooter getHeader()
```


The page header.

**Returns:**
[HeaderFooter](../../com.aspose.pdf/headerfooter) - The page header.
### setHeader(HeaderFooter value) {#setHeader-com.aspose.pdf.HeaderFooter-}
```
public void setHeader(HeaderFooter value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HeaderFooter](../../com.aspose.pdf/headerfooter) |  |

### getFooter() {#getFooter--}
```
public HeaderFooter getFooter()
```


The page header.

**Returns:**
[HeaderFooter](../../com.aspose.pdf/headerfooter) - The page header.
### setFooter(HeaderFooter value) {#setFooter-com.aspose.pdf.HeaderFooter-}
```
public void setFooter(HeaderFooter value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HeaderFooter](../../com.aspose.pdf/headerfooter) |  |

### getParagraphs() {#getParagraphs--}
```
public Paragraphs getParagraphs()
```


Gets the paragraphs.

**Returns:**
[Paragraphs](../../com.aspose.pdf/paragraphs) - The paragraphs.
### setParagraphs(Paragraphs value) {#setParagraphs-com.aspose.pdf.Paragraphs-}
```
public void setParagraphs(Paragraphs value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Paragraphs](../../com.aspose.pdf/paragraphs) |  |

### getPageInfo() {#getPageInfo--}
```
public PageInfo getPageInfo()
```


Gets the page info.(for generator only)

**Returns:**
[PageInfo](../../com.aspose.pdf/pageinfo) - The page info.
### setPageInfo(PageInfo value) {#setPageInfo-com.aspose.pdf.PageInfo-}
```
public void setPageInfo(PageInfo value)
```


Sets the page info.(for generator only)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PageInfo](../../com.aspose.pdf/pageinfo) | The page info. |

### getDocument() {#getDocument--}
```
public IDocument getDocument()
```




**Returns:**
[IDocument](../../com.aspose.pdf/idocument)
### getRect() {#getRect--}
```
public Rectangle getRect()
```


Gets or sets rectangle of the page. Page crop box is returned if specified, otherwise page media box is returned.

--------------------

> ```
> Example demonstrates how to get page rectangle:
>  
>  Document document = new Document("sample.pdf");
>  Page page = document.getPages().get(1);
>  Rectangle pageRect = page.getRect();
> ```

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle)
### getRect_Rename_Namesake() {#getRect-Rename-Namesake--}
```
public Rectangle getRect_Rename_Namesake()
```


Gets or sets rectangle of the page. Page crop box is returned if specified, otherwise page media box is returned. Please note that this property don't consider page rotation. To get page rectangle considering rotation please use ActualRect.

--------------------

> ```
> Example demonstrates how to get page rectangle:
>  
>  Document document = new Document("sample.pdf");
>  Page page = document.Pages[1];
>  Rectangle pageRect = page.Rect;
> ```

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle)
### setRect(Rectangle value) {#setRect-com.aspose.pdf.Rectangle-}
```
public void setRect(Rectangle value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


Sets color type of the pages based on information getting from operators SetColor and images.

**Returns:**
int
### getPageRect(boolean considerRotation) {#getPageRect-boolean-}
```
public Rectangle getPageRect(boolean considerRotation)
```


Returns rectangle of the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| considerRotation | boolean | If true then rotation of the page will be considered in rect calculation. |

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle of the page.
### getTabOrder() {#getTabOrder--}
```
public int getTabOrder()
```


Gets or sets tab order of the page. Possible values: Row, Column. Default, Manual

**Returns:**
int
### setTabOrder(int value) {#setTabOrder-int-}
```
public void setTabOrder(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDuration() {#getDuration--}
```
public double getDuration()
```


Gets of set page display duration. This is time in seconds that page shall be displayed during presentation. Returs -1 if duration is not defined.

--------------------

> ```
> Example demonstrates how to get page duration
>  
>  Document document = new Document("sample.pdf");
>  Page page = document.getPages().get(1);
>  int pageRect = page.Duration;
> ```

**Returns:**
double
### setDuration(double value) {#setDuration-double-}
```
public void setDuration(double value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getContents() {#getContents--}
```
public OperatorCollection getContents()
```


Gets collection of operators in the content stream of the page.  OperatorCollection 

--------------------

> ```
> Example is demonstrates how to scan operators stream of page.
>  
>  Document document = new Document("sample.pdf");
>  Operators contents = document.Pages[1].Contents;
>  for(Operator op : contents)
>  {
>      Ssytem.out.println(op);
>  }
> ```

**Returns:**
[OperatorCollection](../../com.aspose.pdf/operatorcollection)
### getGroup() {#getGroup--}
```
public Group getGroup()
```


Gets a group attributes class specifying the attributes of the page\\ufffds page group for use in the transparent imaging model.

**Returns:**
[Group](../../com.aspose.pdf/group)
### setGroup(Group value) {#setGroup-com.aspose.pdf.Group-}
```
public void setGroup(Group value)
```


Sets a group attributes class specifying the attributes of the page\\ufffds page group for use in the transparent imaging model.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Group](../../com.aspose.pdf/group) |  |

### getAnnotations() {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```


Gets collection of page annotations.  Annotations 

**Returns:**
[AnnotationCollection](../../com.aspose.pdf/annotationcollection)
### getResources() {#getResources--}
```
public Resources getResources()
```


Gets page resources. Resources object contains collections of images, forms and fonts.  Resources 

--------------------

> ```
> Example demonstrates scan through page images:
>  
>  Document document = new Document("sample.pdf");
>  DocumentActions actions = document.Actions;
>  Resources resources = document.getPages().get(1).getResources();
>  for(XImage image : resources.getImages())
>  {
>    System.out.println(image.Width + ":" + image.Height);
>  }
> ```

**Returns:**
[Resources](../../com.aspose.pdf/resources)
### getRotate() {#getRotate--}
```
public int getRotate()
```


Gets rotation of the page.

--------------------

> ```
> Example demonstrates how to determine page rotation.
>  
>  Document document = new Document("sample.pdf");
>  System.out.println(document.getPages().get(1).hryRotate());
> ```

**Returns:**
int
### setRotate(int value) {#setRotate-int-}
```
public void setRotate(int value)
```


Sets rotation of the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTrimBox() {#getTrimBox--}
```
public Rectangle getTrimBox()
```


Gets or sets trim box of the page.

--------------------

> ```
> Example demonstrates how to get trim box of the page:
>  
>  Document document = new Document("sample.pdf");
>  Rectangle trimBox = document.getPages().get(1).getTrimBox();
> ```

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle)
### setTrimBox(Rectangle value) {#setTrimBox-com.aspose.pdf.Rectangle-}
```
public void setTrimBox(Rectangle value)
```


Sets trim box of the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) |  |

### getArtBox() {#getArtBox--}
```
public Rectangle getArtBox()
```


Gets art box of the page.

--------------------

> ```
> Example demonstrates how to get art box of the page:
>  
>  Document document = new Document("sample.pdf");
>  Rectangle artBox = document.getPages().get(1).getArtBox();
> ```

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle)
### setArtBox(Rectangle value) {#setArtBox-com.aspose.pdf.Rectangle-}
```
public void setArtBox(Rectangle value)
```


Sets art box of the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) |  |

### getBleedBox() {#getBleedBox--}
```
public Rectangle getBleedBox()
```


Gets bleed box of the page.

--------------------

> ```
> Example demonstrates how to get bleed box of the page:
>  
>  Document document = new Document("sample.pdf");
>  Rectangle bleedBox = document.getPages().get(1).getBleedBox();
> ```

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle)
### setBleedBox(Rectangle value) {#setBleedBox-com.aspose.pdf.Rectangle-}
```
public void setBleedBox(Rectangle value)
```


Sets bleed box of the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) |  |

### getCropBox() {#getCropBox--}
```
public Rectangle getCropBox()
```


Gets crop box of the page.

--------------------

> ```
> Example demonstrates how to get crop box of the page:
>  
>  Document document = new Document("sample.pdf");
>  Rectangle cropBox = document.getPages().get(1).getCropBox();
> ```

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle)
### setCropBox(Rectangle value) {#setCropBox-com.aspose.pdf.Rectangle-}
```
public void setCropBox(Rectangle value)
```


Sets crop box of the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) |  |

### getMediaBox() {#getMediaBox--}
```
public Rectangle getMediaBox()
```


Gets media box of the page.

--------------------

> ```
> Example demonstrates how to get media box of the page:
>  
>  Document document = new Document("sample.pdf");
>  Rectangle mediaBox = document.getPages().get(1).getMediaBox();
> ```

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle)
### setMediaBox(Rectangle value) {#setMediaBox-com.aspose.pdf.Rectangle-}
```
public void setMediaBox(Rectangle value)
```


Sets media box of the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) |  |

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts  AnnotationSelector  visitor object that provides functionality to work with annotations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) |  |

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
### addStamp(Stamp stamp) {#addStamp-com.aspose.pdf.Stamp-}
```
public void addStamp(Stamp stamp)
```


Put stamp into page. Stamp can be page number, image or simple text, e.g. some logo.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stamp | [Stamp](../../com.aspose.pdf/stamp) | Stamp to add on the page. Each stamp has its coordinates and corresponding properties regarding to the kind of stamp, i.e. image or text value. |

### addImageInternal(System.IO.Stream imageStream, Rectangle imageRect) {#addImageInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.Rectangle-}
```
public void addImageInternal(System.IO.Stream imageStream, Rectangle imageRect)
```


Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | com.aspose.ms.System.IO.Stream | The stream of the image. |
| imageRect | [Rectangle](../../com.aspose.pdf/rectangle) | The position of the image. |

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

### addImageInternal(String hocr, System.IO.Stream imageStream, Rectangle imageRect) {#addImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-com.aspose.pdf.Rectangle-}
```
public void addImageInternal(String hocr, System.IO.Stream imageStream, Rectangle imageRect)
```


Adds searchable image onto the page and locates it in the middle of specified rectangle saving image's proportion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hocr | java.lang.String | The hocr of the image. |
| imageStream | com.aspose.ms.System.IO.Stream | The stream of the image. |
| imageRect | [Rectangle](../../com.aspose.pdf/rectangle) | The position of the image. |

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

### addImage(InputStream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, boolean saveImageProportions) {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-}
```
public void addImage(InputStream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, boolean saveImageProportions)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | java.io.InputStream |  |
| imageRect | [Rectangle](../../com.aspose.pdf/rectangle) |  |
| imageWidth | int |  |
| imageHeight | int |  |
| saveImageProportions | boolean |  |

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

### addImage(System.IO.Stream stream, Rectangle rectangle, CompositingParameters compositingParameters) {#addImage-com.aspose.ms.System.IO.Stream-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-}
```
public void addImage(System.IO.Stream stream, Rectangle rectangle, CompositingParameters compositingParameters)
```


Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The stream of the image. |
| rectangle | [Rectangle](../../com.aspose.pdf/rectangle) | The position of the image. |
| compositingParameters | [CompositingParameters](../../com.aspose.pdf/compositingparameters) | The compositing parameters. |

### flatten() {#flatten--}
```
public void flatten()
```


Removes all fields located on the page and place their values instead.

### accept(TextFragmentAbsorber visitor) {#accept-com.aspose.pdf.TextFragmentAbsorber-}
```
public void accept(TextFragmentAbsorber visitor)
```


Accepts  TextFragmentAbsorber  visitor object that provides functionality to work with text objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber) |  |

### accept(ImagePlacementAbsorber visitor) {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
```
public void accept(ImagePlacementAbsorber visitor)
```


Accepts  ImagePlacementAbsorber  visitor object that provides functionality to work with image placement objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [ImagePlacementAbsorber](../../com.aspose.pdf/imageplacementabsorber) |  |

### accept(TextAbsorber visitor) {#accept-com.aspose.pdf.TextAbsorber-}
```
public void accept(TextAbsorber visitor)
```


Accepts  TextAbsorber  visitor object that provides functionality to work with text objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [TextAbsorber](../../com.aspose.pdf/textabsorber) |  |

### setPageSize(double width, double height) {#setPageSize-double-double-}
```
public void setPageSize(double width, double height)
```


Sets page size for page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | double | Page width |
| height | double | Page size |

### setTransition(IPdfDictionary transition) {#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-}
```
public void setTransition(IPdfDictionary transition)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| transition | [IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) |  |

### getNumber() {#getNumber--}
```
public int getNumber()
```


Get number of the page.

**Returns:**
int
### getRotationMatrix() {#getRotationMatrix--}
```
public Matrix getRotationMatrix()
```


Gets transfomation matrix for the page.

**Returns:**
[Matrix](../../com.aspose.pdf/matrix) - Matrix value
### getContentsAppender() {#getContentsAppender--}
```
public ContentsAppender getContentsAppender()
```


Gets current contents appender.  ContentsAppender 

**Returns:**
[ContentsAppender](../../com.aspose.pdf/contentsappender)
### getBackground() {#getBackground--}
```
public Color getBackground()
```


Gets the background color of the page.

**Returns:**
[Color](../../com.aspose.pdf.java.awt/color)
### setBackground(Color value) {#setBackground-com.aspose.pdf.java.awt.Color-}
```
public void setBackground(Color value)
```


Sets the background color of the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf.java.awt/color) |  |

### getWatermark() {#getWatermark--}
```
public Watermark getWatermark()
```


Gets the watermark of the page.

**Returns:**
[Watermark](../../com.aspose.pdf/watermark)
### setWatermark(Watermark value) {#setWatermark-com.aspose.pdf.Watermark-}
```
public void setWatermark(Watermark value)
```


Sets the watermark of the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Watermark](../../com.aspose.pdf/watermark) |  |

### removeObjectReferences(String name) {#removeObjectReferences-java.lang.String-}
```
public void removeObjectReferences(String name)
```


Remove references to XObject from page contents (i.e. all Do operators which use name of object).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

### removeObjectReferences(OperatorCollection contents, String name) {#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
```
public static void removeObjectReferences(OperatorCollection contents, String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contents | [OperatorCollection](../../com.aspose.pdf/operatorcollection) |  |
| name | java.lang.String |  |

### findReferences(String name) {#findReferences-java.lang.String-}
```
public System.Collections.IList findReferences(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
com.aspose.ms.System.Collections.IList
### findReferences(OperatorCollection contents, String name) {#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
```
public static System.Collections.IList findReferences(OperatorCollection contents, String name)
```


Returns list of operators which uses resource with specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contents | [OperatorCollection](../../com.aspose.pdf/operatorcollection) |  |
| name | java.lang.String |  |

**Returns:**
com.aspose.ms.System.Collections.IList - 
### clearContents() {#clearContents--}
```
public void clearContents()
```




### getArtifacts() {#getArtifacts--}
```
public ArtifactCollection getArtifacts()
```


Gets collection of artifacts on the page.

**Returns:**
[ArtifactCollection](../../com.aspose.pdf/artifactcollection)
### getActions() {#getActions--}
```
public PageActionCollection getActions()
```


Gets collection of page properties.

**Returns:**
[PageActionCollection](../../com.aspose.pdf/pageactioncollection)
### makeGrayscale() {#makeGrayscale--}
```
public void makeGrayscale()
```


Converts images on page as grayscaled.

### freeMemory() {#freeMemory--}
```
public void freeMemory()
```


Clears cached data

