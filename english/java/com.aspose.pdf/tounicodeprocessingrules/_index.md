---
title: ToUnicodeProcessingRules
second_title: Aspose.PDF for Java API Reference
description: This class describes rules which can be used to solve Adobe Preflight error Text cannot be mapped to Unicode.
type: docs
weight: 392
url: /java/com.aspose.pdf/tounicodeprocessingrules/
---
**Inheritance:**
java.lang.Object
```
public class ToUnicodeProcessingRules
```

This class describes rules which can be used to solve Adobe Preflight error "Text cannot be mapped to Unicode".
## Constructors

| Constructor | Description |
| --- | --- |
| [ToUnicodeProcessingRules()](#ToUnicodeProcessingRules--) | Constructor |
| [ToUnicodeProcessingRules(boolean removeSpaces)](#ToUnicodeProcessingRules-boolean-) | Constructor |
| [ToUnicodeProcessingRules(boolean removeSpaces, boolean mapNonLinkedUnicodesOnSpace)](#ToUnicodeProcessingRules-boolean-boolean-) | Constructor |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMapNonLinkedSymbolsOnSpace()](#getMapNonLinkedSymbolsOnSpace--) | Some fonts doesn't provide information about unicodes for some text symbols. |
| [getRemoveSpacesFromCMapNames()](#getRemoveSpacesFromCMapNames--) | Some fonts have ToUnicode character code maps with spaces in names. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMapNonLinkedSymbolsOnSpace(boolean value)](#setMapNonLinkedSymbolsOnSpace-boolean-) | Some fonts doesn't provide information about unicodes for some text symbols. |
| [setRemoveSpacesFromCMapNames(boolean value)](#setRemoveSpacesFromCMapNames-boolean-) | Some fonts have ToUnicode character code maps with spaces in names. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ToUnicodeProcessingRules() {#ToUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules()
```


Constructor

### ToUnicodeProcessingRules(boolean removeSpaces) {#ToUnicodeProcessingRules-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces)
```


Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| removeSpaces | boolean | sets  RemoveSpacesFromCMapNames  flag |

### ToUnicodeProcessingRules(boolean removeSpaces, boolean mapNonLinkedUnicodesOnSpace) {#ToUnicodeProcessingRules-boolean-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces, boolean mapNonLinkedUnicodesOnSpace)
```


Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| removeSpaces | boolean | sets  RemoveSpacesFromCMapNames  flag |
| mapNonLinkedUnicodesOnSpace | boolean | sets  MapNonLinkedSymbolsOnSpace  flag |

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
### getMapNonLinkedSymbolsOnSpace() {#getMapNonLinkedSymbolsOnSpace--}
```
public boolean getMapNonLinkedSymbolsOnSpace()
```


Some fonts doesn't provide information about unicodes for some text symbols. This lack of information calls an error "Text cannot be mapped to Unicode". Use this flag to map non-linked symbols on unicode "space"(code 32).

**Returns:**
boolean - boolean value
### getRemoveSpacesFromCMapNames() {#getRemoveSpacesFromCMapNames--}
```
public boolean getRemoveSpacesFromCMapNames()
```


Some fonts have ToUnicode character code maps with spaces in names. These spaces could call errors with unicode text mapping. This flag commands to remove spaces from names of ToUnicode character code maps. By default false.

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




### setMapNonLinkedSymbolsOnSpace(boolean value) {#setMapNonLinkedSymbolsOnSpace-boolean-}
```
public void setMapNonLinkedSymbolsOnSpace(boolean value)
```


Some fonts doesn't provide information about unicodes for some text symbols. This lack of information calls an error "Text cannot be mapped to Unicode". Use this flag to map non-linked symbols on unicode "space"(code 32).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setRemoveSpacesFromCMapNames(boolean value) {#setRemoveSpacesFromCMapNames-boolean-}
```
public void setRemoveSpacesFromCMapNames(boolean value)
```


Some fonts have ToUnicode character code maps with spaces in names. These spaces could call errors with unicode text mapping. This flag commands to remove spaces from names of ToUnicode character code maps. By default false.

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

