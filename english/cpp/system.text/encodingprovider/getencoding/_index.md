---
title: System::Text::EncodingProvider::GetEncoding method
linktitle: GetEncoding
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::EncodingProvider::GetEncoding method. Gets the encoding associated with the specified name in C++.'
type: docs
weight: 100
url: /cpp/system.text/encodingprovider/getencoding/
---
## EncodingProvider::GetEncoding(const String\&) method


Gets the encoding associated with the specified name.

```cpp
virtual EncodingPtr System::Text::EncodingProvider::GetEncoding(const String &name)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | const String\& | The name of the encoding to retrieve. |

### ReturnValue

A shared pointer to the [Encoding](../../encoding/) object associated with the specified name, or nullptr if the encoding is not supported by this provider.
## Remarks



This method is intended to be overridden in a derived class. 

## See Also

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Class [EncodingProvider](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## EncodingProvider::GetEncoding(int) method


Gets the encoding associated with the specified code page identifier.

```cpp
virtual EncodingPtr System::Text::EncodingProvider::GetEncoding(int codepage)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| codepage | int | The code page identifier of the encoding to retrieve. |

### ReturnValue

A shared pointer to the [Encoding](../../encoding/) object associated with the specified code page, or nullptr if the encoding is not supported by this provider.
## Remarks



This method is intended to be overridden in a derived class. 

## See Also

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [EncodingProvider](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
