---
title: StampInfo
linktitle: StampInfo
second_title: Aspose.PDF for Java API Reference
description: Class representing stamp information.
type: docs
weight: 710
url: /java/com.aspose.pdf.facades/stampinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.StampInfo

```
public final class StampInfo extends Object
```

Class representing stamp information.

## Methods

| Method | Description |
| --- | --- |
| [getForm](#getForm--) | Gets XForm of the stamp. |
| [getImage](#getImage--) | Gets image of stamp. May be null if stamp does not contain images (for example for text stamp). |
| [getImageInternal](#getImageInternal--) | Gets image of stamp. May be null if stamp does not contain images (for example for text stamp). |
| [getIndexOnPage](#getIndexOnPage--) | Gets stamp index on the page. |
| [getRectangle](#getRectangle--) | Gets rectangle where stamp is placed. |
| [getStampId](#getStampId--) | Gets identifier of the stamp. |
| [getStampType](#getStampType--) | Gets stamp type (image / form). |
| [getText](#getText--) | Gets text in the stamp. |
| [getVisible](#getVisible--) | Gets visibility of stamp. If false then stamp is hidden (with HideStampById). Hidden stamp may be restored by ShowStampById. |

### getForm {#getForm--}
```
public XForm getForm()
```

Gets XForm of the stamp.

**Returns:**
XForm object

### getImage {#getImage--}
```
public BufferedImage getImage()
```

Gets image of stamp. May be null if stamp does not contain images (for example for text stamp).

**Returns:**
BufferedImage object

### getImageInternal {#getImageInternal--}
```
public com.aspose.ms.System.Drawing.Image getImageInternal()
```

Gets image of stamp. May be null if stamp does not contain images (for example for text stamp).

**Returns:**
Image object

### getIndexOnPage {#getIndexOnPage--}
```
public int getIndexOnPage()
```

Gets stamp index on the page.

**Returns:**
int value

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Gets rectangle where stamp is placed.

**Returns:**
Rectangle element

### getStampId {#getStampId--}
```
public int getStampId()
```

Gets identifier of the stamp.

**Returns:**
int value

### getStampType {#getStampType--}
```
public StampType getStampType()
```

Gets stamp type (image / form).

**Returns:**
StampType element @see StampType

### getText {#getText--}
```
public String getText()
```

Gets text in the stamp.

**Returns:**
String value

### getVisible {#getVisible--}
```
public boolean getVisible()
```

Gets visibility of stamp. If false then stamp is hidden (with HideStampById). Hidden stamp may be restored by ShowStampById.

**Returns:**
boolean value
