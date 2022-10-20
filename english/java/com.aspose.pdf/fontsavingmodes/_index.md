---
title: HtmlSaveOptions.FontSavingModes
second_title: Aspose.PDF for Java API Reference
description: Enumerates modes that can be used for saving of fonts referenced in saved PDF
type: docs
weight: 16
url: /java/com.aspose.pdf/htmlsaveoptions.fontsavingmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public static final class HtmlSaveOptions.FontSavingModes extends System.Enum
```

Enumerates modes that can be used for saving of fonts referenced in saved PDF
## Fields

| Field | Description |
| --- | --- |
| [AlwaysSaveAsWOFF](#AlwaysSaveAsWOFF) | All referenced fonts will be saved and referenced as WOFF-fonts |
| [AlwaysSaveAsTTF](#AlwaysSaveAsTTF) | All referenced fonts will be saved and referenced as TTF-fonts |
| [AlwaysSaveAsEOT](#AlwaysSaveAsEOT) | All referenced fonts will be saved and referenced as EOT-fonts |
| [SaveInAllFormats](#SaveInAllFormats) | All referenced fonts will be saved (and referenced in CSS) as 3 independent files : EOT, TTH,WOFF. |
| [DontSave](#DontSave) | All referenced fonts will not be saved. |
### AlwaysSaveAsWOFF {#AlwaysSaveAsWOFF}
```
public static final int AlwaysSaveAsWOFF
```


All referenced fonts will be saved and referenced as WOFF-fonts

### AlwaysSaveAsTTF {#AlwaysSaveAsTTF}
```
public static final int AlwaysSaveAsTTF
```


All referenced fonts will be saved and referenced as TTF-fonts

### AlwaysSaveAsEOT {#AlwaysSaveAsEOT}
```
public static final int AlwaysSaveAsEOT
```


All referenced fonts will be saved and referenced as EOT-fonts

### SaveInAllFormats {#SaveInAllFormats}
```
public static final int SaveInAllFormats
```


All referenced fonts will be saved (and referenced in CSS) as 3 independent files : EOT, TTH,WOFF. It increases size of output data but makes output sutable for overhelming majority of web brawsers

### DontSave {#DontSave}
```
public static final int DontSave
```


All referenced fonts will not be saved.

