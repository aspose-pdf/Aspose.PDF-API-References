---
title: PasswordBoxField
second_title: Aspose.PDF for Java API Reference
description: Class descibes text field for entering password.
type: docs
weight: 271
url: /java/com.aspose.pdf/passwordboxfield/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.WidgetAnnotation](../../com.aspose.pdf/widgetannotation), [com.aspose.pdf.Field](../../com.aspose.pdf/field), [com.aspose.pdf.TextBoxField](../../com.aspose.pdf/textboxfield)
```
public final class PasswordBoxField extends TextBoxField
```

Class descibes text field for entering password.
## Fields

| Field | Description |
| --- | --- |
| [_FileSelect](#-FileSelect) | \_FileSelect |
| [_Password](#-Password) | \_Password |
## Methods

| Method | Description |
| --- | --- |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor. |
| [add(WidgetAnnotation item)](#add-com.aspose.pdf.WidgetAnnotation-) |  |
| [addBarcode(String code)](#addBarcode-java.lang.String-) | Adds barcode 128 into the field. |
| [addImage(BufferedImage image)](#addImage-java.awt.image.BufferedImage-) | Adds image into the field resources an draws it. |
| [changeAfterResize(Matrix transform)](#changeAfterResize-com.aspose.pdf.Matrix-) | Update parameters and appearance, according to the matrix transform. |
| [clear()](#clear--) |  |
| [contains(WidgetAnnotation item)](#contains-com.aspose.pdf.WidgetAnnotation-) |  |
| [copyTo(Field[] array, int index)](#copyTo-com.aspose.pdf.Field---int-) | Copies subfields of this field into array starting from specified index. |
| [copyTo(WidgetAnnotation[] array, int arrayIndex)](#copyTo-com.aspose.pdf.WidgetAnnotation---int-) |  |
| [createAnnotation(IPdfObject annotEngineObj, Page page)](#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-) | For internal usage only |
| [deepClone()](#deepClone--) | Clones this instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flatten()](#flatten--) | Removes this field and place its value directly on the page. |
| [getActiveState()](#getActiveState--) | Gets current annotation appearance state. |
| [getAlignment()](#getAlignment--) | Annotation alignment. |
| [getAlternateName()](#getAlternateName--) | Gets alternate name of the field (An alternate field name that shall be used in place of the actual field name wherever the field shall be identified in the user interface). |
| [getAnnotationActions()](#getAnnotationActions--) | Gets the annotation actions. |
| [getAnnotationIndex()](#getAnnotationIndex--) | Gets index of this anotation on the page. |
| [getAnnotationType()](#getAnnotationType--) | Gets type of annotation. |
| [getAppearance()](#getAppearance--) | Gets appearance dictionary of the annotation. |
| [getBorder()](#getBorder--) | Gets annotation border characteristics. |
| [getCharacteristics()](#getCharacteristics--) | Gets annotation characteristics. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Gets annotation color. |
| [getContents()](#getContents--) | Gets annotation text. |
| [getDefaultAppearance()](#getDefaultAppearance--) | Gets default appearance of the field. |
| [getEngineDict()](#getEngineDict--) | Internal only |
| [getEngineObj()](#getEngineObj--) | For Internal usage only |
| [getExportable()](#getExportable--) | Gets exportable flag of the field. |
| [getFlags()](#getFlags--) | Get flags of the annotation. |
| [getForceCombs()](#getForceCombs--) | Gets flag which indicates is field divided into spaced positions. |
| [getFullName()](#getFullName--) | Gets full qualified name of the annotation. |
| [getHeight()](#getHeight--) | Gets height of the annotation. |
| [getHighlighting()](#getHighlighting--) | Annotation highlighting mode. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Gets a horizontal alignment of paragraph |
| [getHorizontalAlignment_Annotation_New()](#getHorizontalAlignment-Annotation-New--) | Gets or sets text alignment for annotation. |
| [getHyperlink()](#getHyperlink--) | Gets the fragment hyperlink(for pdf generator). |
| [getMappingName()](#getMappingName--) | Gets mapping name of the field that shall be used when exporting interactive form field data from the document. |
| [getMargin()](#getMargin--) | Gets a outer margin for paragraph (for pdf generation) |
| [getMaxFontSize()](#getMaxFontSize--) | Maximal font size which can be used for field contents. -1 to don't check size. |
| [getMaxLen()](#getMaxLen--) | Gets maximum length of text in the field. |
| [getMinFontSize()](#getMinFontSize--) | Minimal font size which can be used for field contents. -1 to don't check size. |
| [getModified()](#getModified--) | Gets date and time when annotation was recently modified. |
| [getModifiedInternal()](#getModifiedInternal--) | Gets date and time when annotation was recently modified. |
| [getMultiline()](#getMultiline--) | Gets multiline flag of the field. |
| [getName()](#getName--) | Gets annotation name on the page. |
| [getNormalAppearance()](#getNormalAppearance--) | Gets normal appearance. |
| [getOnActivated()](#getOnActivated--) | Get an action which shall be performed when the annotation is activated. |
| [getPage()](#getPage--) | Gets the page object with which this annotation is associated. |
| [getPageIndex()](#getPageIndex--) | Gets index of page which contains this field. |
| [getPageIndex(Annotation annotation)](#getPageIndex-com.aspose.pdf.Annotation-) | Gets index of page which contains annotation. |
| [getParent()](#getParent--) | Gets annotation parent. |
| [getPartialName()](#getPartialName--) | Gets partial name of the field. |
| [getPdfActions()](#getPdfActions--) | Gets list of annotation actions. |
| [getReadOnly()](#getReadOnly--) | Gets read only status of the field. |
| [getRect()](#getRect--) | Gets the field rectangle. |
| [getRectangle(boolean considerRotation)](#getRectangle-boolean-) | Returns rectangle of annotation taking into consideration page rotation. |
| [getRequired()](#getRequired--) | Gets required status of the field. |
| [getScrollable()](#getScrollable--) | Gets scrollable flag of field. |
| [getSpellCheck()](#getSpellCheck--) | Gets spellcheck flag for field. |
| [getStates()](#getStates--) | Gets appearance dictionary of annotation. |
| [getSyncRoot()](#getSyncRoot--) | Synchronization object. |
| [getTabOrder()](#getTabOrder--) | Gets or sets tab order of the field. |
| [getTextHorizontalAlignment()](#getTextHorizontalAlignment--) | Gets text alignment for annotation. |
| [getTextVerticalAlignment()](#getTextVerticalAlignment--) | Gets or sets text vertical alignment for annotation. |
| [getValue()](#getValue--) | Gets value of the field. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Gets a vertical alignment of paragraph |
| [getWidth()](#getWidth--) | Gets width of the annotation. |
| [getZIndex()](#getZIndex--) | Gets an int value that indicates the Z-order of the graph. |
| [get_Item(int index)](#get-Item-int-) | Gets subfield contained in this field by index. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Gets subfield contained in this field by name of the subfield. |
| [hashCode()](#hashCode--) |  |
| [initialize(IDocument doc)](#initialize-com.aspose.pdf.IDocument-) | Instance initialization |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | Gets or sets a bool value that indicates whether this paragraph will be at next column. |
| [isFitIntoRectangle()](#isFitIntoRectangle--) | If true then font size will reduced to fit text to specified rectangle. |
| [isGroup()](#isGroup--) | Gets boolean value which indicates is this field non-terminal field i.e. group of fields. |
| [isInLineParagraph()](#isInLineParagraph--) | Gets a paragraph is inline. |
| [isInNewPage()](#isInNewPage--) | Gets a bool value that force this paragraph generates at new page. |
| [isKeptWithNext()](#isKeptWithNext--) | Gets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. |
| [isReadOnly()](#isReadOnly--) |  |
| [isSharedField()](#isSharedField--) | Property for Generator support. |
| [isSynchronized()](#isSynchronized--) | Returns true if dictionary is synchronized. |
| [isUpdateAppearanceOnConvert()](#isUpdateAppearanceOnConvert--) | If true, annotation appearance will be updated before converting PF document into image. |
| [isUseFontSubset()](#isUseFontSubset--) | If this property set to true, fonts will be added to document as subsets. |
| [iterator()](#iterator--) | Returns enumerator of contained fields. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [recalculate()](#recalculate--) | Recaculates all calculated fields on the form. |
| [remove(WidgetAnnotation item)](#remove-com.aspose.pdf.WidgetAnnotation-) |  |
| [setActiveState(String value)](#setActiveState-java.lang.String-) | Sets current annotation appearance state. |
| [setAlignment(int value)](#setAlignment-int-) | Annotation alignment. |
| [setAlternateName(String value)](#setAlternateName-java.lang.String-) | Sets alternate name of the field (An alternate field name that shall be used in place of the actual field name wherever the field shall be identified in the user interface). |
| [setAnnotationIndex(int value)](#setAnnotationIndex-int-) | Sets index of this anotation on the page. |
| [setBorder(Border value)](#setBorder-com.aspose.pdf.Border-) | Sets annotation border characteristics. |
| [setColor(Color value)](#setColor-com.aspose.pdf.Color-) | Sets annotation color. |
| [setContents(String value)](#setContents-java.lang.String-) | Sets annotation text. |
| [setDefaultAppearance(DefaultAppearance value)](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | Sets default appearance of the field. |
| [setExportable(boolean value)](#setExportable-boolean-) | Sets read only status of the field. |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | Gets or sets a bool value that indicates whether this paragraph will be at next column. |
| [setFitIntoRectangle(boolean value)](#setFitIntoRectangle-boolean-) | If true then font size will reduced to fit text to specified rectangle. |
| [setFlags(int value)](#setFlags-int-) | Set flags of the annotation. |
| [setForceCombs(boolean value)](#setForceCombs-boolean-) | Sets flag which indicates is field divided into spaced positions. |
| [setHeight(double value)](#setHeight-double-) | Sets height of the annotation. |
| [setHighlighting(int value)](#setHighlighting-int-) | Annotation highlighting mode. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Sets a horizontal alignment of paragraph |
| [setHorizontalAlignment_Annotation_New(int value)](#setHorizontalAlignment-Annotation-New-int-) | Gets or sets text alignment for annotation. |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | Sets hyperlink(for pdf generator). |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | Sets a paragraph is inline. |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | Sets a boolean value that force this paragraph generates at new page. |
| [setJustification(boolean value)](#setJustification-boolean-) | Sets justification |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | Sets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. |
| [setMappingName(String value)](#setMappingName-java.lang.String-) | Sets mapping name of the field that shall be used when exporting interactive form field data from the document. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Sets a outer margin for paragraph (for pdf generation) |
| [setMaxFontSize(double value)](#setMaxFontSize-double-) | Maximal font size which can be used for field contents. -1 to don't check size. |
| [setMaxLen(int value)](#setMaxLen-int-) | Sets maximum length of text in the field. |
| [setMinFontSize(double value)](#setMinFontSize-double-) | Minimal font size which can be used for field contents. -1 to don't check size. |
| [setModified(Date value)](#setModified-java.util.Date-) | Sets date and time when annotation was recently modified. |
| [setModifiedInternal(System.DateTime value)](#setModifiedInternal-com.aspose.ms.System.DateTime-) | Sets date and time when annotation was recently modified. |
| [setMultiline(boolean value)](#setMultiline-boolean-) | Sets multiline flag of the field. |
| [setName(String value)](#setName-java.lang.String-) | Sets annotation name on the page. |
| [setOnActivated(PdfAction value)](#setOnActivated-com.aspose.pdf.PdfAction-) | Set an action which shall be performed when the annotation is activated. |
| [setPartialName(String value)](#setPartialName-java.lang.String-) | Sets partial name of the field. |
| [setPosition(Point point)](#setPosition-com.aspose.pdf.Point-) | Set position of the field. |
| [setReadOnly(boolean value)](#setReadOnly-boolean-) | Sets read only status of the field. |
| [setRect(Rectangle value)](#setRect-com.aspose.pdf.Rectangle-) | Sets the field rectangle. |
| [setRequired(boolean value)](#setRequired-boolean-) | Sets read only status of the field. |
| [setScrollable(boolean value)](#setScrollable-boolean-) | Sets scrollable flag of field. |
| [setSharedField(boolean value)](#setSharedField-boolean-) | Property for Generator support. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Sets spellcheck flag for field. |
| [setTabOrder(int value)](#setTabOrder-int-) | Gets or sets tab order of the field. |
| [setTextHorizontalAlignment(int value)](#setTextHorizontalAlignment-int-) | Sets text alignmennt for annotation. |
| [setTextVerticalAlignment(int value)](#setTextVerticalAlignment-int-) | Gets or sets text vertical alignment for annotation. |
| [setUpdateAppearanceOnConvert(boolean value)](#setUpdateAppearanceOnConvert-boolean-) | If true, annotation appearance will be updated before converting PF document into image. |
| [setUseFontSubset(boolean value)](#setUseFontSubset-boolean-) | If this property set to true, fonts will be added to document as subsets. |
| [setValue(String value)](#setValue-java.lang.String-) | Sets value of the field. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Sets a vertical alignment of paragraph |
| [setWidth(double value)](#setWidth-double-) | Sets width of the annotation. |
| [setZIndex(int value)](#setZIndex-int-) | Sets a int value that indicates the Z-order of the graph. |
| [size()](#size--) | Gets number of subfields in this field. |
| [toString()](#toString--) |  |
| [updateAppearances()](#updateAppearances--) | Update appearances value. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### _FileSelect {#-FileSelect}
```
public static final int _FileSelect
```


\_FileSelect

### _Password {#-Password}
```
public static final int _Password
```


\_Password

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts visitor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor to be accepted. |

### add(WidgetAnnotation item) {#add-com.aspose.pdf.WidgetAnnotation-}
```
public void add(WidgetAnnotation item)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [WidgetAnnotation](../../com.aspose.pdf/widgetannotation) |  |

### addBarcode(String code) {#addBarcode-java.lang.String-}
```
public void addBarcode(String code)
```


Adds barcode 128 into the field. Field value will be changed onto the code and field become read only.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| code | java.lang.String | The text to generate barcode 128. |

### addImage(BufferedImage image) {#addImage-java.awt.image.BufferedImage-}
```
public void addImage(BufferedImage image)
```


Adds image into the field resources an draws it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | Image to add into text field. |

### changeAfterResize(Matrix transform) {#changeAfterResize-com.aspose.pdf.Matrix-}
```
public void changeAfterResize(Matrix transform)
```


Update parameters and appearance, according to the matrix transform.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.pdf/matrix) | Matrix that use for transformation (resize). |

### clear() {#clear--}
```
public void clear()
```




### contains(WidgetAnnotation item) {#contains-com.aspose.pdf.WidgetAnnotation-}
```
public boolean contains(WidgetAnnotation item)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [WidgetAnnotation](../../com.aspose.pdf/widgetannotation) |  |

**Returns:**
boolean
### copyTo(Field[] array, int index) {#copyTo-com.aspose.pdf.Field---int-}
```
public void copyTo(Field[] array, int index)
```


Copies subfields of this field into array starting from specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [Field\[\]](../../com.aspose.pdf/field) | Array where field must be copied. |
| index | int | Starting index where fields will be copied. |

### copyTo(WidgetAnnotation[] array, int arrayIndex) {#copyTo-com.aspose.pdf.WidgetAnnotation---int-}
```
public void copyTo(WidgetAnnotation[] array, int arrayIndex)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [WidgetAnnotation\[\]](../../com.aspose.pdf/widgetannotation) |  |
| arrayIndex | int |  |

### createAnnotation(IPdfObject annotEngineObj, Page page) {#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-}
```
public static Annotation createAnnotation(IPdfObject annotEngineObj, Page page)
```


For internal usage only

Initializes annotation from PDF object which describes the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotEngineObj | [IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) | PDF object describing annotation |
| page | [Page](../../com.aspose.pdf/page) | Page object |

**Returns:**
[Annotation](../../com.aspose.pdf/annotation) - Created annotation object of appropriate type
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clones this instance. Virtual method. Always return null.

**Returns:**
java.lang.Object - Null
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
### flatten() {#flatten--}
```
public void flatten()
```


Removes this field and place its value directly on the page.

### getActiveState() {#getActiveState--}
```
public String getActiveState()
```


Gets current annotation appearance state.

**Returns:**
java.lang.String - String value
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Annotation alignment. This property is obsolete. Use getHorizontalAlignment\_Annotation\_New instead.

**Returns:**
int - TextAlignment element
### getAlternateName() {#getAlternateName--}
```
public String getAlternateName()
```


Gets alternate name of the field (An alternate field name that shall be used in place of the actual field name wherever the field shall be identified in the user interface). Alternate name is used as field tooltip in Adobe Acrobat.

**Returns:**
java.lang.String - String value
### getAnnotationActions() {#getAnnotationActions--}
```
public AnnotationActionCollection getAnnotationActions()
```


Gets the annotation actions.

**Returns:**
[AnnotationActionCollection](../../com.aspose.pdf/annotationactioncollection) - AnnotationActionCollection object
### getAnnotationIndex() {#getAnnotationIndex--}
```
public int getAnnotationIndex()
```


Gets index of this anotation on the page.

**Returns:**
int - int value
### getAnnotationType() {#getAnnotationType--}
```
public int getAnnotationType()
```


Gets type of annotation.

**Returns:**
int - AnnotationType element
### getAppearance() {#getAppearance--}
```
public AppearanceDictionary getAppearance()
```


Gets appearance dictionary of the annotation.

**Returns:**
[AppearanceDictionary](../../com.aspose.pdf/appearancedictionary) - AppearanceDictionary object
### getBorder() {#getBorder--}
```
public Border getBorder()
```


Gets annotation border characteristics.  Border 

**Returns:**
[Border](../../com.aspose.pdf/border) - Border object
### getCharacteristics() {#getCharacteristics--}
```
public Characteristics getCharacteristics()
```


Gets annotation characteristics.

**Returns:**
[Characteristics](../../com.aspose.pdf/characteristics) - Characteristics object
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```


Gets annotation color.

**Returns:**
[Color](../../com.aspose.pdf/color) - Color object
### getContents() {#getContents--}
```
public String getContents()
```


Gets annotation text.

**Returns:**
java.lang.String - String value
### getDefaultAppearance() {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```


Gets default appearance of the field.

**Returns:**
[DefaultAppearance](../../com.aspose.pdf/defaultappearance) - DefaultAppearance object
### getEngineDict() {#getEngineDict--}
```
public IPdfDictionary getEngineDict()
```


Internal only

**Returns:**
[IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) - IPdfDictionary object
### getEngineObj() {#getEngineObj--}
```
public IPdfObject getEngineObj()
```


For Internal usage only

**Returns:**
[IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) - Internal onject
### getExportable() {#getExportable--}
```
public boolean getExportable()
```


Gets exportable flag of the field.

**Returns:**
boolean - boolean value
### getFlags() {#getFlags--}
```
public int getFlags()
```


Get flags of the annotation.

**Returns:**
int - Flags of the annotation
### getForceCombs() {#getForceCombs--}
```
public boolean getForceCombs()
```


Gets flag which indicates is field divided into spaced positions.

**Returns:**
boolean - boolean value
### getFullName() {#getFullName--}
```
public String getFullName()
```


Gets full qualified name of the annotation.

**Returns:**
java.lang.String - String value
### getHeight() {#getHeight--}
```
public double getHeight()
```


Gets height of the annotation.

**Returns:**
double - height of the annotation
### getHighlighting() {#getHighlighting--}
```
public int getHighlighting()
```


Annotation highlighting mode.

**Returns:**
int - HighlightingMode value
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Gets a horizontal alignment of paragraph

**Returns:**
int - HorizontalAlignment value
### getHorizontalAlignment_Annotation_New() {#getHorizontalAlignment-Annotation-New--}
```
public final int getHorizontalAlignment_Annotation_New()
```


Gets or sets text alignment for annotation.

**Returns:**
int - text alignment for annotation.
### getHyperlink() {#getHyperlink--}
```
public Hyperlink getHyperlink()
```


Gets the fragment hyperlink(for pdf generator).

**Returns:**
[Hyperlink](../../com.aspose.pdf/hyperlink) - the fragment hyperlink(for pdf generator).
### getMappingName() {#getMappingName--}
```
public String getMappingName()
```


Gets mapping name of the field that shall be used when exporting interactive form field data from the document.

**Returns:**
java.lang.String - String value
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Gets a outer margin for paragraph (for pdf generation)

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - MarginInfo value
### getMaxFontSize() {#getMaxFontSize--}
```
public static synchronized double getMaxFontSize()
```


Maximal font size which can be used for field contents. -1 to don't check size.

**Returns:**
double - double value
### getMaxLen() {#getMaxLen--}
```
public int getMaxLen()
```


Gets maximum length of text in the field.

**Returns:**
int - int value
### getMinFontSize() {#getMinFontSize--}
```
public static double getMinFontSize()
```


Minimal font size which can be used for field contents. -1 to don't check size.

**Returns:**
double - double value
### getModified() {#getModified--}
```
public Date getModified()
```


Gets date and time when annotation was recently modified.

**Returns:**
[Date](../../java.util/date) - date and time when annotation was recently modified.
### getModifiedInternal() {#getModifiedInternal--}
```
public System.DateTime getModifiedInternal()
```


Gets date and time when annotation was recently modified.

**Returns:**
com.aspose.ms.System.DateTime - DateTime object
### getMultiline() {#getMultiline--}
```
public boolean getMultiline()
```


Gets multiline flag of the field. If Multiline is true field can contain multiple lines of text.

**Returns:**
boolean - boolean value
### getName() {#getName--}
```
public String getName()
```


Gets annotation name on the page.

**Returns:**
java.lang.String - String value
### getNormalAppearance() {#getNormalAppearance--}
```
public XForm getNormalAppearance()
```


Gets normal appearance.

**Returns:**
[XForm](../../com.aspose.pdf/xform) - XForm object
### getOnActivated() {#getOnActivated--}
```
public PdfAction getOnActivated()
```


Get an action which shall be performed when the annotation is activated.

**Returns:**
[PdfAction](../../com.aspose.pdf/pdfaction) - PdfAction object
### getPage() {#getPage--}
```
public Page getPage()
```


Gets the page object with which this annotation is associated.

**Returns:**
[Page](../../com.aspose.pdf/page) - Page object
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


Gets index of page which contains this field.

**Returns:**
int - int value
### getPageIndex(Annotation annotation) {#getPageIndex-com.aspose.pdf.Annotation-}
```
public int getPageIndex(Annotation annotation)
```


Gets index of page which contains annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | Annotation object |

**Returns:**
int - int value
### getParent() {#getParent--}
```
public Field getParent()
```


Gets annotation parent.

**Returns:**
[Field](../../com.aspose.pdf/field) - Field object
### getPartialName() {#getPartialName--}
```
public String getPartialName()
```


Gets partial name of the field.

**Returns:**
java.lang.String - String value
### getPdfActions() {#getPdfActions--}
```
public PdfActionCollection getPdfActions()
```


Gets list of annotation actions.

**Returns:**
[PdfActionCollection](../../com.aspose.pdf/pdfactioncollection) - PdfActionCollection instance
### getReadOnly() {#getReadOnly--}
```
public boolean getReadOnly()
```


Gets read only status of the field.

**Returns:**
boolean - boolean value
### getRect() {#getRect--}
```
public Rectangle getRect()
```


Gets the field rectangle.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - the field rectangle.
### getRectangle(boolean considerRotation) {#getRectangle-boolean-}
```
public Rectangle getRectangle(boolean considerRotation)
```


Returns rectangle of annotation taking into consideration page rotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| considerRotation | boolean | If true, page rotation is taken into consideration. |

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle object
### getRequired() {#getRequired--}
```
public boolean getRequired()
```


Gets required status of the field.

**Returns:**
boolean - boolean value
### getScrollable() {#getScrollable--}
```
public boolean getScrollable()
```


Gets scrollable flag of field. If true field can be scrolled.

**Returns:**
boolean - boolean value
### getSpellCheck() {#getSpellCheck--}
```
public boolean getSpellCheck()
```


Gets spellcheck flag for field. If true field shall be spell checked.

**Returns:**
boolean - boolean value
### getStates() {#getStates--}
```
public AppearanceDictionary getStates()
```


Gets appearance dictionary of annotation.

**Returns:**
[AppearanceDictionary](../../com.aspose.pdf/appearancedictionary) - AppearanceDictionary object
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Synchronization object.

**Returns:**
java.lang.Object - object value
### getTabOrder() {#getTabOrder--}
```
public int getTabOrder()
```


Gets or sets tab order of the field.

**Returns:**
int - int value
### getTextHorizontalAlignment() {#getTextHorizontalAlignment--}
```
public int getTextHorizontalAlignment()
```


Gets text alignment for annotation.

**Returns:**
int - text alignment for annotation.
### getTextVerticalAlignment() {#getTextVerticalAlignment--}
```
public final int getTextVerticalAlignment()
```


Gets or sets text vertical alignment for annotation.

**Returns:**
int - VerticalAlignment element
### getValue() {#getValue--}
```
public String getValue()
```


Gets value of the field.

**Returns:**
java.lang.String - String value
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


Gets a vertical alignment of paragraph

**Returns:**
int - VerticalAlignment element
### getWidth() {#getWidth--}
```
public double getWidth()
```


Gets width of the annotation.

**Returns:**
double - double value, width of the annotation.
### getZIndex() {#getZIndex--}
```
public int getZIndex()
```


Gets an int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page.

**Returns:**
int - int value
### get_Item(int index) {#get-Item-int-}
```
public WidgetAnnotation get_Item(int index)
```


Gets subfield contained in this field by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of the reuqested subfield. |

**Returns:**
[WidgetAnnotation](../../com.aspose.pdf/widgetannotation) - Field instance.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public WidgetAnnotation get_Item(String name)
```


Gets subfield contained in this field by name of the subfield.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Contained subfield name. |

**Returns:**
[WidgetAnnotation](../../com.aspose.pdf/widgetannotation) - Field instance.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initialize(IDocument doc) {#initialize-com.aspose.pdf.IDocument-}
```
public void initialize(IDocument doc)
```


Instance initialization

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) | IDocument object |

### isFirstParagraphInColumn() {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```


Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation)

**Returns:**
boolean - boolean value
### isFitIntoRectangle() {#isFitIntoRectangle--}
```
public static synchronized boolean isFitIntoRectangle()
```


If true then font size will reduced to fit text to specified rectangle.

**Returns:**
boolean - boolean value
### isGroup() {#isGroup--}
```
public boolean isGroup()
```


Gets boolean value which indicates is this field non-terminal field i.e. group of fields.

**Returns:**
boolean - boolean value
### isInLineParagraph() {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```


Gets a paragraph is inline. Default is false.(for pdf generation)

**Returns:**
boolean - boolean value
### isInNewPage() {#isInNewPage--}
```
public boolean isInNewPage()
```


Gets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation)

**Returns:**
boolean - boolean value
### isKeptWithNext() {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```


Gets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation)

**Returns:**
boolean - boolean value
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```




**Returns:**
boolean
### isSharedField() {#isSharedField--}
```
public boolean isSharedField()
```


Property for Generator support. Used when field is added to header or footer. If true, this field will created once and it's appearance will be visible on all pages of the document. If false, separated field will be created for every document page.

**Returns:**
boolean - boolean value
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Returns true if dictionary is synchronized.

**Returns:**
boolean - boolean value
### isUpdateAppearanceOnConvert() {#isUpdateAppearanceOnConvert--}
```
public static synchronized boolean isUpdateAppearanceOnConvert()
```


If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time.

**Returns:**
boolean - boolean value
### isUseFontSubset() {#isUseFontSubset--}
```
public static synchronized boolean isUseFontSubset()
```


If this property set to true, fonts will be added to document as subsets. Default value is true.

**Returns:**
boolean - boolean value
### iterator() {#iterator--}
```
public Iterator<WidgetAnnotation> iterator()
```


Returns enumerator of contained fields.

**Returns:**
java.util.Iterator<com.aspose.pdf.WidgetAnnotation> - Enumerator object.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### recalculate() {#recalculate--}
```
public boolean recalculate()
```


Recaculates all calculated fields on the form.

**Returns:**
boolean - true if field value was changed during recalculation.
### remove(WidgetAnnotation item) {#remove-com.aspose.pdf.WidgetAnnotation-}
```
public boolean remove(WidgetAnnotation item)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [WidgetAnnotation](../../com.aspose.pdf/widgetannotation) |  |

**Returns:**
boolean
### setActiveState(String value) {#setActiveState-java.lang.String-}
```
public void setActiveState(String value)
```


Sets current annotation appearance state.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Annotation alignment. This property is obsolete. Use getHorizontalAlignment\_Annotation\_New instead.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | TextAlignment element |

### setAlternateName(String value) {#setAlternateName-java.lang.String-}
```
public void setAlternateName(String value)
```


Sets alternate name of the field (An alternate field name that shall be used in place of the actual field name wherever the field shall be identified in the user interface). Alternate name is used as field tooltip in Adobe Acrobat.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setAnnotationIndex(int value) {#setAnnotationIndex-int-}
```
public void setAnnotationIndex(int value)
```


Sets index of this anotation on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setBorder(Border value) {#setBorder-com.aspose.pdf.Border-}
```
public void setBorder(Border value)
```


Sets annotation border characteristics.  Border 

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Border](../../com.aspose.pdf/border) | Border value |

### setColor(Color value) {#setColor-com.aspose.pdf.Color-}
```
public void setColor(Color value)
```


Sets annotation color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Color value |

### setContents(String value) {#setContents-java.lang.String-}
```
public void setContents(String value)
```


Sets annotation text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setDefaultAppearance(DefaultAppearance value) {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
```
public void setDefaultAppearance(DefaultAppearance value)
```


Sets default appearance of the field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DefaultAppearance](../../com.aspose.pdf/defaultappearance) | DefaultAppearance object |

### setExportable(boolean value) {#setExportable-boolean-}
```
public void setExportable(boolean value)
```


Sets read only status of the field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setFirstParagraphInColumn(boolean value) {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```


Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setFitIntoRectangle(boolean value) {#setFitIntoRectangle-boolean-}
```
public static synchronized void setFitIntoRectangle(boolean value)
```


If true then font size will reduced to fit text to specified rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Set flags of the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | flags of the annotation |

### setForceCombs(boolean value) {#setForceCombs-boolean-}
```
public void setForceCombs(boolean value)
```


Sets flag which indicates is field divided into spaced positions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Sets height of the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | height of the annotation |

### setHighlighting(int value) {#setHighlighting-int-}
```
public void setHighlighting(int value)
```


Annotation highlighting mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | HighlightingMode value |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


Sets a horizontal alignment of paragraph

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | HorizontalAlignment value |

### setHorizontalAlignment_Annotation_New(int value) {#setHorizontalAlignment-Annotation-New-int-}
```
public final void setHorizontalAlignment_Annotation_New(int value)
```


Gets or sets text alignment for annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | text alignmennt for annotation. |

### setHyperlink(Hyperlink value) {#setHyperlink-com.aspose.pdf.Hyperlink-}
```
public void setHyperlink(Hyperlink value)
```


Sets hyperlink(for pdf generator).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Hyperlink](../../com.aspose.pdf/hyperlink) | hyperlink(for pdf generator). |

### setInLineParagraph(boolean value) {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```


Sets a paragraph is inline. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setInNewPage(boolean value) {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```


Sets a boolean value that force this paragraph generates at new page. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setJustification(boolean value) {#setJustification-boolean-}
```
public void setJustification(boolean value)
```


Sets justification

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setKeptWithNext(boolean value) {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```


Sets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setMappingName(String value) {#setMappingName-java.lang.String-}
```
public void setMappingName(String value)
```


Sets mapping name of the field that shall be used when exporting interactive form field data from the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


Sets a outer margin for paragraph (for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo object |

### setMaxFontSize(double value) {#setMaxFontSize-double-}
```
public static synchronized void setMaxFontSize(double value)
```


Maximal font size which can be used for field contents. -1 to don't check size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setMaxLen(int value) {#setMaxLen-int-}
```
public void setMaxLen(int value)
```


Sets maximum length of text in the field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setMinFontSize(double value) {#setMinFontSize-double-}
```
public static void setMinFontSize(double value)
```


Minimal font size which can be used for field contents. -1 to don't check size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setModified(Date value) {#setModified-java.util.Date-}
```
public void setModified(Date value)
```


Sets date and time when annotation was recently modified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | Date object |

### setModifiedInternal(System.DateTime value) {#setModifiedInternal-com.aspose.ms.System.DateTime-}
```
public void setModifiedInternal(System.DateTime value)
```


Sets date and time when annotation was recently modified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.DateTime | DateTime object |

### setMultiline(boolean value) {#setMultiline-boolean-}
```
public void setMultiline(boolean value)
```


Sets multiline flag of the field. If Multiline is true field can contain multiple lines of text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Sets annotation name on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setOnActivated(PdfAction value) {#setOnActivated-com.aspose.pdf.PdfAction-}
```
public void setOnActivated(PdfAction value)
```


Set an action which shall be performed when the annotation is activated.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | PdfAction object |

### setPartialName(String value) {#setPartialName-java.lang.String-}
```
public void setPartialName(String value)
```


Sets partial name of the field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setPosition(Point point) {#setPosition-com.aspose.pdf.Point-}
```
public void setPosition(Point point)
```


Set position of the field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.pdf/point) | Point where field should be positioned. |

### setReadOnly(boolean value) {#setReadOnly-boolean-}
```
public void setReadOnly(boolean value)
```


Sets read only status of the field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setRect(Rectangle value) {#setRect-com.aspose.pdf.Rectangle-}
```
public void setRect(Rectangle value)
```


Sets the field rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | the field rectangle. |

### setRequired(boolean value) {#setRequired-boolean-}
```
public void setRequired(boolean value)
```


Sets read only status of the field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setScrollable(boolean value) {#setScrollable-boolean-}
```
public void setScrollable(boolean value)
```


Sets scrollable flag of field. If true field can be scrolled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setSharedField(boolean value) {#setSharedField-boolean-}
```
public void setSharedField(boolean value)
```


Property for Generator support. Used when field is added to header or footer. If true, this field will created once and it's appearance will be visible on all pages of the document. If false, separated field will be created for every document page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public void setSpellCheck(boolean value)
```


Sets spellcheck flag for field. If true field shall be spell checked.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setTabOrder(int value) {#setTabOrder-int-}
```
public void setTabOrder(int value)
```


Gets or sets tab order of the field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setTextHorizontalAlignment(int value) {#setTextHorizontalAlignment-int-}
```
public void setTextHorizontalAlignment(int value)
```


Sets text alignmennt for annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | text alignmennt for annotation. |

### setTextVerticalAlignment(int value) {#setTextVerticalAlignment-int-}
```
public final void setTextVerticalAlignment(int value)
```


Gets or sets text vertical alignment for annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | VerticalAlignment element |

### setUpdateAppearanceOnConvert(boolean value) {#setUpdateAppearanceOnConvert-boolean-}
```
public static synchronized void setUpdateAppearanceOnConvert(boolean value)
```


If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setUseFontSubset(boolean value) {#setUseFontSubset-boolean-}
```
public static synchronized void setUseFontSubset(boolean value)
```


If this property set to true, fonts will be added to document as subsets. Default value is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


Sets value of the field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


Sets a vertical alignment of paragraph

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | VerticalAlignment element |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Sets width of the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | width of the annotation. |

### setZIndex(int value) {#setZIndex-int-}
```
public void setZIndex(int value)
```


Sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### size() {#size--}
```
public int size()
```


Gets number of subfields in this field. (For example number of items in radio button field).

**Returns:**
int - int value
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateAppearances() {#updateAppearances--}
```
public void updateAppearances()
```


Update appearances value.

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

