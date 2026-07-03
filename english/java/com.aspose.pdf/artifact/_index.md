---
title: Artifact
linktitle: Artifact
second_title: Aspose.PDF for Java API Reference
description: Class represents PDF Artifact object.
type: docs
weight: 190
url: /java/com.aspose.pdf/artifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public class Artifact extends Object implements com.aspose.ms.System.IDisposable, Closeable
```

Class represents PDF Artifact object.

## Constructors

| Constructor | Description |
| --- | --- |
| [Artifact](#Artifact-com.aspose.pdf.Artifact.ArtifactType-com.aspose.pdf.Artifact.ArtifactSubtype-) | Constructor of artifact with specified type and subtype |
| [Artifact](#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Artifact.ArtifactContext-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.engine.data.IPdfDictionary-) | This constructor is used when artifact is read from the page. |
| [Artifact](#Artifact-java.lang.String-java.lang.String-) | Constructor of artifact with specified type and subtype |

## Methods

| Method | Description |
| --- | --- |
| [beginUpdates](#beginUpdates--) | Start deleted updates. Use this feature if you need make several changes to the same artifact to improve performance. Usually artifact operators are changed any time when artifact property was changed. This causes changing of page contents every time when artifact was changed. To avoid this effect put all artifact updates between StartUpdates/SaveUpdates calls. This allows to change page contents only once. Artifact art = doc.getPages().get_Item(1).getArtifacts().get_Item(1); art.beginUpdates(); art.setOpacity ( 0.3f); art.setPosition ( new Point(10,10)); art.setRotation (30); art.saveUpdates(); |
| [close](#close--) | Closes all resources used by this document. |
| [dispose](#dispose--) | Dispose the artifact. This method is obsolete, use close() instead. |
| [getArtifactHorizontalAlignment](#getArtifactHorizontalAlignment--) | Gets horizontal alignment of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [getArtifactVerticalAlignment](#getArtifactVerticalAlignment--) | Gets vertical alignment of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [getBottomMargin](#getBottomMargin--) | Gets bottom margin of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [getContents](#getContents--) | Gets collection of artifact internal operators. |
| [getCustomSubtype](#getCustomSubtype--) | Gets name of artifact subtype. May be used if artifact subtype is not standard subtype. |
| [getCustomType](#getCustomType--) | Gets name of artifact type. May be used if artifact type is non standard. |
| [getForm](#getForm--) | Gets XForm of the artifact (if XForm is used). |
| [getImage](#getImage--) | Gets image of the artifact (if presents). |
| [getLeftMargin](#getLeftMargin--) | Gets left margin of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [getLines](#getLines--) | Lines of multiline text artifact. |
| [getOpacity](#getOpacity--) | Gets opacity of the artifact. Possible values are in range 0..1. |
| [getPosition](#getPosition--) | Gets artifact position. If this property is specified, then margins and alignments are ignored. |
| [getRectangle](#getRectangle--) | Gets rectangle of the artifact. |
| [getRightMargin](#getRightMargin--) | Gets right margin of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [getRotation](#getRotation--) | Gets artifact rotation angle. |
| [getSubtype](#getSubtype--) | Gets artifact subtype. If artifact has non-standard subtype, name of the subtype may be read via CustomSubtype. |
| [getText](#getText--) | Gets text of the artifact. |
| [getTextState](#getTextState--) | Text state for artifact text. |
| [getTopMargin](#getTopMargin--) | Gets top margin of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [getType](#getType--) | Gets artifact type. |
| [getValue](#getValue-java.lang.String-) | Gets custom value of artifact. |
| [isBackground](#isBackground--) | If true Artifact is placed behind page contents. |
| [removeValue](#removeValue-java.lang.String-) | Remove custom value from the artifact. |
| [saveUpdates](#saveUpdates--) | Saves all updates in artifact which were made after BeginUpdates() call. |
| [setArtifactHorizontalAlignment](#setArtifactHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Gets horizontal alignment of artifact. |
| [setArtifactVerticalAlignment](#setArtifactVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Sets vertical alignment of artifact. |
| [setBackground](#setBackground-boolean-) | If true Artifact is placed behind page contents. |
| [setBottomMargin](#setBottomMargin-double-) | Sets bottom margin of artifact. |
| [setCustomSubtype](#setCustomSubtype-java.lang.String-) |  |
| [setCustomType](#setCustomType-java.lang.String-) | Sets name of artifact type. May be used if artifact type is non standard. |
| [setImage](#setImage-java.io.InputStream-) | Sets image of the artifact. |
| [setImage](#setImage-java.lang.String-) | Sets image of the artifact. |
| [setLeftMargin](#setLeftMargin-double-) | Sets left margin of artifact. If position is specified explicitly (in Position property) this value is ignored. |
| [setLinesAndState](#setLinesAndState-java.lang.String:A-com.aspose.pdf.TextState-) | Set text and text properties of the artifact. Allows to specify multiple lines. |
| [setOpacity](#setOpacity-double-) | Sets opacity of the artifact. Possible values are in range 0..1. |
| [setPageNumberReplacementString](#setPageNumberReplacementString-java.lang.String-) | Sets what string will be replaced with the page number. The default value is #. |
| [setPdfPage](#setPdfPage-com.aspose.pdf.Page-) | Sets PDF page which is placed on the document page as artifact. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Sets artifact position. |
| [setRightMargin](#setRightMargin-double-) | Sets right margin of artifact. |
| [setRotation](#setRotation-double-) | Sets artifact rotation angle. |
| [setSubtype](#setSubtype-com.aspose.pdf.Artifact.ArtifactSubtype-) | Sets artifact subtype. |
| [setText](#setText-com.aspose.pdf.facades.FormattedText-) | Sets text of the artifact. |
| [setText](#setText-java.lang.String-) | Sets text of the artifact. |
| [setTextAndState](#setTextAndState-java.lang.String-com.aspose.pdf.TextState-) | Set text and text properties of the artifact. |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | Text state for artifact text. |
| [setTopMargin](#setTopMargin-double-) | Sets top margin of artifact. |
| [setType](#setType-com.aspose.pdf.Artifact.ArtifactType-) | Sets artifact type. |
| [setValue](#setValue-java.lang.String-java.lang.String-) | Sets custom value of artifact. |

### Artifact {#Artifact-com.aspose.pdf.Artifact.ArtifactType-com.aspose.pdf.Artifact.ArtifactSubtype-}
Constructor of artifact with specified type and subtype

### Artifact {#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Artifact.ArtifactContext-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.engine.data.IPdfDictionary-}
This constructor is used when artifact is read from the page.

### Artifact {#Artifact-java.lang.String-java.lang.String-}
Constructor of artifact with specified type and subtype

### beginUpdates {#beginUpdates--}
```
public void beginUpdates()
```

Start deleted updates. Use this feature if you need make several changes to the same artifact to improve performance. Usually artifact operators are changed any time when artifact property was changed. This causes changing of page contents every time when artifact was changed. To avoid this effect put all artifact updates between StartUpdates/SaveUpdates calls. This allows to change page contents only once. Artifact art = doc.getPages().get_Item(1).getArtifacts().get_Item(1); art.beginUpdates(); art.setOpacity ( 0.3f); art.setPosition ( new Point(10,10)); art.setRotation (30); art.saveUpdates();

### close {#close--}
```
public void close()
```

Closes all resources used by this document.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Dispose the artifact. This method is obsolete, use close() instead.

### getArtifactHorizontalAlignment {#getArtifactHorizontalAlignment--}
```
public HorizontalAlignment getArtifactHorizontalAlignment()
```

Gets horizontal alignment of artifact. If position is specified explicitly (in Position property) this value is ignored.

**Returns:**
HorizontalAlignment value @see HorizontalAlignment

### getArtifactVerticalAlignment {#getArtifactVerticalAlignment--}
```
public VerticalAlignment getArtifactVerticalAlignment()
```

Gets vertical alignment of artifact. If position is specified explicitly (in Position property) this value is ignored.

**Returns:**
VerticalAlignment value. @see VerticalAlignment

### getBottomMargin {#getBottomMargin--}
```
public double getBottomMargin()
```

Gets bottom margin of artifact. If position is specified explicitly (in Position property) this value is ignored.

**Returns:**
bottom margin.

### getContents {#getContents--}
```
public List < Operator > getContents()
```

Gets collection of artifact internal operators.

**Returns:**
list artifact internal operators.

### getCustomSubtype {#getCustomSubtype--}
```
public String getCustomSubtype()
```

Gets name of artifact subtype. May be used if artifact subtype is not standard subtype.

**Returns:**
String value

### getCustomType {#getCustomType--}
```
public String getCustomType()
```

Gets name of artifact type. May be used if artifact type is non standard.

**Returns:**
String artifact name

### getForm {#getForm--}
```
public XForm getForm()
```

Gets XForm of the artifact (if XForm is used).

**Returns:**
XForm object

### getImage {#getImage--}
```
public XImage getImage()
```

Gets image of the artifact (if presents).

**Returns:**
XImage object

### getLeftMargin {#getLeftMargin--}
```
public double getLeftMargin()
```

Gets left margin of artifact. If position is specified explicitly (in Position property) this value is ignored.

**Returns:**
left margin of artifact.

### getLines {#getLines--}
```
public final List < String > getLines()
```

Lines of multiline text artifact.

**Returns:**
List of Strings

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

Gets opacity of the artifact. Possible values are in range 0..1.

**Returns:**
opacity of the artifact.

### getPosition {#getPosition--}
```
public Point getPosition()
```

Gets artifact position. If this property is specified, then margins and alignments are ignored.

**Returns:**
artifact position.

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Gets rectangle of the artifact.

**Returns:**
Rectangle object

### getRightMargin {#getRightMargin--}
```
public double getRightMargin()
```

Gets right margin of artifact. If position is specified explicitly (in Position property) this value is ignored.

**Returns:**
right margin of artifact.

### getRotation {#getRotation--}
```
public double getRotation()
```

Gets artifact rotation angle.

**Returns:**
artifact rotation angle.

### getSubtype {#getSubtype--}
```
public Artifact.ArtifactSubtype getSubtype()
```

Gets artifact subtype. If artifact has non-standard subtype, name of the subtype may be read via CustomSubtype.

**Returns:**
artifact subtype. @see ArtifactSubtype

### getText {#getText--}
```
public String getText()
```

Gets text of the artifact.

**Returns:**
String value

### getTextState {#getTextState--}
```
public final TextState getTextState()
```

Text state for artifact text.

**Returns:**
TextState instance

### getTopMargin {#getTopMargin--}
```
public double getTopMargin()
```

Gets top margin of artifact. If position is specified explicitly (in Position property) this value is ignored.

**Returns:**
top margin of artifact.

### getType {#getType--}
```
public Artifact.ArtifactType getType()
```

Gets artifact type.

**Returns:**
artifact type value. @see ArtifactType

### getValue {#getValue-java.lang.String-}
Gets custom value of artifact.

### isBackground {#isBackground--}
```
public boolean isBackground()
```

If true Artifact is placed behind page contents.

**Returns:**
boolean value

### removeValue {#removeValue-java.lang.String-}
Remove custom value from the artifact.

### saveUpdates {#saveUpdates--}
```
public void saveUpdates()
```

Saves all updates in artifact which were made after BeginUpdates() call.

### setArtifactHorizontalAlignment {#setArtifactHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Gets horizontal alignment of artifact.

### setArtifactVerticalAlignment {#setArtifactVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Sets vertical alignment of artifact.

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

If true Artifact is placed behind page contents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setBottomMargin {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```

Sets bottom margin of artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | bottom margin. |

### setCustomSubtype {#setCustomSubtype-java.lang.String-}


### setCustomType {#setCustomType-java.lang.String-}
Sets name of artifact type. May be used if artifact type is non standard.

### setImage {#setImage-java.io.InputStream-}
Sets image of the artifact.

### setImage {#setImage-java.lang.String-}
Sets image of the artifact.

### setLeftMargin {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```

Sets left margin of artifact. If position is specified explicitly (in Position property) this value is ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | left margin of artifact. |

### setLinesAndState {#setLinesAndState-java.lang.String:A-com.aspose.pdf.TextState-}
Set text and text properties of the artifact. Allows to specify multiple lines.

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

Sets opacity of the artifact. Possible values are in range 0..1.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | opacity of the artifact. |

### setPageNumberReplacementString {#setPageNumberReplacementString-java.lang.String-}
Sets what string will be replaced with the page number. The default value is #.

### setPdfPage {#setPdfPage-com.aspose.pdf.Page-}
Sets PDF page which is placed on the document page as artifact.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Sets artifact position.

### setRightMargin {#setRightMargin-double-}
```
public void setRightMargin(double value)
```

Sets right margin of artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | right margin of artifact. |

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

Sets artifact rotation angle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | artifact rotation angle. |

### setSubtype {#setSubtype-com.aspose.pdf.Artifact.ArtifactSubtype-}
Sets artifact subtype.

### setText {#setText-com.aspose.pdf.facades.FormattedText-}
Sets text of the artifact.

### setText {#setText-java.lang.String-}
Sets text of the artifact.

### setTextAndState {#setTextAndState-java.lang.String-com.aspose.pdf.TextState-}
Set text and text properties of the artifact.

### setTextState {#setTextState-com.aspose.pdf.TextState-}
Text state for artifact text.

### setTopMargin {#setTopMargin-double-}
```
public void setTopMargin(double value)
```

Sets top margin of artifact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | top margin of artifact. |

### setType {#setType-com.aspose.pdf.Artifact.ArtifactType-}
Sets artifact type.

### setValue {#setValue-java.lang.String-java.lang.String-}
Sets custom value of artifact.
