---
title: PdfXmpMetadata
second_title: Aspose.PDF для справочника API .NET
description: Класс для работы с метаданными XMP.
type: docs
weight: 2650
url: /ru/net/aspose.pdf.facades/pdfxmpmetadata/
---
## PdfXmpMetadata class

Класс для работы с метаданными XMP.

```csharp
public sealed class PdfXmpMetadata : SaveableFacade, IDictionary<string, XmpValue>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfXmpMetadata](pdfxmpmetadata#constructor)() | Конструктор для PdfXmpMetadata. |
| [PdfXmpMetadata](pdfxmpmetadata#constructor_1)(Document) | Инициализирует новый[`PdfXmpMetadata`](../pdfxmpmetadata) объект на базе*document* . |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.pdf.facades/pdfxmpmetadata/count) { get; } | Получает количество элементов в коллекции. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Получает фасад документа, над которым работает. |
| [ExtensionFields](../../aspose.pdf.facades/pdfxmpmetadata/extensionfields) { get; } | Получает словарь полей расширения. |
| [IsFixedSize](../../aspose.pdf.facades/pdfxmpmetadata/isfixedsize) { get; } | Возвращает true, если коллекция имеет фиксированный размер. |
| [IsReadOnly](../../aspose.pdf.facades/pdfxmpmetadata/isreadonly) { get; } | Возвращает true, если коллекция доступна только для чтения. |
| [IsSynchronized](../../aspose.pdf.facades/pdfxmpmetadata/issynchronized) { get; } | Возвращает true, если коллекция синхронизирована. |
| [Item](../../aspose.pdf.facades/pdfxmpmetadata/item) { get; set; } | Получает или устанавливает значение по ключу. (2 indexers) |
| [Keys](../../aspose.pdf.facades/pdfxmpmetadata/keys) { get; } | Получает ключи из словаря. |
| [SyncRoot](../../aspose.pdf.facades/pdfxmpmetadata/syncroot) { get; } | Получает объект синхронизации коллекции. |
| [Values](../../aspose.pdf.facades/pdfxmpmetadata/values) { get; } | Получает набор значений в словаре. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add_2)(KeyValuePair&lt;string, XmpValue&gt;) | Добавляет пару с ключом и значением в словарь. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add)(DefaultMetadataProperties, XmpValue) | Добавляет значение к метаданным XMP. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add_4)(string, object) | Добавляет новый элемент в объект словаря. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add_3)(string, XmpValue) | Добавляет новый элемент в объект словаря. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add_1)(XmpPdfAExtensionObject, string, string, string) | Добавляет поле расширения в метаданные. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Инициализирует фасад. |
| [Clear](../../aspose.pdf.facades/pdfxmpmetadata/clear)() | Удаляет все элементы из объекта. |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Удаляет Aspose.Pdf.Document, связанный с фасадом. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains#contains)(DefaultMetadataProperties) | Проверяет, содержит ли словарь указанное свойство. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains#contains_1)(KeyValuePair&lt;string, XmpValue&gt;) | Проверяет, содержится ли указанная пара ключ-значение в словаре. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains#contains_2)(string) | Проверяет, содержит ли словарь указанный ключ. |
| [ContainsKey](../../aspose.pdf.facades/pdfxmpmetadata/containskey)(string) | Определяет, содержит ли этот словарь указанный ключ. |
| [CopyTo](../../aspose.pdf.facades/pdfxmpmetadata/copyto)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Удаляет фасад. |
| [GetEnumerator](../../aspose.pdf.facades/pdfxmpmetadata/getenumerator)() | Получает объект перечислителя словаря. |
| [GetNamespaceURIByPrefix](../../aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix)(string) | Получает URI пространства имен по префиксу. |
| [GetPrefixByNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri)(string) | Получает префикс по URI пространства имен. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata#getxmpmetadata)() | Получить метаданные Xmp входного PDF-файла в формате xml. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata#getxmpmetadata_1)(string) | Получить часть метаданных Xmp входного PDF-файла в соответствии с мета-именем. |
| [RegisterNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri)(string, string) | Регистрирует URI пространства имен. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove#remove_2)(DefaultMetadataProperties) | Удаляет элемент с указанным ключом. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove#remove)(KeyValuePair&lt;string, XmpValue&gt;) | Удаляет пару ключ/значение из коллекции. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove#remove_1)(string) | Удаляет ключ из словаря. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Сохраняет документ PDF в указанный поток. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Сохраняет документ PDF в указанный файл. |
| [TryGetValue](../../aspose.pdf.facades/pdfxmpmetadata/trygetvalue)(string, out XmpValue) | Пытается найти ключ в словаре и извлекает значение, если оно найдено. |

### Смотрите также

* class [SaveableFacade](../saveablefacade)
* class [XmpValue](../../aspose.pdf/xmpvalue)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
