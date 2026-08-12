---
title: "Метод System::Threading::Interlocked::CompareExchange"
linktitle: "CompareExchange"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Threading::Interlocked::CompareExchange. Выполняет сравнение‑обмен значения переменной: проверяет, равно ли переменная определённому значению, и сохраняет новое значение только если текущее значение соответствует ожидаемому, в C++."
type: docs
weight: 200
url: /ru/cpp/system.threading/interlocked/compareexchange/
---
## Interlocked::CompareExchange(int32_t\&, int32_t, int32_t, bool\&) method


Сравнивает и меняет значение переменной: проверяет, равно ли переменная определённому значению, и сохраняет новое значение только если текущее значение соответствует ожидаемому.

```cpp
static int32_t System::Threading::Interlocked::CompareExchange(int32_t &location1, int32_t value, int32_t comparand, bool &succeeded)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| location1 | int32_t\& | Ссылка на переменную для изменения. |
| value | int32_t | Значение для сохранения. |
| сравниваемое | int32_t | Значение, с которым сравнивается значение переменной перед обменом. |
| успешно | bool\& | Ссылка на переменную, которая устанавливается в true, если обмен произошёл, и в false в противном случае. |

### ReturnValue

Значение переменной в начале операции, независимо от того, было ли оно изменено.

## См. также

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Interlocked::CompareExchange(T\&, T, T) method


Сравнивает и меняет значение переменной: проверяет, равно ли переменная определённому значению, и сохраняет новое значение только если текущее значение соответствует ожидаемому.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```


| Параметр | Описание |
| --- | --- |
| T | Тип переменной. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| location1 | T\& | Ссылка на переменную для изменения. |
| value | T | Значение для сохранения. |
| сравниваемое | T | Значение, с которым сравнивается значение переменной перед обменом. |

### ReturnValue

Значение переменной в начале операции, независимо от того, было ли оно изменено.

## См. также

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Interlocked::CompareExchange(T\&, T, T) method


Сравнивает и меняет значение переменной: проверяет, равно ли переменная определённому значению, и сохраняет новое значение только если текущее значение соответствует ожидаемому. Не реализовано.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```


| Параметр | Описание |
| --- | --- |
| T | Тип переменной. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| location1 | T\& | Ссылка на переменную для изменения. |
| value | T | Значение для сохранения. |
| сравниваемое | T | Значение, с которым сравнивается значение переменной перед обменом. |

### ReturnValue

Значение переменной в начале операции, независимо от того, было ли оно изменено.

## См. также

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
