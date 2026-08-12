---
title: "Метод System::CastEnumerableTo"
linktitle: "CastEnumerableTo"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::CastEnumerableTo. Выполняет явное приведение элементов указанного перечислимого объекта к другому типу в C++."
type: docs
weight: 16000
url: /ru/cpp/system/castenumerableto/
---
## System::CastEnumerableTo(const From\&) method


Выполняет явное приведение элементов указанного перечислимого объекта к другому типу.

```cpp
template<class To,class From> std::enable_if<!System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```


| Параметр | Описание |
| --- | --- |
| К | Тип, к которому статически приводятся элементы объекта enumerable |
| От | Тип объекта enumerable |

| Параметр | Тип | Описание |
| --- | --- | --- |
| enumerable | const From\& | Enumerable объект, содержащий элементы для приведения |

### ReturnValue

Указатель на новую коллекцию, содержащую элементы типа **To**, эквивалентные элементам **enumerable**

## См. также

* Class [ListPtr](../../system.collections.generic/listptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::CastEnumerableTo(const From\&) method


Выполняет явное приведение элементов указанного перечислимого объекта к другому типу.

```cpp
template<class To,class From> std::enable_if<System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```


| Параметр | Описание |
| --- | --- |
| К | Тип, к которому статически приводятся элементы объекта enumerable |
| От | Тип объекта enumerable |

| Параметр | Тип | Описание |
| --- | --- | --- |
| enumerable | const From\& | является наследником объекта Enumerable с определённым методом get_Count и содержащим элементы для приведения |

### ReturnValue

Указатель на новую коллекцию, содержащую элементы типа **To**, эквивалентные элементам **enumerable**

## См. также

* Class [ListPtr](../../system.collections.generic/listptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
