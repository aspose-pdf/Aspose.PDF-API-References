---
title: "Aspose::Pdf::Forms::SignatureField class"
linktitle: "SignatureField"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Forms::SignatureField class. Представляет поле формы подписи в C++."
type: docs
weight: 2600
url: /ru/cpp/aspose.pdf.forms/signaturefield/
---
## SignatureField class


Представляет поле формы подписи.

```cpp
class SignatureField : public Aspose::Pdf::Forms::Field
```

## Методы

| Метод | Описание |
| --- | --- |
| [ExtractCertificate](./extractcertificate/)() | Извлекает единственный сертификат X.509 в формате DER как поток. |
| [ExtractCertificateObject](./extractcertificateobject/)() | Извлекает единственный объект сертификата X.509. |
| [ExtractImage](./extractimage/)() | Извлекает изображение подписи как поток, закодированный в JPEG. |
| [ExtractImage](./extractimage/)(const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Извлекает изображение подписи как закодированный поток. |
| [get_Signature](./get_signature/)() | Получает объект подписи. Этот объект содержит данные подписи, относящиеся к стандартам криптографии с открытым ключом. Классы [PKCS1](../pkcs1/), [PKCS7](../pkcs7/) и [PKCS7Detached](../pkcs7detached/) представляют все поддерживаемые типы объектов подписи. |
| [Sign](./sign/)(const System::SharedPtr\<Aspose::Pdf::Forms::Signature\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Подписывает документ, используя это поле подписи. |
| [Sign](./sign/)(const System::SharedPtr\<Aspose::Pdf::Forms::Signature\>\&) | Подписать документ, используя это поле подписи. |
| [SignatureField](./signaturefield/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Инициализирует новый экземпляр класса [SignatureField](./). |
| [SignatureField](./signaturefield/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Rectangle\>\&) | Инициализирует новый экземпляр класса [SignatureField](./). |
## См. также

* Class [Field](../field/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
