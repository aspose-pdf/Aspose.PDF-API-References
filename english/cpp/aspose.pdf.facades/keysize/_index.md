---
title: Aspose::Pdf::Facades::KeySize enum
linktitle: KeySize
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::KeySize enum. Defines different key sizes which can be used to encrypt pdf documents in C++.'
type: docs
weight: 4800
url: /cpp/aspose.pdf.facades/keysize/
---
## KeySize enum


Defines different key sizes which can be used to encrypt pdf documents.

```cpp
enum class KeySize
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| x40 | 0 | 40 bit key. Such key size is used with RC4 algorithm and provides low level of security. Nevertheless old versions of pdf documents can be encrypted only with such keys (v. 1.3 and lower); |
| x128 | 1 | 128 bit key. Both RC4 and AES algorithms can use such key size. |
| x256 | 2 | 256 bit key. Such key size can be used only with AES and is recognized with the last Adobe Reader versions (starting from v.9). |

## See Also

* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
