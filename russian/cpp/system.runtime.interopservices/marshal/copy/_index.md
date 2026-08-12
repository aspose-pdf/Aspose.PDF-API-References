---
title: "System::Runtime::InteropServices::Marshal::Copy метод"
linktitle: "Copy"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Runtime::InteropServices::Marshal::Copy метод. Реализует public static void Copy(char[] source, int startIndex, IntPtr destination, int length) в C++."
type: docs
weight: 200
url: /ru/cpp/system.runtime.interopservices/marshal/copy/
---
## Marshal::Copy(const container\&, int, IntPtr, int) method


Реализует public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, IntPtr destination, int length)
```


| Параметр | Описание |
| --- | --- |
| контейнер | Тип контейнера-источника. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | const container\& | Указатель на данные источника. |
| startIndex | int | Начальный индекс источника. |
| destination | IntPtr | Указатель на данные назначения. |
| длина | int | Количество элементов для копирования. |

## См. также

* Class [Marshal](../)
* Namespace [System::Runtime::InteropServices](../../)
* Library [Aspose.PDF for C++](../../../)
## Marshal::Copy(const container\&, int, void *, int) method


Реализует public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, void *destination, int length)
```


| Параметр | Описание |
| --- | --- |
| контейнер | Тип контейнера-источника. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | const container\& | Указатель на данные источника. |
| startIndex | int | Начальный индекс источника. |
| destination | void * | Указатель на данные назначения. |
| длина | int | Количество элементов для копирования. |

## См. также

* Class [Marshal](../)
* Namespace [System::Runtime::InteropServices](../../)
* Library [Aspose.PDF for C++](../../../)
## Marshal::Copy(const IntPtr, container\&&, int, int) method


Реализует семантику public static void Copy(IntPtr source, byte[] destination, int startIndex, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const IntPtr source, container &&destination, int startIndex, int length)
```


| Параметр | Описание |
| --- | --- |
| контейнер | Тип контейнера назначения. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | const IntPtr | Указатель на данные источника. |
| destination | container\&& | Контейнер, в который копировать данные. |
| startIndex | int | Начальный индекс источника. |
| длина | int | Количество элементов для копирования. |

## См. также

* Class [Marshal](../)
* Namespace [System::Runtime::InteropServices](../../)
* Library [Aspose.PDF for C++](../../../)
## Marshal::Copy(const void *, container\&&, int, int) method


Реализует семантику public static void Copy(IntPtr source, byte[] destination, int startIndex, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const void *source, container &&destination, int startIndex, int length)
```


| Параметр | Описание |
| --- | --- |
| контейнер | Тип контейнера назначения. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| источник | const void * | Указатель на данные источника. |
| destination | container\&& | Контейнер, в который копировать данные. |
| startIndex | int | Начальный индекс источника. |
| длина | int | Количество элементов для копирования. |

## См. также

* Class [Marshal](../)
* Namespace [System::Runtime::InteropServices](../../)
* Library [Aspose.PDF for C++](../../../)
