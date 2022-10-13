---
title: SaveOptions.ResourceSavingInfo
second_title: Aspose.PDF for Java API Reference
description: This class represents set of data    that related to external resource files saving that    occures during conversion of PDF to some other format f.e.
type: docs
weight: 14
url: /java/com.aspose.pdf/saveoptions.resourcesavinginfo/
---
**Inheritance:**
java.lang.Object
```
public static class SaveOptions.ResourceSavingInfo
```

This class represents set of data that related to external resource file's saving that occures during conversion of PDF to some other format (f.e. HTML)
## Fields

| Field | Description |
| --- | --- |
| [SupposedFileName](#SupposedFileName) | Set by converter. |
| [ContentStream](#ContentStream) | Set by converter. |
| [CustomProcessingCancelled](#CustomProcessingCancelled) | this flag must set to "true" in custom code if for some reasons proposed file should be processed not with custom code but with converter's code itself in standard for converter way. |
## Methods

| Method | Description |
| --- | --- |
| [getResourceType()](#getResourceType--) | Set by converter. |
### SupposedFileName {#SupposedFileName}
```
public String SupposedFileName
```


Set by converter. Supposed file name that goes from converter to code of custom method Can be use in custom code to decide how to process or where save that file

### ContentStream {#ContentStream}
```
public System.IO.Stream ContentStream
```


Set by converter. Represents binary content of saved file.

### CustomProcessingCancelled {#CustomProcessingCancelled}
```
public boolean CustomProcessingCancelled
```


this flag must set to "true" in custom code if for some reasons proposed file should be processed not with custom code but with converter's code itself in standard for converter way. So, it' setting set to true means that custom code did not process referenced file and converter must handle it itself (in both sences - for saving somewhere and for naming in referencing file).

### getResourceType() {#getResourceType--}
```
public int getResourceType()
```


Set by converter. Supposed file name that goes from converter to code of custom method Can be use in custom code to decide how to process or where save that file

**Returns:**
int
