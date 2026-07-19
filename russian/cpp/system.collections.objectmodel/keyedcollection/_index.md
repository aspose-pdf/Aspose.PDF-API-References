---
title: "System::Collections::ObjectModel::KeyedCollection class"
linktitle: "KeyedCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::ObjectModel::KeyedCollection class. Абстрактная коллекция элементов с встроенными ключами. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 200
url: /ru/cpp/system.collections.objectmodel/keyedcollection/
---
## KeyedCollection class


Абстрактная коллекция элементов с встроенными ключами. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
template<typename TKey,typename TItem>class KeyedCollection : public System::Collections::ObjectModel::Collection<TItem>
```


| Параметр | Описание |
| --- | --- |
| TKey | Тип ключа. |
| TItem | тип значения. |
## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const TItem\&) override | Добавить элемент в конец контейнера. |
| [Contains](./contains/)(TKey) | Проверяет, присутствует ли ключ в контейнере. |
| [get_Comparer](./get_comparer/)() | Получает компаратор. |
| [idx_get](./idx_get/)(TKey) | Получает элемент по указанному индексу. |
| [Remove](./remove/)(TKey) | Удаляет ключ из контейнера. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Позволяет рассматривать конкретный аргумент шаблона как слабый указатель вместо разделяемого указателя (если применимо). |
## Поля

| Поле | Описание |
| --- | --- |
| static [defaultThreshold](./defaultthreshold/) | Порог создания словаря поиска, по умолчанию. |

## См. также

* Class [Collection](../collection/)
* Namespace [System::Collections::ObjectModel](../)
* Library [Aspose.PDF for C++](../../)
