---
title: Interface IOperationResult
second_title: Aspose.PDF for .NET API Reference
description: Интерфейс Aspose.Pdf.Plugins.IOperationResult. Общий интерфейс результата операции, который определяет общие методы, которые должен реализовать конкретный результат операции плагина
type: docs
weight: 8850
url: /ru/net/aspose.pdf.plugins/ioperationresult/
---
## Интерфейс IOperationResult

Общий интерфейс результата операции, который определяет общие методы, которые должен реализовать конкретный результат операции плагина.

```csharp
public interface IOperationResult
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Data](../../aspose.pdf.plugins/ioperationresult/data/) { get; } | Получает необработанные данные. |
| [IsFile](../../aspose.pdf.plugins/ioperationresult/isfile/) { get; } | Указывает, является ли результат путем к выходному файлу. |
| [IsStream](../../aspose.pdf.plugins/ioperationresult/isstream/) { get; } | Указывает, является ли результат выходным потоком. |
| [IsString](../../aspose.pdf.plugins/ioperationresult/isstring/) { get; } | Указывает, является ли результат текстовой строкой. |

## Методы

| Имя | Описание |
| --- | --- |
| [ToFile](../../aspose.pdf.plugins/ioperationresult/tofile/)() | Пытается преобразовать результат в файл. |
| [ToStream](../../aspose.pdf.plugins/ioperationresult/tostream/)() | Пытается преобразовать результат в объект потока. |

### См. Также

* пространство имен [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* сборка [Aspose.PDF](../../)