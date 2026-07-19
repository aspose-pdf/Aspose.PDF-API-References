---
title: "System::IO::BinaryWriter::BinaryWriter конструктор"
linktitle: "BinaryWriter"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::BinaryWriter::BinaryWriter конструктор. Создаёт экземпляр класса BinaryWriter, который записывает данные в указанный поток, используя указанную кодировку, в C++."
type: docs
weight: 100
url: /ru/cpp/system.io/binarywriter/binarywriter/
---
## BinaryWriter::BinaryWriter constructor


Создаёт экземпляр класса [BinaryWriter](../), который записывает данные в указанный поток, используя указанную кодировку.

```cpp
System::IO::BinaryWriter::BinaryWriter(const StreamPtr &stream, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked(), bool leaveopen=false)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | const StreamPtr\& | Выходной поток |
| encoding | const EncodingPtr\& | Кодировка, которую следует использовать |
| leaveopen | bool | Указывает, должен ли поток **stream** оставаться открытым (true) после того, как текущий объект был освобождён, или нет (false). |

## См. также

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [BinaryWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
