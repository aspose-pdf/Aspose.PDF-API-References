---
title: HtmlSaveOptions.CssUrlRequestInfo
second_title: Aspose.PDF for Java API Reference
description: Represents set of data that related to request from converter to custom code aimed to get desirable URL or URL templateof subject CSS
type: docs
weight: 14
url: /java/com.aspose.pdf/htmlsaveoptions.cssurlrequestinfo/
---
**Inheritance:**
java.lang.Object
```
public static class HtmlSaveOptions.CssUrlRequestInfo
```

Represents set of data that related to request from converter to custom code aimed to get desirable URL (or URL template)of subject CSS
## Constructors

| Constructor | Description |
| --- | --- |
| [CssUrlRequestInfo()](#CssUrlRequestInfo--) | Creates instance of CssUrlRequestInfo |
## Methods

| Method | Description |
| --- | --- |
| [isCustomProcessingCancelled()](#isCustomProcessingCancelled--) | Should be set by custom code if it cannot or should not define URL that will be used in generated HTML for referencing of that CSS. |
| [setCustomProcessingCancelled(boolean customProcessingCancelled)](#setCustomProcessingCancelled-boolean-) | Should be set by custom code if it cannot or should not define URL that will be used in generated HTML for referencing of that CSS. |
### CssUrlRequestInfo() {#CssUrlRequestInfo--}
```
public CssUrlRequestInfo()
```


Creates instance of CssUrlRequestInfo

### isCustomProcessingCancelled() {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```


Should be set by custom code if it cannot or should not define URL that will be used in generated HTML for referencing of that CSS. If it's 'true', then CSS file will be saved in standard way in standard place.

**Returns:**
boolean - boolean value
### setCustomProcessingCancelled(boolean customProcessingCancelled) {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```


Should be set by custom code if it cannot or should not define URL that will be used in generated HTML for referencing of that CSS. If it's 'true', then CSS file will be saved in standard way in standard place.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| customProcessingCancelled | boolean | boolean value |

