---
title: WarningCallback
second_title: Aspose.PDF for Java API Reference
description: Interface for users callback mechanism support.
type: docs
weight: 398
url: /java/com.aspose.pdf/warningcallback/
---
**Inheritance:**
java.lang.Object
```
public abstract class WarningCallback
```

Interface for user's callback mechanism support.
## Constructors

| Constructor | Description |
| --- | --- |
| [WarningCallback()](#WarningCallback--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [warning(WarningInfo warning)](#warning-com.aspose.pdf.WarningInfo-) | The callback method for some program notifications. |
### WarningCallback() {#WarningCallback--}
```
public WarningCallback()
```


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

### warning(WarningInfo warning) {#warning-com.aspose.pdf.WarningInfo-}
```
public abstract WarningCallback.ReturnAction warning(WarningInfo warning)
```


The callback method for some program notifications.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| warning | [WarningInfo](../../com.aspose.pdf/warninginfo) | the warning information for some happened warning |

**Returns:**
[ReturnAction](../../com.aspose.pdf/returnaction) - the result of further program workflow
