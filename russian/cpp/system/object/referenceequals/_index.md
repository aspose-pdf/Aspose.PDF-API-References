---
title: "System::Object::ReferenceEquals метод"
linktitle: "ReferenceEquals"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Object::ReferenceEquals метод. Специализация Object::ReferenceEquals для случая строки и nullptr в C++."
type: docs
weight: 1200
url: /ru/cpp/system/object/referenceequals/
---
## Object::ReferenceEquals(String const\&, std::nullptr_t) method


Специализация [Object::ReferenceEquals](./) для случая строки и nullptr.

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | String const\& | [String](../../string/) для сравнения с nullptr. |

### ReturnValue

true, если строка равна null, иначе false.

## См. также

* Class [String](../../string/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::ReferenceEquals(String const\&, String const\&) method


Специализация [Object::ReferenceEquals](./) для случая строк.

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str1 | String const\& | Первая строка для сравнения. |
| str2 | String const\& | Вторая строка для сравнения. |

### ReturnValue

true, если строки совпадают, иначе false.

## См. также

* Class [String](../../string/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::ReferenceEquals(ptr const\&, ptr const\&) method


Сравнивает объекты по ссылке.

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| objA | ptr const\& | Первый указатель для сравнения. |
| objB | ptr const\& | Второй указатель для сравнения. |

### ReturnValue

Истина, если указатели совпадают, и ложь в противном случае.

## См. также

* Typedef [ptr](../ptr/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::ReferenceEquals(T const\&, std::nullptr_t) method


Сравнивает объект значимого типа со значением nullptr по ссылке.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```


| Параметр | Описание |
| --- | --- |
| T | Тип объекта для сравнения. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| objA | T const\& | Первый объект для сравнения. |

### ReturnValue

Всегда возвращает false, так как типы значений не могут быть обнулены.

## См. также

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Object::ReferenceEquals(T const\&, T const\&) method


Сравнивает объекты по ссылке.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```


| Параметр | Описание |
| --- | --- |
| T | Тип объектов для сравнения. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| objA | T const\& | Первый объект для сравнения. |
| objB | T const\& | Второй объект для сравнения. |

### ReturnValue

Истина, если адреса объектов совпадают, и ложь в противном случае.

## См. также

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
