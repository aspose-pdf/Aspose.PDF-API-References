---
title: MarkupAnnotation
second_title: Aspose.PDF for Java API Reference
description: Abstract class representing markup annotation.
type: docs
weight: 205
url: /java/com.aspose.pdf/markupannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation)

**All Implemented Interfaces:**
[com.aspose.pdf.engine.ITitledAnnotation](../../com.aspose.pdf.engine/ititledannotation)
```
public abstract class MarkupAnnotation extends Annotation implements ITitledAnnotation
```

Abstract class representing markup annotation.
## Constructors

| Constructor | Description |
| --- | --- |
| [MarkupAnnotation(IDocument document)](#MarkupAnnotation-com.aspose.pdf.IDocument-) | Constructor for markup annotation. |
| [MarkupAnnotation()](#MarkupAnnotation--) | Constructor |
## Methods

| Method | Description |
| --- | --- |
| [getTitle()](#getTitle--) | Gets a text that shall be displayed in title bar of annotation. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Sets a text that shall be displayed in title bar of annotation. |
| [getRichText()](#getRichText--) | Gets a rich text string to be displayed in the pop-up window when the annotation is opened. |
| [setRichText(String value)](#setRichText-java.lang.String-) | Sets a rich text string to be displayed in the pop-up window when the annotation is opened. |
| [getCreationDate()](#getCreationDate--) | Gets date and time when annotation was created. |
| [getSubject()](#getSubject--) | Gets text representing desciption of the object. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Sets text representing desciption of the object. |
| [getPopup()](#getPopup--) | Pop-up annotation for entering or editing the text associated with this annotation. |
| [setPopup(PopupAnnotation value)](#setPopup-com.aspose.pdf.PopupAnnotation-) | Pop-up annotation for entering or editing the text associated with this annotation. |
| [getOpacity()](#getOpacity--) | Gets the constant opacity value to be used in painting the annotation. |
| [setOpacity(double value)](#setOpacity-double-) | Sets the constant opacity value to be used in painting the annotation. |
| [getInReplyTo()](#getInReplyTo--) | A reference to the annotation that this annotation is "in reply to". |
| [setInReplyTo(Annotation value)](#setInReplyTo-com.aspose.pdf.Annotation-) | A reference to the annotation that this annotation is "in reply to". |
| [getReplyType()](#getReplyType--) | A string specifying the relationship (the "reply type") between this annotation and one specified by InReplyTo. |
| [setReplyType(int value)](#setReplyType-int-) | A string specifying the relationship (the "reply type") between this annotation and one specified by InReplyTo. |
### MarkupAnnotation(IDocument document) {#MarkupAnnotation-com.aspose.pdf.IDocument-}
```
public MarkupAnnotation(IDocument document)
```


Constructor for markup annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Document where annotation will be created. |

### MarkupAnnotation() {#MarkupAnnotation--}
```
public MarkupAnnotation()
```


Constructor

### getTitle() {#getTitle--}
```
public String getTitle()
```


Gets a text that shall be displayed in title bar of annotation.

**Returns:**
java.lang.String - String value
### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Sets a text that shall be displayed in title bar of annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getRichText() {#getRichText--}
```
public String getRichText()
```


Gets a rich text string to be displayed in the pop-up window when the annotation is opened.

**Returns:**
java.lang.String - String value
### setRichText(String value) {#setRichText-java.lang.String-}
```
public void setRichText(String value)
```


Sets a rich text string to be displayed in the pop-up window when the annotation is opened.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Gets date and time when annotation was created.

**Returns:**
[Date](../../java.util/date) - Date object
### getSubject() {#getSubject--}
```
public String getSubject()
```


Gets text representing desciption of the object.

**Returns:**
java.lang.String - String value
### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


Sets text representing desciption of the object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getPopup() {#getPopup--}
```
public PopupAnnotation getPopup()
```


Pop-up annotation for entering or editing the text associated with this annotation.

**Returns:**
[PopupAnnotation](../../com.aspose.pdf/popupannotation) - PopupAnnotation value
### setPopup(PopupAnnotation value) {#setPopup-com.aspose.pdf.PopupAnnotation-}
```
public void setPopup(PopupAnnotation value)
```


Pop-up annotation for entering or editing the text associated with this annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PopupAnnotation](../../com.aspose.pdf/popupannotation) | PopupAnnotation value |

### getOpacity() {#getOpacity--}
```
public double getOpacity()
```


Gets the constant opacity value to be used in painting the annotation.

**Returns:**
double - double value
### setOpacity(double value) {#setOpacity-double-}
```
public void setOpacity(double value)
```


Sets the constant opacity value to be used in painting the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getInReplyTo() {#getInReplyTo--}
```
public Annotation getInReplyTo()
```


A reference to the annotation that this annotation is "in reply to". Both annotations must be on the same page of the document.

**Returns:**
[Annotation](../../com.aspose.pdf/annotation) - Annotation value
### setInReplyTo(Annotation value) {#setInReplyTo-com.aspose.pdf.Annotation-}
```
public void setInReplyTo(Annotation value)
```


A reference to the annotation that this annotation is "in reply to". Both annotations must be on the same page of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Annotation](../../com.aspose.pdf/annotation) | Annotation value |

### getReplyType() {#getReplyType--}
```
public int getReplyType()
```


A string specifying the relationship (the "reply type") between this annotation and one specified by InReplyTo.

**Returns:**
int - ReplyType value
### setReplyType(int value) {#setReplyType-int-}
```
public void setReplyType(int value)
```


A string specifying the relationship (the "reply type") between this annotation and one specified by InReplyTo.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ReplyType value |

