---
title: "Класс Collection"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Collection. Представляет класс для Collection12.3.5 Collections"
type: docs
weight: 3130
url: /ru/net/aspose.pdf/collection/
---
## Collection class

Представляет класс для Collection(12.3.5 Collections).

```csharp
public class Collection : EmbeddedFileCollection
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Collection](collection/)() | Инициализирует новый объект Collection. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.pdf/embeddedfilecollection/count/) { get; } | Получает количество вложенных файлов в коллекции. |
| [DefaultEntry](../../aspose.pdf/collection/defaultentry/) { get; } | Имя вложенного файла по умолчанию. |
| [IsSynchronized](../../aspose.pdf/embeddedfilecollection/issynchronized/) { get; } | Получает значение, указывающее, синхронизирован ли доступ к этой коллекции (потокобезопасно). |
| [Item](../../aspose.pdf/embeddedfilecollection/item/) { get; } | Получает вложенный файл по его индексу. (2 индексатора) |
| [Keys](../../aspose.pdf/embeddedfilecollection/keys/) { get; } | Возвращает список ключей вложений файлов. |
| [Schema](../../aspose.pdf/collection/schema/) { get; } | Получает "Schema" коллекции документов. |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot/) { get; } | Получает объект, который можно использовать для синхронизации доступа к этой коллекции. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(FileSpecification) | Добавляет спецификацию вложенного файла в коллекцию. |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(string, FileSpecification) | Добавляет файл во вложенные файлы с указанным ключом. |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto/)(FileSpecification[], int) | Копирует массив объектов FileSpecification в colleciton. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)() | Удалить все вложенные файлы из документа. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)(string) | Удалить вложенный файл по имени. |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey/)(string) | Удаляет файл из коллекции по его ключу в коллекции. |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname/)(string) | Возвращает вложенный файл по его имени. |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator/)() | Возвращает enumerator colleciton. |
| [GetSortedCollection](../../aspose.pdf/collection/getsortedcollection/)() | Получает коллекцию файлов, отсортированных согласно спецификации. |

### См. также

* class [EmbeddedFileCollection](../embeddedfilecollection/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


