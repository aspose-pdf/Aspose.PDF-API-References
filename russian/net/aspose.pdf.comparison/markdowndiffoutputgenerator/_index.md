---
title: "Класс MarkdownDiffOutputGenerator"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Comparison.MarkdownDiffOutputGenerator. Представляет класс для создания markdown‑представления различий текста. Из‑за синтаксиса markdown невозможно отобразить изменения пробельных символов. Выбор изменений приводит к добавлению пробельных символов вокруг форматирования, иначе markdown‑просмотрщик некорректно отобразит текст. Удалённые разрывы строк обозначаются знаком абзаца."
type: docs
weight: 3360
url: /ru/net/aspose.pdf.comparison/markdowndiffoutputgenerator/
---
## MarkdownDiffOutputGenerator class

Представляет класс для генерации markdown‑представления различий текстов. Из‑за синтаксиса markdown невозможно отобразить изменения пробельных символов. Выбор изменений приводит к добавлению пробельных символов вокруг форматирования, иначе markdown‑просмотрщик некорректно отобразит текст. Удалённые разрывы строк обозначаются знаком абзаца «-».

```csharp
public class MarkdownDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MarkdownDiffOutputGenerator](markdowndiffoutputgenerator/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |

### См. также

* interface [IFileOutputGenerator](../ifileoutputgenerator/)
* interface [IStringOutputGenerator](../istringoutputgenerator/)
* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


