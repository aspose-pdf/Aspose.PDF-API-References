---
title: "Aspose::Pdf::Metadata class"
linktitle: "Metadata"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Metadata. Предоставляет доступ к потоку XMP‑метаданных в C++."
type: docs
weight: 11200
url: /ru/cpp/aspose.pdf/metadata/
---
## Metadata class


Предоставляет доступ к потоку метаданных XMP.

```cpp
class Metadata : public System::Collections::Generic::IDictionary<System::String, System::SharedPtr<XmpValue>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<XmpValue\>\&) override | Добавляет значение в метаданные. |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<System::Object\>\&) | Добавляет значение в метаданные. |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<XmpPdfAExtensionObject\>\&) | Добавляет расширение pdf в метаданные. |
| [Add](./add/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) override | Добавляет пару ключ‑значение в словарь. |
| [Clear](./clear/)() override | Очищает метаданные. |
| [Contains](./contains/)(const System::String\&) const | Проверяет, содержится ли ключ в метаданных. |
| [Contains](./contains/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) const override | Проверяет, содержится ли указанная пара ключ‑значение в словаре. |
| [ContainsKey](./containskey/)(const System::String\&) const override | Определяет, содержит ли этот словарь указанный ключ. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\>, int32_t) override | Копирует элементы коллекции в массив. |
| [get_Count](./get_count/)() const override | Получает количество элементов в коллекции. |
| [get_ExtensionFields](./get_extensionfields/)() | Получает словарь полей расширения. |
| [get_IsFixedSize](./get_isfixedsize/)() const | Проверяет, имеет ли коллекция фиксированный размер. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Проверяет, является ли коллекция только для чтения. |
| [get_IsSynchronized](./get_issynchronized/)() | Проверяет, синхронизирована ли коллекция. |
| [get_Keys](./get_keys/)() const override | Получает коллекцию ключей метаданных. |
| [get_NamespaceManager](./get_namespacemanager/)() | Получает менеджер пространств имён. |
| [get_SyncRoot](./get_syncroot/)() const | Получает объект синхронизации коллекции. |
| [get_Values](./get_values/)() const override | Получает значения в метаданных. |
| [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель словаря. |
| [GetNamespaceUriByPrefix](./getnamespaceuribyprefix/)(const System::String\&) | Возвращает URI пространства имён по префиксу. |
| [GetPrefixByNamespaceUri](./getprefixbynamespaceuri/)(const System::String\&) | Возвращает префикс по URI пространства имён. |
| [idx_get](./idx_get/)(const System::String\&) const override | Получает данные из метаданных. |
| [idx_set](./idx_set/)(const System::String\&, System::SharedPtr\<XmpValue\>) override | Устанавливает данные в метаданных. |
| [RegisterNamespaceUri](./registernamespaceuri/)(const System::String\&, const System::String\&) | Регистрирует URI пространства имён. |
| [RegisterNamespaceUri](./registernamespaceuri/)(const System::String\&, const System::String\&, const System::String\&) | Регистрирует URI пространства имён. |
| [Remove](./remove/)(const System::String\&) override | Удаляет запись из метаданных. |
| [Remove](./remove/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) override | Удаляет пару ключ/значение из коллекции. |
| [TryGetValue](./trygetvalue/)(const System::String\&, System::SharedPtr\<XmpValue\>\&) const override | Пытается найти ключ в словаре и получить значение, если найден. |
## См. также

* Class [IDictionary](../../system.collections.generic/idictionary/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
