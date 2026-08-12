---
title: "System::Buffer::ByteLength метод"
linktitle: "ByteLength"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Buffer::ByteLength метод. Определяет количество байтов, занимаемых всеми элементами указанного массива в C++."
type: docs
weight: 200
url: /ru/cpp/system/buffer/bytelength/
---
## Buffer::ByteLength(const SharedPtr\<Array\<T\>\>\&) method


Определяет количество байтов, занимаемых всеми элементами указанного массива.

```cpp
template<class T> static int System::Buffer::ByteLength(const SharedPtr<Array<T>> &array)
```


| Параметр | Описание |
| --- | --- |
| T | Тип элементов массива |

| Параметр | Тип | Описание |
| --- | --- | --- |
| массив | const SharedPtr\<Array\<T\>\>\& | Массив |

### ReturnValue

Количество байтов, занимаемых всеми элементами указанного массива

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../../array/)
* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Buffer::ByteLength(const System::Details::ArrayView\<T\>\&) method


Определяет количество байтов, занимаемых всеми элементами указанного массива.

```cpp
template<class T> static int System::Buffer::ByteLength(const System::Details::ArrayView<T> &array)
```


| Параметр | Описание |
| --- | --- |
| T | Тип элементов представления массива |

| Параметр | Тип | Описание |
| --- | --- | --- |
| массив | const System::Details::ArrayView\<T\>\& | Представление массива |

### ReturnValue

Количество байтов, занимаемых всеми элементами указанного представления массива

## См. также

* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Buffer::ByteLength(const System::Details::StackArray\<T, N\>\&) method


Определяет количество байтов, занимаемых всеми элементами указанного массива.

```cpp
template<class T,std::size_t> static int System::Buffer::ByteLength(const System::Details::StackArray<T, N> &array)
```


| Параметр | Описание |
| --- | --- |
| T | Тип элементов стекового массива |
| N | Размер стекового массива |

| Параметр | Тип | Описание |
| --- | --- | --- |
| массив | const System::Details::StackArray\<T, N\>\& | Стековый массив |

### ReturnValue

Количество байтов, занимаемых всеми элементами указанного стекового массива

## См. также

* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
