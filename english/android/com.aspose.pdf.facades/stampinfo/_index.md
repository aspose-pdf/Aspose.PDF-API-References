---
title: StampInfo
second_title: Aspose.PDF for Java API Reference
description: Class representing stamp information.
type: docs
weight: 52
url: /java/com.aspose.pdf.facades/stampinfo/
---
**Inheritance:**
java.lang.Object
```
public final class StampInfo
```

Class representing stamp information.
## Methods

| Method | Description |
| --- | --- |
| [getStampId()](#getStampId--) | Gets identifier of the stamp. |
| [getIndexOnPage()](#getIndexOnPage--) | Gets stamp index on the page. |
| [getStampType()](#getStampType--) | Gets stamp type (image / form). |
| [getRectangle()](#getRectangle--) | Gets rectangle where stamp is placed. |
| [getForm()](#getForm--) | Gets XForm of the stamp. |
| [getText()](#getText--) | Gets text in the stamp. |
| [getVisible()](#getVisible--) | Gets visibility of stamp. |
### getStampId() {#getStampId--}
```
public int getStampId()
```


Gets identifier of the stamp.

**Returns:**
int
### getIndexOnPage() {#getIndexOnPage--}
```
public int getIndexOnPage()
```


Gets stamp index on the page.

**Returns:**
int
### getStampType() {#getStampType--}
```
public int getStampType()
```


Gets stamp type (image / form).

**Returns:**
int
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Gets rectangle where stamp is placed.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle)
### getForm() {#getForm--}
```
public XForm getForm()
```


Gets XForm of the stamp.

**Returns:**
[XForm](../../com.aspose.pdf/xform)
### getText() {#getText--}
```
public String getText()
```


Gets text in the stamp.

**Returns:**
java.lang.String
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Gets visibility of stamp. If false then stamp is hidden (with HideStampById). Hidden stamp may be restored by ShowStampById.

**Returns:**
boolean
