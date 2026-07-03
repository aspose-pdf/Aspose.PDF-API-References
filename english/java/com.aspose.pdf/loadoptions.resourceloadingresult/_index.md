---
title: LoadOptions.ResourceLoadingResult
linktitle: LoadOptions.ResourceLoadingResult
second_title: Aspose.PDF for Java API Reference
description: Result of custom loading of resource
type: docs
weight: 2820
url: /java/com.aspose.pdf/loadoptions.resourceloadingresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions.ResourceLoadingResult

```
public static class LoadOptions.ResourceLoadingResult extends Object
```

Result of custom loading of resource

## Constructors

| Constructor | Description |
| --- | --- |
| [ResourceLoadingResult](#ResourceLoadingResult-byte:A-) | Creates instance of loading result |

## Methods

| Method | Description |
| --- | --- |
| [getData](#getData--) | Binary data that loaded with custom loader - it must be set after loading |
| [getEncodingIfKnown](#getEncodingIfKnown--) | Sometimes encoding of resource is known after or during loading. In such case custom code can provide converter with that knowledge via this parameter. You can leave null in this parameter if encoding is unknown or does not matter. |
| [getExceptionOfLoadingIfAny](#getExceptionOfLoadingIfAny--) | Sometimes it's impossible to load requested resource for some reason. Unavailability of resource often does not lead to crash of conversions and result document can be created anyway(but maybe in a bit worse quality, without images etc.). If exception occurred during loading, just catch it and put in this parameter - sometimes that information is useful for converter for rendering of result. |
| [getMIMETypeIfKnown](#getMIMETypeIfKnown--) | Sometimes knowledge about MIME type of loaded resource is useful for converter You can provide MIME type(if it'd known after loading) in this parameter. Please leave parameter equal to null when MIME type unknown or it's not necessary to supply it. |
| [isLoadingCancelled](#isLoadingCancelled--) | Sometimes for some reasons loading should not occur custom code. In such case please set this flag as True. In such case converter will try use internal default resource loader to get that result(as it behave in situation when custom strategy not supplied). |
| [setEncodingIfKnown](#setEncodingIfKnown-java.nio.charset.Charset-) | Sometimes encoding of resource is known after or during loading. In such case custom code can provide converter with that knowledge via this parameter. You can leave null in this parameter if encoding is unknown or does not matter. |
| [setExceptionOfLoadingIfAny](#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-) | Sometimes it's impossible to load requested resource for some reason. |
| [setLoadingCancelled](#setLoadingCancelled-boolean-) | Sometimes for some reasons loading should not occur custom code. In such case please set this flag as True. In such case converter will try use internal default resource loader to get that result(as it behave in situation when custom strategy not supplied). |
| [setMIMETypeIfKnown](#setMIMETypeIfKnown-java.lang.String-) | Sometimes knowledge about MIME type of loaded resource is usefull for converter You can provide MIME type(if it'd known after loading) in this parameter. Please leave parameter equal to null when MIME type unknown or it's not necessary to supply it. |

### ResourceLoadingResult {#ResourceLoadingResult-byte:A-}
```
public ResourceLoadingResult(byte[] data)
```

Creates instance of loading result

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data |  | result of custom loading must be always provided, it can be zero-length array if it's impossible to get any result |

### getData {#getData--}
```
public byte[] getData()
```

Binary data that loaded with custom loader - it must be set after loading

**Returns:**
array of byte values

### getEncodingIfKnown {#getEncodingIfKnown--}
```
public Charset getEncodingIfKnown()
```

Sometimes encoding of resource is known after or during loading. In such case custom code can provide converter with that knowledge via this parameter. You can leave null in this parameter if encoding is unknown or does not matter.

**Returns:**
Charset instance

### getExceptionOfLoadingIfAny {#getExceptionOfLoadingIfAny--}
```
public com.aspose.ms.System.Exception getExceptionOfLoadingIfAny()
```

Sometimes it's impossible to load requested resource for some reason. Unavailability of resource often does not lead to crash of conversions and result document can be created anyway(but maybe in a bit worse quality, without images etc.). If exception occurred during loading, just catch it and put in this parameter - sometimes that information is useful for converter for rendering of result.

**Returns:**
Exception

### getMIMETypeIfKnown {#getMIMETypeIfKnown--}
```
public String getMIMETypeIfKnown()
```

Sometimes knowledge about MIME type of loaded resource is useful for converter You can provide MIME type(if it'd known after loading) in this parameter. Please leave parameter equal to null when MIME type unknown or it's not necessary to supply it.

**Returns:**
String value

### isLoadingCancelled {#isLoadingCancelled--}
```
public boolean isLoadingCancelled()
```

Sometimes for some reasons loading should not occur custom code. In such case please set this flag as True. In such case converter will try use internal default resource loader to get that result(as it behave in situation when custom strategy not supplied).

**Returns:**
boolean value

### setEncodingIfKnown {#setEncodingIfKnown-java.nio.charset.Charset-}
Sometimes encoding of resource is known after or during loading. In such case custom code can provide converter with that knowledge via this parameter. You can leave null in this parameter if encoding is unknown or does not matter.

### setExceptionOfLoadingIfAny {#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-}
Sometimes it's impossible to load requested resource for some reason.

### setLoadingCancelled {#setLoadingCancelled-boolean-}
```
public void setLoadingCancelled(boolean loadingCancelled)
```

Sometimes for some reasons loading should not occur custom code. In such case please set this flag as True. In such case converter will try use internal default resource loader to get that result(as it behave in situation when custom strategy not supplied).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| loadingCancelled |  | boolean value |

### setMIMETypeIfKnown {#setMIMETypeIfKnown-java.lang.String-}
Sometimes knowledge about MIME type of loaded resource is usefull for converter You can provide MIME type(if it'd known after loading) in this parameter. Please leave parameter equal to null when MIME type unknown or it's not necessary to supply it.
