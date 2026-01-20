---
title: System::Web::HttpUtility::UrlDecode method
linktitle: UrlDecode
second_title: Aspose.PDF for C++ API Reference
description: 'System::Web::HttpUtility::UrlDecode method. Decodes URI fragment from bytes array in C++.'
type: docs
weight: 300
url: /cpp/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) method


Decodes URI fragment from bytes array.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```


| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const System::ArrayPtr\<uint8_t\>\& | Encoded URI fragment. |
| e | const System::SharedPtr\<Text::Encoding\>\& | Encoding to use. |

### ReturnValue

Decoded URI fragment.

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Encoding](../../../system.text/encoding/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) method


Decodes URI fragment from bytes array.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```


| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const System::ArrayPtr\<uint8_t\>\& | Encoded URI fragment. |
| offset | int32_t | Offset in the given byte array. |
| count | int32_t | Number of bytes to read from. |
| e | const System::SharedPtr\<Text::Encoding\>\& | Encoding to use. |

### ReturnValue

Decoded URI fragment.

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Encoding](../../../system.text/encoding/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
## HttpUtility::UrlDecode(String) method


Decodes URI fragment from string.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | String | Encoded URI fragment. |

### ReturnValue

Decoded URI fragment.

## See Also

* Class [String](../../../system/string/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) method


Decodes URI fragment from string.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | String | Encoded URI fragment. |
| e | System::SharedPtr\<Text::Encoding\> | Encoding to use. |

### ReturnValue

Decoded URI fragment.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Encoding](../../../system.text/encoding/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
