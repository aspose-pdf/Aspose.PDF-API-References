---
title: "Класс System::Net::CookieCollection"
linktitle: "CookieCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Net::CookieCollection. Представляет список отсортированных файлов cookie. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 200
url: /ru/cpp/system.net/cookiecollection/
---
## CookieCollection class


Представляет список отсортированных файлов cookie. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class CookieCollection : public System::Collections::Generic::ICollection<System::SharedPtr<System::Net::Cookie>>
```

## Enums

| Перечисление | Описание |
| --- | --- |
| [Stamp](./stamp/) | Информация RTTI. |
## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<Cookie\>\&) override | Добавляет cookie в коллекцию. |
| [Add](./add/)(System::SharedPtr\<CookieCollection\>) | Добавляет файлы cookie из указанной коллекции в текущую. |
| [Clear](./clear/)() override | Удаляет все файлы cookie из коллекции. |
| [Contains](./contains/)(const System::SharedPtr\<Cookie\>\&) const override | Проверяет, содержит ли коллекция указанный файл cookie. |
| [CookieCollection](./cookiecollection/)() | Создаёт новый экземпляр. |
| [get_Count](./get_count/)() const override | Возвращает количество элементов в коллекции. |
| [get_IsOtherVersionSeen](./get_isotherversionseen/)() | Возвращает значение, указывающее, содержит ли коллекция файл cookie с версией, не равной [Cookie::MaxSupportedVersion](../cookie/maxsupportedversion/). |
| [GetEnumerator](./getenumerator/)() override | Получает перечислитель. |
| [idx_get](./idx_get/)(int32_t) | Возвращает файл cookie из коллекции cookie по указанному индексу. |
| [idx_get](./idx_get/)(String) | Возвращает файл cookie из коллекции cookie по указанному имени. |
| [IndexOf](./indexof/)(System::SharedPtr\<Cookie\>) | Возвращает индекс указанного файла cookie. |
| [InternalAdd](./internaladd/)(System::SharedPtr\<Cookie\>, bool) | Добавляет указанный файл cookie в коллекцию. |
| [Remove](./remove/)(const System::SharedPtr\<Cookie\>\&) override | Удаляет указанный файл cookie из коллекции. |
| [RemoveAt](./removeat/)(int32_t) | Удаляет файл cookie по указанному индексу. |
| [TimeStamp](./timestamp/)(CookieCollection::Stamp) | Обновляет метку времени согласно указанному сценарию и возвращает новое значение. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Получает реализацию константного итератора begin для текущего контейнера. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Получает реализацию итератора begin для текущего контейнера. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Получает реализацию константного итератора end для текущего контейнера. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Получает реализацию итератора end для текущего контейнера. |
## См. также

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
