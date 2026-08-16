---
title: "TextReplaceOptions.Scope"
linktitle: "TextReplaceOptions.Scope"
second_title: "Справочник API Aspose.PDF для Java"
description: "Область, в которой применяется операция замены текста REPLACE_FIRST по умолчанию. Этот устаревший параметр сохранён для совместимости. Он влияет на PdfContentEditor и не оказывает влияния на."
type: docs
weight: 5280
url: /ru/java/com.aspose.pdf/textreplaceoptions.scope/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < TextReplaceOptions.Scope > com.aspose.pdf.TextReplaceOptions.Scope, java.lang.Enum < TextReplaceOptions.Scope >, com.aspose.pdf.TextReplaceOptions.Scope

**All Implemented Interfaces:**
Serializable, Comparable < TextReplaceOptions.Scope >

```
public static enum TextReplaceOptions.Scope extends Enum < TextReplaceOptions.Scope >
```

Область, в которой применяется операция замены текста REPLACE_FIRST по умолчанию. Этот устаревший параметр сохранён для совместимости. Он влияет на PdfContentEditor и не оказывает влияния на TextFragmentAbsorber.

## Поля

| Поле | Описание |
| --- | --- |
| [REPLACE_ALL](#REPLACE_ALL) | Заменить все вхождения текста на всех затронутых страницах |
| [REPLACE_FIRST](#REPLACE_FIRST) | Заменить только первое вхождение текста на каждой из затронутых страниц |

## Методы

| Метод | Описание |
| --- | --- |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Возвращает константу перечисления этого типа с указанным именем. |
| [values](#values--) | Возвращает массив, содержащий константы этого типа перечисления в порядке их объявления. |

### REPLACE_ALL {#REPLACE_ALL}
```
public static final TextReplaceOptions.Scope REPLACE_ALL
```

Заменить все вхождения текста на всех затронутых страницах

### REPLACE_FIRST {#REPLACE_FIRST}
```
public static final TextReplaceOptions.Scope REPLACE_FIRST
```

Заменить только первое вхождение текста на каждой из затронутых страниц

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Возвращает константу перечисления этого типа с указанным именем.

### values {#values--}
```
public static TextReplaceOptions.Scope [] values()
```

Возвращает массив, содержащий константы этого типа перечисления в порядке их объявления.

**Returns:**
массив, содержащий константы этого типа перечисления в порядке их объявления
