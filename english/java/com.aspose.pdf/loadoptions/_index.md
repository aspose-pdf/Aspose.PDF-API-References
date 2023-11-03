---
title: LoadOptions
second_title: Aspose.PDF for Java API Reference
description: LoadOptions type holds level of abstraction on individual load options
type: docs
weight: 200
url: /java/com.aspose.pdf/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class LoadOptions
```

LoadOptions type holds level of abstraction on individual load options
## Constructors

| Constructor | Description |
| --- | --- |
| [LoadOptions()](#LoadOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getWarningHandler()](#getWarningHandler--) | Callback to handle any warnings generated. |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Callback to handle any warnings generated. |
| [getLoadFormat()](#getLoadFormat--) | Represents file format which  LoadOptions  describes. |
| [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | Gets or sets flag to disable any license restrictions for all fonts while loading the file. |
| [setDisableFontLicenseVerifications(boolean value)](#setDisableFontLicenseVerifications-boolean-) | Gets or sets flag to disable any license restrictions for all fonts while loading the file. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


### getWarningHandler() {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```


Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease.

**Returns:**
[WarningCallback](../../com.aspose.pdf/warningcallback) - IWarningCallback value
### setWarningHandler(WarningCallback value) {#setWarningHandler-com.aspose.pdf.WarningCallback-}
```
public void setWarningHandler(WarningCallback value)
```


Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WarningCallback](../../com.aspose.pdf/warningcallback) | IWarningCallback value |

### getLoadFormat() {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```


Represents file format which  LoadOptions  describes.

**Returns:**
[LoadFormat](../../com.aspose.pdf/loadformat) - LoadFormat element
### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public final boolean isDisableFontLicenseVerifications()
```


Gets or sets flag to disable any license restrictions for all fonts while loading the file. When  , allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default  .

Be careful when using this flag. When it is set it means that person who sets this flag, takes all responsibility of possible license/law violations on himself. So he takes it on it's own risk. It's strongly recommended to use this flag only when you are fully confident that you are not breaking the copyright law.

**Returns:**
boolean - boolean value
### setDisableFontLicenseVerifications(boolean value) {#setDisableFontLicenseVerifications-boolean-}
```
public final void setDisableFontLicenseVerifications(boolean value)
```


Gets or sets flag to disable any license restrictions for all fonts while loading the file. When  , allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default  .

Be careful when using this flag. When it is set it means that person who sets this flag, takes all responsibility of possible license/law violations on himself. So he takes it on it's own risk. It's strongly recommended to use this flag only when you are fully confident that you are not breaking the copyright law.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

