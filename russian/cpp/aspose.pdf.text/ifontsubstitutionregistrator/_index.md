---
title: "Aspose::Pdf::Text::IFontSubstitutionRegistrator class"
linktitle: "IFontSubstitutionRegistrator"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::IFontSubstitutionRegistrator class. Этот интерфейс объявляет необходимый функционал для регистрации замен шрифтов в C++."
type: docs
weight: 1900
url: /ru/cpp/aspose.pdf.text/ifontsubstitutionregistrator/
---
## IFontSubstitutionRegistrator class


Этот интерфейс объявляет необходимый функционал для регистрации замен шрифтов.

```cpp
class IFontSubstitutionRegistrator : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [GetAllSubstitutions](./getallsubstitutions/)() | Этот метод должен возвращать все замены, зарегистрированные для текущего документа. Добавлен для целей трассировки. |
| virtual [RegistrySubstitution](./registrysubstitution/)(System::SharedPtr\<Engine::CommonData::Text::Fonts::IPdfFont\>, System::SharedPtr\<Engine::CommonData::Text::Fonts::IPdfFont\>, System::SharedPtr\<Engine::Data::ITrailerable\>) | Регистрировать замену для переданных шрифтов. Шрифты передаются как объекты IPdfFont в этом методе. |
| virtual [RegistrySubstitution](./registrysubstitution/)(System::SharedPtr\<Aspose::Font::Sources::FontDefinition\>, System::SharedPtr\<Aspose::Font::Sources::FontDefinition\>) | Регистрировать замену для шрифтов, представленных объектами FontDefinition. Этот метод был добавлен из‑за необходимости регистрировать "неявные" замены, которые находятся в объекте PdfFont. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
