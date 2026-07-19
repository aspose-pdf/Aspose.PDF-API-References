---
title: "Aspose::Pdf::Comparison::HtmlDiffOutputGenerator class"
linktitle: "HtmlDiffOutputGenerator"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Comparison::HtmlDiffOutputGenerator class. Представляет класс для генерации HTML‑представления различий текстов. Удалённые разрывы строк обозначаются маркером абзаца в C++."
type: docs
weight: 700
url: /ru/cpp/aspose.pdf.comparison/htmldiffoutputgenerator/
---
## HtmlDiffOutputGenerator class


Представляет класс для генерации HTML‑представления различий текстов. Удалённые разрывы строк обозначаются знаком абзаца.

```cpp
class HtmlDiffOutputGenerator : public Aspose::Pdf::Comparison::IStringOutputGenerator,
                                public Aspose::Pdf::Comparison::IFileOutputGenerator
```

## Методы

| Метод | Описание |
| --- | --- |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>) override | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>, System::String) override | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>) override | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>, System::String) override | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |
| [get_DeleteStyle](./get_deletestyle/)() const | Получает и задаёт строку CSS‑стиля для операции Delete. Пример: **color: &#35;003300; background-color: &#35;ccff66;** |
| [get_EqualStyle](./get_equalstyle/)() const | Получает и задаёт строку CSS‑стиля для операции Equal. Пример: **color: &#35;003300; background-color: &#35;ccff66;** |
| [get_InsertStyle](./get_insertstyle/)() const | Получает и задаёт строку CSS‑стиля для операции Insert. Пример: **color: &#35;003300; background-color: &#35;ccff66;** |
| [get_StrikethroughDeleted](./get_strikethroughdeleted/)() const | Получить или задать стиль text-decoration: line-through для операции delete. Значение по умолчанию — **False**. |
| [HtmlDiffOutputGenerator](./htmldiffoutputgenerator/)() | Создает экземпляр класса [HtmlDiffOutputGenerator](./). |
| [HtmlDiffOutputGenerator](./htmldiffoutputgenerator/)(const System::SharedPtr\<OutputTextStyle\>\&) | Создает экземпляр класса [HtmlDiffOutputGenerator](./). |
| [set_DeleteStyle](./set_deletestyle/)(const System::String\&) | Получает и задаёт строку CSS‑стиля для операции Delete. Пример: **color: &#35;003300; background-color: &#35;ccff66;** |
| [set_EqualStyle](./set_equalstyle/)(const System::String\&) | Получает и задаёт строку CSS‑стиля для операции Equal. Пример: **color: &#35;003300; background-color: &#35;ccff66;** |
| [set_InsertStyle](./set_insertstyle/)(const System::String\&) | Получает и задаёт строку CSS‑стиля для операции Insert. Пример: **color: &#35;003300; background-color: &#35;ccff66;** |
| [set_StrikethroughDeleted](./set_strikethroughdeleted/)(bool) | Получить или задать стиль text-decoration: line-through для операции delete. Значение по умолчанию — **False**. |
## См. также

* Class [IStringOutputGenerator](../istringoutputgenerator/)
* Class [IFileOutputGenerator](../ifileoutputgenerator/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
