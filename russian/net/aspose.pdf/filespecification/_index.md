---
title: "Класс FileSpecification"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.FileSpecification. Класс, представляющий встроенный файл"
type: docs
weight: 4970
url: /ru/net/aspose.pdf/filespecification/
---
## FileSpecification class

Класс, представляющий встроенный файл.

```csharp
public sealed class FileSpecification : IDisposable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FileSpecification](filespecification/#constructor)() | Создать новую пустую спецификацию файла. |
| [FileSpecification](filespecification/#constructor_3)(string) | Конструктор для FileSpecification |
| [FileSpecification](filespecification/#constructor_1)(Stream, string) | Конструктор для спецификации файла. |
| [FileSpecification](filespecification/#constructor_4)(string, Annotation) | Конструктор для FileSpecification. |
| [FileSpecification](filespecification/#constructor_5)(string, string) | Конструктор для FileSpecification. |
| [FileSpecification](filespecification/#constructor_2)(Stream, string, string) | Конструктор для FileSpecification. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AFRelationship](../../aspose.pdf/filespecification/afrelationship/) { get; set; } | Связанное отношение файла. |
| [CollectionItem](../../aspose.pdf/filespecification/collectionitem/) { get; } | Получает элемент коллекции спецификации файла. |
| [Contents](../../aspose.pdf/filespecification/contents/) { get; set; } | Получает или задает файл содержимого. Это свойство возвращает данные, загруженные в память, что может вызвать исключение Out of memory при больших объёмах данных. Чтобы уменьшить использование памяти, пожалуйста, используйте StreamContents. |
| [Description](../../aspose.pdf/filespecification/description/) { get; set; } | Получает или задает текст, связанный со спецификацией файла. |
| [Encoding](../../aspose.pdf/filespecification/encoding/) { get; set; } | Получает или задает формат кодирования. Возможные значения: Zip — файл сжат с помощью ZIP, None — файл не сжат. |
| [EncryptedPayload](../../aspose.pdf/filespecification/encryptedpayload/) { get; } | Получает зашифрованные данные. |
| [FileSystem](../../aspose.pdf/filespecification/filesystem/) { get; set; } | Получает или задает имя файловой системы. |
| [IncludeContents](../../aspose.pdf/filespecification/includecontents/) { get; set; } | Если true, содержимое файла будет включено в спецификацию файла. |
| [MIMEType](../../aspose.pdf/filespecification/mimetype/) { get; set; } | Получает подтип встроенного файла |
| [Name](../../aspose.pdf/filespecification/name/) { get; set; } | Получает или задает имя спецификации файла. |
| [Params](../../aspose.pdf/filespecification/params/) { get; set; } | Получает параметры файла. |
| [StreamContents](../../aspose.pdf/filespecification/streamcontents/) { get; } | Получает содержимое файла как поток. Содержимое не загружается в память, что позволяет уменьшить использование памяти. Однако этот поток не поддерживает позиционирование и свойство Length. Если вам нужны эти возможности, пожалуйста, используйте свойство Contents вместо него. |
| [UnicodeName](../../aspose.pdf/filespecification/unicodename/) { get; set; } | Получает или задает Unicode‑имя спецификации файла. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.pdf/filespecification/dispose/)() | Освободить содержимое. |
| [GetValue](../../aspose.pdf/filespecification/getvalue/)(string) | Получает параметр, специфичный для приложения. |
| [SetValue](../../aspose.pdf/filespecification/setvalue/)(string, string) | Задает параметр, специфичный для приложения. |

### См. также

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


