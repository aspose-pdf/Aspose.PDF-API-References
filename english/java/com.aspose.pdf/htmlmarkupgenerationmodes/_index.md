---
title: HtmlSaveOptions.HtmlMarkupGenerationModes
second_title: Aspose.PDF for Java API Reference
description: Sometimes specific reqirments to created HTML are present.
type: docs
weight: 19
url: /java/com.aspose.pdf/htmlsaveoptions.htmlmarkupgenerationmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public static final class HtmlSaveOptions.HtmlMarkupGenerationModes extends System.Enum
```

Sometimes specific reqirments to created HTML are present. This enum defines HTML preparing modes that can be used during conversion of PDF to HTML to match such specific requirments.
## Fields

| Field | Description |
| --- | --- |
| [WriteAllHtml](#WriteAllHtml) | Default mode any specific requirments are absent. |
| [WriteOnlyBodyContent](#WriteOnlyBodyContent) | will be stripped away all HTML content that is outside HTML's body, i.e. will be left only content that is inside    tags |
### WriteAllHtml {#WriteAllHtml}
```
public static final int WriteAllHtml
```


Default mode any specific requirments are absent. Will be generated output that will contain all parts of HTML without any special additional processing.

### WriteOnlyBodyContent {#WriteOnlyBodyContent}
```
public static final int WriteOnlyBodyContent
```


will be stripped away all HTML content that is outside HTML's body, i.e. will be left only content that is inside    tags

