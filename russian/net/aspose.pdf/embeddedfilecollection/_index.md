---
title: Class EmbeddedFileCollection
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.EmbeddedFileCollection. Класс, представляющий коллекцию встроенных файлов
type: docs
weight: 4010
url: /ru/net/aspose.pdf/embeddedfilecollection/
---
## Класс EmbeddedFileCollection

Класс, представляющий коллекцию встроенных файлов.

```csharp
public class EmbeddedFileCollection : ICollection<FileSpecification>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.pdf/embeddedfilecollection/count/) { get; } | Получает количество встроенных файлов в коллекции. |
| [IsSynchronized](../../aspose.pdf/embeddedfilecollection/issynchronized/) { get; } | Получает значение, указывающее, синхронизирован ли доступ к этой коллекции (безопасно для потоков). |
| [Item](../../aspose.pdf/embeddedfilecollection/item/) { get; } | Получает встроенный файл по его индексу. (2 индексатора) |
| [Keys](../../aspose.pdf/embeddedfilecollection/keys/) { get; } | Возвращает список ключей вложенных файлов. |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot/) { get; } | Получает объект, который можно использовать для синхронизации доступа к этой коллекции. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add/#add)(FileSpecification) | Добавляет спецификацию встроенного файла в коллекцию. |
| [Add](../../aspose.pdf/embeddedfilecollection/add/#add_1)(string, FileSpecification) | Добавляет файл во встроенные файлы с указанным ключом. |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto/)(FileSpecification[], int) | Копирует массив объектов FileSpecification в коллекцию. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/#delete)() | Удаляет все встроенные файлы из документа. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/#delete_1)(string) | Удаляет встроенный файл по имени. |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey/)(string) | Удаляет файл из коллекции по его ключу в коллекции. |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname/)(string) | Возвращает встроенный файл по его имени. |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator/)() | Возвращает перечислитель коллекции. |

### См. также

* класс [FileSpecification](../filespecification/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)