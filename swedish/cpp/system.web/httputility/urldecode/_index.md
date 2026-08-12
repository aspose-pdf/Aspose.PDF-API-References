---
title: "System::Web::HttpUtility::UrlDecode metod"
linktitle: "UrlDecode"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Web::HttpUtility::UrlDecode metod. Avkodar URI-fragment från byte-array i C++."
type: docs
weight: 300
url: /sv/cpp/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) method


Avkodar URI-fragment från byte-array.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| byte | const System::ArrayPtr\<uint8_t\>\& | Kodad URI-fragment. |
| e | const System::SharedPtr\<Text::Encoding\>\& | Kodning att använda. |

### ReturnValue

Avkodad URI-fragment.

## Se även

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Encoding](../../../system.text/encoding/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) method


Avkodar URI-fragment från byte-array.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| byte | const System::ArrayPtr\<uint8_t\>\& | Kodad URI-fragment. |
| förskjutning | int32_t | Offset i den givna bytearrayen. |
| count | int32_t | Antal byte att läsa från. |
| e | const System::SharedPtr\<Text::Encoding\>\& | Kodning att använda. |

### ReturnValue

Avkodad URI-fragment.

## Se även

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Encoding](../../../system.text/encoding/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
## HttpUtility::UrlDecode(String) method


Avkodar URI-fragment från sträng.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | String | Kodad URI-fragment. |

### ReturnValue

Avkodad URI-fragment.

## Se även

* Class [String](../../../system/string/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) method


Avkodar URI-fragment från sträng.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | String | Kodad URI-fragment. |
| e | System::SharedPtr\<Text::Encoding\> | Kodning att använda. |

### ReturnValue

Avkodad URI-fragment.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Encoding](../../../system.text/encoding/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
