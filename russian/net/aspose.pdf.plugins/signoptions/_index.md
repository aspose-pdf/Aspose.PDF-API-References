---
title: Class SignOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Plugins.SignOptions. Представляет параметры подписи для плагина подписи
type: docs
weight: 9250
url: /ru/net/aspose.pdf.plugins/signoptions/
---
## Класс SignOptions

Представляет параметры подписи для [`Signature`](../signature/) плагина.

```csharp
public sealed class SignOptions : OrganizerBaseOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SignOptions](signoptions/#constructor)(Stream, string) | Инициализирует новый экземпляр объекта `SignOptions` с параметрами по умолчанию. |
| [SignOptions](signoptions/#constructor_1)(string, string) | Инициализирует новый экземпляр объекта `SignOptions` с параметрами по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | Закрыть входные потоки после завершения операции. |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | Закрыть выходные потоки после завершения операции. |
| [Contact](../../aspose.pdf.plugins/signoptions/contact/) { get; set; } | Контакт для подписи. |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | Возвращает коллекцию данных плагина OrganizerOptions. |
| [Location](../../aspose.pdf.plugins/signoptions/location/) { get; set; } | Местоположение подписи. |
| [Name](../../aspose.pdf.plugins/signoptions/name/) { get; set; } | Имя существующего поля подписи. Null для создания нового поля. |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | Получает коллекцию добавленных целей для сохранения результатов операции. |
| [PageNumber](../../aspose.pdf.plugins/signoptions/pagenumber/) { get; set; } | Номер страницы, на которой сделана подпись. |
| [Reason](../../aspose.pdf.plugins/signoptions/reason/) { get; set; } | Причина подписи. |
| [Rectangle](../../aspose.pdf.plugins/signoptions/rectangle/) { get; set; } | Прямоугольник подписи. |
| [Visible](../../aspose.pdf.plugins/signoptions/visible/) { get; set; } | Видимость подписи. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | Добавляет новый источник данных в коллекцию данных плагина PdfOrganizer. |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | Добавляет новый источник данных в коллекцию данных плагина PdfOrganizer. |

### См. также

* класс [OrganizerBaseOptions](../organizerbaseoptions/)
* пространство имен [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* сборка [Aspose.PDF](../../)