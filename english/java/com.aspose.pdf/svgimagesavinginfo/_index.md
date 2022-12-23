---
title: SvgSaveOptions.SvgImageSavingInfo
second_title: Aspose.PDF for Java API Reference
description: This class represents set of data that related to external resource image files saving during PDF to HTML conversion.
type: docs
weight: 11
url: /java/com.aspose.pdf/svgsaveoptions.svgimagesavinginfo/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.SaveOptions.ResourceSavingInfo](../../com.aspose.pdf/resourcesavinginfo)
```
public static class SvgSaveOptions.SvgImageSavingInfo extends SaveOptions.ResourceSavingInfo
```

This class represents set of data that related to external resource image file's saving during PDF to HTML conversion.
## Constructors

| Constructor | Description |
| --- | --- |
| [SvgImageSavingInfo()](#SvgImageSavingInfo--) | creates new instance of HtmlImageSavingInfo |
## Methods

| Method | Description |
| --- | --- |
| [getImageType()](#getImageType--) | represent type os saved image referenced in HTML. |
| [setImageType(int imageType)](#setImageType-int-) | represent type os saved image referenced in HTML. |
### SvgImageSavingInfo() {#SvgImageSavingInfo--}
```
public SvgImageSavingInfo()
```


creates new instance of HtmlImageSavingInfo

### getImageType() {#getImageType--}
```
public int getImageType()
```


represent type os saved image referenced in HTML. Set by converter and can be used in custom code to decide what should be done

**Returns:**
int - SvgExternalImageType element
### setImageType(int imageType) {#setImageType-int-}
```
public void setImageType(int imageType)
```


represent type os saved image referenced in HTML. Set by converter and can be used in custom code to decide what should be done

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageType | int | SvgExternalImageType element |

