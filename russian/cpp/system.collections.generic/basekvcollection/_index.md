---
title: "System::Collections::Generic::BaseKVCollection класс"
linktitle: "BaseKVCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::Generic::BaseKVCollection класс. Содержит общий код для коллекций ключей или значений. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 700
url: /ru/cpp/system.collections.generic/basekvcollection/
---
## BaseKVCollection class


Содержит общий код для коллекций ключей или значений. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
template<typename Dict,typename KV>class BaseKVCollection : public System::Collections::Generic::IKVCollection<KV>
```


| Параметр | Описание |
| --- | --- |
| Dict | [Dictionary](../dictionary/) тип. |
| KV | Тип ключа или значения, в зависимости от того, для чего используется интерфейс. |
## Методы

| Метод | Описание |
| --- | --- |
| [BaseKVCollection](./basekvcollection/)(const typename Dict::Ptr\&) | Создаёт коллекцию. |
| [CopyTo](./copyto/)(ArrayPtr\<KV\>, int) override | Копирует данные в существующие элементы массива. |
| [get_Count](./get_count/)() const override | Получает количество элементов. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Обеспечивает компиляцию, но фактически ничего не делает, так как эта структура не владеет данными. |

## См. также

* Class [IKVCollection](../ikvcollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
