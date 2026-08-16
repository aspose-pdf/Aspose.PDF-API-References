---
title: "TextReplaceOptions.ReplaceAdjustment"
linktitle: "TextReplaceOptions.ReplaceAdjustment"
second_title: "Справочник API Aspose.PDF для Java"
description: "Определяет действие, которое будет выполнено после замены фрагмента текста на более короткий. None — без действия, заменённый текст может перекрывать остальную часть строки; AdjustSpaceWidth — пытается."
type: docs
weight: 5270
url: /ru/java/com.aspose.pdf/textreplaceoptions.replaceadjustment/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment, com.aspose.ms.System.Enum, com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment

```
public static final class TextReplaceOptions.ReplaceAdjustment extends com.aspose.ms.System.Enum
```

Определяет действие, которое будет выполнено после замены фрагмента текста на более короткий. None — без действия, заменённый текст может перекрывать остальную часть строки; AdjustSpaceWidth — пытается скорректировать пробелы между словами, чтобы сохранить длину строки; WholeWordsHyphenation — пытается распределить слова между строками абзаца, чтобы сохранить правое поле абзаца; ShiftRestOfLine — сдвигает оставшуюся часть строки в соответствии с изменением длины текста, длина строки может измениться; Значение по умолчанию — ShiftRestOfLine.

## Поля

| Поле | Описание |
| --- | --- |
| [AdjustSpaceWidth](#AdjustSpaceWidth) | Пытается скорректировать пробелы между словами, чтобы сохранить длину строки. |
| [IsFormFillingMode](#IsFormFillingMode) | Пытается распределить слова в доступном пустом пространстве, используя ширину абзаца. Если текст переполняет, он будет скрыт. |
| [None](#None) | Без действия, заменённый текст может перекрывать остальную часть строки. |
| [ShiftRestOfLine](#ShiftRestOfLine) | (По умолчанию) Сдвигает оставшуюся часть строки в соответствии с изменением длины текста, длина строки может измениться. |
| [WholeWordsHyphenation](#WholeWordsHyphenation) | Пытается распределить слова между строками абзаца, чтобы сохранить правое поле абзаца. |

## Методы

| Метод | Описание |
| --- | --- |
| [hasFlag](#hasFlag-int-int-) |  |

### AdjustSpaceWidth {#AdjustSpaceWidth}
```
public static final int AdjustSpaceWidth
```

Пытается скорректировать пробелы между словами, чтобы сохранить длину строки.

### IsFormFillingMode {#IsFormFillingMode}
```
public static final int IsFormFillingMode
```

Пытается распределить слова в доступном пустом пространстве, используя ширину абзаца. Если текст переполняет, он будет скрыт.

### None {#None}
```
public static final int None
```

Без действия, заменённый текст может перекрывать остальную часть строки.

### ShiftRestOfLine {#ShiftRestOfLine}
```
public static final int ShiftRestOfLine
```

(По умолчанию) Сдвигает оставшуюся часть строки в соответствии с изменением длины текста, длина строки может измениться.

### WholeWordsHyphenation {#WholeWordsHyphenation}
```
public static final int WholeWordsHyphenation
```

Пытается распределить слова между строками абзаца, чтобы сохранить правое поле абзаца.

### hasFlag {#hasFlag-int-int-}
```
public static boolean hasFlag(int flag, int flagToCheck)
```



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| флаг |  |  |
| flagToCheck |  |  |
