---
title: HtmlSaveOptions.ResourceSavingStrategy
second_title: Aspose.PDF for Java API Reference
description: To this property You can assign delegate created from custom method that implements processing of external resourceFont or Image that was extracted from PDF and must be saved as external resource during conversion of PDF to HTML.
type: docs
weight: 25
url: /java/com.aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class HtmlSaveOptions.ResourceSavingStrategy extends System.MulticastDelegate
```

To this property You can assign delegate created from custom method that implements processing of external resource(Font or Image) that was extracted from PDF and must be saved as external resource during conversion of PDF to HTML. In such case processing (like saving in stream or disk) can be done in that custom code and that custom code must return path(or any another string without quotemarks) that will be afterwards incorporated into generated HTML instead of original supposed path to that image resource. In such case All the necessary actions for saving of image must be undertaken in code of supplied method, because saving of result in code of converter will be not in use . If processing for this or that file for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'resourceSavingInfo' parameter's variable It signals to converter that all the necessary steps for processing of that resource must be done in converter itself as if there was no any external custom code .
## Constructors

| Constructor | Description |
| --- | --- |
| [ResourceSavingStrategy()](#ResourceSavingStrategy--) |  |
## Methods

| Method | Description |
| --- | --- |
| [combine(System.Delegate arg0, System.Delegate arg1)](#combine-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-) |  |
| [combine(System.Delegate[] arg0)](#combine-com.aspose.ms.System.Delegate...-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getInvocationList()](#getInvocationList--) |  |
| [hashCode()](#hashCode--) |  |
| [invoke(SaveOptions.ResourceSavingInfo resourceSavingInfo)](#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-) | Invoked method |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(System.Delegate arg0, System.Delegate arg1)](#op-Equality-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-) |  |
| [op_Equality(System.MulticastDelegate arg0, System.MulticastDelegate arg1)](#op-Equality-com.aspose.ms.System.MulticastDelegate-com.aspose.ms.System.MulticastDelegate-) |  |
| [op_Inequality(System.Delegate arg0, System.Delegate arg1)](#op-Inequality-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-) |  |
| [op_Inequality(System.MulticastDelegate arg0, System.MulticastDelegate arg1)](#op-Inequality-com.aspose.ms.System.MulticastDelegate-com.aspose.ms.System.MulticastDelegate-) |  |
| [peekOutRefParam(int arg0)](#peekOutRefParam-int-) |  |
| [peekResult()](#peekResult--) |  |
| [remove(System.Delegate arg0, System.Delegate arg1)](#remove-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-) |  |
| [removeAll(System.Delegate arg0, System.Delegate arg1)](#removeAll-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-) |  |
| [setException(RuntimeException arg0)](#setException-java.lang.RuntimeException-) |  |
| [throwException()](#throwException--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResourceSavingStrategy() {#ResourceSavingStrategy--}
```
public ResourceSavingStrategy()
```


### combine(System.Delegate arg0, System.Delegate arg1) {#combine-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-}
```
public static System.Delegate combine(System.Delegate arg0, System.Delegate arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Delegate |  |
| arg1 | com.aspose.ms.System.Delegate |  |

**Returns:**
com.aspose.ms.System.Delegate
### combine(System.Delegate[] arg0) {#combine-com.aspose.ms.System.Delegate...-}
```
public static System.Delegate combine(System.Delegate[] arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Delegate[] |  |

**Returns:**
com.aspose.ms.System.Delegate
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
### getInvocationList() {#getInvocationList--}
```
public final System.Delegate[] getInvocationList()
```




**Returns:**
com.aspose.ms.System.Delegate[]
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### invoke(SaveOptions.ResourceSavingInfo resourceSavingInfo) {#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-}
```
public abstract String invoke(SaveOptions.ResourceSavingInfo resourceSavingInfo)
```


Invoked method

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resourceSavingInfo | [ResourceSavingInfo](../../com.aspose.pdf/resourcesavinginfo) | SaveOptions.ResourceSavingInfo object |

**Returns:**
java.lang.String - String object
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(System.Delegate arg0, System.Delegate arg1) {#op-Equality-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-}
```
public static boolean op_Equality(System.Delegate arg0, System.Delegate arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Delegate |  |
| arg1 | com.aspose.ms.System.Delegate |  |

**Returns:**
boolean
### op_Equality(System.MulticastDelegate arg0, System.MulticastDelegate arg1) {#op-Equality-com.aspose.ms.System.MulticastDelegate-com.aspose.ms.System.MulticastDelegate-}
```
public static boolean op_Equality(System.MulticastDelegate arg0, System.MulticastDelegate arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.MulticastDelegate |  |
| arg1 | com.aspose.ms.System.MulticastDelegate |  |

**Returns:**
boolean
### op_Inequality(System.Delegate arg0, System.Delegate arg1) {#op-Inequality-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-}
```
public static boolean op_Inequality(System.Delegate arg0, System.Delegate arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Delegate |  |
| arg1 | com.aspose.ms.System.Delegate |  |

**Returns:**
boolean
### op_Inequality(System.MulticastDelegate arg0, System.MulticastDelegate arg1) {#op-Inequality-com.aspose.ms.System.MulticastDelegate-com.aspose.ms.System.MulticastDelegate-}
```
public static boolean op_Inequality(System.MulticastDelegate arg0, System.MulticastDelegate arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.MulticastDelegate |  |
| arg1 | com.aspose.ms.System.MulticastDelegate |  |

**Returns:**
boolean
### peekOutRefParam(int arg0) {#peekOutRefParam-int-}
```
public Object peekOutRefParam(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

**Returns:**
java.lang.Object
### peekResult() {#peekResult--}
```
public Object peekResult()
```




**Returns:**
java.lang.Object
### remove(System.Delegate arg0, System.Delegate arg1) {#remove-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-}
```
public static System.Delegate remove(System.Delegate arg0, System.Delegate arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Delegate |  |
| arg1 | com.aspose.ms.System.Delegate |  |

**Returns:**
com.aspose.ms.System.Delegate
### removeAll(System.Delegate arg0, System.Delegate arg1) {#removeAll-com.aspose.ms.System.Delegate-com.aspose.ms.System.Delegate-}
```
public static System.Delegate removeAll(System.Delegate arg0, System.Delegate arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Delegate |  |
| arg1 | com.aspose.ms.System.Delegate |  |

**Returns:**
com.aspose.ms.System.Delegate
### setException(RuntimeException arg0) {#setException-java.lang.RuntimeException-}
```
public void setException(RuntimeException arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.RuntimeException |  |

### throwException() {#throwException--}
```
public void throwException()
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

