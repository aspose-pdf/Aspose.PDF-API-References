---
title: "Метод System::IO::BinaryReader::Read"
linktitle: "Read"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::IO::BinaryReader::Read. Считывает один символ из входного потока в C++."
type: docs
weight: 700
url: /ru/cpp/system.io/binaryreader/read/
---
## BinaryReader::Read() method


Читает один символ из входного потока.

```cpp
virtual int System::IO::BinaryReader::Read()
```


### ReturnValue

Считать символ, закодированный в UTF-16; если считанный символ представлен двумя кодовыми точками в кодировке UTF-16, то возвращается только старший суррогат.

## См. также

* Class [BinaryReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BinaryReader::Read(ArrayPtr\<char_t\>, int, int) method


Читает указанное количество символов из входного потока, преобразует их в кодировку UTF-16 и записывает полученные UTF-16 символы в указанный массив символов, начиная с указанной позиции.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | ArrayPtr\<char_t\> | Массив символов UTF-16, в который записываются считанные из входного потока символы |
| индекс | int | Нулевой индекс в **buffer**, с которого начинать запись |
| count | int | Количество символов для чтения из потока |

### ReturnValue

Количество символов, считанных из входного потока

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BinaryReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BinaryReader::Read(ArrayPtr\<uint8_t\>, int, int) method


Читает указанное количество байтов из входного потока и записывает их в указанный массив байтов.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<uint8_t> buffer, int index, int count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | ArrayPtr\<uint8_t\> | Массив байтов, в который записываются считанные байты |
| индекс | int | Позиция, начинающаяся с 0, в **buffer**, с которой начинать запись |
| count | int | Количество байтов для чтения |

### ReturnValue

Количество считанных байтов

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BinaryReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
