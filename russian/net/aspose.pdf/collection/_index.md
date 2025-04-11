---
title: Class Collection
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Collection. Представляет класс для Collection12.3.5 Коллекции
type: docs
weight: 3020
url: /ru/net/aspose.pdf/collection/
---
## Класс Коллекция

Представляет класс для Collection(12.3.5 Коллекции).

```csharp
public class Collection : EmbeddedFileCollection
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Collection](collection/)() | Инициализирует новый объект Коллекция. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.pdf/embeddedfilecollection/count/) { get; } | Получает количество встроенных файлов в коллекции. |
| [DefaultEntry](../../aspose.pdf/collection/defaultentry/) { get; } | Имя по умолчанию для встроенного файла. |
| [IsSynchronized](../../aspose.pdf/embeddedfilecollection/issynchronized/) { get; } | Получает значение, указывающее, синхронизирован ли доступ к этой коллекции (безопасно для потоков). |
| [Item](../../aspose.pdf/embeddedfilecollection/item/) { get; } | Получает встроенный файл по его индексу. (2 индексатора) |
| [Keys](../../aspose.pdf/embeddedfilecollection/keys/) { get; } | Возвращает список ключей вложенных файлов. |
| [Schema](../../aspose.pdf/collection/schema/) { get; } | Получает "Схему" коллекции документов. |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot/) { get; } | Получает объект, который можно использовать для синхронизации доступа к этой коллекции. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(FileSpecification) | Добавляет спецификацию встроенного файла в коллекцию. |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(string, FileSpecification) | Добавляет файл во встроенные файлы с указанным ключом. |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto/)(FileSpecification[], int) | Копирует массив объектов FileSpecification в коллекцию. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)() | Удаляет все встроенные файлы из документа. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)(string) | Удаляет встроенный файл по имени. |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey/)(string) | Удаляет файл из коллекции по его ключу в коллекции. |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname/)(string) | Возвращает встроенный файл по его имени. |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator/)() | Возвращает перечислитель коллекции. |
| [GetSortedCollection](../../aspose.pdf/collection/getsortedcollection/)() | Получает коллекцию файлов, отсортированных в соответствии со спецификацией. |

### См. также

* класс [EmbeddedFileCollection](../embeddedfilecollection/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)