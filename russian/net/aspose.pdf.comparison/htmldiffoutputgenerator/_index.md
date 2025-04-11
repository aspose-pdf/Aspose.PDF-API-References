---
title: Class HtmlDiffOutputGenerator
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Comparison.HtmlDiffOutputGenerator. Представляет класс для генерации html представления различий текстов. Удаленные разрывы строк обозначаются знаком абзаца
type: docs
weight: 3200
url: /ru/net/aspose.pdf.comparison/htmldiffoutputgenerator/
---
## Класс HtmlDiffOutputGenerator

Представляет класс для генерации html представления различий текстов. Удаленные разрывы строк обозначаются знаком абзаца.

```csharp
public class HtmlDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor)() | Создает экземпляр класса `HtmlDiffOutputGenerator`. |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor_1)(OutputTextStyle) | Создает экземпляр класса `HtmlDiffOutputGenerator`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [DeleteStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/deletestyle/) { get; set; } | Получает и устанавливает строку CSS-стиля для операции удаления. Пример: |
| [EqualStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/equalstyle/) { get; set; } | Получает и устанавливает строку CSS-стиля для операции равенства. Пример: |
| [InsertStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/insertstyle/) { get; set; } | Получает и устанавливает строку CSS-стиля для операции вставки. Пример: |
| [StrikethroughDeleted](../../aspose.pdf.comparison/htmldiffoutputgenerator/strikethroughdeleted/) { get; set; } | Получает или устанавливает стиль text-decoration: line-through для операции удаления. Значение по умолчанию `False`. |

## Методы

| Имя | Описание |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |

### См. также

* интерфейс [IFileOutputGenerator](../ifileoutputgenerator/)
* интерфейс [IStringOutputGenerator](../istringoutputgenerator/)
* пространство имен [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* сборка [Aspose.PDF](../../)