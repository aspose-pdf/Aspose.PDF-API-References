---
title: Copier
second_title: Aspose.PDF for Java API Reference
description: Class for coping object
type: docs
weight: 77
url: /java/com.aspose.pdf/copier/
---
**Inheritance:**
java.lang.Object
```
public class Copier
```

Class for coping object
## Constructors

| Constructor | Description |
| --- | --- |
| [Copier(ITrailerable trailerable)](#Copier-com.aspose.pdf.engine.data.ITrailerable-) | Constructor |
## Methods

| Method | Description |
| --- | --- |
| [duplicate(IPdfPrimitive src)](#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-) | Duplicates IPdfPrimitive |
| [duplicate(IPdfPrimitive src, boolean IsResourceObject)](#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-boolean-) | Creates copy of object with all dependent object. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowReusePageContent()](#getAllowReusePageContent--) | get Allow Reuse Page Content |
| [getClass()](#getClass--) |  |
| [getIgnoreCorruptedObjects()](#getIgnoreCorruptedObjects--) | get Ignore Corrupted Objects |
| [getRestrictedKeys()](#getRestrictedKeys--) | get Restricted Keys |
| [getReuseStreams()](#getReuseStreams--) | get Reuse Streams |
| [getUseStubs()](#getUseStubs--) | get Use Stubs |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowReusePageContent(boolean value)](#setAllowReusePageContent-boolean-) | set Allow Reuse Page Content |
| [setIgnoreCorruptedObjects(boolean value)](#setIgnoreCorruptedObjects-boolean-) | Set Ignore Corrupted Objects |
| [setRestrictedKeys(String[] value)](#setRestrictedKeys-java.lang.String---) | set Restricted Keys |
| [setReuseStreams(boolean value)](#setReuseStreams-boolean-) | set Reuse Streams |
| [setUseStubs(boolean value)](#setUseStubs-boolean-) | set Use Stubs |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Copier(ITrailerable trailerable) {#Copier-com.aspose.pdf.engine.data.ITrailerable-}
```
public Copier(ITrailerable trailerable)
```


Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| trailerable | [ITrailerable](../../com.aspose.pdf.engine.data/itrailerable) | ITrailerable object |

### duplicate(IPdfPrimitive src) {#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public IPdfPrimitive duplicate(IPdfPrimitive src)
```


Duplicates IPdfPrimitive

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| src | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) | IPdfPrimitive object |

**Returns:**
[IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) - IPdfPrimitive object
### duplicate(IPdfPrimitive src, boolean IsResourceObject) {#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-boolean-}
```
public IPdfPrimitive duplicate(IPdfPrimitive src, boolean IsResourceObject)
```


Creates copy of object with all dependent object. The object may be from part of other document (e.g. coping pages between documents, etc.)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| src | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) | IPdfPrimitive object |
| IsResourceObject | boolean | boolean value |

**Returns:**
[IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) - IPdfPrimitive object
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
### getAllowReusePageContent() {#getAllowReusePageContent--}
```
public boolean getAllowReusePageContent()
```


get Allow Reuse Page Content

**Returns:**
boolean - boolean value
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getIgnoreCorruptedObjects() {#getIgnoreCorruptedObjects--}
```
public boolean getIgnoreCorruptedObjects()
```


get Ignore Corrupted Objects

**Returns:**
boolean - boolean value
### getRestrictedKeys() {#getRestrictedKeys--}
```
public String[] getRestrictedKeys()
```


get Restricted Keys

**Returns:**
java.lang.String[] - String[] array
### getReuseStreams() {#getReuseStreams--}
```
public boolean getReuseStreams()
```


get Reuse Streams

**Returns:**
boolean - boolean value
### getUseStubs() {#getUseStubs--}
```
public boolean getUseStubs()
```


get Use Stubs

**Returns:**
boolean - boolean value
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




### setAllowReusePageContent(boolean value) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean value)
```


set Allow Reuse Page Content

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setIgnoreCorruptedObjects(boolean value) {#setIgnoreCorruptedObjects-boolean-}
```
public void setIgnoreCorruptedObjects(boolean value)
```


Set Ignore Corrupted Objects

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setRestrictedKeys(String[] value) {#setRestrictedKeys-java.lang.String---}
```
public void setRestrictedKeys(String[] value)
```


set Restricted Keys

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | String[] array |

### setReuseStreams(boolean value) {#setReuseStreams-boolean-}
```
public void setReuseStreams(boolean value)
```


set Reuse Streams

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setUseStubs(boolean value) {#setUseStubs-boolean-}
```
public void setUseStubs(boolean value)
```


set Use Stubs

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

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

