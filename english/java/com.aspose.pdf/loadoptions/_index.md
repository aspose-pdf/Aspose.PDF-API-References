---
title: LoadOptions
second_title: Aspose.PDF for Java API Reference
description: LoadOptions type holds level of abstraction on individual load options
type: docs
weight: 2790
url: /java/com.aspose.pdf/loadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions

```
public abstract class LoadOptions extends Object
```

LoadOptions type holds level of abstraction on individual load options

## Constructors

| Constructor | Description |
| --- | --- |
| [LoadOptions](#LoadOptions--) |  |

## Methods

| Method | Description |
| --- | --- |
| [getLoadFormat](#getLoadFormat--) | Represents file format which {@code LoadOptions} describes. |
| [getWarningHandler](#getWarningHandler--) | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | Gets or sets flag to disable any license restrictions for all fonts while loading the file. When {@code }, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default {@code }. Be careful when using this flag. When it is set it means that person who sets this flag, takes all responsibility of possible license/law violations on himself. So he takes it on it's own risk. It's strongly recommended to use this flag only when you are fully confident that you are not breaking the copyright law. |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | Gets or sets flag to disable any license restrictions for all fonts while loading the file. When {@code }, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default {@code }. Be careful when using this flag. When it is set it means that person who sets this flag, takes all responsibility of possible license/law violations on himself. So he takes it on it's own risk. It's strongly recommended to use this flag only when you are fully confident that you are not breaking the copyright law. |
| [setWarningHandler](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |

### LoadOptions {#LoadOptions--}
```
public LoadOptions()
```



### getLoadFormat {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```

Represents file format which {@code LoadOptions} describes.

**Returns:**
LoadFormat element @see LoadFormat

### getWarningHandler {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```

Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease.

**Returns:**
IWarningCallback value

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
public final boolean isDisableFontLicenseVerifications()
```

Gets or sets flag to disable any license restrictions for all fonts while loading the file. When {@code }, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default {@code }. Be careful when using this flag. When it is set it means that person who sets this flag, takes all responsibility of possible license/law violations on himself. So he takes it on it's own risk. It's strongly recommended to use this flag only when you are fully confident that you are not breaking the copyright law.

**Returns:**
boolean value

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
public final void setDisableFontLicenseVerifications(boolean value)
```

Gets or sets flag to disable any license restrictions for all fonts while loading the file. When {@code }, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default {@code }. Be careful when using this flag. When it is set it means that person who sets this flag, takes all responsibility of possible license/law violations on himself. So he takes it on it's own risk. It's strongly recommended to use this flag only when you are fully confident that you are not breaking the copyright law.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setWarningHandler {#setWarningHandler-com.aspose.pdf.WarningCallback-}
Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease.
