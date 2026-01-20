---
title: System::String::ToByteArray method
linktitle: ToByteArray
second_title: Aspose.PDF for C++ API Reference
description: 'System::String::ToByteArray method. Converts string or substring to array of bytes in C++.'
type: docs
weight: 4600
url: /cpp/system/string/tobytearray/
---
## String::ToByteArray method


Converts string or substring to array of bytes.

```cpp
ArrayPtr<uint8_t> System::String::ToByteArray(int32_t startIndex=0, int32_t length=INT32_MAX, bool LE=true) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int32_t | Substring start index. |
| length | int32_t | Substring length. |
| LE | bool | If true, encode characters using little endianness; otherwise, use big endianness. |

### ReturnValue

[Array](../../array/) containing bytes representing characters of the string.

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
