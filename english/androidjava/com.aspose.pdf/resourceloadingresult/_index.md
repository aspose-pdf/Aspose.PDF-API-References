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
## Fields

| Field | Description |
| --- | --- |
| [EncodingIfKnown](#EncodingIfKnown) | Sometimes encoding of resource is known after or during loading. |
| [ExceptionOfLoadingIfAny](#ExceptionOfLoadingIfAny) | Sometimes it's impossible to load requested resource for some reason. |
| [MIMETypeIfKnown](#MIMETypeIfKnown) | Sometimes knowledge about MIME type of loaded resource is usefull for converter You can provide MIME type(if it'd known after loading) in this parameter. |
| [LoadingCancelled](#LoadingCancelled) | Sometimes for some reasons loading should not occure custom code. |
## Methods

| Method | Description |
| --- | --- |
| [getData()](#getData--) | Bynary data that loaded with custom loader - it must be set after loading |
### ResourceLoadingResult(byte[] data) {#ResourceLoadingResult-byte---}
```
public ResourceLoadingResult(byte[] data)
```


Creates instance of loading result

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | reult of custom loading must be allways provided, it can be zero-length array if it's impossible to get any result |

### EncodingIfKnown {#EncodingIfKnown}
```
public System.Text.Encoding EncodingIfKnown
```


Sometimes encoding of resource is known after or during loading. In such case custom code can provide converter with that knowledge via this parameter. You can leave null in this parameter if encoding is unknown or does not matter.

### ExceptionOfLoadingIfAny {#ExceptionOfLoadingIfAny}
```
public System.Exception ExceptionOfLoadingIfAny
```


Sometimes it's impossible to load requested resource for some reason. Unavailability of resource often does not lead to crash of conversiov and result document can be created anyway(but maybe in a bit worse Quality, without images etc.). If exception occured during loading, just catch it and put in this parameter - sometimes that information is usefull for converter for rendering of result.

### MIMETypeIfKnown {#MIMETypeIfKnown}
```
public String MIMETypeIfKnown
```


Sometimes knowledge about MIME type of loaded resource is usefull for converter You can provide MIME type(if it'd known after loading) in this parameter. Please leave parameter equal to null when MIME type unknown or it's not necessary to supply it.

### LoadingCancelled {#LoadingCancelled}
```
public boolean LoadingCancelled
```


Sometimes for some reasons loading should not occure custom code. In such case please set this flag as True. In such case converter will try use internal default resource loader to get that result(as it behave in situation when custom strategy not supplied).

### getData() {#getData--}
```
public byte[] getData()
```


Bynary data that loaded with custom loader - it must be set after loading

**Returns:**
byte[] - array of byte values
