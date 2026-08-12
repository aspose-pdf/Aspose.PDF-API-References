---
title: "Класс Aspose::Pdf::HtmlFragment"
linktitle: "HtmlFragment"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::HtmlFragment. Представляет HTML‑фрагмент на C++."
type: docs
weight: 7100
url: /ru/cpp/aspose.pdf/htmlfragment/
---
## HtmlFragment class


Представляет html‑фрагмент.

```cpp
class HtmlFragment : public Aspose::Pdf::FormattedFragment
```

## Методы

| Метод | Описание |
| --- | --- |
| [Clone](./clone/)() override | Клонирует HTML‑фрагмент. |
| [get_HtmlLoadOptions](./get_htmlloadoptions/)() const | Получает [HtmlLoadOptions](../htmlloadoptions/), которые будут использоваться для загрузки (и рендеринга) HTML в этот экземпляр класса. Пожалуйста, используйте их, когда необходимо задать специфические настройки импорта HTML для того или иного экземпляра (например, когда данный экземпляр должен использовать определённый BasePath для импортированного HTML или определённый загрузчик внешних ресурсов). Если параметр имеет значение по умолчанию (null), будут использованы стандартные параметры загрузки HTML. |
| [get_IsBreakWords](./get_isbreakwords/)() const | Получает разбиение слов. |
| [get_IsParagraphHasMargin](./get_isparagraphhasmargin/)() const | Определяет, имеет ли абзац отступ по умолчанию; иначе отступ равен 0. |
| [get_Rectangle](./get_rectangle/)() const | Получает прямоугольник [HtmlFragment](./). |
| [get_TextState](./get_textstate/)() const | Получает шрифт. |
| [HtmlFragment](./htmlfragment/)(const System::String\&) | Инициализирует новый экземпляр класса [HtmlFragment](./). |
| [set_HtmlLoadOptions](./set_htmlloadoptions/)(const System::SharedPtr\<Aspose::Pdf::HtmlLoadOptions\>\&) | Устанавливает [HtmlLoadOptions](../htmlloadoptions/), которые будут использоваться для загрузки (и рендеринга) HTML в этот экземпляр класса. Пожалуйста, используйте их, когда необходимо задать специфические настройки импорта HTML для того или иного экземпляра (например, когда данный экземпляр должен использовать определённый BasePath для импортируемого HTML или специфический загрузчик внешних ресурсов). Если параметр имеет значение по умолчанию (null), будут использованы стандартные параметры загрузки HTML. |
| [set_IsBreakWords](./set_isbreakwords/)(bool) | Устанавливает разрыв слов. |
| [set_IsParagraphHasMargin](./set_isparagraphhasmargin/)(bool) | Устанавливает, имеет ли абзац отступ по умолчанию; в противном случае отступ равен 0. |
| [set_TextState](./set_textstate/)(const System::SharedPtr\<Aspose::Pdf::Text::TextState\>\&) | Устанавливает шрифт. |
## См. также

* Class [FormattedFragment](../formattedfragment/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
