---
title: GoToAction
second_title: Aspose.PDF for Java API Reference
description: Represents a go-to action that changes the view to a specified destination page location and magnification factor.
type: docs
weight: 122
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
| [GoToAction(int page)](#GoToAction-int-) | Constructor. |
| [GoToAction(Page page)](#GoToAction-com.aspose.pdf.Page-) | Constructor. |
| [GoToAction(Page page, int type, double[] values)](#GoToAction-com.aspose.pdf.Page-int-double...-) |  |
| [GoToAction(ExplicitDestination destination)](#GoToAction-com.aspose.pdf.ExplicitDestination-) | Constructor. |
| [GoToAction()](#GoToAction--) | Constructor. |
## Methods

| Method | Description |
| --- | --- |
| [getDestination()](#getDestination--) | Gets the destination to jump to. |
| [setDestination(IAppointment value)](#setDestination-com.aspose.pdf.IAppointment-) | Sets the destination to jump to. |
### GoToAction(int page) {#GoToAction-int-}
```
public GoToAction(int page)
```


Constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | int |  |

### GoToAction(Page page) {#GoToAction-com.aspose.pdf.Page-}
```
public GoToAction(Page page)
```


Constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Aspose.Pdf.Page destination object to jump to. |

### GoToAction(Page page, int type, double[] values) {#GoToAction-com.aspose.pdf.Page-int-double...-}
```
public GoToAction(Page page, int type, double[] values)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) |  |
| type | int |  |
| values | double[] |  |

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

### getDestination() {#getDestination--}
```
public IAppointment getDestination()
```


Gets the destination to jump to.

**Returns:**
[IAppointment](../../com.aspose.pdf/iappointment)
### setDestination(IAppointment value) {#setDestination-com.aspose.pdf.IAppointment-}
```
public void setDestination(IAppointment value)
```


Sets the destination to jump to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAppointment](../../com.aspose.pdf/iappointment) |  |

