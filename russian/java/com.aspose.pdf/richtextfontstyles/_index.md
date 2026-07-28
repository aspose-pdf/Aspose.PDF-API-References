---
title: "RichTextFontStyles"
linktitle: "RichTextFontStyles"
second_title: "Справочник API Aspose.PDF для Java"
description: "Параметры стилизации текстовых фрагментов в RichText."
type: docs
weight: 4300
url: /ru/java/com.aspose.pdf/richtextfontstyles/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.RichTextFontStyles, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.RichTextFontStyles, com.aspose.ms.System.Enum, com.aspose.pdf.RichTextFontStyles

```
public final class RichTextFontStyles extends com.aspose.ms.System.Enum
```

Параметры стилизации текстовых фрагментов в RichText.

## Поля

| Поле | Описание |
| --- | --- |
| [Bold](#Bold) | Опция, указывающая полужирный шрифт. |
| [ClearExisting](#ClearExisting) | Если установлено, очищает все существующие стили перед применением дополнительных. При комбинировании с другими флагами стилей (например, {@code RichTextFontStyles#Bold}) сначала сбрасываются стили, затем применяются указанные. Без этого флага новые стили добавляются к существующим. |
| [Italic](#Italic) | Опция, указывающая курсив. |
| [Underline](#Underline) | Опция, указывающая подчеркивание. |

## Методы

| Метод | Описание |
| --- | --- |
| [hasFlag](#hasFlag-int-int-) | Проверяет, установлен ли указанный флаг. |

### Bold {#Bold}
```
public static final int Bold
```

Опция, указывающая полужирный шрифт.

### ClearExisting {#ClearExisting}
```
public static final int ClearExisting
```

Если установлено, очищает все существующие стили перед применением дополнительных. При комбинировании с другими флагами стилей (например, {@code RichTextFontStyles#Bold}) сначала сбрасываются стили, затем применяются указанные. Без этого флага новые стили добавляются к существующим.

### Italic {#Italic}
```
public static final int Italic
```

Опция, указывающая курсив.

### Underline {#Underline}
```
public static final int Underline
```

Опция, указывающая подчеркивание.

### hasFlag {#hasFlag-int-int-}
```
public static boolean hasFlag(int flag, int flagToCheck)
```

Проверяет, установлен ли указанный флаг.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| флаг |  | значение перечисления, представляющее проверяемый флаг |
| flagToCheck |  | значение перечисления, представляющее проверяемый флаг |

**Returns:**
{@code true}, если флаг установлен; {@code false} в противном случае
