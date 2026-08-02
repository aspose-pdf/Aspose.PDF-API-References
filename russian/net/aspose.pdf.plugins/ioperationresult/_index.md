---
title: "Интерфейс IOperationResult"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Интерфейс Aspose.Pdf.Plugins.IOperationResult. Общий интерфейс результата операции, который определяет общие методы, которые конкретный результат плагина операции должен реализовать"
type: docs
weight: 8980
url: /ru/net/aspose.pdf.plugins/ioperationresult/
---
## IOperationResult interface

Общий интерфейс результата операции, определяющий общие методы, которые конкретный результат операции плагина должен реализовать.

```csharp
public interface IOperationResult
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Data](../../aspose.pdf.plugins/ioperationresult/data/) { get; } | Получает необработанные данные. |
| [IsFile](../../aspose.pdf.plugins/ioperationresult/isfile/) { get; } | Указывает, является ли результат путём к выходному файлу. |
| [IsStream](../../aspose.pdf.plugins/ioperationresult/isstream/) { get; } | Указывает, является ли результат выходным потоком. |
| [IsString](../../aspose.pdf.plugins/ioperationresult/isstring/) { get; } | Указывает, является ли результат текстовой строкой. |

## Методы

| Имя | Описание |
| --- | --- |
| [ToFile](../../aspose.pdf.plugins/ioperationresult/tofile/)() | Пытается преобразовать результат в файл. |
| [ToStream](../../aspose.pdf.plugins/ioperationresult/tostream/)() | Пытается преобразовать результат в объект потока. |

### См. также

* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


