---
title: "HtmlSaveOptions.FontEncodingRules"
linktitle: "HtmlSaveOptions.FontEncodingRules"
second_title: "Справочник API Aspose.PDF для Java"
description: "Эта перечисление определяет правила, которые настраивают логику кодирования."
type: docs
weight: 2050
url: /ru/java/com.aspose.pdf/htmlsaveoptions.fontencodingrules/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.FontEncodingRules, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.FontEncodingRules, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.FontEncodingRules

```
public static final class HtmlSaveOptions.FontEncodingRules extends com.aspose.ms.System.Enum
```

Эта перечисление определяет правила, которые настраивают логику кодирования.

## Поля

| Поле | Описание |
| --- | --- |
| [DecreaseToUnicodePriorityLevel](#DecreaseToUnicodePriorityLevel) | ToUnicode — это специальный механизм, который помогает декодировать входные коды в символы Unicode. Согласно спецификации, он должен использоваться в качестве первого из всех механизмов получения символов Unicode для конкретного входного кода. Однако в некоторых документах используются нестандартные шрифты, и для корректного преобразования таких документов может потребоваться снизить приоритет ToUnicode и использовать другие механизмы декодирования входных кодов. |
| [Default](#Default) | Оставить логику кодирования «как есть» — в соответствии со спецификацией PDF. |

### DecreaseToUnicodePriorityLevel {#DecreaseToUnicodePriorityLevel}
```
public static final byte DecreaseToUnicodePriorityLevel
```

ToUnicode — это специальный механизм, который помогает декодировать входные коды в символы Unicode. Согласно спецификации, он должен использоваться в качестве первого из всех механизмов получения символов Unicode для конкретного входного кода. Однако в некоторых документах используются нестандартные шрифты, и для корректного преобразования таких документов может потребоваться снизить приоритет ToUnicode и использовать другие механизмы декодирования входных кодов.

### Default {#Default}
```
public static final byte Default
```

Оставить логику кодирования «как есть» — в соответствии со спецификацией PDF.
