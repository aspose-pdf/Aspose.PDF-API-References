---
title: Class EncryptionOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Plugins.EncryptionOptions. Представляет параметры шифрования для плагина безопасности
type: docs
weight: 8540
url: /ru/net/aspose.pdf.plugins/encryptionoptions/
---
## Класс EncryptionOptions

Представляет параметры шифрования для [`Security`](../security/) плагина.

```csharp
public class EncryptionOptions : OrganizerBaseOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EncryptionOptions](encryptionoptions/)(string, string, DocumentPrivilege, CryptoAlgorithm) | Инициализирует новый экземпляр объекта `EncryptionOptions` с параметрами по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | Закрыть входные потоки после завершения операции. |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | Закрыть выходные потоки после завершения операции. |
| [CryptoAlgorithm](../../aspose.pdf.plugins/encryptionoptions/cryptoalgorithm/) { get; set; } | Криптографический алгоритм, см. [`CryptoAlgorithm`](./cryptoalgorithm/) для получения подробной информации. |
| [DocumentPrivilege](../../aspose.pdf.plugins/encryptionoptions/documentprivilege/) { get; set; } | Права на документ, см. [`Permissions`](../../aspose.pdf/permissions/) для получения подробной информации. |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | Возвращает коллекцию данных плагина OrganizerOptions. |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | Получает коллекцию добавленных целей для сохранения результатов операции. |
| [OwnerPassword](../../aspose.pdf.plugins/encryptionoptions/ownerpassword/) { get; set; } | Пароль владельца. |
| [UserPassword](../../aspose.pdf.plugins/encryptionoptions/userpassword/) { get; set; } | Пароль пользователя. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | Добавляет новый источник данных в коллекцию данных плагина PdfOrganizer. |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | Добавляет новый источник данных в коллекцию данных плагина PdfOrganizer. |

### См. также

* класс [OrganizerBaseOptions](../organizerbaseoptions/)
* пространство имен [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* сборка [Aspose.PDF](../../)