---
title: "System::Web::HttpUtility::UrlEncodeToBytes метод"
linktitle: "UrlEncodeToBytes"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Web::HttpUtility::UrlEncodeToBytes метод. Кодирует фрагмент URI в C++."
type: docs
weight: 600
url: /ru/cpp/system.web/httputility/urlencodetobytes/
---
## HttpUtility::UrlEncodeToBytes(const String\&) method


Кодирует фрагмент URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const String\& | Фрагмент URI для кодирования. |

### ReturnValue

Закодированный фрагмент URI.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
## HttpUtility::UrlEncodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) method


Кодирует фрагмент URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const String\& | Фрагмент URI для кодирования. |
| e | const System::SharedPtr\<Text::Encoding\>\& | Кодировка для использования. |

### ReturnValue

Закодированный фрагмент URI.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Encoding](../../../system.text/encoding/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&) method


Кодирует фрагмент URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| байты | const System::ArrayPtr\<uint8_t\>\& | Фрагмент URI для кодирования. |

### ReturnValue

Закодированный фрагмент URI.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Кодирует фрагмент URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| байты | const System::ArrayPtr\<uint8_t\>\& | Фрагмент URI для кодирования. |
| смещение | int32_t | Смещение в заданном массиве байтов. |
| count | int32_t | Количество байтов для чтения. |

### ReturnValue

Закодированный фрагмент URI.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
