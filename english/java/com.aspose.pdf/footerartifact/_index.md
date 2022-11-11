---
title: FooterArtifact
second_title: Aspose.PDF for Java API Reference
description: Describes footer artifact.
type: docs
weight: 138
url: /java/com.aspose.pdf/footerartifact/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Artifact](../../com.aspose.pdf/artifact)
```
public class FooterArtifact extends Artifact
```

Describes footer artifact. This may be used to set footer of the page.
## Constructors

| Constructor | Description |
| --- | --- |
| [FooterArtifact()](#FooterArtifact--) | Creates Footer Artifact instance. |
## Methods

| Method | Description |
| --- | --- |
| [beginUpdates()](#beginUpdates--) | Start deleted updates. |
| [close()](#close--) | Closes all resources used by this document. |
| [dispose()](#dispose--) | Dispose the artifact. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArtifactHorizontalAlignment()](#getArtifactHorizontalAlignment--) | Gets horizontal alignment of artifact. |
| [getArtifactVerticalAlignment()](#getArtifactVerticalAlignment--) | Gets vertical alignment of artifact. |
| [getBottomMargin()](#getBottomMargin--) | Gets bottom margin of artifact. |
| [getClass()](#getClass--) |  |
| [getContents()](#getContents--) | Gets collection of artifact internal operators. |
| [getCustomSubtype()](#getCustomSubtype--) | Gets name of artifact subtype. |
| [getCustomType()](#getCustomType--) | Gets name of artifact type. |
| [getForm()](#getForm--) | Gets XForm of the artifact (if XForm is used). |
| [getImage()](#getImage--) | Gets image of the artifact (if presents). |
| [getLeftMargin()](#getLeftMargin--) | Gets left margin of artifact. |
| [getLines()](#getLines--) | Lines of multiline text artifact. |
| [getOpacity()](#getOpacity--) | Gets opacity of the artifact. |
| [getPosition()](#getPosition--) | Gets artifact position. |
| [getRectangle()](#getRectangle--) | Gets rectangle of the artifact. |
| [getRightMargin()](#getRightMargin--) | Gets right margin of artifact. |
| [getRotation()](#getRotation--) | Gets artifact rotation angle. |
| [getSubtype()](#getSubtype--) | Gets artifact subtype. |
| [getText()](#getText--) | Gets text of the artifact. |
| [getTextState()](#getTextState--) | Text state for artifact text. |
| [getTopMargin()](#getTopMargin--) | Gets top margin of artifact. |
| [getType()](#getType--) | Gets artifact type. |
| [getValue(String name)](#getValue-java.lang.String-) | Gets custom value of artifact. |
| [hashCode()](#hashCode--) |  |
| [isBackground()](#isBackground--) | If true Artifact is placed behind page contents. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeValue(String name)](#removeValue-java.lang.String-) | Remove custom value from the artifact. |
| [saveUpdates()](#saveUpdates--) | Saves all updates in artifact which were made after BeginUpdates() call. |
| [setArtifactHorizontalAlignment(int value)](#setArtifactHorizontalAlignment-int-) | Gets horizontal alignment of artifact. |
| [setArtifactVerticalAlignment(int value)](#setArtifactVerticalAlignment-int-) | Sets vertical alignment of artifact. |
| [setBackground(boolean value)](#setBackground-boolean-) | If true Artifact is placed behind page contents. |
| [setBottomMargin(double value)](#setBottomMargin-double-) | Sets bottom margin of artifact. |
| [setCustomSubtype(String value)](#setCustomSubtype-java.lang.String-) |  |
| [setCustomType(String value)](#setCustomType-java.lang.String-) | Sets name of artifact type. |
| [setImage(InputStream imageStream)](#setImage-java.io.InputStream-) | Sets image of the artifact. |
| [setImage(String imageName)](#setImage-java.lang.String-) | Sets image of the artifact. |
| [setLeftMargin(double value)](#setLeftMargin-double-) | Sets left margin of artifact. |
| [setLinesAndState(String[] text, TextState textState)](#setLinesAndState-java.lang.String---com.aspose.pdf.TextState-) | Set text and text properties of the artifact. |
| [setOpacity(double value)](#setOpacity-double-) | Sets opacity of the artifact. |
| [setPdfPage(Page page)](#setPdfPage-com.aspose.pdf.Page-) | Sets PDF page which is placed on the document page as artifact. |
| [setPosition(Point value)](#setPosition-com.aspose.pdf.Point-) | Sets artifact position. |
| [setRightMargin(double value)](#setRightMargin-double-) | Sets right margin of artifact. |
| [setRotation(double value)](#setRotation-double-) | Sets artifact rotation angle. |
| [setSubtype(int value)](#setSubtype-int-) | Sets artifact subtype. |
| [setText(FormattedText formattedText)](#setText-com.aspose.pdf.facades.FormattedText-) | Sets text of the artifact. |
| [setText(String value)](#setText-java.lang.String-) | Sets text of the artifact. |
| [setTextAndState(String text, TextState textState)](#setTextAndState-java.lang.String-com.aspose.pdf.TextState-) | Set text and text properties of the artifact. |
| [setTextState(TextState value)](#setTextState-com.aspose.pdf.TextState-) | Text state for artifact text. |
| [setTopMargin(double value)](#setTopMargin-double-) | Sets top margin of artifact. |
| [setType(int value)](#setType-int-) | Sets artifact type. |
| [setValue(String name, String value)](#setValue-java.lang.String-java.lang.String-) | Sets custom value of artifact. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FooterArtifact() {#FooterArtifact--}
```
public FooterArtifact()
```


Creates Footer Artifact instance.

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
### getArtifactHorizontalAlignment() {#getArtifactHorizontalAlignment--}
```
public int getArtifactHorizontalAlignment()
```


Gets horizontal alignment of artifact. If position is specified explicitly (in Position property) this value is ignored.

**Returns:**
int - HorizontalAlignment value
### getArtifactVerticalAlignment() {#getArtifactVerticalAlignment--}
```
public int getArtifactVerticalAlignment()
```


Gets vertical alignment of artifact. If position is specified explicitly (in Position property) this value is ignored.

**Returns:**
int - VerticalAlignment value.
### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


Gets bottom margin of artifact. If position is specified explicitly (in Position property) this value is ignored.

**Returns:**
double - bottom margin.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContents() {#getContents--}
```
public List<Operator> getContents()
```


Gets collection of artifact internal operators.

**Returns:**
java.util.List<com.aspose.pdf.Operator> - list artifact internal operators.
### getCustomSubtype() {#getCustomSubtype--}
```
public String getCustomSubtype()
```


Gets name of artifact subtype. May be used if artifact subtype is not standard subtype.

**Returns:**
java.lang.String - String value
### getCustomType() {#getCustomType--}
```
public String getCustomType()
```


Gets name of artifact type. May be used if artifact type is non standard.

**Returns:**
java.lang.String - String artifact name
### getForm() {#getForm--}
```
public XForm getForm()
```


Gets XForm of the artifact (if XForm is used).

**Returns:**
[XForm](../../com.aspose.pdf/xform) - XForm object
### getImage() {#getImage--}
```
public XImage getImage()
```


Gets image of the artifact (if presents).

**Returns:**
[XImage](../../com.aspose.pdf/ximage) - XImage object
### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


Gets left margin of artifact. If position is specified explicitly (in Position property) this value is ignored.

**Returns:**
double - left margin of artifact.
### getLines() {#getLines--}
```
public final List<String> getLines()
```


Lines of multiline text artifact.

**Returns:**
java.util.List<java.lang.String> - List of Strings
### getOpacity() {#getOpacity--}
```
public double getOpacity()
```


Gets opacity of the artifact. Possible values are in range 0..1.

**Returns:**
double - opacity of the artifact.
### getPosition() {#getPosition--}
```
public Point getPosition()
```


Gets artifact position. If this property is specified, then margins and alignments are ignored.

**Returns:**
[Point](../../com.aspose.pdf/point) - artifact position.
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Gets rectangle of the artifact.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle object
### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


Gets right margin of artifact. If position is specified explicitly (in Position property) this value is ignored.

**Returns:**
double - right margin of artifact.
### getRotation() {#getRotation--}
```
public double getRotation()
```


Gets artifact rotation angle.

**Returns:**
double - artifact rotation angle.
### getSubtype() {#getSubtype--}
```
public int getSubtype()
```


Gets artifact subtype. If artifact has non-standard subtype, name of the subtype may be read via CustomSubtype.

**Returns:**
int - artifact subtype.
### getText() {#getText--}
```
public String getText()
```


Gets text of the artifact.

**Returns:**
java.lang.String - String value
### getTextState() {#getTextState--}
```
public final TextState getTextState()
```


Text state for artifact text.

**Returns:**
[TextState](../../com.aspose.pdf/textstate) - TextState instance
### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


Gets top margin of artifact. If position is specified explicitly (in Position property) this value is ignored.

**Returns:**
double - top margin of artifact.
### getType() {#getType--}
```
public int getType()
```


Gets artifact type.

**Returns:**
int - artifact type value.
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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isBackground() {#isBackground--}
```
public boolean isBackground()
```


If true Artifact is placed behind page contents.

**Returns:**
boolean - boolean value
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeValue(String name) {#removeValue-java.lang.String-}
```
public void removeValue(String name)
```


Remove custom value from the artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of custom value to be removed. |

### saveUpdates() {#saveUpdates--}
```
public void saveUpdates()
```


Saves all updates in artifact which were made after BeginUpdates() call.

### setArtifactHorizontalAlignment(int value) {#setArtifactHorizontalAlignment-int-}
```
public void setArtifactHorizontalAlignment(int value)
```


Gets horizontal alignment of artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | horizontal alignment of artifact. |

### setArtifactVerticalAlignment(int value) {#setArtifactVerticalAlignment-int-}
```
public void setArtifactVerticalAlignment(int value)
```


Sets vertical alignment of artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | vertical alignment of artifact. |

### setBackground(boolean value) {#setBackground-boolean-}
```
public void setBackground(boolean value)
```


If true Artifact is placed behind page contents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setBottomMargin(double value) {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```


Sets bottom margin of artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | bottom margin. |

### setCustomSubtype(String value) {#setCustomSubtype-java.lang.String-}
```
public void setCustomSubtype(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setCustomType(String value) {#setCustomType-java.lang.String-}
```
public void setCustomType(String value)
```


Sets name of artifact type. May be used if artifact type is non standard.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String artifact name |

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

### setLeftMargin(double value) {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```


Sets left margin of artifact. If position is specified explicitly (in Position property) this value is ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | left margin of artifact. |

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

### setOpacity(double value) {#setOpacity-double-}
```
public void setOpacity(double value)
```


Sets opacity of the artifact. Possible values are in range 0..1.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | opacity of the artifact. |

### setPdfPage(Page page) {#setPdfPage-com.aspose.pdf.Page-}
```
public void setPdfPage(Page page)
```


Sets PDF page which is placed on the document page as artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page which is placed as Artifcact. |

### setPosition(Point value) {#setPosition-com.aspose.pdf.Point-}
```
public void setPosition(Point value)
```


Sets artifact position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.pdf/point) | artifact position. |

### setRightMargin(double value) {#setRightMargin-double-}
```
public void setRightMargin(double value)
```


Sets right margin of artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | right margin of artifact. |

### setRotation(double value) {#setRotation-double-}
```
public void setRotation(double value)
```


Sets artifact rotation angle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | artifact rotation angle. |

### setSubtype(int value) {#setSubtype-int-}
```
public void setSubtype(int value)
```


Sets artifact subtype. If artifact has non-standard subtype, name of the subtype may be read via CustomSubtype.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | artifact subtype. |

### setText(FormattedText formattedText) {#setText-com.aspose.pdf.facades.FormattedText-}
```
public void setText(FormattedText formattedText)
```


Sets text of the artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | FormattedText object which contains artifact text. |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Sets text of the artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

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

### setTextState(TextState value) {#setTextState-com.aspose.pdf.TextState-}
```
public final void setTextState(TextState value)
```


Text state for artifact text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | TextState instance |

### setTopMargin(double value) {#setTopMargin-double-}
```
public void setTopMargin(double value)
```


Sets top margin of artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | top margin of artifact. |

### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Sets artifact type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | artifact type. |

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

