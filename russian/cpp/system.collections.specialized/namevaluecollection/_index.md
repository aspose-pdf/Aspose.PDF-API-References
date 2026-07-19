---
title: "System::Collections::Specialized::NameValueCollection класс"
linktitle: "NameValueCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::Specialized::NameValueCollection класс. Коллекция связанных ключей String и значений String, к которым можно получить доступ либо по ключу, либо по индексу в C++."
type: docs
weight: 200
url: /ru/cpp/system.collections.specialized/namevaluecollection/
---
## NameValueCollection class


Коллекция связанных ключей [String](../../system/string/) и значений [String](../../system/string/), к которым можно получить доступ либо по ключу, либо по индексу.

```cpp
class NameValueCollection : public System::Collections::Generic::ICollection<System::String>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const String\&) override | Переопределить метод [ICollection](../../system.collections/icollection/) - не реализовано. |
| [Add](./add/)(const System::SharedPtr\<NameValueCollection\>\&) | Копирует элементы из указанного [NameValueCollection](./) в текущий. |
| virtual [Add](./add/)(const String\&, const String\&) | Добавляет запись с указанным именем и значением. |
| [Clear](./clear/)() override | Удаляет все элементы. |
| [Contains](./contains/)(const String\&) const override | Проверяет, присутствует ли элемент в коллекции. |
| [CopyTo](./copyto/)(System::ArrayPtr\<String\>, int32_t) override | Копирует элементы коллекции в существующие элементы массива. |
| virtual [Get](./get/)(const String\&) | Получает значения, связанные с указанным ключом. |
| virtual [get_AllKeys](./get_allkeys/)() | Получает все ключи. |
| [get_Count](./get_count/)() const override | Получает количество пар ключ/значение. |
| virtual [get_Keys](./get_keys/)() | Получает все ключи. |
| [GetEnumerator](./getenumerator/)() override | Получает перечислитель для перебора коллекции. |
| virtual [GetValues](./getvalues/)(const String\&) | Получает значения, связанные с указанным ключом. |
| [HasKeys](./haskeys/)() | Получает значение, указывающее, содержит ли [NameValueCollection](./) ключи, не равные null. |
| [idx_get](./idx_get/)(const String\&) | Получает значение по указанному индексу. |
| [idx_set](./idx_set/)(const String\&, const String\&) | Устанавливает значение записи. |
| [NameValueCollection](./namevaluecollection/)() | Инициализирует новый экземпляр класса [NameValueCollection](./), который пуст. |
| [NameValueCollection](./namevaluecollection/)(const System::SharedPtr\<NameValueCollection\>\&) | Копирует записи из указанного [NameValueCollection](./) в новый [NameValueCollection](./). |
| [Remove](./remove/)(const String\&) override | Удаляет конкретный элемент. |
| virtual [Set](./set/)(const String\&, const String\&) | Устанавливает значение записи. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Получает реализацию константного итератора begin для текущего контейнера. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Получает реализацию итератора begin для текущего контейнера. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Получает реализацию константного итератора end для текущего контейнера. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Получает реализацию итератора end для текущего контейнера. |
## См. также

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [System::Collections::Specialized](../)
* Library [Aspose.PDF for C++](../../)
