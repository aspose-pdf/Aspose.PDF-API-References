---
title: TrySubstitute
second_title: Aspose.PDF для справочника API .NET
description: Заменяет исходный шрифт другим шрифтом.
type: docs
weight: 20
url: /ru/net/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## CustomFontSubstitutionBase.TrySubstitute method

Заменяет исходный шрифт другим шрифтом.

```csharp
public virtual bool TrySubstitute(OriginalFontSpecification originalFontSpecification, 
    out Font substitutionFont)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| originalFontSpecification | OriginalFontSpecification | Оригинальная спецификация шрифта. |
| substitutionFont | Font& | Подстановочный шрифт. |

### Возвращаемое значение

Верно, если замена прошла успешно.

### Примечания

Класс CustomFontSubstitutionBase должен быть унаследован для реализации пользовательской логики замены шрифта. Метод TrySubstitute должен быть правильно переопределен: Должен возвращать значение true, если требуется замена. Для substitutionFont должен быть задан действительный объект Font. Должен возвращать значение false, если подстановка не требуется. substitutionFont может иметь значение null.

### Смотрите также

* class [OriginalFontSpecification](../../customfontsubstitutionbase.originalfontspecification)
* class [Font](../../font)
* class [CustomFontSubstitutionBase](../../customfontsubstitutionbase)
* пространство имен [Aspose.Pdf.Text](../../customfontsubstitutionbase)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->