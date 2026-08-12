---
title: "System::Uri::TryCreate method"
linktitle: "TryCreate"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Uri::TryCreate method. Создаёт объект Uri из указанных базового и относительного URI в C++."
type: docs
weight: 4400
url: /ru/cpp/system/uri/trycreate/
---
## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) method


Создаёт объект [Uri](../) из указанных базового и относительного URI.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| baseUri | const SharedPtr\<Uri\>\& | Базовый URI |
| relativeUri | const SharedPtr\<Uri\>\& | Относительный URI, который добавляется к базовому URI |
| result | SharedPtr\<Uri\>\& | Выходной параметр, который при успешном создании указывает на вновь созданный объект [Uri](../) при возврате из метода |

### ReturnValue

True, если создание успешно, иначе — false

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) method


Создаёт объект [Uri](../) из указанного объекта [Uri](../), представляющего базовый URI, и строкового представления относительного URI.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| baseUri | const SharedPtr\<Uri\>\& | Базовый URI |
| relativeUri | const String\& | Относительный URI, который добавляется к базовому URI |
| result | SharedPtr\<Uri\>\& | Выходной параметр, который при успешном создании указывает на вновь созданный объект [Uri](../) при возврате из метода |

### ReturnValue

True, если создание успешно, иначе — false

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) method


Создаёт объект [Uri](../), представляющий указанный URI; аргумент определяет тип URI.

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| uriString | const String\& | Строковый URI, который будет представлять создаваемый объект |
| uriKind | UriKind | Указывает тип URI |
| result | SharedPtr\<Uri\>\& | Выходной параметр, который при успешном создании указывает на вновь созданный объект [Uri](../) при возврате из метода |

### ReturnValue

True, если создание успешно, иначе — false

## См. также

* Class [String](../../string/)
* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
