---
title: Artifact
second_title: Aspose.PDF for Java API Reference
description: 
type: docs
weight: 26
url: /java/com.aspose.pdf/artifact/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public class Artifact implements System.IDisposable
```
## Constructors

| Constructor | Description |
| --- | --- |
| [Artifact(ArtifactCollection owner, Resources resources, Matrix matrix, System.Collections.ArrayList _contents, IPdfDictionary _properties)](#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Resources-com.aspose.pdf.Matrix-com.aspose.ms.System.Collections.ArrayList-com.aspose.pdf.engine.data.IPdfDictionary-) | This constructor is used when artifact is read from the page. |
| [Artifact(String type, String subType)](#Artifact-java.lang.String-java.lang.String-) | Constructor of artifact with specified type and subtype |
| [Artifact(int type, int subType)](#Artifact-int-int-) | Constructor of artifact with specified type and subtype |
## Methods

| Method | Description |
| --- | --- |
| [getCustomType()](#getCustomType--) | Gets name of artifact type. |
| [setCustomType(String value)](#setCustomType-java.lang.String-) |  |
| [getCustomSubtype()](#getCustomSubtype--) | Gets name of artifact subtype. |
| [setCustomSubtype(String value)](#setCustomSubtype-java.lang.String-) |  |
| [getType()](#getType--) | Gets artifact type. |
| [setType(int value)](#setType-int-) | Set tpye of the artifact. |
| [getSubtype()](#getSubtype--) | Gets artifact subtype. |
| [setSubtype(int value)](#setSubtype-int-) |  |
| [getContentsInternal()](#getContentsInternal--) | Gets collection of artifact internal operators. |
| [getForm()](#getForm--) | Gets XForm of the artifact (if XForm is used). |
| [getRectangle()](#getRectangle--) | Gets rectangle of the artifact. |
| [getPosition()](#getPosition--) | Gets or sets artifact position. |
| [setPosition(Point value)](#setPosition-com.aspose.pdf.Point-) |  |
| [getRightMargin()](#getRightMargin--) | Right margin of artifact. |
| [setRightMargin(double value)](#setRightMargin-double-) | Sets right margin of the artifact. |
| [getLeftMargin()](#getLeftMargin--) | Left margin of artifact. |
| [setLeftMargin(double value)](#setLeftMargin-double-) | Set left margin of the artifact. |
| [getTopMargin()](#getTopMargin--) | Top margin of artifact. |
| [setTopMargin(double value)](#setTopMargin-double-) | Sets top margin of the artifact. |
| [getBottomMargin()](#getBottomMargin--) | Bottom margin of artifact. |
| [setBottomMargin(double value)](#setBottomMargin-double-) | Sets bottom margin of artifact. |
| [getArtifactHorizontalAlignment()](#getArtifactHorizontalAlignment--) | Horizontal alignment of artifact. |
| [setArtifactHorizontalAlignment(int value)](#setArtifactHorizontalAlignment-int-) | Sets horizontal alignment of the artifact. |
| [getArtifactVerticalAlignment()](#getArtifactVerticalAlignment--) | Vertical alignment of artifact. |
| [setArtifactVerticalAlignment(int value)](#setArtifactVerticalAlignment-int-) | Sets vertical alignment of the artifact. |
| [getRotation()](#getRotation--) | Gets articat rotation angle. |
| [setRotation(double value)](#setRotation-double-) | Sets artifact rotation angle. |
| [getText()](#getText--) | Gets text of the artifact. |
| [setText(String value)](#setText-java.lang.String-) | Sets text of the artifact. |
| [getImage()](#getImage--) | Gets image of the artifact (if presents). |
| [getOpacity()](#getOpacity--) | Gets or sets opacity of the artifact. |
| [setOpacity(double value)](#setOpacity-double-) | Sets opacity of the artifact. |
| [setText(FormattedText formattedText)](#setText-com.aspose.pdf.facades.FormattedText-) | Sets text of the artifact. |
| [setImage(System.IO.Stream imageStream)](#setImage-com.aspose.ms.System.IO.Stream-) | Sets image of the artifact. |
| [setImage(String imageName)](#setImage-java.lang.String-) | Sets image of the artifact. |
| [SetPdfPage(Page page)](#SetPdfPage-com.aspose.pdf.Page-) | Sets PDF page which is placed on the document page as artifact. |
| [dispose()](#dispose--) |  |
| [getValue(String name)](#getValue-java.lang.String-) | Gets custom value of artifact. |
| [setValue(String name, String value)](#setValue-java.lang.String-java.lang.String-) | Sets custom value of artifact. |
| [removeValue(String name)](#removeValue-java.lang.String-) | Remove custom value from the artifact. |
| [beginUpdates()](#beginUpdates--) | Start delated updates. |
| [saveUpdates()](#saveUpdates--) | Saves all updates in artifact which were made after BeginUpdates() call. |
### Artifact(ArtifactCollection owner, Resources resources, Matrix matrix, System.Collections.ArrayList _contents, IPdfDictionary _properties) {#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Resources-com.aspose.pdf.Matrix-com.aspose.ms.System.Collections.ArrayList-com.aspose.pdf.engine.data.IPdfDictionary-}
```
public Artifact(ArtifactCollection owner, Resources resources, Matrix matrix, System.Collections.ArrayList _contents, IPdfDictionary _properties)
```


This constructor is used when artifact is read from the page. ARtifactCollection passes page resources, initial matrix, operators of the artifact ("contents") and properties dictionary.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| owner | [ArtifactCollection](../../com.aspose.pdf/artifactcollection) | ArtifactCollection object |
| resources | [Resources](../../com.aspose.pdf/resources) | Resources object |
| matrix | [Matrix](../../com.aspose.pdf/matrix) |  |
| _contents | com.aspose.ms.System.Collections.ArrayList | Collection of Operators |
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

### Artifact(int type, int subType) {#Artifact-int-int-}
```
public Artifact(int type, int subType)
```


Constructor of artifact with specified type and subtype

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Artifact type. |
| subType | int | Artifact subtype. |

### getCustomType() {#getCustomType--}
```
public String getCustomType()
```


Gets name of artifact type. May be used if artifact type is non standard.

**Returns:**
java.lang.String - Non-standard type or the artifact.
### setCustomType(String value) {#setCustomType-java.lang.String-}
```
public void setCustomType(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCustomSubtype() {#getCustomSubtype--}
```
public String getCustomSubtype()
```


Gets name of artifact subtype. May be used if artifact subtype is not standard subtype.

**Returns:**
java.lang.String - Return non-stnadard subtype of the artifact.
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
public int getType()
```


Gets artifact type.

**Returns:**
int - Type of the artifact.
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Set tpye of the artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | New artifact type. |

### getSubtype() {#getSubtype--}
```
public int getSubtype()
```


Gets artifact subtype. If artifact has non-standard subtype, name of the subtype may be read via CustomSubtype.

**Returns:**
int - Subtype of the artifact.
### setSubtype(int value) {#setSubtype-int-}
```
public void setSubtype(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getContentsInternal() {#getContentsInternal--}
```
public System.Collections.IList getContentsInternal()
```


Gets collection of artifact internal operators.

**Returns:**
com.aspose.ms.System.Collections.IList - Contents of the artifact.
### getForm() {#getForm--}
```
public XForm getForm()
```


Gets XForm of the artifact (if XForm is used).

**Returns:**
[XForm](../../com.aspose.pdf/xform) - Form X-Object of the artifact.
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Gets rectangle of the artifact.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle of the artifact.
### getPosition() {#getPosition--}
```
public Point getPosition()
```


Gets or sets artifact position. If this property is specified, then margins and alignments are ignored.

**Returns:**
[Point](../../com.aspose.pdf/point) - Position of the artifact.
### setPosition(Point value) {#setPosition-com.aspose.pdf.Point-}
```
public void setPosition(Point value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.pdf/point) |  |

### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


Right margin of artifact. If position is specified explicitly (in Position property) this value is ignored.

**Returns:**
double - Right margin of the artifact.
### setRightMargin(double value) {#setRightMargin-double-}
```
public void setRightMargin(double value)
```


Sets right margin of the artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | New value of artifact right margin. |

### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


Left margin of artifact. If position is specified explicitly (in Position property) this value is ignored.

**Returns:**
double - Left margin of the artifact.
### setLeftMargin(double value) {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```


Set left margin of the artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | New left margin of the artifact. |

### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


Top margin of artifact. If position is specified explicitly (in Position property) this value is ignored.

**Returns:**
double - Top margin.
### setTopMargin(double value) {#setTopMargin-double-}
```
public void setTopMargin(double value)
```


Sets top margin of the artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | New value of artifact top margin. |

### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


Bottom margin of artifact. If position is specified explicitly (in Position property) this value is ignored.

**Returns:**
double - Bottom margin of artifact.
### setBottomMargin(double value) {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```


Sets bottom margin of artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | New value of bottom margin of the artifact. |

### getArtifactHorizontalAlignment() {#getArtifactHorizontalAlignment--}
```
public int getArtifactHorizontalAlignment()
```


Horizontal alignment of artifact. If position is specified explicitly (in Position property) this value is ignored.

**Returns:**
int - Horizontal alignment of the artifact.
### setArtifactHorizontalAlignment(int value) {#setArtifactHorizontalAlignment-int-}
```
public void setArtifactHorizontalAlignment(int value)
```


Sets horizontal alignment of the artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | New value of horizontal alignment. |

### getArtifactVerticalAlignment() {#getArtifactVerticalAlignment--}
```
public int getArtifactVerticalAlignment()
```


Vertical alignment of artifact. If position is specified explicitly (in Position property) this value is ignored.

**Returns:**
int - Vertical alignment of the artifact.
### setArtifactVerticalAlignment(int value) {#setArtifactVerticalAlignment-int-}
```
public void setArtifactVerticalAlignment(int value)
```


Sets vertical alignment of the artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | New vertical alignment of the artifact. |

### getRotation() {#getRotation--}
```
public double getRotation()
```


Gets articat rotation angle.

**Returns:**
double - Artifact rotation.
### setRotation(double value) {#setRotation-double-}
```
public void setRotation(double value)
```


Sets artifact rotation angle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | New value of rotation angle. |

### getText() {#getText--}
```
public String getText()
```


Gets text of the artifact.

**Returns:**
java.lang.String - Text of the artifact.
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Sets text of the artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | New text value. |

### getImage() {#getImage--}
```
public XImage getImage()
```


Gets image of the artifact (if presents).

**Returns:**
[XImage](../../com.aspose.pdf/ximage) - Image X-object of the artifact.
### getOpacity() {#getOpacity--}
```
public double getOpacity()
```


Gets or sets opacity of the artifact. Possible values are in range 0..1.

**Returns:**
double - Opacity of the artifact.
### setOpacity(double value) {#setOpacity-double-}
```
public void setOpacity(double value)
```


Sets opacity of the artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | New value of the opacity. |

### setText(FormattedText formattedText) {#setText-com.aspose.pdf.facades.FormattedText-}
```
public void setText(FormattedText formattedText)
```


Sets text of the artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | FormattedText object which contains artifact text. |

### setImage(System.IO.Stream imageStream) {#setImage-com.aspose.ms.System.IO.Stream-}
```
public void setImage(System.IO.Stream imageStream)
```


Sets image of the artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | com.aspose.ms.System.IO.Stream | Stream which contains image data. |

### setImage(String imageName) {#setImage-java.lang.String-}
```
public void setImage(String imageName)
```


Sets image of the artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageName | java.lang.String | Name of image file. |

### SetPdfPage(Page page) {#SetPdfPage-com.aspose.pdf.Page-}
```
public void SetPdfPage(Page page)
```


Sets PDF page which is placed on the document page as artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Value of page. |

### dispose() {#dispose--}
```
public void dispose()
```




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
| value | java.lang.String | Custom value. |

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


Start delated updates. Use this feature if you need make several changes to the same artifact to improve performance. Usually artifact operators are changed anytime when artifact property was changed. This causes changing of page contents everytime when artifact was changed. To avoid this effect put all artifact updates between StartUpdates/SaveUpdates calls. This allows to change page contents only once.

### saveUpdates() {#saveUpdates--}
```
public void saveUpdates()
```


Saves all updates in artifact which were made after BeginUpdates() call.

