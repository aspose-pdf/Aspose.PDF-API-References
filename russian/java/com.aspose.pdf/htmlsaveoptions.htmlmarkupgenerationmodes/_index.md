---
title: "HtmlSaveOptions.HtmlMarkupGenerationModes"
linktitle: "HtmlSaveOptions.HtmlMarkupGenerationModes"
second_title: "Справочник API Aspose.PDF для Java"
description: "Иногда присутствуют специфические требования к создаваемому HTML. Этот перечисление определяет режимы подготовки HTML, которые могут использоваться при конвертации PDF в HTML для соответствия таким специфическим требованиям."
type: docs
weight: 2090
url: /ru/java/com.aspose.pdf/htmlsaveoptions.htmlmarkupgenerationmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.HtmlMarkupGenerationModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.HtmlMarkupGenerationModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.HtmlMarkupGenerationModes

```
public static final class HtmlSaveOptions.HtmlMarkupGenerationModes extends com.aspose.ms.System.Enum
```

Иногда присутствуют специфические требования к создаваемому HTML. Этот перечисление определяет режимы подготовки HTML, которые могут использоваться при конвертации PDF в HTML для соответствия таким специфическим требованиям.

## Поля

| Поле | Описание |
| --- | --- |
| [WriteAllHtml](#WriteAllHtml) | Режим по умолчанию, когда отсутствуют какие-либо специфические требования. Будет сгенерирован вывод, содержащий все части HTML без какой-либо специальной дополнительной обработки. |
| [WriteOnlyBodyContent](#WriteOnlyBodyContent) | будет удалено всё содержимое HTML, находящееся за пределами тела HTML, т.е. останется только содержимое, находящееся внутри тегов {@code }. |

### WriteAllHtml {#WriteAllHtml}
```
public static final int WriteAllHtml
```

Режим по умолчанию, когда отсутствуют какие-либо специфические требования. Будет сгенерирован вывод, содержащий все части HTML без какой-либо специальной дополнительной обработки.

### WriteOnlyBodyContent {#WriteOnlyBodyContent}
```
public static final int WriteOnlyBodyContent
```

будет удалено всё содержимое HTML, находящееся за пределами тела HTML, т.е. останется только содержимое, находящееся внутри тегов {@code }.
