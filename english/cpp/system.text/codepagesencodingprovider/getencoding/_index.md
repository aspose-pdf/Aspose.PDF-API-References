---
title: System::Text::CodePagesEncodingProvider::GetEncoding method
linktitle: GetEncoding
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::CodePagesEncodingProvider::GetEncoding method. Gets the encoding associated with the specified name in C++.'
type: docs
weight: 200
url: /cpp/system.text/codepagesencodingprovider/getencoding/
---
## CodePagesEncodingProvider::GetEncoding(const String\&) method


Gets the encoding associated with the specified name.

```cpp
EncodingPtr System::Text::CodePagesEncodingProvider::GetEncoding(const String &name) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | const String\& | The name of the encoding to retrieve. |

### ReturnValue

A shared pointer to the [Encoding](../../encoding/) object associated with the specified name, or nullptr if the encoding is not supported by this provider.
## Remarks



Overrides the base class method to provide code page specific encoding resolution. 

## See Also

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Class [CodePagesEncodingProvider](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## CodePagesEncodingProvider::GetEncoding(int) method


Gets the encoding associated with the specified code page identifier.

```cpp
EncodingPtr System::Text::CodePagesEncodingProvider::GetEncoding(int codepage) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| codepage | int | The code page identifier of the encoding to retrieve. |

### ReturnValue

A shared pointer to the [Encoding](../../encoding/) object associated with the specified code page, or nullptr if the encoding is not supported by this provider.
## Remarks



Overrides the base class method to provide code page specific encoding resolution. 

## See Also

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [CodePagesEncodingProvider](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
