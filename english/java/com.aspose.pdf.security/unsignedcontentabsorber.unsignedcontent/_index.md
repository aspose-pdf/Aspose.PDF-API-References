---
title: UnsignedContentAbsorber.UnsignedContent
linktitle: UnsignedContentAbsorber.UnsignedContent
second_title: Aspose.PDF for Java API Reference
description: Encapsulates unsigned content elements extracted from a PDF document. This class provides access to pages, form fields, XForms, and annotations that are part of the unsigned.
type: docs
weight: 50
url: /java/com.aspose.pdf.security/unsignedcontentabsorber.unsignedcontent/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber.UnsignedContent

```
public static final class UnsignedContentAbsorber.UnsignedContent extends Object
```

Encapsulates unsigned content elements extracted from a PDF document. This class provides access to pages, form fields, XForms, and annotations that are part of the unsigned content within the document.

## Methods

| Method | Description |
| --- | --- |
| [getAnnotations](#getAnnotations--) | Gets a dictionary of modified annotations that may have changed or added. |
| [getForms](#getForms--) | Gets form fields that have been incrementally changed or added. |
| [getPages](#getPages--) | Gets a list of pages whose content is unsigned or has been incrementally changed. The page is considered modified and XForms are not checked and do not appear in the XForms list. |
| [getXForms](#getXForms--) | Gets a dictionary of modified XForm objects that may have changed, although the page itself has not changed (not in the Pages list). |
| [setXForms](#setXForms-java.util.HashMap-) | A dictionary of modified XForm objects that may have changed, although the page itself has not changed (not in the Pages list). |

### getAnnotations {#getAnnotations--}
```
public final HashMap < Integer , Annotation > getAnnotations()
```

Gets a dictionary of modified annotations that may have changed or added.

**Returns:**
a dictionary of modified annotations that may have changed or added.

### getForms {#getForms--}
```
public final List < WidgetAnnotation > getForms()
```

Gets form fields that have been incrementally changed or added.

**Returns:**
form fields that have been incrementally changed or added.

### getPages {#getPages--}
```
public final List < Page > getPages()
```

Gets a list of pages whose content is unsigned or has been incrementally changed. The page is considered modified and XForms are not checked and do not appear in the XForms list.

**Returns:**
a list of pages whose content is unsigned or has been incrementally changed.

### getXForms {#getXForms--}
```
public final HashMap < Integer , XForm > getXForms()
```

Gets a dictionary of modified XForm objects that may have changed, although the page itself has not changed (not in the Pages list).

**Returns:**
a dictionary of modified XForm objects that may have changed, although the page itself has not changed (not in the Pages list).

### setXForms {#setXForms-java.util.HashMap-}
A dictionary of modified XForm objects that may have changed, although the page itself has not changed (not in the Pages list).
