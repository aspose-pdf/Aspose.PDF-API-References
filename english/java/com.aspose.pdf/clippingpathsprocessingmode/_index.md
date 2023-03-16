---
title: TextEditOptions.ClippingPathsProcessingMode
second_title: Aspose.PDF for Java API Reference
description: Clipping path processing modes
type: docs
weight: 10
url: /java/com.aspose.pdf/texteditoptions.clippingpathsprocessingmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextEditOptions.ClippingPathsProcessingMode extends Enum<TextEditOptions.ClippingPathsProcessingMode>
```

Clipping path processing modes
## Fields

| Field | Description |
| --- | --- |
| [KeepIntact](#KeepIntact) | Keeps clipping paths of the original page layout. |
| [Expand](#Expand) | Original clipping path will be expanded in the case edited text requires more space. |
| [Remove](#Remove) | Original clipping path will be removed in the case edited text requires more space. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [getValue()](#getValue--) |  |
### KeepIntact {#KeepIntact}
```
public static final TextEditOptions.ClippingPathsProcessingMode KeepIntact
```


Keeps clipping paths of the original page layout. (Default)

### Expand {#Expand}
```
public static final TextEditOptions.ClippingPathsProcessingMode Expand
```


Original clipping path will be expanded in the case edited text requires more space.

### Remove {#Remove}
```
public static final TextEditOptions.ClippingPathsProcessingMode Remove
```


Original clipping path will be removed in the case edited text requires more space. Caution: Because of clipping paths may interact with each other removing of it may lead to unexpected result on the page layout.

### values() {#values--}
```
public static TextEditOptions.ClippingPathsProcessingMode[] values()
```




**Returns:**
com.aspose.pdf.TextEditOptions.ClippingPathsProcessingMode[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static TextEditOptions.ClippingPathsProcessingMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[ClippingPathsProcessingMode](../../com.aspose.pdf/clippingpathsprocessingmode)
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
