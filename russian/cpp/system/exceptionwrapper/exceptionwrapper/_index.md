---
title: "Конструктор System::ExceptionWrapper::ExceptionWrapper"
linktitle: "ExceptionWrapper"
second_title: "Справочник API Aspose.PDF для C++"
description: "Конструктор System::ExceptionWrapper::ExceptionWrapper. Конструктор, который передаёт параметры конструкторам класса Exception и создаёт умный указатель, содержащий новый экземпляр класса Exception в C++."
type: docs
weight: 100
url: /ru/cpp/system/exceptionwrapper/exceptionwrapper/
---
## ExceptionWrapper::ExceptionWrapper(Args\&&...) constructor


Конструктор, который передаёт параметры конструкторам класса [Exception](../../exception/) и создаёт умный указатель, содержащий новый экземпляр класса [Exception](../../exception/).

```cpp
template<typename ...,typename> System::ExceptionWrapper<T>::ExceptionWrapper(Args &&...args)
```

## См. также

* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ExceptionWrapper::ExceptionWrapper(const ExceptionPtr\&) constructor


Создаёт экземпляр класса [ExceptionWrapper](../), содержащий переданный указатель.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionPtr &ptr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| ptr | const ExceptionPtr\& | Умный указатель на экземпляр класса [Exception](../../exception/). |

## См. также

* Typedef [ExceptionPtr](../../exceptionptr/)
* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ExceptionWrapper::ExceptionWrapper(const ExceptionWrapper\&) constructor


Конструктор копирования.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionWrapper &other)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| другое | const ExceptionWrapper\& | Другой экземпляр класса-обёртки, который должен быть скопирован. |

## См. также

* Class [ExceptionWrapper](../)
* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ExceptionWrapper::ExceptionWrapper(ExceptionWrapper\&&) constructor


Конструктор перемещения.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(ExceptionWrapper &&other) noexcept
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| другое | ExceptionWrapper\&& | Другой экземпляр класса-обёртки, который должен быть перемещён. |

## См. также

* Class [ExceptionWrapper](../)
* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ExceptionWrapper::ExceptionWrapper(std::nullptr_t) constructor


Создаёт нулевой экземпляр класса [ExceptionWrapper](../), который не представляет никакого исключения.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(std::nullptr_t)
```

## См. также

* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
