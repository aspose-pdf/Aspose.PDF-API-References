---
title: "Класс HtmlDiffOutputGenerator"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Comparison.HtmlDiffOutputGenerator. Представляет класс для генерации HTML‑представления различий текстов. Удалённые разрывы строк обозначаются знаком абзаца."
type: docs
weight: 3310
url: /ru/net/aspose.pdf.comparison/htmldiffoutputgenerator/
---
## HtmlDiffOutputGenerator class

Представляет класс для генерации HTML‑представления различий текстов. Удалённые разрывы строк обозначаются знаком абзаца.

```csharp
public class HtmlDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor)() | Создаёт экземпляр класса `HtmlDiffOutputGenerator`. |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor_1)(OutputTextStyle) | Создаёт экземпляр класса `HtmlDiffOutputGenerator`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [DeleteStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/deletestyle/) { get; set; } | Получает и задаёт строку в стиле CSS для операции Delete. Пример: |
| [EqualStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/equalstyle/) { get; set; } | Получает и задаёт строку в стиле CSS для операции Equal. Пример: |
| [InsertStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/insertstyle/) { get; set; } | Получает и задаёт строку в стиле CSS для операции Insert. Пример: |
| [StrikethroughDeleted](../../aspose.pdf.comparison/htmldiffoutputgenerator/strikethroughdeleted/) { get; set; } | Получает или задаёт стиль text-decoration: line-through для операции delete. Значение по умолчанию — `False`. |

## Методы

| Имя | Описание |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |

### См. также

* interface [IFileOutputGenerator](../ifileoutputgenerator/)
* interface [IStringOutputGenerator](../istringoutputgenerator/)
* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


