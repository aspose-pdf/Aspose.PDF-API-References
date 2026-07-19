---
title: "Класс System::Net::CookieContainer"
linktitle: "CookieContainer"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Net::CookieContainer. Предоставляет контейнер для экземпляров класса CookieCollection. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 400
url: /ru/cpp/system.net/cookiecontainer/
---
## CookieContainer class


Предоставляет контейнер для экземпляров класса CookieCollection. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class CookieContainer : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<Cookie\>) | Добавляет cookie в коллекцию. |
| [Add](./add/)(System::SharedPtr\<Cookie\>, bool) | Добавляет cookie в коллекцию. |
| [Add](./add/)(System::SharedPtr\<CookieCollection\>) | Копирует cookie из указанной коллекции в текущую. |
| [Add](./add/)(System::SharedPtr\<Uri\>, System::SharedPtr\<Cookie\>) | Добавляет cookie для указанного URI. |
| [Add](./add/)(System::SharedPtr\<Uri\>, System::SharedPtr\<CookieCollection\>) | Копирует cookie из указанной коллекции для указанного URI в текущую коллекцию. |
| [CookieContainer](./cookiecontainer/)() | Создаёт новый экземпляр. |
| [CookieContainer](./cookiecontainer/)(int32_t) | Создаёт новый экземпляр. |
| [CookieContainer](./cookiecontainer/)(int32_t, int32_t, int32_t) | Создаёт новый экземпляр. |
| [CookieCutter](./cookiecutter/)(System::SharedPtr\<Uri\>, String, String, bool) | Копирует cookie из указанного HTTP-заголовка для указанного URI. |
| [get_Capacity](./get_capacity/)() | Получает ёмкость коллекции. |
| [get_Count](./get_count/)() | Возвращает количество элементов коллекции. |
| [get_MaxCookieSize](./get_maxcookiesize/)() | Получает максимальный размер cookie. |
| [get_PerDomainCapacity](./get_perdomaincapacity/)() | Получает ёмкость коллекции на домен. |
| [GetCookieHeader](./getcookieheader/)(System::SharedPtr\<Uri\>) | Возвращает HTTP-заголовок, содержащий cookie, связанные с указанным URI. |
| [GetCookieHeader](./getcookieheader/)(System::SharedPtr\<Uri\>, String\&) | Возвращает HTTP-заголовок, содержащий cookie, связанные с указанным URI. |
| [GetCookies](./getcookies/)(System::SharedPtr\<Uri\>) | Возвращает коллекцию cookie, связанных с указанным URI. |
| [InternalGetCookies](./internalgetcookies/)(System::SharedPtr\<Uri\>) | Возвращает коллекцию cookie, связанных с указанным URI. |
| [IsLocalDomain](./islocaldomain/)(String) | Проверяет, является ли указанный домен localhost. |
| [set_Capacity](./set_capacity/)(int32_t) | Устанавливает ёмкость коллекции. |
| [set_MaxCookieSize](./set_maxcookiesize/)(int32_t) | Устанавливает максимальный размер cookie. |
| [set_PerDomainCapacity](./set_perdomaincapacity/)(int32_t) | Устанавливает ёмкость коллекции на домен. |
| [SetCookies](./setcookies/)(System::SharedPtr\<Uri\>, String) | Копирует cookie из указанного заголовка в коллекцию и связывает их с указанным URI. |
## Поля

| Поле | Описание |
| --- | --- |
| static [DefaultCookieLengthLimit](./defaultcookielengthlimit/) | Максимальный размер cookie. |
| static [DefaultCookieLimit](./defaultcookielimit/) | Информация RTTI. |
| static [DefaultPerDomainCookieLimit](./defaultperdomaincookielimit/) | Максимальное количество элементов коллекции на домен. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
