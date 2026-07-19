---
title: "класс System::Collections::Generic::IDictionary"
linktitle: "IDictionary"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Collections::Generic::IDictionary. Интерфейс для контейнеров, похожих на словарь. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2100
url: /ru/cpp/system.collections.generic/idictionary/
---
## IDictionary class


Интерфейс для контейнеров, похожих на словарь. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
template<typename TKey,typename TValue>class IDictionary : public System::Collections::Generic::ICollection<KeyValuePair<TKey, TValue>>
```


| Параметр | Описание |
| --- | --- |
| TKey | Тип ключа. |
| TValue | Тип значения. |
## Методы

| Метод | Описание |
| --- | --- |
| virtual [Add](./add/)(const TKey\&, const TValue\&) | Добавляет пару ключ‑значение в контейнер. |
| virtual [ContainsKey](./containskey/)(const TKey\&) const | Проверяет, содержит ли контейнер ключ. |
| [CopyTo](./copyto/)(ArrayPtr\<KeyValuePair\<TKey, TValue\>\>, int) override | Копирует содержимое словаря в существующие элементы массива. |
| virtual [get_Count](./get_count/)() const | Делает видимой функцию‑член get_Count. |
| [get_IsFixedSize](./get_isfixedsize/)() const | Проверяет, фиксирован ли размер коллекции. |
| [get_IsSynchronized](./get_issynchronized/)() const | Проверяет, является ли контейнер потокобезопасным. |
| virtual [get_Keys](./get_keys/)() const | Получает доступ к коллекции ключей. |
| virtual [get_Values](./get_values/)() const | Получает доступ к коллекции значений. |
| virtual [GetValueOrDefault](./getvalueordefault/)(const TKey\&) const | Возвращает значение, если найдено; иначе **Value()**. |
| virtual [GetValueOrDefault](./getvalueordefault/)(const TKey\&, const TValue\&) const | Возвращает значение, если найдено; иначе **defaultValue**. |
| virtual [GetValueOrNull](./getvalueornull/)(const TKey\&) const | Возвращает значение, если найдено; иначе **null**, имеет смысл только для ссылочных типов. |
| virtual [idx_get](./idx_get/)(const TKey\&) const | Функция получения. |
| virtual [idx_set](./idx_set/)(const TKey\&, TValue) | Функция установки. |
| virtual [Remove](./remove/)(const TKey\&) | Удаляет ключ из контейнера. |
| virtual [TryGetValue](./trygetvalue/)(const TKey\&, TValue\&) const | Ищет значение и получает его, если найдено. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [BaseType](./basetype/) | Информация RTTI. |
| [KeyValuePairType](./keyvaluepairtype/) | Тип пары ключ‑значение. |

## См. также

* Class [ICollection](../icollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
