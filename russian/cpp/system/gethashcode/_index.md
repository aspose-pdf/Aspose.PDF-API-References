---
title: "Метод System::GetHashCode"
linktitle: "GetHashCode"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::GetHashCode. Специализация для std::thread::id; возвращает хеш-код для указанного объекта потока в C++."
type: docs
weight: 21900
url: /ru/cpp/system/gethashcode/
---
## System::GetHashCode(const std::thread::id\&) method


Специализация для std::thread::id; возвращает хеш-код для указанного объекта потока.

```cpp
int System::GetHashCode(const std::thread::id &id)
```

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::GetHashCode(const T\&) method


Возвращает хеш‑код для указанного скалярного значения.

```cpp
template<typename T> std::enable_if<std::is_scalar<T>::value, int>::type System::GetHashCode(const T &obj)
```


| Параметр | Описание |
| --- | --- |
| T | Тип значения, для которого функция генерирует хеш‑код |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const T\& | Значение, для которого генерируется хеш‑код |

### ReturnValue

Хеш‑код, сгенерированный для указанного значения

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::GetHashCode(const T\&) method


Возвращает хеш‑код для указанного объекта.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&System::IsSmartPtr<T>::value, int>::type System::GetHashCode(const T &obj)
```


| Параметр | Описание |
| --- | --- |
| T | Тип объекта, для которого функция генерирует хеш‑код |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const T\& | Указатель [SmartPtr](../smartptr/), указывающий на объект, для которого генерируется хеш‑код |

### ReturnValue

Хеш‑код, сгенерированный для указанного объекта

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::GetHashCode(const T\&) method


Возвращает хеш‑код для указанного объекта, который является исключением.

```cpp
template<typename T> std::enable_if<System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```


| Параметр | Описание |
| --- | --- |
| T | Тип объекта, для которого функция генерирует хеш‑код |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const T\& | Обёртка [Exception](../exception/), содержащая объект, для которого генерируется хеш‑код |

### ReturnValue

Хеш‑код, сгенерированный для указанного объекта

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::GetHashCode(const T\&) method


Возвращает хеш‑код для указанного объекта, который не является умным указателем и не является исключением.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&!System::IsSmartPtr<T>::value &&!System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```


| Параметр | Описание |
| --- | --- |
| T | Тип объекта, для которого функция генерирует хеш‑код |

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const T\& | Константная ссылка на объект, для которого генерируется хеш‑код |

### ReturnValue

Хеш‑код, сгенерированный для указанного объекта

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
