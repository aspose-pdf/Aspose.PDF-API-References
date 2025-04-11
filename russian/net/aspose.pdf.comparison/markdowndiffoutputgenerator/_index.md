---
title: Class MarkdownDiffOutputGenerator
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Comparison.MarkdownDiffOutputGenerator. Представляет класс для генерации markdown представления различий текстов. Из-за синтаксиса markdown невозможно показать изменения в символах пробела. Выбор изменений требует добавления символов пробела вокруг форматирования, иначе просмотрщик markdown не сможет корректно отобразить текст. Удаленные разрывы строк обозначаются знаком абзаца.
type: docs
weight: 3250
url: /ru/net/aspose.pdf.comparison/markdowndiffoutputgenerator/
---
## Класс MarkdownDiffOutputGenerator

Представляет класс для генерации markdown представления различий текстов. Из-за синтаксиса markdown невозможно показать изменения в символах пробела. Выбор изменений требует добавления символов пробела вокруг форматирования, иначе просмотрщик markdown не сможет корректно отобразить текст. Удаленные разрывы строк обозначаются знаком абзаца.

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

* интерфейс [IFileOutputGenerator](../ifileoutputgenerator/)
* интерфейс [IStringOutputGenerator](../istringoutputgenerator/)
* пространство имен [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* сборка [Aspose.PDF](../../)