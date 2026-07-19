---
title: "System::setter_increment_wrap метод"
linktitle: "setter_increment_wrap"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::setter_increment_wrap метод. Переводчик переводит выражения инкремента C#''s, направленные на свойство класса, у которого определены сеттер и геттер, в вызов этой функции в C++."
type: docs
weight: 39800
url: /ru/cpp/system/setter_increment_wrap/
---
## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) method


Переводчик переводит выражения инкремента C#'s, направленные на свойство класса, у которого определены сеттер и геттер, в вызов этой функции.

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


| Параметр | Описание |
| --- | --- |
| T | Тип свойства |
| Хост | - класс экземпляра, который будет изменён |
| HostGet | - Сам хост или его базовый тип, где определён getter свойства |
| HostSet | - Host сам по себе, или его базовый тип, где определён сеттер свойства |

| Параметр | Тип | Описание |
| --- | --- | --- |
| host | Host *const | Указатель на объект, свойство которого должно быть инкрементировано. |
| pGetter | T(HostGet::*)() | Указатель на функцию, указывающий на метод‑getter свойства. |
| pSetter | void(HostSet::*)(T) | Указатель на функцию, указывающий на метод‑setter свойства. |

### ReturnValue

Инкрементированное значение свойства.

## См. также

* Enum [UriComponents](../uricomponents/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::setter_increment_wrap(T(*)(), void(*)(T)) method


Переводчик переводит выражения инкремента C#'s, направленные на свойство класса, у которого определены сеттер и геттер, в вызов этой функции.

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```


| Параметр | Описание |
| --- | --- |
| T | Тип свойства |

| Параметр | Тип | Описание |
| --- | --- | --- |
| pGetter | T(*)() | Указатель на функцию, указывающий на свободную функцию‑геттер свойства |
| pSetter | void(*)(T) | Указатель на функцию, указывающий на свободную функцию‑сеттер свойства |

### ReturnValue

Инкрементированное значение свойства.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
