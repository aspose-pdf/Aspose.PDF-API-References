---
title: SaveOptions
linktitle: SaveOptions
second_title: Aspose.PDF for Java API Reference
description: SaveOptions type hold level of abstraction on individual save options
type: docs
weight: 4370
url: /java/com.aspose.pdf/saveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions

```
public abstract class SaveOptions extends Object
```

SaveOptions type hold level of abstraction on individual save options

## Methods

| Method | Description |
| --- | --- |
| [getSaveFormat](#getSaveFormat--) | Format of data save. |
| [getWarningHandler](#getWarningHandler--) | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |
| [isCacheGlyphs](#isCacheGlyphs--) | Gets or sets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [isCloseResponse](#isCloseResponse--) | Gets boolean value which indicates will Response object be closed after document saved into response. |
| [setCacheGlyphs](#setCacheGlyphs-boolean-) | Gets or sets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [setCloseResponse](#setCloseResponse-boolean-) | Sets boolean value which indicates will Response object be closed after document saved into response. |
| [setWarningHandler](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |

### getSaveFormat {#getSaveFormat--}
```
public SaveFormat getSaveFormat()
```

Format of data save.

**Returns:**
SaveFormat value @see SaveFormat

### getWarningHandler {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```

Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease.

**Returns:**
IWarningCallback value

### isCacheGlyphs {#isCacheGlyphs--}
```
public final boolean isCacheGlyphs()
```

Gets or sets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption.

**Returns:**
boolean value

### isCloseResponse {#isCloseResponse--}
```
public boolean isCloseResponse()
```

Gets boolean value which indicates will Response object be closed after document saved into response.

**Returns:**
boolean value

### setCacheGlyphs {#setCacheGlyphs-boolean-}
```
public final void setCacheGlyphs(boolean value)
```

Gets or sets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setCloseResponse {#setCloseResponse-boolean-}
```
public void setCloseResponse(boolean value)
```

Sets boolean value which indicates will Response object be closed after document saved into response.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setWarningHandler {#setWarningHandler-com.aspose.pdf.WarningCallback-}
Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease.
