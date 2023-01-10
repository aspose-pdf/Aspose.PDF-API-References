---
title: GoToAction
second_title: Aspose.PDF for Java API Reference
description: Represents a go-to action that changes the view to a specified destination page location and magnification factor.
type: docs
weight: 145
url: /java/com.aspose.pdf/gotoaction/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.PdfAction](../../com.aspose.pdf/pdfaction)
```
public class GoToAction extends PdfAction
```

Represents a go-to action that changes the view to a specified destination (page, location, and magnification factor).
## Constructors

| Constructor | Description |
| --- | --- |
| [GoToAction(int page)](#GoToAction-int-) | Constructor for GoToAction class. |
| [GoToAction(Page page)](#GoToAction-com.aspose.pdf.Page-) | Constructor for GoToAction class. |
| [GoToAction(Page page, int type, double[] values)](#GoToAction-com.aspose.pdf.Page-int-double...-) | Constructor for GoToAction class. |
| [GoToAction(ExplicitDestination destination)](#GoToAction-com.aspose.pdf.ExplicitDestination-) | Constructor. |
| [GoToAction()](#GoToAction--) | Constructor. |
| [GoToAction(Document doc, String name)](#GoToAction-com.aspose.pdf.Document-java.lang.String-) | Action which linked with Named Destination. |
## Methods

| Method | Description |
| --- | --- |
| [getDestination()](#getDestination--) | Gets the destination to jump to. |
| [setDestination(IAppointment value)](#setDestination-com.aspose.pdf.IAppointment-) | Sets the destination to jump to. |
### GoToAction(int page) {#GoToAction-int-}
```
public GoToAction(int page)
```


Constructor for GoToAction class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | int | int value |

### GoToAction(Page page) {#GoToAction-com.aspose.pdf.Page-}
```
public GoToAction(Page page)
```


Constructor for GoToAction class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page destination object to jump to. |

### GoToAction(Page page, int type, double[] values) {#GoToAction-com.aspose.pdf.Page-int-double...-}
```
public GoToAction(Page page, int type, double[] values)
```


Constructor for GoToAction class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Destination page. |
| type | int | Destination type. |
| values | double[] | Action parameters. |

### GoToAction(ExplicitDestination destination) {#GoToAction-com.aspose.pdf.ExplicitDestination-}
```
public GoToAction(ExplicitDestination destination)
```


Constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destination | [ExplicitDestination](../../com.aspose.pdf/explicitdestination) | Explicit destination. |

### GoToAction() {#GoToAction--}
```
public GoToAction()
```


Constructor.

### GoToAction(Document doc, String name) {#GoToAction-com.aspose.pdf.Document-java.lang.String-}
```
public GoToAction(Document doc, String name)
```


Action which linked with Named Destination.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doc | [Document](../../com.aspose.pdf/document) | Document where action will be created. |
| name | java.lang.String | Name of the destination. |

### getDestination() {#getDestination--}
```
public IAppointment getDestination()
```


Gets the destination to jump to.

**Returns:**
[IAppointment](../../com.aspose.pdf/iappointment) - IAppointment value
### setDestination(IAppointment value) {#setDestination-com.aspose.pdf.IAppointment-}
```
public void setDestination(IAppointment value)
```


Sets the destination to jump to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAppointment](../../com.aspose.pdf/iappointment) | IAppointment value |

