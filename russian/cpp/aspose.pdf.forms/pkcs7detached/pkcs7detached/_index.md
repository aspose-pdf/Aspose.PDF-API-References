---
title: "Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached конструктор"
linktitle: "PKCS7Detached"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached конструктор. Инициализирует новый экземпляр класса PKCS7Detached в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.forms/pkcs7detached/pkcs7detached/
---
## PKCS7Detached::PKCS7Detached() constructor


Инициализирует новый экземпляр класса [PKCS7Detached](../).

```cpp
Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached()
```

## См. также

* Class [PKCS7Detached](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7Detached::PKCS7Detached(const System::SharedPtr\<Aspose::Pdf::TimestampSettings\>\&) constructor


Инициализирует новый экземпляр класса [PKCS7Detached](../).

```cpp
Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached(const System::SharedPtr<Aspose::Pdf::TimestampSettings> &timestampSettings)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| timestampSettings | const System::SharedPtr\<Aspose::Pdf::TimestampSettings\>\& | Настройки отметки времени для подписи. |
## Примечания



Настройки отметки времени используются для создания подписи с отметкой времени без необходимости предоставления сертификата. Вы можете установить отметку времени для документа как отдельную подпись.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TimestampSettings](../../../aspose.pdf/timestampsettings/)
* Class [PKCS7Detached](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7Detached::PKCS7Detached(const System::SharedPtr\<System::IO::Stream\>\&) constructor


Инициализирует новый экземпляр класса [PKCS7Detached](../).

```cpp
Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached(const System::SharedPtr<System::IO::Stream> &image)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const System::SharedPtr\<System::IO::Stream\>\& | Это изображение определит внешний вид подписи на странице. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PKCS7Detached](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7Detached::PKCS7Detached(const System::SharedPtr\<System::IO::Stream\>\&, DigestHashAlgorithm) constructor


Инициализирует новый экземпляр класса [PKCS7Detached](../).

```cpp
Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached(const System::SharedPtr<System::IO::Stream> &image, DigestHashAlgorithm digestHashAlgorithm)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const System::SharedPtr\<System::IO::Stream\>\& | Это изображение определит внешний вид подписи на странице. |
| digestHashAlgorithm | DigestHashAlgorithm | Алгоритм хеширования для подписи документа. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* Class [PKCS7Detached](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7Detached::PKCS7Detached(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) constructor


Инициализирует новый экземпляр класса [PKCS7Detached](../).

```cpp
Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached(const System::SharedPtr<System::IO::Stream> &pfx, const System::String &password)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| pfx | const System::SharedPtr\<System::IO::Stream\>\& | Поток с данными сертификата, организованными как pfx. |
| password | const System::String\& | Пароль для доступа к закрытому ключу в сертификате. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [PKCS7Detached](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7Detached::PKCS7Detached(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, DigestHashAlgorithm) constructor


Инициализирует новый экземпляр класса [PKCS7Detached](../).

```cpp
Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached(const System::SharedPtr<System::IO::Stream> &pfx, const System::String &password, DigestHashAlgorithm digestHashAlgorithm)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| pfx | const System::SharedPtr\<System::IO::Stream\>\& | Поток с данными сертификата, организованными как pfx. |
| password | const System::String\& | Пароль для доступа к закрытому ключу в сертификате. |
| digestHashAlgorithm | DigestHashAlgorithm | Алгоритм хеширования для подписи документа. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* Class [PKCS7Detached](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7Detached::PKCS7Detached(const System::String\&, const System::String\&) constructor


Инициализирует новый экземпляр класса [PKCS7Detached](../).

```cpp
Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached(const System::String &pfx, const System::String &password)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| pfx | const System::String\& | Файл pfx, содержащий сертификат для подписи. |
| password | const System::String\& | Пароль для доступа к закрытому ключу в сертификате. |

## См. также

* Class [String](../../../system/string/)
* Class [PKCS7Detached](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7Detached::PKCS7Detached(const System::String\&, const System::String\&, DigestHashAlgorithm) constructor


Инициализирует новый экземпляр класса [PKCS7Detached](../).

```cpp
Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached(const System::String &pfx, const System::String &password, DigestHashAlgorithm digestHashAlgorithm)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| pfx | const System::String\& | Файл pfx, содержащий сертификат для подписи. |
| password | const System::String\& | Пароль для доступа к закрытому ключу в сертификате. |
| digestHashAlgorithm | DigestHashAlgorithm | Алгоритм хеширования для подписи документа. |

## См. также

* Class [String](../../../system/string/)
* Enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* Class [PKCS7Detached](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7Detached::PKCS7Detached(DigestHashAlgorithm) constructor


Инициализирует новый экземпляр класса [PKCS7Detached](../).

```cpp
Aspose::Pdf::Forms::PKCS7Detached::PKCS7Detached(DigestHashAlgorithm digestHashAlgorithm)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| digestHashAlgorithm | DigestHashAlgorithm | Алгоритм хеширования для подписи документа. |

## См. также

* Enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* Class [PKCS7Detached](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
