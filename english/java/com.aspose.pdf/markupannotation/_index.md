---
title: MarkupAnnotation
second_title: Aspose.PDF for Java API Reference
description: Abstract class representing markup annotation.
type: docs
weight: 2870
url: /java/com.aspose.pdf/markupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class MarkupAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

Abstract class representing markup annotation.

## Constructors

| Constructor | Description |
| --- | --- |
| [MarkupAnnotation](#MarkupAnnotation--) | Constructor |
| [MarkupAnnotation](#MarkupAnnotation-com.aspose.pdf.IDocument-) | Constructor |

## Methods

| Method | Description |
| --- | --- |
| [clearState](#clearState--) | Clears state and state model for the annotation. For example, clears the review status for an annotation. Note, the state stored in other text annotation which has state and statemodel keys. |
| [getCreationDate](#getCreationDate--) | Gets date and time when annotation was created. |
| [getInReplyTo](#getInReplyTo--) | A reference to the annotation that this annotation is "in reply to". Both annotations must be on the same page of the document. |
| [getOpacity](#getOpacity--) | Gets the constant opacity value to be used in painting the annotation. |
| [getPopup](#getPopup--) | Pop-up annotation for entering or editing the text associated with this annotation. |
| [getReplyType](#getReplyType--) | A string specifying the relationship (the "reply type") between this annotation and one specified by InReplyTo. |
| [getRichText](#getRichText--) | Gets a rich text string to be displayed in the pop-up window when the annotation is opened. |
| [getRichText](#getRichText-com.aspose.pdf.engine.data.IPdfDictionary-) | Gets a rich text string to be displayed in the pop-up window when the annotation is opened. |
| [getState](#getState--) | Gets the state of the annotation. Note, the state stored in other text annotation which has state and statemodel keys. |
| [getStateModel](#getStateModel--) | Gets the state model of the annotation. Note, the state stored in other text annotation which has state and statemodel keys. |
| [getSubject](#getSubject--) | Gets text representing description of the object. |
| [getTitle](#getTitle--) | Gets a text label that shall be displayed in the title bar of the annotationпїЅs popup window when open and active. This entry shall identify the user who added the annotation. |
| [setCreationDate](#setCreationDate-java.util.Date-) | Gets date and time when annotation was created. |
| [setInReplyTo](#setInReplyTo-com.aspose.pdf.Annotation-) | A reference to the annotation that this annotation is "in reply to". Both annotations must be on the same page of the document. |
| [setMarkedState](#setMarkedState-boolean-) | Sets Marked and Unmarked state for the annotation. Note, the state stored in other text annotation which has state and statemodel keys. |
| [setOpacity](#setOpacity-double-) | Sets the constant opacity value to be used in painting the annotation. |
| [setPopup](#setPopup-com.aspose.pdf.PopupAnnotation-) | Pop-up annotation for entering or editing the text associated with this annotation. |
| [setReplyType](#setReplyType-com.aspose.pdf.ReplyType-) | A string specifying the relationship (the "reply type") between this annotation and one specified by InReplyTo. |
| [setReviewState](#setReviewState-com.aspose.pdf.AnnotationState-) | Sets the review state for an annotation. Marked and Unmarked states are ignored as they do not belong to the Review StateModel. The state is set by the user who created the target annotation. The value is taken from the Title property of the target annotation. Note, the state stored in other text annotation which has state and statemodel keys. |
| [setReviewState](#setReviewState-com.aspose.pdf.AnnotationState-java.lang.String-) | Sets the review state for an annotation. Marked and Unmarked states are ignored as they do not belong to the Review StateModel. Note, the state stored in other text annotation which has state and statemodel keys. |
| [setRichText](#setRichText-java.lang.String-) | Sets a rich text string to be displayed in the pop-up window when the annotation is opened. |
| [setSubject](#setSubject-java.lang.String-) | Sets text representing desciption of the object. |
| [setTitle](#setTitle-java.lang.String-) | Sets a text label that shall be displayed in the title bar of the annotationпїЅs popup window when open and active. This entry shall identify the user who added the annotation. |

### MarkupAnnotation {#MarkupAnnotation--}
```
public MarkupAnnotation()
```

Constructor

### MarkupAnnotation {#MarkupAnnotation-com.aspose.pdf.IDocument-}
Constructor

### clearState {#clearState--}
```
public final void clearState()
```

Clears state and state model for the annotation. For example, clears the review status for an annotation. Note, the state stored in other text annotation which has state and statemodel keys.

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

Gets date and time when annotation was created.

**Returns:**
Date object

### getInReplyTo {#getInReplyTo--}
```
public Annotation getInReplyTo()
```

A reference to the annotation that this annotation is "in reply to". Both annotations must be on the same page of the document.

**Returns:**
Annotation value

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

Gets the constant opacity value to be used in painting the annotation.

**Returns:**
double value

### getPopup {#getPopup--}
```
public PopupAnnotation getPopup()
```

Pop-up annotation for entering or editing the text associated with this annotation.

**Returns:**
PopupAnnotation value

### getReplyType {#getReplyType--}
```
public ReplyType getReplyType()
```

A string specifying the relationship (the "reply type") between this annotation and one specified by InReplyTo.

**Returns:**
ReplyType value @see ReplyType

### getRichText {#getRichText--}
```
public final String getRichText()
```

Gets a rich text string to be displayed in the pop-up window when the annotation is opened.

**Returns:**
String value

### getRichText {#getRichText-com.aspose.pdf.engine.data.IPdfDictionary-}
Gets a rich text string to be displayed in the pop-up window when the annotation is opened.

**Returns:**
String value

### getState {#getState--}
```
public final AnnotationState getState()
```

Gets the state of the annotation. Note, the state stored in other text annotation which has state and statemodel keys.

**Returns:**
Annotation state.

### getStateModel {#getStateModel--}
```
public final AnnotationStateModel getStateModel()
```

Gets the state model of the annotation. Note, the state stored in other text annotation which has state and statemodel keys.

**Returns:**
Annotation state model.

### getSubject {#getSubject--}
```
public String getSubject()
```

Gets text representing description of the object.

**Returns:**
String value

### getTitle {#getTitle--}
```
public String getTitle()
```

Gets a text label that shall be displayed in the title bar of the annotationпїЅs popup window when open and active. This entry shall identify the user who added the annotation.

**Returns:**
String value

### setCreationDate {#setCreationDate-java.util.Date-}
Gets date and time when annotation was created.

### setInReplyTo {#setInReplyTo-com.aspose.pdf.Annotation-}
A reference to the annotation that this annotation is "in reply to". Both annotations must be on the same page of the document.

### setMarkedState {#setMarkedState-boolean-}
```
public final void setMarkedState(boolean marked)
```

Sets Marked and Unmarked state for the annotation. Note, the state stored in other text annotation which has state and statemodel keys.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| marked |  | True if sets Marked state, and false if sets Unmarked state. |

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

Sets the constant opacity value to be used in painting the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setPopup {#setPopup-com.aspose.pdf.PopupAnnotation-}
Pop-up annotation for entering or editing the text associated with this annotation.

### setReplyType {#setReplyType-com.aspose.pdf.ReplyType-}
A string specifying the relationship (the "reply type") between this annotation and one specified by InReplyTo.

### setReviewState {#setReviewState-com.aspose.pdf.AnnotationState-}
Sets the review state for an annotation. Marked and Unmarked states are ignored as they do not belong to the Review StateModel. The state is set by the user who created the target annotation. The value is taken from the Title property of the target annotation. Note, the state stored in other text annotation which has state and statemodel keys.

### setReviewState {#setReviewState-com.aspose.pdf.AnnotationState-java.lang.String-}
Sets the review state for an annotation. Marked and Unmarked states are ignored as they do not belong to the Review StateModel. Note, the state stored in other text annotation which has state and statemodel keys.

### setRichText {#setRichText-java.lang.String-}
Sets a rich text string to be displayed in the pop-up window when the annotation is opened.

### setSubject {#setSubject-java.lang.String-}
Sets text representing desciption of the object.

### setTitle {#setTitle-java.lang.String-}
Sets a text label that shall be displayed in the title bar of the annotationпїЅs popup window when open and active. This entry shall identify the user who added the annotation.
