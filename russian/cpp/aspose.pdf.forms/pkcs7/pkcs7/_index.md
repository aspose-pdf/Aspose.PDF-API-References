---
title: "Aspose::Pdf::Forms::PKCS7::PKCS7 конструктор"
linktitle: "PKCS7"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Forms::PKCS7::PKCS7 конструктор. Инициализирует новый экземпляр класса PKCS7 на C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.forms/pkcs7/pkcs7/
---
## PKCS7::PKCS7() constructor


Инициализирует новый экземпляр класса [PKCS7](../).

```cpp
Aspose::Pdf::Forms::PKCS7::PKCS7()
```

## См. также

* Class [PKCS7](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7::PKCS7(const System::SharedPtr\<Aspose::Pdf::TimestampSettings\>\&) constructor


Инициализирует новый экземпляр класса [PKCS7](../).

```cpp
Aspose::Pdf::Forms::PKCS7::PKCS7(const System::SharedPtr<Aspose::Pdf::TimestampSettings> &timestampSettings)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| timestampSettings | const System::SharedPtr\<Aspose::Pdf::TimestampSettings\>\& | Настройки отметки времени для подписи. |
## Примечания



Настройки отметки времени используются для создания подписи с отметкой времени без необходимости предоставления сертификата. Вы можете установить отметку времени для документа как отдельную подпись.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TimestampSettings](../../../aspose.pdf/timestampsettings/)
* Class [PKCS7](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7::PKCS7(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) constructor


Инициализирует новый экземпляр класса [PKCS7](../).

```cpp
Aspose::Pdf::Forms::PKCS7::PKCS7(const System::SharedPtr<System::IO::Stream> &pfx, const System::String &password)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| pfx | const System::SharedPtr\<System::IO::Stream\>\& | Поток с данными сертификата, организованными как pfx. |
| password | const System::String\& | Пароль для доступа к закрытому ключу в сертификате. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [PKCS7](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## PKCS7::PKCS7(const System::String\&, const System::String\&) constructor


Инициализирует новый экземпляр класса [PKCS7](../).

```cpp
Aspose::Pdf::Forms::PKCS7::PKCS7(const System::String &pfx, const System::String &password)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| pfx | const System::String\& | Файл pfx, содержащий сертификат для подписи. |
| password | const System::String\& | Пароль для сертификата. |
## Примечания



Пароль для доступа к закрытому ключу в сертификате.
## См. также

* Class [String](../../../system/string/)
* Class [PKCS7](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
