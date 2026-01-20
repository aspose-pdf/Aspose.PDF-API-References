---
title: System::Web::HttpUtility::UrlEncodeToBytes method
linktitle: UrlEncodeToBytes
second_title: Aspose.PDF for C++ API Reference
description: 'System::Web::HttpUtility::UrlEncodeToBytes method. Encodes URI fragment in C++.'
type: docs
weight: 600
url: /cpp/system.web/httputility/urlencodetobytes/
---
## HttpUtility::UrlEncodeToBytes(const String\&) method


Encodes URI fragment.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str)
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | const String\& | URI fragment to encode. |

### ReturnValue

Encoded URI fragment.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
## HttpUtility::UrlEncodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) method


Encodes URI fragment.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | const String\& | URI fragment to encode. |
| e | const System::SharedPtr\<Text::Encoding\>\& | Encoding to use. |

### ReturnValue

Encoded URI fragment.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Encoding](../../../system.text/encoding/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&) method


Encodes URI fragment.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```


| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const System::ArrayPtr\<uint8_t\>\& | URI fragment to encode. |

### ReturnValue

Encoded URI fragment.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Encodes URI fragment.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const System::ArrayPtr\<uint8_t\>\& | URI fragment to encode. |
| offset | int32_t | Offset in the given byte array. |
| count | int32_t | Number of bytes to read from. |

### ReturnValue

Encoded URI fragment.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
