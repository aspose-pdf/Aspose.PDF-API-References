---
title: ContentsAppender
second_title: Aspose.PDF for Java API Reference
description: Performs contents modifications in APPEND mode only.
type: docs
weight: 73
url: /java/com.aspose.pdf/contentsappender/
---
**Inheritance:**
java.lang.Object
```
public class ContentsAppender
```

Performs contents modifications in APPEND mode only. this mode allows to avoid unneeded and heavy contents parsing before some change is made to the contents. It only appends new operators to the end or to the begin of the contents
## Constructors

| Constructor | Description |
| --- | --- |
| [ContentsAppender(Page page)](#ContentsAppender-com.aspose.pdf.Page-) | Initializez new instance of the contents appender with page attached |
| [ContentsAppender(XForm form)](#ContentsAppender-com.aspose.pdf.XForm-) | Initializes new instanse of the contets appender with Form XObject. |
## Methods

| Method | Description |
| --- | --- |
| [appendToBegin(System.Collections.Generic.List<Operator> operators)](#appendToBegin-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.Operator--) | Appends operators to the end of the contents |
| [appendToBegin(Operator op)](#appendToBegin-com.aspose.pdf.Operator-) | Appends operator to the end of the contents |
| [appendToBegin(Operator[] operators)](#appendToBegin-com.aspose.pdf.Operator---) | Appends operators to the end of the contents |
| [appendToEnd(System.Collections.Generic.List<Operator> operators)](#appendToEnd-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.Operator--) | Appends operators to the begin of the contents |
| [appendToEnd(Operator op)](#appendToEnd-com.aspose.pdf.Operator-) | Appends operator to the begin of the contents |
| [appendToEnd(Operator[] operators)](#appendToEnd-com.aspose.pdf.Operator---) | Appends operators to the begin of the contents |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBeginCode()](#getBeginCode--) | String containing operators to insert into start of page. |
| [getBeginOperators()](#getBeginOperators--) | returns begin operators |
| [getClass()](#getClass--) |  |
| [getEndCode()](#getEndCode--) | Stirng containing operators to append to the end of page. |
| [getEndOperators()](#getEndOperators--) | returns end operators |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resumeUpdate()](#resumeUpdate--) | resumes document update |
| [setBeginCode(String value)](#setBeginCode-java.lang.String-) | String containing operators to insert into start of page. |
| [setEndCode(String value)](#setEndCode-java.lang.String-) | String containing operators to insert into start of page. |
| [suppressUpdate()](#suppressUpdate--) | Suppresses update contents data The contents is not updated until ResumeUpdate is called |
| [toString()](#toString--) |  |
| [updateData()](#updateData--) | this is new version of UpdateData, which avoid decoding of the existing contents. |
| [updateDataOld()](#updateDataOld--) | Must be called to apply the changes |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ContentsAppender(Page page) {#ContentsAppender-com.aspose.pdf.Page-}
```
public ContentsAppender(Page page)
```


Initializez new instance of the contents appender with page attached

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page object |

### ContentsAppender(XForm form) {#ContentsAppender-com.aspose.pdf.XForm-}
```
public ContentsAppender(XForm form)
```


Initializes new instanse of the contets appender with Form XObject.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| form | [XForm](../../com.aspose.pdf/xform) | XForm object |

### appendToBegin(System.Collections.Generic.List<Operator> operators) {#appendToBegin-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.Operator--}
```
public void appendToBegin(System.Collections.Generic.List<Operator> operators)
```


Appends operators to the end of the contents

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operators | com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> |  List  object |

### appendToBegin(Operator op) {#appendToBegin-com.aspose.pdf.Operator-}
```
public void appendToBegin(Operator op)
```


Appends operator to the end of the contents

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | Operator object |

### appendToBegin(Operator[] operators) {#appendToBegin-com.aspose.pdf.Operator---}
```
public void appendToBegin(Operator[] operators)
```


Appends operators to the end of the contents

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operators | [Operator\[\]](../../com.aspose.pdf/operator) | Operators array |

### appendToEnd(System.Collections.Generic.List<Operator> operators) {#appendToEnd-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.Operator--}
```
public void appendToEnd(System.Collections.Generic.List<Operator> operators)
```


Appends operators to the begin of the contents

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operators | com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> |  List  object |

### appendToEnd(Operator op) {#appendToEnd-com.aspose.pdf.Operator-}
```
public void appendToEnd(Operator op)
```


Appends operator to the begin of the contents

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | Operator object |

### appendToEnd(Operator[] operators) {#appendToEnd-com.aspose.pdf.Operator---}
```
public void appendToEnd(Operator[] operators)
```


Appends operators to the begin of the contents

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operators | [Operator\[\]](../../com.aspose.pdf/operator) | Operators array |

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
### getBeginCode() {#getBeginCode--}
```
public String getBeginCode()
```


String containing operators to insert into start of page.

**Returns:**
java.lang.String - String object
### getBeginOperators() {#getBeginOperators--}
```
public System.Collections.Generic.List<Operator> getBeginOperators()
```


returns begin operators

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> -  List  object
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEndCode() {#getEndCode--}
```
public String getEndCode()
```


Stirng containing operators to append to the end of page.

**Returns:**
java.lang.String - String object
### getEndOperators() {#getEndOperators--}
```
public System.Collections.Generic.List<Operator> getEndOperators()
```


returns end operators

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> -  List  object
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




### resumeUpdate() {#resumeUpdate--}
```
public void resumeUpdate()
```


resumes document update

### setBeginCode(String value) {#setBeginCode-java.lang.String-}
```
public void setBeginCode(String value)
```


String containing operators to insert into start of page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

### setEndCode(String value) {#setEndCode-java.lang.String-}
```
public void setEndCode(String value)
```


String containing operators to insert into start of page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

### suppressUpdate() {#suppressUpdate--}
```
public void suppressUpdate()
```


Suppresses update contents data The contents is not updated until ResumeUpdate is called

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateData() {#updateData--}
```
public void updateData()
```


this is new version of UpdateData, which avoid decoding of the existing contents.

### updateDataOld() {#updateDataOld--}
```
public void updateDataOld()
```


Must be called to apply the changes

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

