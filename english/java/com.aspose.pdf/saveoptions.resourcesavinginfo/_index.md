---
title: SaveOptions.ResourceSavingInfo
linktitle: SaveOptions.ResourceSavingInfo
second_title: Aspose.PDF for Java API Reference
description: This class represents set of data that related to external resource file's saving that occures during conversion of PDF to some other format (f.e. HTML)
type: docs
weight: 4440
url: /java/com.aspose.pdf/saveoptions.resourcesavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.ResourceSavingInfo

```
public static class SaveOptions.ResourceSavingInfo extends Object
```

This class represents set of data that related to external resource file's saving that occures during conversion of PDF to some other format (f.e. HTML)

## Methods

| Method | Description |
| --- | --- |
| [getContentStream](#getContentStream--) | Set by converter. Represents binary content of saved file. |
| [getResourceType](#getResourceType--) | Set by converter. Supposed file name that goes from converter to code of custom method Can be use in custom code to decide how to process or where save that file |
| [getSupposedFileName](#getSupposedFileName--) | Set by converter. Supposed file name that goes from converter to code of custom method Can be use in custom code to decide how to process or where save that file |
| [isCustomProcessingCancelled](#isCustomProcessingCancelled--) | this flag must set to "true" in custom code if for some reasons proposed file should be processed not with custom code but with converter's code itself in standard for converter way. So, it' setting set to true means that custom code did not process referenced file and converter must handle it itself (in both sences - for saving somewhere and for naming in referencing file). |
| [setCustomProcessingCancelled](#setCustomProcessingCancelled-boolean-) | this flag must set to "true" in custom code if for some reasons proposed file should be processed not with custom code but with converter's code itself in standard for converter way. So, it' setting set to true means that custom code did not process referenced file and converter must handle it itself (in both senses - for saving somewhere and for naming in referencing file). |

### getContentStream {#getContentStream--}
```
public byte[] getContentStream()
```

Set by converter. Represents binary content of saved file.

**Returns:**
array of bytes

### getResourceType {#getResourceType--}
```
public SaveOptions.NodeLevelResourceType getResourceType()
```

Set by converter. Supposed file name that goes from converter to code of custom method Can be use in custom code to decide how to process or where save that file

**Returns:**
NodeLevelResourceType element @see NodeLevelResourceType

### getSupposedFileName {#getSupposedFileName--}
```
public String getSupposedFileName()
```

Set by converter. Supposed file name that goes from converter to code of custom method Can be use in custom code to decide how to process or where save that file

**Returns:**
String value

### isCustomProcessingCancelled {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```

this flag must set to "true" in custom code if for some reasons proposed file should be processed not with custom code but with converter's code itself in standard for converter way. So, it' setting set to true means that custom code did not process referenced file and converter must handle it itself (in both sences - for saving somewhere and for naming in referencing file).

**Returns:**
boolean value

### setCustomProcessingCancelled {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```

this flag must set to "true" in custom code if for some reasons proposed file should be processed not with custom code but with converter's code itself in standard for converter way. So, it' setting set to true means that custom code did not process referenced file and converter must handle it itself (in both senses - for saving somewhere and for naming in referencing file).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| customProcessingCancelled |  | boolean value |
