---
title: CustomFontSubstitutionBase.TrySubstitute
second_title: Aspose.PDF for .NET API Reference
description: Метод CustomFontSubstitutionBase. Заменяет оригинальный шрифт другим шрифтом
type: docs
weight: 20
url: /ru/net/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## Метод CustomFontSubstitutionBase.TrySubstitute

Заменяет оригинальный шрифт другим шрифтом.

```csharp
public virtual bool TrySubstitute(OriginalFontSpecification originalFontSpecification, 
    out Font substitutionFont)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| originalFontSpecification | OriginalFontSpecification | Спецификация оригинального шрифта. |
| substitutionFont | Font& | Шрифт замены. |

### Возвращаемое значение

True в случае успешной замены.

## Примечания

Класс CustomFontSubstitutionBase должен быть унаследован для реализации логики замены шрифтов. Метод TrySubstitute должен быть правильно переопределен: должен возвращать true в случае, если замена требуется. substitutionFont должен быть установлен на действительный объект Font. Должен возвращать false в случае, если замена не требуется. substitutionFont может быть установлен в null.

### См. также

* класс [OriginalFontSpecification](../../customfontsubstitutionbase.originalfontspecification/)
* класс [Font](../../font/)
* класс [CustomFontSubstitutionBase](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)