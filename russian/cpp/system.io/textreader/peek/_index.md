---
title: "System::IO::TextReader::Peek method"
linktitle: "Peek"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::TextReader::Peek method. Считывает один символ из потока, не изменяя курсор чтения потока в C++."
type: docs
weight: 300
url: /ru/cpp/system.io/textreader/peek/
---
## TextReader::Peek method


Читает один символ из потока, не изменяя курсор чтения потока.

```cpp
virtual int System::IO::TextReader::Peek()
```


### ReturnValue

Считать символ, закодированный в UTF-16; если считанный символ представлен двумя кодовыми точками в кодировке UTF-16, то возвращается только старший суррогат; если символ не считан, возвращается -1.

## См. также

* Class [TextReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
