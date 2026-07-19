---
title: "Метод System::Web::HttpUtility::UrlDecodeToBytes"
linktitle: "UrlDecodeToBytes"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Web::HttpUtility::UrlDecodeToBytes. Декодирует URI-фрагмент из строкового массива байтов в C++."
type: docs
weight: 400
url: /ru/cpp/system.web/httputility/urldecodetobytes/
---
## HttpUtility::UrlDecodeToBytes(const String\&) method


Декодирует фрагмент URI из байтовой строки.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const String\& | Закодированный фрагмент URI. |

### ReturnValue

Декодированный URI-фрагмент.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
## HttpUtility::UrlDecodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) method


Декодирует фрагмент URI из строки.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const String\& | Закодированный фрагмент URI. |
| e | const System::SharedPtr\<Text::Encoding\>\& | Кодировка для использования. |

### ReturnValue

Декодированный URI-фрагмент.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Encoding](../../../system.text/encoding/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&) method


Декодирует фрагмент URI из массива байтов.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| байты | const System::ArrayPtr\<uint8_t\>\& | Закодированный фрагмент URI. |

### ReturnValue

Декодированный URI-фрагмент.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Декодирует фрагмент URI из массива байтов.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| байты | const System::ArrayPtr\<uint8_t\>\& | Закодированный фрагмент URI. |
| смещение | int32_t | Смещение в заданном массиве байтов. |
| count | int32_t | Количество байтов для чтения. |

### ReturnValue

Декодированный URI-фрагмент.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
