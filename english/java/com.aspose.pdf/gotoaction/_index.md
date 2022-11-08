---
title: GoToAction
second_title: Aspose.PDF for Java API Reference
description: Represents a go-to action that changes the view to a specified destination page location and magnification factor.
type: docs
weight: 144
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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDestination()](#getDestination--) | Gets the destination to jump to. |
| [getNext()](#getNext--) | Next actions in sequence. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDestination(IAppointment value)](#setDestination-com.aspose.pdf.IAppointment-) | Sets the destination to jump to. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDestination() {#getDestination--}
```
public IAppointment getDestination()
```


Gets the destination to jump to.

**Returns:**
[IAppointment](../../com.aspose.pdf/iappointment) - IAppointment value
### getNext() {#getNext--}
```
public ActionCollection getNext()
```


Next actions in sequence.

**Returns:**
[ActionCollection](../../com.aspose.pdf/actioncollection) - ActionCollection object
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDestination(IAppointment value) {#setDestination-com.aspose.pdf.IAppointment-}
```
public void setDestination(IAppointment value)
```


Sets the destination to jump to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAppointment](../../com.aspose.pdf/iappointment) | IAppointment value |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

