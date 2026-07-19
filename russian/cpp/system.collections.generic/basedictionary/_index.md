---
title: "Класс System::Collections::Generic::BaseDictionary"
linktitle: "BaseDictionary"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Collections::Generic::BaseDictionary. Содержит общий код для различных структур данных, похожих на словари (например, Dictionary, SortedDictionary). Не следует использовать напрямую, за исключением наследования при определении контейнеров. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 500
url: /ru/cpp/system.collections.generic/basedictionary/
---
## BaseDictionary class


Содержит общий код для различных структур данных, похожих на словари (например, [Dictionary](../dictionary/), [SortedDictionary](../sorteddictionary/)). Не следует использовать напрямую, за исключением наследования при определении контейнеров. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
template<typename Map>class BaseDictionary : public System::Collections::Generic::IDictionary<Map::key_type, Map::mapped_type>
```


| Параметр | Описание |
| --- | --- |
| Map | Базовый тип карты. |
## Методы

| Метод | Описание |
| --- | --- |
| [_add_range](./_add_range/)(std::initializer_list\<typename Map::value_type\>) | Специфично для C++. |
| [Add](./add/)(const key_t\&, const mapped_t\&) override | Добавляет пару ключ-значение в словарь. |
| [BaseDictionary](./basedictionary/)() | Создаёт пустую структуру данных. |
| [BaseDictionary](./basedictionary/)(int, const Args\&...) | Перенаправляющий конструктор, передающий аргументы в конструктор базовой карты. |
| [BaseDictionary](./basedictionary/)(BaseType *, const Args\&...) | Конструктор копирования. |
| [BaseDictionary](./basedictionary/)(BaseType *) | Конструктор копирования. |
| [begin](./begin/)() const | Возвращает итератор к обёртке KVPair для элемента ключ-значение контейнера. Реализовано в стиле C# — итератор должен возвращать объект KVPair с интерфейсом get_Key() и get_Value(). Если контейнер пуст, возвращённый итератор будет равен [end()](../ienumerable/end/). |
| [cbegin](./cbegin/)() const | Возвращает итератор к первому элементу контейнера. Реализовано в стиле STL. Если контейнер пуст, возвращённый итератор будет равен [end()](../ienumerable/end/). |
| [cend](./cend/)() const | Возвращает итератор к элементу, следующему за последним элементом контейнера. Реализовано в стиле STL. Этот элемент служит заполнителем; попытка доступа к нему приводит к неопределённому поведению. |
| [Clear](./clear/)() override | Удаляет все элементы. |
| [ContainsKey](./containskey/)(const key_t\&) const override | Проверяет, присутствует ли ключ в словаре. |
| [ContainsValue](./containsvalue/)(const mapped_t\&) | Проверяет, присутствует ли значение в словаре. Для сравнения значений используется оператор ==. |
| [data](./data/)() | Доступ к базовому хранилищу данных. |
| [data](./data/)() const | Доступ к базовому хранилищу данных. |
| [end](./end/)() const | Возвращает итератор к обёртке KVPair для элемента ключ-значение, следующего за последним элементом контейнера. Реализовано в стиле C# — итератор должен возвращать объект KVPair с интерфейсом get_Key() и get_Value(). Этот элемент служит заполнителем; попытка доступа к нему приводит к неопределённому поведению. |
| [get_Count](./get_count/)() const override | Получает количество элементов. |
| virtual [GetEnumerator](./getenumerator/)() | Создаёт экземпляр перечислителя, должен быть реализован в подклассе. |
| [GetValueOrDefault](./getvalueordefault/)(const key_t\&) const override | Возвращает значение, если найдено; иначе **Value()**. |
| [GetValueOrDefault](./getvalueordefault/)(const key_t\&, const mapped_t\&) const override | Возвращает значение, если найдено; иначе **defaultValue**. |
| [GetValueOrNull](./getvalueornull/)(const key_t\&) const override | Возвращает значение, если найдено; иначе **null**. Имеет смысл только для ссылочных типов. |
| [idx_get](./idx_get/)(const key_t\&) const override | Функция получения по ключу. |
| [idx_set](./idx_set/)(const key_t\&, mapped_t) override | Функция установки по ключу. Изменяет или создаёт элемент. |
| virtual [operator[]](./operator[]/)(const key_t\&) | Функция доступа. |
| [Remove](./remove/)(const key_t\&) override | Удаляет определённый ключ из словаря. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(unsigned int) override |  |
| [TryGetValue](./trygetvalue/)(const key_t\&, mapped_t\&) const override | Ищет значение по ключу и извлекает его, если найдено. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Получает реализацию константного итератора begin для текущего контейнера. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Получает реализацию итератора begin для текущего контейнера. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Получает реализацию константного итератора end для текущего контейнера. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Получает реализацию итератора end для текущего контейнера. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [BaseType](./basetype/) | Реализованный интерфейс. |
| [const_iterator](./const_iterator/) | Тип константного итератора. |
| [iterator](./iterator/) | Тип итератора. |
| [KeyCollection](./keycollection/) | Убедитесь, что мы используем правильный аллокатор с базовым типом хранилища. |
| [KVPair](./kvpair/) | Тип пары ключ‑значение. |
| [map_t](./map_t/) | Внутренний тип карты. |
| [ValueCollection](./valuecollection/) | Коллекция значений. |

## См. также

* Class [IDictionary](../idictionary/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
