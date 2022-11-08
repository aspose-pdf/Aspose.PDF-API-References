---
title: LoadOptions.ResourceLoadingResult
second_title: Aspose.PDF for Java API Reference
description: Result of custom loading of resource
type: docs
weight: 12
url: /java/com.aspose.pdf/loadoptions.resourceloadingresult/
---
**Inheritance:**
java.lang.Object
```
public static class LoadOptions.ResourceLoadingResult
```

Result of custom loading of resource
## Constructors

| Constructor | Description |
| --- | --- |
| [ResourceLoadingResult(byte[] data)](#ResourceLoadingResult-byte---) | Creates instance of loading result |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Bynary data that loaded with custom loader - it must be set after loading |
| [getEncodingIfKnown()](#getEncodingIfKnown--) | Sometimes encoding of resource is known after or during loading. |
| [getExceptionOfLoadingIfAny()](#getExceptionOfLoadingIfAny--) | Sometimes it's impossible to load requested resource for some reason. |
| [getMIMETypeIfKnown()](#getMIMETypeIfKnown--) | Sometimes knowledge about MIME type of loaded resource is usefull for converter You can provide MIME type(if it'd known after loading) in this parameter. |
| [hashCode()](#hashCode--) |  |
| [isLoadingCancelled()](#isLoadingCancelled--) | Sometimes for some reasons loading should not occure custom code. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEncodingIfKnown(Charset encodingIfKnown)](#setEncodingIfKnown-java.nio.charset.Charset-) | Sometimes encoding of resource is known after or during loading. |
| [setExceptionOfLoadingIfAny(System.Exception exceptionOfLoadingIfAny)](#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-) | Sometimes it's impossible to load requested resource for some reason. |
| [setLoadingCancelled(boolean loadingCancelled)](#setLoadingCancelled-boolean-) | Sometimes for some reasons loading should not occure custom code. |
| [setMIMETypeIfKnown(String MIMETypeIfKnown)](#setMIMETypeIfKnown-java.lang.String-) | Sometimes knowledge about MIME type of loaded resource is usefull for converter You can provide MIME type(if it'd known after loading) in this parameter. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResourceLoadingResult(byte[] data) {#ResourceLoadingResult-byte---}
```
public ResourceLoadingResult(byte[] data)
```


Creates instance of loading result

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | reult of custom loading must be allways provided, it can be zero-length array if it's impossible to get any result |

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
### getData() {#getData--}
```
public byte[] getData()
```


Bynary data that loaded with custom loader - it must be set after loading

**Returns:**
byte[] - array of byte values
### getEncodingIfKnown() {#getEncodingIfKnown--}
```
public Charset getEncodingIfKnown()
```


Sometimes encoding of resource is known after or during loading. In such case custom code can provide converter with that knowledge via this parameter. You can leave null in this parameter if encoding is unknown or does not matter.

**Returns:**
java.nio.charset.Charset - Charset instance
### getExceptionOfLoadingIfAny() {#getExceptionOfLoadingIfAny--}
```
public System.Exception getExceptionOfLoadingIfAny()
```


Sometimes it's impossible to load requested resource for some reason. Unavailability of resource often does not lead to crash of conversions and result document can be created anyway(but maybe in a bit worse quality, without images etc.). If exception occurred during loading, just catch it and put in this parameter - sometimes that information is useful for converter for rendering of result.

**Returns:**
com.aspose.ms.System.Exception - Exception
### getMIMETypeIfKnown() {#getMIMETypeIfKnown--}
```
public String getMIMETypeIfKnown()
```


Sometimes knowledge about MIME type of loaded resource is usefull for converter You can provide MIME type(if it'd known after loading) in this parameter. Please leave parameter equal to null when MIME type unknown or it's not necessary to supply it.

**Returns:**
java.lang.String - String value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isLoadingCancelled() {#isLoadingCancelled--}
```
public boolean isLoadingCancelled()
```


Sometimes for some reasons loading should not occure custom code. In such case please set this flag as True. In such case converter will try use internal default resource loader to get that result(as it behave in situation when custom strategy not supplied).

**Returns:**
boolean - boolean value
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setEncodingIfKnown(Charset encodingIfKnown) {#setEncodingIfKnown-java.nio.charset.Charset-}
```
public void setEncodingIfKnown(Charset encodingIfKnown)
```


Sometimes encoding of resource is known after or during loading. In such case custom code can provide converter with that knowledge via this parameter. You can leave null in this parameter if encoding is unknown or does not matter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| encodingIfKnown | java.nio.charset.Charset | Charset instance |

### setExceptionOfLoadingIfAny(System.Exception exceptionOfLoadingIfAny) {#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-}
```
public void setExceptionOfLoadingIfAny(System.Exception exceptionOfLoadingIfAny)
```


Sometimes it's impossible to load requested resource for some reason. Unavailability of resource often does not lead to crash of conversions and result document can be created anyway(but maybe in a bit worse quality, without images etc.). If exception occurred during loading, just catch it and put in this parameter - sometimes that information is useful for converter for rendering of result.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| exceptionOfLoadingIfAny | com.aspose.ms.System.Exception | Exception |

### setLoadingCancelled(boolean loadingCancelled) {#setLoadingCancelled-boolean-}
```
public void setLoadingCancelled(boolean loadingCancelled)
```


Sometimes for some reasons loading should not occure custom code. In such case please set this flag as True. In such case converter will try use internal default resource loader to get that result(as it behave in situation when custom strategy not supplied).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| loadingCancelled | boolean | boolean value |

### setMIMETypeIfKnown(String MIMETypeIfKnown) {#setMIMETypeIfKnown-java.lang.String-}
```
public void setMIMETypeIfKnown(String MIMETypeIfKnown)
```


Sometimes knowledge about MIME type of loaded resource is usefull for converter You can provide MIME type(if it'd known after loading) in this parameter. Please leave parameter equal to null when MIME type unknown or it's not necessary to supply it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| MIMETypeIfKnown | java.lang.String | String value |

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

