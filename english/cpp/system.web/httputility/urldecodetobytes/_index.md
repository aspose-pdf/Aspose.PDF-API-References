---
title: System::Web::HttpUtility::UrlDecodeToBytes method
linktitle: UrlDecodeToBytes
second_title: Aspose.PDF for C++ API Reference
description: 'System::Web::HttpUtility::UrlDecodeToBytes method. Decodes URI fragment from bytes string in C++.'
type: docs
weight: 400
url: /cpp/system.web/httputility/urldecodetobytes/
---
## HttpUtility::UrlDecodeToBytes(const String\&) method


Decodes URI fragment from bytes string.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str)
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | const String\& | Encoded URI fragment. |

### ReturnValue

Decoded URI fragment.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
## HttpUtility::UrlDecodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) method


Decodes URI fragment from string.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | const String\& | Encoded URI fragment. |
| e | const System::SharedPtr\<Text::Encoding\>\& | Encoding to use. |

### ReturnValue

Decoded URI fragment.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Encoding](../../../system.text/encoding/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&) method


Decodes URI fragment from bytes array.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```


| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const System::ArrayPtr\<uint8_t\>\& | Encoded URI fragment. |

### ReturnValue

Decoded URI fragment.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Decodes URI fragment from bytes array.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const System::ArrayPtr\<uint8_t\>\& | Encoded URI fragment. |
| offset | int32_t | Offset in the given byte array. |
| count | int32_t | Number of bytes to read from. |

### ReturnValue

Decoded URI fragment.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
