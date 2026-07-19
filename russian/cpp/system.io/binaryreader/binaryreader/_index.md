---
title: "System::IO::BinaryReader::BinaryReader конструктор"
linktitle: "BinaryReader"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::BinaryReader::BinaryReader конструктор. Создаёт экземпляр класса BinaryReader, который читает данные из указанного потока, используя кодировку UTF-8 в C++."
type: docs
weight: 100
url: /ru/cpp/system.io/binaryreader/binaryreader/
---
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&) constructor


Создаёт экземпляр класса [BinaryReader](../) который читает данные из указанного потока, используя кодировку UTF-8.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<Stream\>\& | Входной поток |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [BinaryReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) constructor


Создаёт экземпляр класса [BinaryReader](../) который читает данные из указанного потока, используя указанную кодировку.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<Stream\>\& | Входной поток |
| encoding | const SharedPtr\<Text::Encoding\>\& | Кодировка, которую следует использовать |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [Encoding](../../../system.text/encoding/)
* Class [BinaryReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) constructor


Создаёт экземпляр класса [BinaryReader](../) который читает данные из указанного потока, используя указанную кодировку.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding, bool leaveOpen)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const SharedPtr\<Stream\>\& | Входной поток |
| encoding | const SharedPtr\<Text::Encoding\>\& | Кодировка, которую следует использовать |
| leaveOpen | bool | Указывает, должен ли поток **input** оставаться открытым (true) после того, как текущий объект был освобождён, или нет (false) |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [Encoding](../../../system.text/encoding/)
* Class [BinaryReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
