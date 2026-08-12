---
title: "Класс Aspose::Pdf::Text::IFontSubstitutionCallback"
linktitle: "IFontSubstitutionCallback"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Text::IFontSubstitutionCallback. Этот интерфейс объявляет механизм обратного вызова для отправки уведомлений в C++."
type: docs
weight: 1800
url: /ru/cpp/aspose.pdf.text/ifontsubstitutioncallback/
---
## IFontSubstitutionCallback class


Этот интерфейс объявляет механизм обратного вызова для отправки уведомлений.

```cpp
class IFontSubstitutionCallback : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [get_NotifyAboutFontSubstitutions](./get_notifyaboutfontsubstitutions/)() | Возвращает true, если замена шрифтов включена. |
| virtual [get_Registrar](./get_registrar/)() | IRegistrar для текущего документа. |
| virtual [NotifyAboutSubstitution](./notifyaboutsubstitution/)(System::SharedPtr\<Aspose::Pdf::Text::Font\>, System::SharedPtr\<Aspose::Pdf::Text::Font\>) | Отправляет уведомление о замене шрифтов через механизм событий. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
