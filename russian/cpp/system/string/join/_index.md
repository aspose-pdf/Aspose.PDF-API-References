---
title: "System::String::Join метод"
linktitle: "Join"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::String::Join метод. Объединяет массив, используя строку в качестве разделителя в C++."
type: docs
weight: 7300
url: /ru/cpp/system/string/join/
---
## String::Join(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) method


Объединяет массив, используя строку в качестве разделителя.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<SharedPtr<Object>> &parts)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| separator | const String\& | [String](../) для вставки между элементами массива при их объединении. |
| parts | const ArrayPtr\<SharedPtr\<Object\>\>\& | [Array](../../array/) частей для объединения. |

### ReturnValue

[String](../) representing joint elements.

## См. также

* Class [String](../)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Join(const String\&, const ArrayPtr\<String\>\&, int, int) method


Объединяет массив, используя строку в качестве разделителя.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<String> &parts, int startIndex=0, int count=-1)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| separator | const String\& | [String](../) для вставки между элементами массива при их объединении. |
| parts | const ArrayPtr\<String\>\& | [Array](../../array/) частей для объединения. |
| startIndex | int | Первый индекс в массиве, с которого начинать объединение. |
| count | int | Количество элементов массива для объединения. -1 означает «до конца массива». |

### ReturnValue

[String](../) representing joint array elements.

## См. также

* Class [String](../)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Join(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) method


Объединяет массив, используя строку в качестве разделителя.

```cpp
static String System::String::Join(const String &separator, const SharedPtr<System::Collections::Generic::IEnumerable<String>> &parts)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| separator | const String\& | [String](../) для вставки между элементами массива при их объединении. |
| части | const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\& | - объект перечисления parts |

### ReturnValue

[String](../) representing joint elements.

## См. также

* Class [String](../)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Join(const String\&, const System::Details::ArrayView\<String\>\&, int, int) method


Объединяет массив, используя строку в качестве разделителя.

```cpp
static String System::String::Join(const String &separator, const System::Details::ArrayView<String> &parts, int startIndex=0, int count=-1)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| separator | const String\& | [String](../) для вставки между элементами массива при их объединении. |
| части | const System::Details::ArrayView\<String\>\& | ArrayView частей для объединения. |
| startIndex | int | Первый индекс в массиве, с которого начинать объединение. |
| count | int | Количество элементов массива для объединения. -1 означает «до конца массива». |

### ReturnValue

[String](../) representing joint array elements.

## См. также

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
