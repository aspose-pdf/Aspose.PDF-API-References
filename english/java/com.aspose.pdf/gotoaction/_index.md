---
title: GoToAction
second_title: Aspose.PDF for Java API Reference
description: Represents a go-to action that changes the view to a specified destination (page, location, and magnification factor).
type: docs
weight: 1810
url: /java/com.aspose.pdf/gotoaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.GoToAction, com.aspose.pdf.PdfAction, com.aspose.pdf.GoToAction

**All Implemented Interfaces:**
IAppointment

```
public class GoToAction extends PdfAction
```

Represents a go-to action that changes the view to a specified destination (page, location, and magnification factor).

## Constructors

| Constructor | Description |
| --- | --- |
| [GoToAction](#GoToAction--) | Constructor. |
| [GoToAction](#GoToAction-com.aspose.pdf.Document-java.lang.String-) | Constructor. |
| [GoToAction](#GoToAction-com.aspose.pdf.ExplicitDestination-) | Constructor. |
| [GoToAction](#GoToAction-int-) | Constructor for GoToAction class. |
| [GoToAction](#GoToAction-com.aspose.pdf.Page-) | Constructor. |
| [GoToAction](#GoToAction-com.aspose.pdf.Page-com.aspose.pdf.ExplicitDestinationType-double...-) | Constructor. |

## Methods

| Method | Description |
| --- | --- |
| [getDestination](#getDestination--) | Gets the destination to jump to. |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | Sets the destination to jump to. |

### GoToAction {#GoToAction--}
```
@Deprecated public GoToAction()
```

Constructor.

### GoToAction {#GoToAction-com.aspose.pdf.Document-java.lang.String-}
Constructor.

### GoToAction {#GoToAction-com.aspose.pdf.ExplicitDestination-}
Constructor.

### GoToAction {#GoToAction-int-}
```
@Deprecated public GoToAction(int page)
```

Constructor for GoToAction class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page |  | int value |

### GoToAction {#GoToAction-com.aspose.pdf.Page-}
Constructor.

### GoToAction {#GoToAction-com.aspose.pdf.Page-com.aspose.pdf.ExplicitDestinationType-double...-}
Constructor.

### getDestination {#getDestination--}
```
public IAppointment getDestination()
```

Gets the destination to jump to.

**Returns:**
IAppointment value

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
Sets the destination to jump to.
