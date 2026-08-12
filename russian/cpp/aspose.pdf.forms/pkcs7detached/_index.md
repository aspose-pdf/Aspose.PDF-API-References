---
title: "Класс Aspose::Pdf::Forms::PKCS7Detached"
linktitle: "PKCS7Detached"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Forms::PKCS7Detached. Представляет объект PKCS#7, соответствующий спецификации PKCS#7 в Internet RFC 2315, PKCS #7: Cryptographic Message Syntax, версия 1.5. Оригинальный подписанный дайджест сообщения над диапазоном байтов документа включён в обычное поле PKCS#7 SignedData. В поле PKCS#7 SignedData в C++ не должно быть инкапсулировано никаких данных."
type: docs
weight: 2000
url: /ru/cpp/aspose.pdf.forms/pkcs7detached/
---
## PKCS7Detached class


Представляет объект PKCS#7, соответствующий спецификации PKCS#7 в Internet RFC 2315, PKCS #7: Cryptographic Message Syntax, версия 1.5. Оригинальный дайджест подписанного сообщения над диапазоном байтов документа включается как обычное поле PKCS#7 SignedData. Данные не инкапсулируются в поле PKCS#7 SignedData.

```cpp
class PKCS7Detached : public Aspose::Pdf::Forms::Signature
```

## Методы

| Метод | Описание |
| --- | --- |
| [PKCS7Detached](./pkcs7detached/)(const System::SharedPtr\<System::IO::Stream\>\&) | Инициализирует новый экземпляр класса [PKCS7Detached](./). |
| [PKCS7Detached](./pkcs7detached/)(const System::SharedPtr\<System::IO::Stream\>\&, DigestHashAlgorithm) | Инициализирует новый экземпляр класса [PKCS7Detached](./). |
| [PKCS7Detached](./pkcs7detached/)() | Инициализирует новый экземпляр класса [PKCS7Detached](./). |
| [PKCS7Detached](./pkcs7detached/)(DigestHashAlgorithm) | Инициализирует новый экземпляр класса [PKCS7Detached](./). |
| [PKCS7Detached](./pkcs7detached/)(const System::String\&, const System::String\&) | Инициализирует новый экземпляр класса [PKCS7Detached](./). |
| [PKCS7Detached](./pkcs7detached/)(const System::String\&, const System::String\&, DigestHashAlgorithm) | Инициализирует новый экземпляр класса [PKCS7Detached](./). |
| [PKCS7Detached](./pkcs7detached/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Инициализирует новый экземпляр класса [PKCS7Detached](./). |
| [PKCS7Detached](./pkcs7detached/)(const System::SharedPtr\<Aspose::Pdf::TimestampSettings\>\&) | Инициализирует новый экземпляр класса [PKCS7Detached](./). |
| [PKCS7Detached](./pkcs7detached/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, DigestHashAlgorithm) | Инициализирует новый экземпляр класса [PKCS7Detached](./). |
## См. также

* Class [Signature](../signature/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
