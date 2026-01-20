---
title: System::Security::Cryptography::CryptoStream::CryptoStream constructor
linktitle: CryptoStream
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::CryptoStream::CryptoStream constructor. Constructor in C++.'
type: docs
weight: 100
url: /cpp/system.security.cryptography/cryptostream/cryptostream/
---
## CryptoStream::CryptoStream constructor


Constructor.

```cpp
System::Security::Cryptography::CryptoStream::CryptoStream(const SharedPtr<System::IO::Stream> &stream, const SharedPtr<ICryptoTransform> &transform, CryptoStreamMode mode)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | const SharedPtr\<System::IO::Stream\>\& | Stream to wrap. |
| transform | const SharedPtr\<ICryptoTransform\>\& | Transformation function to process data with when sending/reading it to/from stream. |
| mode | CryptoStreamMode | Stream direction. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ICryptoTransform](../../icryptotransform/)
* Enum [CryptoStreamMode](../../cryptostreammode/)
* Class [CryptoStream](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.PDF for C++](../../../)
