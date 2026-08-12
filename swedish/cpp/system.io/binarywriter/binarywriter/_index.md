---
title: "System::IO::BinaryWriter::BinaryWriter konstruktor"
linktitle: "BinaryWriter"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::BinaryWriter::BinaryWriter konstruktor. Skapar en instans av BinaryWriter-klassen som skriver data till den angivna strömmen med den angivna kodningen i C++."
type: docs
weight: 100
url: /sv/cpp/system.io/binarywriter/binarywriter/
---
## BinaryWriter::BinaryWriter constructor


Skapar en instans av [BinaryWriter](../) klass som skriver data till den angivna strömmen med den angivna kodningen.

```cpp
System::IO::BinaryWriter::BinaryWriter(const StreamPtr &stream, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked(), bool leaveopen=false)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | const StreamPtr\& | Utdataströmmen |
| encoding | const EncodingPtr\& | Kodningen att använda |
| leaveopen | bool | Anger om strömmen **stream** ska lämnas öppen (true) efter att det aktuella objektet har avyttrats eller inte (false) |

## Se även

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [BinaryWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
