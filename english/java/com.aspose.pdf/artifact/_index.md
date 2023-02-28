---
title: Artifact
second_title: Aspose.PDF for Java API Reference
description: Class represents PDF Artifact object.
type: docs
weight: 27
url: /java/com.aspose.pdf/artifact/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class Artifact implements System.IDisposable, Closeable
```

Class represents PDF Artifact object.
## Constructors

| Constructor | Description |
| --- | --- |
| [Artifact(ArtifactCollection owner, Artifact.ArtifactContext context, System.Collections.Generic.List<Operator> _contents, IPdfDictionary _properties)](#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Artifact.ArtifactContext-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.Operator--com.aspose.pdf.engine.data.IPdfDictionary-) | This constructor is used when artifact is read from the page. |
| [Artifact(String type, String subType)](#Artifact-java.lang.String-java.lang.String-) | Constructor of artifact with specified type and subtype |
| [Artifact(Artifact.ArtifactType type, Artifact.ArtifactSubtype subType)](#Artifact-com.aspose.pdf.Artifact.ArtifactType-com.aspose.pdf.Artifact.ArtifactSubtype-) | Constructor of artifact with specified type and subtype |
## Methods

| Method | Description |
| --- | --- |
| [getCustomType()](#getCustomType--) | Gets name of artifact type. |
| [setCustomType(String value)](#setCustomType-java.lang.String-) | Sets name of artifact type. |
| [getCustomSubtype()](#getCustomSubtype--) | Gets name of artifact subtype. |
| [setCustomSubtype(String value)](#setCustomSubtype-java.lang.String-) |  |
| [getType()](#getType--) | Gets artifact type. |
| [setType(Artifact.ArtifactType value)](#setType-com.aspose.pdf.Artifact.ArtifactType-) | Sets artifact type. |
| [getSubtype()](#getSubtype--) | Gets artifact subtype. |
| [setSubtype(Artifact.ArtifactSubtype value)](#setSubtype-com.aspose.pdf.Artifact.ArtifactSubtype-) | Sets artifact subtype. |
| [getContents()](#getContents--) | Gets collection of artifact internal operators. |
| [getForm()](#getForm--) | Gets XForm of the artifact (if XForm is used). |
| [getRectangle()](#getRectangle--) | Gets rectangle of the artifact. |
| [getPosition()](#getPosition--) | Gets artifact position. |
| [setPosition(Point value)](#setPosition-com.aspose.pdf.Point-) | Sets artifact position. |
| [getRightMargin()](#getRightMargin--) | Gets right margin of artifact. |
| [setRightMargin(double value)](#setRightMargin-double-) | Sets right margin of artifact. |
| [getLeftMargin()](#getLeftMargin--) | Gets left margin of artifact. |
| [setLeftMargin(double value)](#setLeftMargin-double-) | Sets left margin of artifact. |
| [getTopMargin()](#getTopMargin--) | Gets top margin of artifact. |
| [setTopMargin(double value)](#setTopMargin-double-) | Sets top margin of artifact. |
| [getBottomMargin()](#getBottomMargin--) | Gets bottom margin of artifact. |
| [setBottomMargin(double value)](#setBottomMargin-double-) | Sets bottom margin of artifact. |
| [getArtifactHorizontalAlignment()](#getArtifactHorizontalAlignment--) | Gets horizontal alignment of artifact. |
| [setArtifactHorizontalAlignment(HorizontalAlignment value)](#setArtifactHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Gets horizontal alignment of artifact. |
| [getArtifactVerticalAlignment()](#getArtifactVerticalAlignment--) | Gets vertical alignment of artifact. |
| [setArtifactVerticalAlignment(VerticalAlignment value)](#setArtifactVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Sets vertical alignment of artifact. |
| [getRotation()](#getRotation--) | Gets artifact rotation angle. |
| [setRotation(double value)](#setRotation-double-) | Sets artifact rotation angle. |
| [getText()](#getText--) | Gets text of the artifact. |
| [setText(String value)](#setText-java.lang.String-) | Sets text of the artifact. |
| [getImage()](#getImage--) | Gets image of the artifact (if presents). |
| [getOpacity()](#getOpacity--) | Gets opacity of the artifact. |
| [setOpacity(double value)](#setOpacity-double-) | Sets opacity of the artifact. |
| [setText(FormattedText formattedText)](#setText-com.aspose.pdf.facades.FormattedText-) | Sets text of the artifact. |
| [getLines()](#getLines--) | Lines of multiline text artifact. |
| [getTextState()](#getTextState--) | Text state for artifact text. |
| [setTextState(TextState value)](#setTextState-com.aspose.pdf.TextState-) | Text state for artifact text. |
| [setTextAndState(String text, TextState textState)](#setTextAndState-java.lang.String-com.aspose.pdf.TextState-) | Set text and text properties of the artifact. |
| [setLinesAndState(String[] text, TextState textState)](#setLinesAndState-java.lang.String---com.aspose.pdf.TextState-) | Set text and text properties of the artifact. |
| [setImage(InputStream imageStream)](#setImage-java.io.InputStream-) | Sets image of the artifact. |
| [setImage(String imageName)](#setImage-java.lang.String-) | Sets image of the artifact. |
| [setPdfPage(Page page)](#setPdfPage-com.aspose.pdf.Page-) | Sets PDF page which is placed on the document page as artifact. |
| [close()](#close--) | Closes all resources used by this document. |
| [dispose()](#dispose--) | Dispose the artifact. |
| [getValue(String name)](#getValue-java.lang.String-) | Gets custom value of artifact. |
| [setValue(String name, String value)](#setValue-java.lang.String-java.lang.String-) | Sets custom value of artifact. |
| [removeValue(String name)](#removeValue-java.lang.String-) | Remove custom value from the artifact. |
| [beginUpdates()](#beginUpdates--) | Start deleted updates. |
| [saveUpdates()](#saveUpdates--) | Saves all updates in artifact which were made after BeginUpdates() call. |
| [isBackground()](#isBackground--) | If true Artifact is placed behind page contents. |
| [setBackground(boolean value)](#setBackground-boolean-) | If true Artifact is placed behind page contents. |
### Artifact(ArtifactCollection owner, Artifact.ArtifactContext context, System.Collections.Generic.List<Operator> _contents, IPdfDictionary _properties) {#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Artifact.ArtifactContext-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.Operator--com.aspose.pdf.engine.data.IPdfDictionary-}
```
public Artifact(ArtifactCollection owner, Artifact.ArtifactContext context, System.Collections.Generic.List<Operator> _contents, IPdfDictionary _properties)
```


This constructor is used when artifact is read from the page. ARtifactCollection passes page resources, initial matrix, operators of the artifact ("contents") and properties dictionary.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| owner | [ArtifactCollection](../../com.aspose.pdf/artifactcollection) | ArtifactCollection object |
| context | com.aspose.pdf.Artifact.ArtifactContext | ArtifactContext object |
| _contents | com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> | Collection of Operators |
| _properties | [IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) | IPdfDictionary object |

### Artifact(String type, String subType) {#Artifact-java.lang.String-java.lang.String-}
```
public Artifact(String type, String subType)
```


Constructor of artifact with specified type and subtype

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | java.lang.String | Name of artifact type. |
| subType | java.lang.String | NAme of artifact subtype. |

### Artifact(Artifact.ArtifactType type, Artifact.ArtifactSubtype subType) {#Artifact-com.aspose.pdf.Artifact.ArtifactType-com.aspose.pdf.Artifact.ArtifactSubtype-}
```
public Artifact(Artifact.ArtifactType type, Artifact.ArtifactSubtype subType)
```


Constructor of artifact with specified type and subtype

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | [ArtifactType](../../com.aspose.pdf/artifacttype) | Artifact type. |
| subType | [ArtifactSubtype](../../com.aspose.pdf/artifactsubtype) | Artifact subtype. |

### getCustomType() {#getCustomType--}
```
public String getCustomType()
```


Gets name of artifact type. May be used if artifact type is non standard.

**Returns:**
java.lang.String - String artifact name
### setCustomType(String value) {#setCustomType-java.lang.String-}
```
public void setCustomType(String value)
```


Sets name of artifact type. May be used if artifact type is non standard.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String artifact name |

### getCustomSubtype() {#getCustomSubtype--}
```
public String getCustomSubtype()
```


Gets name of artifact subtype. May be used if artifact subtype is not standard subtype.

**Returns:**
java.lang.String - String value
### setCustomSubtype(String value) {#setCustomSubtype-java.lang.String-}
```
public void setCustomSubtype(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getType() {#getType--}
```
public Artifact.ArtifactType getType()
```


Gets artifact type.

**Returns:**
[ArtifactType](../../com.aspose.pdf/artifacttype) - artifact type value.
### setType(Artifact.ArtifactType value) {#setType-com.aspose.pdf.Artifact.ArtifactType-}
```
public void setType(Artifact.ArtifactType value)
```


Sets artifact type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ArtifactType](../../com.aspose.pdf/artifacttype) | artifact type. |

### getSubtype() {#getSubtype--}
```
public Artifact.ArtifactSubtype getSubtype()
```


Gets artifact subtype. If artifact has non-standard subtype, name of the subtype may be read via CustomSubtype.

**Returns:**
[ArtifactSubtype](../../com.aspose.pdf/artifactsubtype) - artifact subtype.
### setSubtype(Artifact.ArtifactSubtype value) {#setSubtype-com.aspose.pdf.Artifact.ArtifactSubtype-}
```
public void setSubtype(Artifact.ArtifactSubtype value)
```


Sets artifact subtype. If artifact has non-standard subtype, name of the subtype may be read via CustomSubtype.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ArtifactSubtype](../../com.aspose.pdf/artifactsubtype) | artifact subtype. |

### getContents() {#getContents--}
```
public List<Operator> getContents()
```


Gets collection of artifact internal operators.

**Returns:**
java.util.List<com.aspose.pdf.Operator> - list artifact internal operators.
### getForm() {#getForm--}
```
public XForm getForm()
```


Gets XForm of the artifact (if XForm is used).

**Returns:**
[XForm](../../com.aspose.pdf/xform) - XForm object
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Gets rectangle of the artifact.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle object
### getPosition() {#getPosition--}
```
public Point getPosition()
```


Gets artifact position. If this property is specified, then margins and alignments are ignored.

**Returns:**
[Point](../../com.aspose.pdf/point) - artifact position.
### setPosition(Point value) {#setPosition-com.aspose.pdf.Point-}
```
public void setPosition(Point value)
```


Sets artifact position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.pdf/point) | artifact position. |

### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


Gets right margin of artifact. If position is specified explicitly (in Position property) this value is ignored.

**Returns:**
double - right margin of artifact.
### setRightMargin(double value) {#setRightMargin-double-}
```
public void setRightMargin(double value)
```


Sets right margin of artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | right margin of artifact. |

### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


Gets left margin of artifact. If position is specified explicitly (in Position property) this value is ignored.

**Returns:**
double - left margin of artifact.
### setLeftMargin(double value) {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```


Sets left margin of artifact. If position is specified explicitly (in Position property) this value is ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | left margin of artifact. |

### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


Gets top margin of artifact. If position is specified explicitly (in Position property) this value is ignored.

**Returns:**
double - top margin of artifact.
### setTopMargin(double value) {#setTopMargin-double-}
```
public void setTopMargin(double value)
```


Sets top margin of artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | top margin of artifact. |

### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


Gets bottom margin of artifact. If position is specified explicitly (in Position property) this value is ignored.

**Returns:**
double - bottom margin.
### setBottomMargin(double value) {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```


Sets bottom margin of artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | bottom margin. |

### getArtifactHorizontalAlignment() {#getArtifactHorizontalAlignment--}
```
public HorizontalAlignment getArtifactHorizontalAlignment()
```


Gets horizontal alignment of artifact. If position is specified explicitly (in Position property) this value is ignored.

**Returns:**
[HorizontalAlignment](../../com.aspose.pdf/horizontalalignment) - HorizontalAlignment value
### setArtifactHorizontalAlignment(HorizontalAlignment value) {#setArtifactHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
```
public void setArtifactHorizontalAlignment(HorizontalAlignment value)
```


Gets horizontal alignment of artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HorizontalAlignment](../../com.aspose.pdf/horizontalalignment) | horizontal alignment of artifact. |

### getArtifactVerticalAlignment() {#getArtifactVerticalAlignment--}
```
public VerticalAlignment getArtifactVerticalAlignment()
```


Gets vertical alignment of artifact. If position is specified explicitly (in Position property) this value is ignored.

**Returns:**
[VerticalAlignment](../../com.aspose.pdf/verticalalignment) - VerticalAlignment value.
### setArtifactVerticalAlignment(VerticalAlignment value) {#setArtifactVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
```
public void setArtifactVerticalAlignment(VerticalAlignment value)
```


Sets vertical alignment of artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VerticalAlignment](../../com.aspose.pdf/verticalalignment) | vertical alignment of artifact. |

### getRotation() {#getRotation--}
```
public double getRotation()
```


Gets artifact rotation angle.

**Returns:**
double - artifact rotation angle.
### setRotation(double value) {#setRotation-double-}
```
public void setRotation(double value)
```


Sets artifact rotation angle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | artifact rotation angle. |

### getText() {#getText--}
```
public String getText()
```


Gets text of the artifact.

**Returns:**
java.lang.String - String value
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Sets text of the artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getImage() {#getImage--}
```
public XImage getImage()
```


Gets image of the artifact (if presents).

**Returns:**
[XImage](../../com.aspose.pdf/ximage) - XImage object
### getOpacity() {#getOpacity--}
```
public double getOpacity()
```


Gets opacity of the artifact. Possible values are in range 0..1.

**Returns:**
double - opacity of the artifact.
### setOpacity(double value) {#setOpacity-double-}
```
public void setOpacity(double value)
```


Sets opacity of the artifact. Possible values are in range 0..1.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | opacity of the artifact. |

### setText(FormattedText formattedText) {#setText-com.aspose.pdf.facades.FormattedText-}
```
public void setText(FormattedText formattedText)
```


Sets text of the artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | FormattedText object which contains artifact text. |

### getLines() {#getLines--}
```
public final List<String> getLines()
```


Lines of multiline text artifact.

**Returns:**
java.util.List<java.lang.String> - List of Strings
### getTextState() {#getTextState--}
```
public final TextState getTextState()
```


Text state for artifact text.

**Returns:**
[TextState](../../com.aspose.pdf/textstate) - TextState instance
### setTextState(TextState value) {#setTextState-com.aspose.pdf.TextState-}
```
public final void setTextState(TextState value)
```


Text state for artifact text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | TextState instance |

### setTextAndState(String text, TextState textState) {#setTextAndState-java.lang.String-com.aspose.pdf.TextState-}
```
public void setTextAndState(String text, TextState textState)
```


Set text and text properties of the artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text string. |
| textState | [TextState](../../com.aspose.pdf/textstate) | Text state. |

### setLinesAndState(String[] text, TextState textState) {#setLinesAndState-java.lang.String---com.aspose.pdf.TextState-}
```
public void setLinesAndState(String[] text, TextState textState)
```


Set text and text properties of the artifact. Allows to specify multiple lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String[] | Array of text string. |
| textState | [TextState](../../com.aspose.pdf/textstate) | Text properties. |

### setImage(InputStream imageStream) {#setImage-java.io.InputStream-}
```
public void setImage(InputStream imageStream)
```


Sets image of the artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | java.io.InputStream | Stream which contains image data. |

### setImage(String imageName) {#setImage-java.lang.String-}
```
public void setImage(String imageName)
```


Sets image of the artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageName | java.lang.String | Name of image file. |

### setPdfPage(Page page) {#setPdfPage-com.aspose.pdf.Page-}
```
public void setPdfPage(Page page)
```


Sets PDF page which is placed on the document page as artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page which is placed as Artifcact. |

### close() {#close--}
```
public void close()
```


Closes all resources used by this document.

### dispose() {#dispose--}
```
public void dispose()
```


Dispose the artifact.

This method is obsolete, use close() instead.

### getValue(String name) {#getValue-java.lang.String-}
```
public String getValue(String name)
```


Gets custom value of artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of value. |

**Returns:**
java.lang.String - Value, or null if value does not exists.
### setValue(String name, String value) {#setValue-java.lang.String-java.lang.String-}
```
public void setValue(String name, String value)
```


Sets custom value of artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of custom value. |
| value | java.lang.String | Custom value in the artifact. |

### removeValue(String name) {#removeValue-java.lang.String-}
```
public void removeValue(String name)
```


Remove custom value from the artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of custom value to be removed. |

### beginUpdates() {#beginUpdates--}
```
public void beginUpdates()
```


Start deleted updates. Use this feature if you need make several changes to the same artifact to improve performance. Usually artifact operators are changed any time when artifact property was changed. This causes changing of page contents every time when artifact was changed. To avoid this effect put all artifact updates between StartUpdates/SaveUpdates calls. This allows to change page contents only once.

```
Artifact art = doc.getPages().get_Item(1).getArtifacts().get_Item(1);
  art.beginUpdates();
  art.setOpacity ( 0.3f);
  art.setPosition ( new Point(10,10));
  art.setRotation (30);
  art.saveUpdates();
```

### saveUpdates() {#saveUpdates--}
```
public void saveUpdates()
```


Saves all updates in artifact which were made after BeginUpdates() call.

### isBackground() {#isBackground--}
```
public boolean isBackground()
```


If true Artifact is placed behind page contents.

**Returns:**
boolean - boolean value
### setBackground(boolean value) {#setBackground-boolean-}
```
public void setBackground(boolean value)
```


If true Artifact is placed behind page contents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

