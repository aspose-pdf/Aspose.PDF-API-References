---
title: "System::Security::Cryptography::CryptoStream::CryptoStream конструктор"
linktitle: "CryptoStream"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::CryptoStream::CryptoStream конструктор. Конструктор в C++."
type: docs
weight: 100
url: /ru/cpp/system.security.cryptography/cryptostream/cryptostream/
---
## CryptoStream::CryptoStream constructor


Конструктор.

```cpp
System::Security::Cryptography::CryptoStream::CryptoStream(const SharedPtr<System::IO::Stream> &stream, const SharedPtr<ICryptoTransform> &transform, CryptoStreamMode mode)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | const SharedPtr\<System::IO::Stream\>\& | Поток для обёртывания. |
| преобразование | const SharedPtr\<ICryptoTransform\>\& | Функция преобразования для обработки данных при отправке/чтении их в/из потока. |
| режим | CryptoStreamMode | Направление потока. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ICryptoTransform](../../icryptotransform/)
* Enum [CryptoStreamMode](../../cryptostreammode/)
* Class [CryptoStream](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
