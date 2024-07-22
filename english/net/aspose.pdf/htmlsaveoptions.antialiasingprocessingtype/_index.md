---
title: Enum HtmlSaveOptions.AntialiasingProcessingType
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsAntialiasingProcessingType enum. This enum describes possible antialiasing measures during conversion
type: docs
weight: 3920
url: /net/aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
## HtmlSaveOptions.AntialiasingProcessingType enumeration

This enum describes possible antialiasing measures during conversion

```csharp
public enum AntialiasingProcessingType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| NoAdditionalProcessing | `0` | no special antialiasing processing in use. This is an optimal option for overhelming majority of documents and it does not require additional time during conversion |
| TryCorrectResultHtml | `1` | In such case converter tries to detect places with ajacent background graphical elements and correct result HTML in relevant way. This option allows enhance result of export for documents that contain backgrounds built from several ajacent graphical elements (for such kind of documents PDF renderers , f.e. Acrobat Reader, usually try smooth boundaries of elements during rendering. With this option converter imitates that behaviour of PDF-renderers. This option allows enhance layout of result of export for some specific documents (that use such compound backgrounds), but it requires additional time for processng (usually about 10-15% of additional time). So usage of this mode in general case is not recommended. |

### See Also

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


