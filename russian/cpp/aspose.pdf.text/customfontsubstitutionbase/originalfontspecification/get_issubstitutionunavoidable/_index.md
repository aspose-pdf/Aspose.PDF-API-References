---
title: "Aspose::Pdf::Text::CustomFontSubstitutionBase::OriginalFontSpecification::get_IsSubstitutionUnavoidable method"
linktitle: "get_IsSubstitutionUnavoidable"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::CustomFontSubstitutionBase::OriginalFontSpecification::get_IsSubstitutionUnavoidable method. Получает значение, указывающее, что замена неизбежна в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf.text/customfontsubstitutionbase/originalfontspecification/get_issubstitutionunavoidable/
---
## OriginalFontSpecification::get_IsSubstitutionUnavoidable method


Получает значение, указывающее, что замена неизбежна.

```cpp
bool Aspose::Pdf::Text::CustomFontSubstitutionBase::OriginalFontSpecification::get_IsSubstitutionUnavoidable() const
```

## Примечания


Возвращает true, если замена была запрошена из‑за отсутствия оригинального шрифта или если оригинальный шрифт нельзя использовать в контексте какой‑либо задачи. Если пользователь игнорирует флаг и не заменяет шрифт — выполняется процедура замены шрифта по умолчанию. Однако это предоставляет пользователю возможность изменить стандартную процедуру замены шрифта и установить более подходящий шрифт в системе.

Возвращает false, если оригинальный шрифт присутствует, действителен, но пользователю разрешено его заменить.
## См. также

* Class [OriginalFontSpecification](../)
* Class [CustomFontSubstitutionBase](../../)
* Namespace [Aspose::Pdf::Text](../../../)
* Library [Aspose.PDF for C++](../../../../)
