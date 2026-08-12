---
title: "System::IO::StringReader::Read метод"
linktitle: "Read"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::StringReader::Read метод. Считывает один символ из потока в C++."
type: docs
weight: 500
url: /ru/cpp/system.io/stringreader/read/
---
## StringReader::Read() method


Читает один символ из потока.

```cpp
virtual int System::IO::StringReader::Read() override
```


### ReturnValue

Прочитанный символ или -1, если символ не был прочитан

## См. также

* Class [StringReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StringReader::Read(ArrayPtr\<char_t\>, int, int) method


Читает указанное количество символов из потока в указанный массив символов, начиная с указанной позиции.

```cpp
virtual int System::IO::StringReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | ArrayPtr\<char_t\> | Массив символов, в который записываются символы, считанные из потока |
| индекс | int | Нулевой индекс в **buffer**, с которого начинать запись |
| count | int | Количество символов для чтения из потока |

### ReturnValue

Количество символов, считанных из потока

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
