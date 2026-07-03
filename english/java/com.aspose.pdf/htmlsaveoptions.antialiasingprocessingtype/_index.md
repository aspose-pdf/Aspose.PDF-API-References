---
title: HtmlSaveOptions.AntialiasingProcessingType
linktitle: HtmlSaveOptions.AntialiasingProcessingType
second_title: Aspose.PDF for Java API Reference
description: This enum describes possible antialiasing measures during conversion
type: docs
weight: 2000
url: /java/com.aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType

```
public static final class HtmlSaveOptions.AntialiasingProcessingType extends com.aspose.ms.System.Enum
```

This enum describes possible antialiasing measures during conversion

## Fields

| Field | Description |
| --- | --- |
| [NoAdditionalProcessing](#NoAdditionalProcessing) | no special antialiasing processing in use. This is an optimal option for overhelming majority of documents and it does not require additional time during conversion |
| [TryCorrectResultHtml](#TryCorrectResultHtml) | In such case converter tries to detect places with ajacent background graphical elements and correct result HTML in relevant way. This option allows enhance result of export for documents that contain backgrounds built from several ajacent graphical elements (for such kind of documents PDF renderers , f.e. Acrobat Reader, usually try smooth boundaries of elements during rendering. With this option converter imitates that behaviour of PDF-renderers. This option allows enhance layout of result of export for some specific documents (that use such compound backgrounds), but it requires additional time for processng (usually about 10-15% of additional time). So usage of this mode in general case is not recommended. |

### NoAdditionalProcessing {#NoAdditionalProcessing}
```
public static final int NoAdditionalProcessing
```

no special antialiasing processing in use. This is an optimal option for overhelming majority of documents and it does not require additional time during conversion

### TryCorrectResultHtml {#TryCorrectResultHtml}
```
public static final int TryCorrectResultHtml
```

In such case converter tries to detect places with ajacent background graphical elements and correct result HTML in relevant way. This option allows enhance result of export for documents that contain backgrounds built from several ajacent graphical elements (for such kind of documents PDF renderers , f.e. Acrobat Reader, usually try smooth boundaries of elements during rendering. With this option converter imitates that behaviour of PDF-renderers. This option allows enhance layout of result of export for some specific documents (that use such compound backgrounds), but it requires additional time for processng (usually about 10-15% of additional time). So usage of this mode in general case is not recommended.
