---
title: "Aspose::Pdf::Facades::PdfFileSignature::Certify method"
linktitle: "Certify"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileSignature::Certify method. Подпишите документ с помощью подписи MDP, которая размещена в уже существующем поле подписи. Перед подписанием поле подписи должно быть пустым, то есть поле не должно содержать словарь подписи. Таким образом, PDF‑документ уже имеет поле подписи; вам не нужно указывать место для нанесения подписи, соответствующая страница и прямоугольник берутся из поля подписи, найденного по имени подписи (см. параметр sigName) в C++."
type: docs
weight: 300
url: /ru/cpp/aspose.pdf.facades/pdffilesignature/certify/
---
## PdfFileSignature::Certify(const System::String\&, const System::SharedPtr\<Forms::DocMDPSignature\>\&) method


Заверить документ подписью MDP, размещённой в уже существующем поле подписи. Перед подписью поле подписи должно быть пустым, то есть поле не должно содержать словарь подписи. Таким образом, pdf‑документ уже содержит поле подписи; вам не нужно указывать место для нанесения подписи, соответствующая страница и прямоугольник берутся из поля подписи, найденного по имени подписи (см. параметр sigName).

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Certify(const System::String &sigName, const System::SharedPtr<Forms::DocMDPSignature> &docMdpSignature)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| sigName | const System::String\& | Имя поля подписи. |
| docMdpSignature | const System::SharedPtr\<Forms::DocMDPSignature\>\& | Тип подписи, может быть [Aspose::Pdf::Forms::PKCS1](../../../aspose.pdf.forms/pkcs1/), [Aspose::Pdf::Forms::PKCS7](../../../aspose.pdf.forms/pkcs7/) и [Aspose::Pdf::Forms::PKCS7Detached](../../../aspose.pdf.forms/pkcs7detached/). |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::Certify(int32_t, const System::String\&, const System::String\&, const System::String\&, bool, System::Drawing::Rectangle, const System::SharedPtr\<Forms::DocMDPSignature\>\&) method


Заверить документ подписью MDP. Такие данные, как причина подписи, контакт и место, должны быть предоставлены соответствующими свойствами объекта Signature sig.

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Certify(int32_t page, const System::String &SigReason, const System::String &SigContact, const System::String &SigLocation, bool visible, System::Drawing::Rectangle annotRect, const System::SharedPtr<Forms::DocMDPSignature> &docMdpSignature)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | int32_t | Страница, на которой выполнена подпись. |
| SigReason | const System::String\& | Причина подписи. |
| SigContact | const System::String\& | Контакт подписи. |
| SigLocation | const System::String\& | Местоположение подписи. |
| visible | bool | Видимость подписи. |
| annotRect | System::Drawing::Rectangle | Прямоугольник подписи. |
| docMdpSignature | const System::SharedPtr\<Forms::DocMDPSignature\>\& | Тип MDP документа подписи. |

## См. также

* Class [String](../../../system/string/)
* Class [Rectangle](../../../system.drawing/rectangle/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
