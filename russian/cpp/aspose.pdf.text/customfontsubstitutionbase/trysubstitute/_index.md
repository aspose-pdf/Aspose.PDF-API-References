---
title: "Aspose::Pdf::Text::CustomFontSubstitutionBase::TrySubstitute method"
linktitle: "TrySubstitute"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::CustomFontSubstitutionBase::TrySubstitute method. Заменяет оригинальный шрифт другим шрифтом в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## CustomFontSubstitutionBase::TrySubstitute method


Заменяет оригинальный шрифт другим шрифтом.

```cpp
virtual bool Aspose::Pdf::Text::CustomFontSubstitutionBase::TrySubstitute(System::SharedPtr<CustomFontSubstitutionBase::OriginalFontSpecification> originalFontSpecification, System::SharedPtr<Font> &substitutionFont)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| originalFontSpecification | System::SharedPtr\<CustomFontSubstitutionBase::OriginalFontSpecification\> | Спецификация оригинального шрифта. |
| substitutionFont | System::SharedPtr\<Font\>\& | Шрифт замены. |

### ReturnValue

True, если замена прошла успешно.
## Примечания


Класс [CustomFontSubstitutionBase](../) должен быть унаследован для реализации пользовательской логики замены шрифтов. Метод TrySubstitute должен быть правильно переопределён:

Должен возвращать true, если требуется замена. substitutionFont должен быть установлен в действительный объект [Font](../../font/). Должен возвращать false, если замена не требуется. substitutionFont может быть установлен в null.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [OriginalFontSpecification](../originalfontspecification/)
* Class [Font](../../font/)
* Class [CustomFontSubstitutionBase](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
