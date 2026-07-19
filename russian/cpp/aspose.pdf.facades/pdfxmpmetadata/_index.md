---
title: "Aspose::Pdf::Facades::PdfXmpMetadata class"
linktitle: "PdfXmpMetadata"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfXmpMetadata class. Класс для работы с XMP‑метаданными в C++."
type: docs
weight: 3100
url: /ru/cpp/aspose.pdf.facades/pdfxmpmetadata/
---
## PdfXmpMetadata class


Класс для работы с XMP‑метаданными.

```cpp
class PdfXmpMetadata : public Aspose::Pdf::Facades::SaveableFacade,
                       public System::Collections::Generic::IDictionary<System::String, System::SharedPtr<XmpValue>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const DefaultMetadataProperties\&, const System::SharedPtr\<XmpValue\>\&) | Добавляет значение в XMP‑метаданные. |
| [Add](./add/)(const System::SharedPtr\<XmpPdfAExtensionObject\>\&, const System::String\&, const System::String\&, const System::String\&) | Добавляет поле расширения в метаданные. |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<XmpValue\>\&) override | Добавляет новый элемент в объект словаря. |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<System::Object\>\&) | Добавляет новый элемент в объект словаря. |
| [Add](./add/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) override | Добавляет пару ключ‑значение в словарь. |
| [Clear](./clear/)() override | Удаляет все элементы из объекта. |
| [Contains](./contains/)(const System::String\&) const | Проверяет, содержит ли словарь указанный ключ. |
| [Contains](./contains/)(const DefaultMetadataProperties\&) const | Проверяет, содержит ли словарь указанное свойство. |
| [Contains](./contains/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) const override | Проверяет, содержится ли указанная пара ключ‑значение в словаре. |
| [ContainsKey](./containskey/)(const System::String\&) const override | Определяет, содержит ли этот словарь указанный ключ. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\>, int32_t) override | Копирует метаданные в массив. |
| [get_Count](./get_count/)() const override | Получает количество элементов в коллекции. |
| [get_ExtensionFields](./get_extensionfields/)() | Получает словарь полей расширения. |
| [get_IsFixedSize](./get_isfixedsize/)() const | Возвращает true, если коллекция имеет фиксированный размер. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Возвращает true, если коллекция только для чтения. |
| [get_IsSynchronized](./get_issynchronized/)() | Возвращает true, если коллекция синхронизирована. |
| [get_Keys](./get_keys/)() const override | Получает ключи из словаря. |
| [get_Values](./get_values/)() const override | Получает коллекцию значений в словаре. |
| [GetEnumerator](./getenumerator/)() override | Получает объект перечислителя словаря. |
| [GetNamespaceURIByPrefix](./getnamespaceuribyprefix/)(const System::String\&) | Получает URI пространства имён по префиксу. |
| [GetPrefixByNamespaceURI](./getprefixbynamespaceuri/)(const System::String\&) | Получает префикс по URI пространства имён. |
| [GetXmpMetadata](./getxmpmetadata/)() | Получить XmpMetadata входного pdf в формате xml. |
| [GetXmpMetadata](./getxmpmetadata/)(const System::String\&) | Получить часть XmpMetadata входного pdf согласно имени метаданных. |
| [idx_get](./idx_get/)(const System::String\&) const override | Получает значение по ключу. |
| [idx_get](./idx_get/)(const DefaultMetadataProperties\&) const | Получает значение XMP‑метаданных по ключу. |
| [idx_set](./idx_set/)(const System::String\&, System::SharedPtr\<XmpValue\>) override | Устанавливает значение по ключу. |
| [idx_set](./idx_set/)(const DefaultMetadataProperties\&, const System::SharedPtr\<XmpValue\>\&) | Получает значение XMP‑метаданных по ключу. |
| [PdfXmpMetadata](./pdfxmpmetadata/)() | Конструктор для [PdfXmpMetadata](./). |
| [PdfXmpMetadata](./pdfxmpmetadata/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Инициализирует новый объект [PdfXmpMetadata](./) на основе *document*. |
| [RegisterNamespaceURI](./registernamespaceuri/)(const System::String\&, const System::String\&) | Регистрирует URI пространства имён. |
| [Remove](./remove/)(DefaultMetadataProperties) | Удаляет элемент с указанным ключом. |
| [Remove](./remove/)(const System::String\&) override | Удаляет ключ из словаря. |
| [Remove](./remove/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) override | Удаляет пару ключ/значение из коллекции. |
| [TryGetValue](./trygetvalue/)(const System::String\&, System::SharedPtr\<XmpValue\>\&) const override | Пытается найти ключ в словаре и получить значение, если найден. |
## См. также

* Class [SaveableFacade](../saveablefacade/)
* Class [IDictionary](../../system.collections.generic/idictionary/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
