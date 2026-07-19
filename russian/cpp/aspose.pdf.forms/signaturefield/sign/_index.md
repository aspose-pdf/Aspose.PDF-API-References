---
title: "Aspose::Pdf::Forms::SignatureField::Sign метод"
linktitle: "Sign"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Forms::SignatureField::Sign method. Подписывает документ с использованием этого поля подписи в C++."
type: docs
weight: 600
url: /ru/cpp/aspose.pdf.forms/signaturefield/sign/
---
## SignatureField::Sign(const System::SharedPtr\<Aspose::Pdf::Forms::Signature\>\&) method


Подписать документ, используя это поле подписи.

```cpp
void Aspose::Pdf::Forms::SignatureField::Sign(const System::SharedPtr<Aspose::Pdf::Forms::Signature> &signature)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| signature | const System::SharedPtr\<Aspose::Pdf::Forms::Signature\>\& | объект [Signature](../../signature/), см. [PKCS1](../../pkcs1/), [PKCS7](../../pkcs7/) и [PKCS7Detached](../../pkcs7detached/). |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../signature/)
* Class [SignatureField](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## SignatureField::Sign(const System::SharedPtr\<Aspose::Pdf::Forms::Signature\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) method


Подписывает документ, используя это поле подписи.

```cpp
void Aspose::Pdf::Forms::SignatureField::Sign(const System::SharedPtr<Aspose::Pdf::Forms::Signature> &signature, const System::SharedPtr<System::IO::Stream> &pfx, const System::String &pass)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| signature | const System::SharedPtr\<Aspose::Pdf::Forms::Signature\>\& | объект [Signature](../../signature/), см. [PKCS1](../../pkcs1/), [PKCS7](../../pkcs7/), [PKCS7Detached](../../pkcs7detached/). |
| pfx | const System::SharedPtr\<System::IO::Stream\>\& | Поток с сертификатом. |
| пароль | const System::String\& | Пароль для доступа к приватному в *pfx*. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../signature/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [SignatureField](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
