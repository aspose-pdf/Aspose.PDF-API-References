---
title: "TextReplaceOptions.FontSizeAdjustment"
linktitle: "TextReplaceOptions.FontSizeAdjustment"
second_title: "Справочник API Aspose.PDF для Java"
description: "Указывает политику того, как размер шрифта текста должен корректироваться, чтобы вписаться в ограничивающую область."
type: docs
weight: 5260
url: /ru/java/com.aspose.pdf/textreplaceoptions.fontsizeadjustment/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < TextReplaceOptions.FontSizeAdjustment > com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment, java.lang.Enum < TextReplaceOptions.FontSizeAdjustment >, com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment

**All Implemented Interfaces:**
Serializable, Comparable < TextReplaceOptions.FontSizeAdjustment >

```
public static enum TextReplaceOptions.FontSizeAdjustment extends Enum < TextReplaceOptions.FontSizeAdjustment >
```

Указывает политику того, как размер шрифта текста должен корректироваться, чтобы вписаться в ограничивающую область.

## Поля

| Поле | Описание |
| --- | --- |
| [None](#None) | Размер шрифта не изменяется. |
| [ScaleToFill](#ScaleToFill) | Размер шрифта корректируется (как уменьшается, так и увеличивается), чтобы текст максимально заполнял границы прямоугольника. |
| [ShrinkToFit](#ShrinkToFit) | Размер шрифта уменьшается, если текст слишком велик, чтобы поместиться в границы. |

## Методы

| Метод | Описание |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Возвращает константу перечисления этого типа с указанным именем. |
| [values](#values--) | Возвращает массив, содержащий константы этого типа перечисления в порядке их объявления. |

### None {#None}
```
public static final TextReplaceOptions.FontSizeAdjustment None
```

Размер шрифта не изменяется.

### ScaleToFill {#ScaleToFill}
```
public static final TextReplaceOptions.FontSizeAdjustment ScaleToFill
```

Размер шрифта корректируется (как уменьшается, так и увеличивается), чтобы текст максимально заполнял границы прямоугольника.

### ShrinkToFit {#ShrinkToFit}
```
public static final TextReplaceOptions.FontSizeAdjustment ShrinkToFit
```

Размер шрифта уменьшается, если текст слишком велик, чтобы поместиться в границы.

### getByValue {#getByValue-int-}
```
public static TextReplaceOptions.FontSizeAdjustment getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Возвращает константу перечисления этого типа с указанным именем.

### values {#values--}
```
public static TextReplaceOptions.FontSizeAdjustment [] values()
```

Возвращает массив, содержащий константы этого типа перечисления в порядке их объявления.

**Returns:**
массив, содержащий константы этого типа перечисления в порядке их объявления
