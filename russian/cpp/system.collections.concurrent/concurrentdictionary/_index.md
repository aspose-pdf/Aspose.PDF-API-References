---
title: "System::Collections::Concurrent::ConcurrentDictionary класс"
linktitle: "ConcurrentDictionary"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::Concurrent::ConcurrentDictionary класс. Реализация потокобезопасного словаря. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 100
url: /ru/cpp/system.collections.concurrent/concurrentdictionary/
---
## ConcurrentDictionary class


Реализация потокобезопасного словаря. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
template<class TKey,class TValue>class ConcurrentDictionary : public System::Collections::Generic::Dictionary<TKey, TValue>
```


| Параметр | Описание |
| --- | --- |
| TKey | Тип ключа. |
| TValue | Тип значения. |
## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const TKey\&, const TValue\&) override | Добавляет значение в словарь. |
| [Clear](./clear/)() override | Удаляет все элементы в контейнере. |
| [CopyTo](./copyto/)(ArrayPtr\<System::Collections::Generic::KeyValuePair\<TKey, TValue\>\>, int) override | Копирует элементы контейнера в существующие элементы массива. |
| [get_KeysInternal](./get_keysinternal/)() const override | Получает обёртку коллекции для доступа к ключам словаря. |
| [idx_set](./idx_set/)(const TKey\&, TValue) override | Информация RTTI. |
| [Remove](./remove/)(const TKey\&) override | Удаляет элемент из контейнера. |
| [TryAdd](./tryadd/)(const TKey\&, const TValue\&) | Пытается добавить пару ключ/значение в словарь. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [BaseType](./basetype/) | Тип реализации. |
| [ThisType](./thistype/) | Этот тип. |
## Примечания



```cpp
#include <system/collections/concurrent/concurrent_dictionary.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  const int itemsCount = 32;

  // Создайте экземпляр класса ConcurrentDictionary.
  auto concurrentDictionary = MakeObject<ConcurrentDictionary<int, int>>();

  // Заполните ConcurrentDictionary.
  for (auto i = 0; i < itemsCount; ++i)
  {
    concurrentDictionary->Add(i, i * i);
  }

  Console::WriteLine(concurrentDictionary->idx_get(3));

  return 0;
}
/*
This code example produces the following output:
9
*/
```

## См. также

* Class [Dictionary](../../system.collections.generic/dictionary/)
* Namespace [System::Collections::Concurrent](../)
* Library [Aspose.PDF for C++](../../)
