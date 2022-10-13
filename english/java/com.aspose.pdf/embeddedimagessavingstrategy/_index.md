---
title: SvgSaveOptions.EmbeddedImagesSavingStrategy
second_title: Aspose.PDF for Java API Reference
description: To property of such type You can assign delegate created from custom method that implements processing of external saving of image that was extracted from SVG created from PDF and must be saved as external resource during conversion of PDF to HTML.
type: docs
weight: 12
url: /java/com.aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---```
public static interface SvgSaveOptions.EmbeddedImagesSavingStrategy
```

To property of such type You can assign delegate created from custom method that implements processing of external saving of image that was extracted from SVG created from PDF and must be saved as external resource during conversion of PDF to HTML. In such case processing (like self-made saving into stream or on disk) can be done in that custom code and that custom code must return path(or any another string without quotemarks) that will be afterwards incorporated into generated SVG instead of original supposed path to that image resource. In such case all the necessary actions for saving of image must be undertaken in code of supplied method, because saving of result in code of converter will be not in use. If processing for this or that file for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'imageSavingInfo' parameter's variable It signals to converter that all the necessary steps for processing of that resource must be done in converter itself as if there was no any external custom code .
## Methods

| Method | Description |
| --- | --- |
| [invoke(SvgSaveOptions.SvgImageSavingInfo imageSavingInfo)](#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-) |  |
### invoke(SvgSaveOptions.SvgImageSavingInfo imageSavingInfo) {#invoke-com.aspose.pdf.SvgSaveOptions.SvgImageSavingInfo-}
```
public abstract String invoke(SvgSaveOptions.SvgImageSavingInfo imageSavingInfo)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageSavingInfo | [SvgImageSavingInfo](../../com.aspose.pdf/svgimagesavinginfo) |  |

**Returns:**
java.lang.String
