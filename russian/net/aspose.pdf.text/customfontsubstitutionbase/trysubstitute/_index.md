---
title: "CustomFontSubstitutionBase.TrySubstitute"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод CustomFontSubstitutionBase. Заменяет оригинальный шрифт другим шрифтом"
type: docs
weight: 20
url: /ru/net/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## CustomFontSubstitutionBase.TrySubstitute method

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

True, если замена прошла успешно.

## Примечания

Класс CustomFontSubstitutionBase должен быть унаследован для реализации пользовательской логики замены шрифтов. Метод TrySubstitute следует правильно переопределить: необходимо возвращать true, если замена требуется. substitutionFont должен быть установлен в действительный объект Font. Необходимо возвращать false, если замена не требуется. substitutionFont может быть установлен в null.

### См. также

* class [OriginalFontSpecification](../../customfontsubstitutionbase.originalfontspecification/)
* class [Font](../../font/)
* class [CustomFontSubstitutionBase](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


