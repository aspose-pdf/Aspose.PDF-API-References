---
title: "Aspose::Pdf::Comparison::MarkdownDiffOutputGenerator класс"
linktitle: "MarkdownDiffOutputGenerator"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Comparison::MarkdownDiffOutputGenerator класс. Представляет класс для создания markdown‑представления различий текстов. Из‑за синтаксиса markdown невозможно показать изменения пробельных символов. Выбор изменений приводит к добавлению пробельных символов вокруг форматирования, иначе markdown‑просмотрщик не отобразит текст корректно. Удалённые разрывы строк обозначаются символом - абзаца в C++."
type: docs
weight: 1100
url: /ru/cpp/aspose.pdf.comparison/markdowndiffoutputgenerator/
---
## MarkdownDiffOutputGenerator class


Представляет класс для генерации markdown‑представления различий текстов. Из‑за синтаксиса markdown невозможно отобразить изменения пробельных символов. Выделение изменений подразумевает добавление пробельных символов вокруг форматирования, иначе markdown‑просмотрщик некорректно отобразит текст. Удалённые разрывы строк обозначаются знаком «‑» абзаца.

```cpp
class MarkdownDiffOutputGenerator : public Aspose::Pdf::Comparison::IStringOutputGenerator,
                                    public Aspose::Pdf::Comparison::IFileOutputGenerator
```

## Методы

| Метод | Описание |
| --- | --- |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>) override | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>, System::String) override | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>) override | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>, System::String) override | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |
| [MarkdownDiffOutputGenerator](./markdowndiffoutputgenerator/)() | Создаёт экземпляр класса [MarkdownDiffOutputGenerator](./). |
## См. также

* Class [IStringOutputGenerator](../istringoutputgenerator/)
* Class [IFileOutputGenerator](../ifileoutputgenerator/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
