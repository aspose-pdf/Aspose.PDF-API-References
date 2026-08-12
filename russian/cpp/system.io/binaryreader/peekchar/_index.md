---
title: "Метод System::IO::BinaryReader::PeekChar"
linktitle: "PeekChar"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::IO::BinaryReader::PeekChar. Считывает один символ из входного потока, не изменяя курсор чтения потока, в C++."
type: docs
weight: 600
url: /ru/cpp/system.io/binaryreader/peekchar/
---
## BinaryReader::PeekChar method


Читает один символ из входного потока, не изменяя курсор чтения потока.

```cpp
virtual int System::IO::BinaryReader::PeekChar()
```


### ReturnValue

Считать символ, закодированный в UTF-16; если считанный символ представлен двумя кодовыми точками в кодировке UTF-16, то возвращается только старший суррогат; если символ не считан, возвращается -1.

## См. также

* Class [BinaryReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
