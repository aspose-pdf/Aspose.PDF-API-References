---
title: Class Tool
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.AI.Tool. Представляет инструмент, который может быть вызван моделью
type: docs
weight: 1190
url: /ru/net/aspose.pdf.ai/tool/
---
## Класс Tool

Представляет инструмент, который может быть вызван моделью.

```csharp
public class Tool
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Tool](tool/#constructor)() | Инициализирует новый экземпляр класса `Tool`. |
| [Tool](tool/#constructor_1)(Function) | Инициализирует новый экземпляр класса `Tool` с указанной функцией. |
| [Tool](tool/#constructor_2)(string) | Инициализирует новый экземпляр класса `Tool` с указанным типом инструмента. |

## Свойства

| Имя | Описание |
| --- | --- |
| static [CodeInterpreter](../../aspose.pdf.ai/tool/codeinterpreter/) { get; } | Получает экземпляр инструмента, представляющий интерпретатор кода. |
| static [FileSearch](../../aspose.pdf.ai/tool/filesearch/) { get; } | Получает экземпляр инструмента, представляющий инструмент поиска файлов. |
| [ToolFunction](../../aspose.pdf.ai/tool/toolfunction/) { get; set; } | Получает или задает функцию, которую может вызывать модель. |
| [ToolType](../../aspose.pdf.ai/tool/tooltype/) { get; set; } | Получает или задает тип инструмента. В настоящее время поддерживается только функция. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Function](../../aspose.pdf.ai/tool/function/)(Function) | Создает новый экземпляр инструмента с указанной функцией. |

### См. также

* пространство имен [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* сборка [Aspose.PDF](../../)