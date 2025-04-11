---
title: Class Metadata
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Metadata. Предоставляет доступ к потоку XMP метаданных
type: docs
weight: 6950
url: /ru/net/aspose.pdf/metadata/
---
## Класс метаданных

Предоставляет доступ к потоку XMP метаданных.

```csharp
public sealed class Metadata : IDictionary<string, XmpValue>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.pdf/metadata/count/) { get; } | Получает количество элементов в коллекции. |
| [ExtensionFields](../../aspose.pdf/metadata/extensionfields/) { get; } | Получает словарь полей расширения. |
| [IsFixedSize](../../aspose.pdf/metadata/isfixedsize/) { get; } | Проверяет, имеет ли коллекция фиксированный размер. |
| [IsReadOnly](../../aspose.pdf/metadata/isreadonly/) { get; } | Проверяет, является ли коллекция только для чтения. |
| [IsSynchronized](../../aspose.pdf/metadata/issynchronized/) { get; } | Проверяет, синхронизирована ли коллекция. |
| [Item](../../aspose.pdf/metadata/item/) { get; set; } | Получает или устанавливает данные из метаданных. |
| [Keys](../../aspose.pdf/metadata/keys/) { get; } | Получает коллекцию ключей метаданных. |
| [NamespaceManager](../../aspose.pdf/metadata/namespacemanager/) { get; } | Получает менеджер пространств имен. |
| [SyncRoot](../../aspose.pdf/metadata/syncroot/) { get; } | Получает объект синхронизации коллекции. |
| [Values](../../aspose.pdf/metadata/values/) { get; } | Получает значения в метаданных. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../aspose.pdf/metadata/add/#add)(KeyValuePair&lt;string, XmpValue&gt;) | Добавляет пару с ключом и значением в словарь. |
| [Add](../../aspose.pdf/metadata/add/#add_3)(string, object) | Добавляет значение в метаданные. |
| [Add](../../aspose.pdf/metadata/add/#add_1)(string, XmpPdfAExtensionObject) | Добавляет расширение pdf в метаданные. |
| [Add](../../aspose.pdf/metadata/add/#add_2)(string, XmpValue) | Добавляет значение в метаданные. |
| [Clear](../../aspose.pdf/metadata/clear/)() | Очищает метаданные. |
| [Contains](../../aspose.pdf/metadata/contains/#contains)(KeyValuePair&lt;string, XmpValue&gt;) | Проверяет, содержится ли указанная пара ключ-значение в словаре. |
| [Contains](../../aspose.pdf/metadata/contains/#contains_1)(string) | Проверяет, содержится ли ключ в метаданных. |
| [ContainsKey](../../aspose.pdf/metadata/containskey/)(string) | Определяет, содержит ли этот словарь указанный ключ. |
| [CopyTo](../../aspose.pdf/metadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/metadata/getenumerator/)() | Возвращает перечислитель словаря. |
| [GetNamespaceUriByPrefix](../../aspose.pdf/metadata/getnamespaceuribyprefix/)(string) | Возвращает URI пространства имен по префиксу. |
| [GetPrefixByNamespaceUri](../../aspose.pdf/metadata/getprefixbynamespaceuri/)(string) | Возвращает префикс по URI пространства имен. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri)(string, string) | Регистрирует URI пространства имен. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri_1)(string, string, string) | Регистрирует URI пространства имен. |
| [Remove](../../aspose.pdf/metadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | Удаляет пару ключ/значение из коллекции. |
| [Remove](../../aspose.pdf/metadata/remove/#remove_1)(string) | Удаляет запись из метаданных. |
| [TryGetValue](../../aspose.pdf/metadata/trygetvalue/)(string, out XmpValue) | Пытается найти ключ в словаре и извлекает значение, если найдено. |

### См. также

* класс [XmpValue](../xmpvalue/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)