---
title: "Метод System::Web::HttpUtility::UrlDecode"
linktitle: "UrlDecode"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Web::HttpUtility::UrlDecode. Декодирует URI-фрагмент из массива байтов в C++."
type: docs
weight: 300
url: /ru/cpp/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) method


Декодирует фрагмент URI из массива байтов.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| байты | const System::ArrayPtr\<uint8_t\>\& | Закодированный фрагмент URI. |
| e | const System::SharedPtr\<Text::Encoding\>\& | Кодировка для использования. |

### ReturnValue

Декодированный URI-фрагмент.

## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Encoding](../../../system.text/encoding/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) method


Декодирует фрагмент URI из массива байтов.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| байты | const System::ArrayPtr\<uint8_t\>\& | Закодированный фрагмент URI. |
| смещение | int32_t | Смещение в заданном массиве байтов. |
| count | int32_t | Количество байтов для чтения. |
| e | const System::SharedPtr\<Text::Encoding\>\& | Кодировка для использования. |

### ReturnValue

Декодированный URI-фрагмент.

## См. также

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Encoding](../../../system.text/encoding/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
## HttpUtility::UrlDecode(String) method


Декодирует фрагмент URI из строки.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | String | Закодированный фрагмент URI. |

### ReturnValue

Декодированный URI-фрагмент.

## См. также

* Class [String](../../../system/string/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) method


Декодирует фрагмент URI из строки.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | String | Закодированный фрагмент URI. |
| e | System::SharedPtr\<Text::Encoding\> | Кодировка для использования. |

### ReturnValue

Декодированный URI-фрагмент.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Encoding](../../../system.text/encoding/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
