---
title: "Метод System::BitConverter::ToString"
linktitle: "ToString"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::BitConverter::ToString. Преобразует все значения указанного массива байтов в их шестнадцатеричное строковое представление. Регистры букв, используемых в шестнадцатеричной нотации, и разделитель, вставляемый между каждой парой соседних байтов, задаются соответствующими аргументами в C++."
type: docs
weight: 1200
url: /ru/cpp/system/bitconverter/tostring/
---
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, bool, const String\&) method


Преобразует все значения указанного массива байтов в их шестнадцатеричное строковое представление. Регистр букв в шестнадцатеричной нотации и разделитель, вставляемый между каждой парой соседних байтов, задаются соответствующими аргументами.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, bool uppercase=true, const String &separator=u"-")
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const ArrayPtr\<uint8_t\>\& | [Array](../../array/), содержащий байты для преобразования |
| верхний регистр | bool | Указывает регистр букв, используемых в полученном шестнадцатеричном представлении |
| separator | const String\& | Строка, используемая в качестве разделителя, вставляемого между каждой парой соседних байтов в результирующей строке |

### ReturnValue

[String](../../string/) containing hexadecimal representation of the specified byte array

## См. также

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int) method


Преобразует значения указанного массива байтов в их шестнадцатеричное строковое представление, начиная с указанного индекса.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const ArrayPtr\<uint8_t\>\& | [Array](../../array/), содержащий байты для преобразования |
| startIndex | int | [Index](../../index/) в указанном массиве, с которого начинать преобразование |

### ReturnValue

[String](../../string/) containing hexadecimal representation of the specified range of elements of the specified array

## См. также

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int, int) method


Преобразует диапазон значений указанного массива байтов в их шестнадцатеричное строковое представление.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex, int length)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const ArrayPtr\<uint8_t\>\& | [Array](../../array/), содержащий байты для преобразования |
| startIndex | int | [Index](../../index/) в указанном массиве, с которого начинается диапазон элементов массива байтов для преобразования |
| длина | int | Длина диапазона элементов массива байтов для преобразования |

### ReturnValue

[String](../../string/) containing hexadecimal representation of the specified range of elements of the specified array

## См. также

* Class [String](../../string/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
