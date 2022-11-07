---
title: HtmlSaveOptions.CssSavingInfo
second_title: Aspose.PDF for Java API Reference
description: This class represents set of data that related to custom saving of CSS during conversion of PDF to HTML format
type: docs
weight: 11
url: /java/com.aspose.pdf/htmlsaveoptions.csssavinginfo/
---
**Inheritance:**
java.lang.Object
```
public static class HtmlSaveOptions.CssSavingInfo
```

This class represents set of data that related to custom saving of CSS during conversion of PDF to HTML format
## Fields

| Field | Description |
| --- | --- |
| [CssNumber](#CssNumber) | Set by converter. |
| [SupposedURL](#SupposedURL) | Set by converter. |
| [ContentStream](#ContentStream) | Set by converter. |
### CssNumber {#CssNumber}
```
public int CssNumber
```


Set by converter. During conversion several CSS-files are created . This properties shows ordinal of saved CSS-file during conversion. It can be used in logic of custom code to decide how to process or where to save CSS content

### SupposedURL {#SupposedURL}
```
public String SupposedURL
```


Set by converter. Supposed file name that goes from converter to code of custom method Can be used in custom code to decide how to process or where to save content

### ContentStream {#ContentStream}
```
public System.IO.Stream ContentStream
```


Set by converter. Represents binary content of saved CSS

