---
title: "Aspose::Pdf::Facades::PdfFileSignature::Sign метод"
linktitle: "Sign"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileSignature::Sign метод. Подписать документ с заданной типовой подписью, размещённой в уже представленном поле подписи. Перед подписанием поле подписи должно быть пустым, т.е. поле не должно содержать словарь подписи. Таким образом, в PDF‑документе уже есть поле подписи, вам не нужно указывать место для нанесения подписи, соответствующая страница и прямоугольник берутся из поля подписи, найденного по имени подписи (см. параметр SigName). Такие данные, как причина подписи, контакт и место, должны быть предоставлены соответствующими свойствами объекта Signature sig в C++."
type: docs
weight: 3600
url: /ru/cpp/aspose.pdf.facades/pdffilesignature/sign/
---
## PdfFileSignature::Sign(const System::String\&, const System::SharedPtr\<Forms::Signature\>\&) method


Подпишите документ подписью указанного типа, размещённой в уже существующем поле подписи. Перед подписью поле подписи должно быть пустым, то есть не должно содержать словарь подписи. Таким образом, PDF‑документ уже содержит поле подписи, вам не нужно указывать место для нанесения подписи; соответствующая страница и прямоугольник берутся из поля подписи, найденного по имени подписи (см. параметр SigName). Такие данные, как причина подписи, контакт и место, должны быть заданы соответствующими свойствами объекта Signature sig.

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Sign(const System::String &SigName, const System::SharedPtr<Forms::Signature> &sig)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| SigName | const System::String\& | Имя поля подписи. |
| sig | const System::SharedPtr\<Forms::Signature\>\& | Тип подписи может быть PKCS1 (объект Pkcs1Signature), PKCS7 и PKCS7 detached (объект Pkcs7Signature) |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../../aspose.pdf.forms/signature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::Sign(const System::String\&, const System::String\&, const System::String\&, const System::String\&, const System::SharedPtr\<Forms::Signature\>\&) method


Подпишите документ подписью указанного типа, размещённой в уже существующем поле подписи. Перед подписью поле подписи должно быть пустым, то есть не должно содержать словарь подписи. Таким образом, PDF‑документ уже содержит поле подписи, вам не нужно указывать место для нанесения подписи; соответствующая страница и прямоугольник берутся из поля подписи, найденного по имени подписи (см. параметр SigName).

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Sign(const System::String &SigName, const System::String &SigReason, const System::String &SigContact, const System::String &SigLocation, const System::SharedPtr<Forms::Signature> &sig)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| SigName | const System::String\& | Имя поля подписи. |
| SigReason | const System::String\& | Причина подписи. |
| SigContact | const System::String\& | Контакт подписи. |
| SigLocation | const System::String\& | Местоположение подписи. |
| sig | const System::SharedPtr\<Forms::Signature\>\& | Тип подписи может быть PKCS1, PKCS7 и PKCS7Detached. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../../aspose.pdf.forms/signature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::Sign(int32_t, bool, System::Drawing::Rectangle, const System::SharedPtr\<Forms::Signature\>\&) method


Подпишите документ подписью указанного типа.

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Sign(int32_t page, bool visible, System::Drawing::Rectangle annotRect, const System::SharedPtr<Forms::Signature> &sig)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | int32_t | Номер страницы, на которой выполнена подпись. |
| visible | bool | Видимость подписи. |
| annotRect | System::Drawing::Rectangle | Прямоугольник подписи. |
| sig | const System::SharedPtr\<Forms::Signature\>\& | Тип подписи может быть PKCS1, PKCS7 и PKCS7Detached. Такие данные, как причина подписи, контакт и место, должны уже присутствовать в этом объекте (см. соответствующие свойства). |

## См. также

* Class [Rectangle](../../../system.drawing/rectangle/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../../aspose.pdf.forms/signature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::Sign(int32_t, const System::String\&, const System::String\&, const System::String\&, const System::String\&, bool, System::Drawing::Rectangle, const System::SharedPtr\<Forms::Signature\>\&) method


Подпишите документ подписью указанного типа, размещённой в уже существующем поле подписи. Перед подписью PDF‑документ уже должен содержать поле подписи; соответствующая страница и прямоугольник берутся из поля подписи, найденного по имени подписи (см. параметр SigName).

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Sign(int32_t page, const System::String &SigName, const System::String &SigReason, const System::String &SigContact, const System::String &SigLocation, bool visible, System::Drawing::Rectangle annotRect, const System::SharedPtr<Forms::Signature> &sig)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | int32_t | Номер страницы, на которой выполнена подпись. |
| SigName | const System::String\& | Имя поля подписи. |
| SigReason | const System::String\& | Причина подписи. |
| SigContact | const System::String\& | Контакт подписи. |
| SigLocation | const System::String\& | Местоположение подписи. |
| visible | bool | Видимость подписи. |
| annotRect | System::Drawing::Rectangle | Прямоугольник подписи. |
| sig | const System::SharedPtr\<Forms::Signature\>\& | Тип подписи может быть PKCS1, PKCS7 и PKCS7Detached. |

## См. также

* Class [String](../../../system/string/)
* Class [Rectangle](../../../system.drawing/rectangle/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../../aspose.pdf.forms/signature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::Sign(int32_t, const System::String\&, const System::String\&, const System::String\&, bool, System::Drawing::Rectangle) method


Создайте подпись в PDF‑документе.

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Sign(int32_t page, const System::String &SigReason, const System::String &SigContact, const System::String &SigLocation, bool visible, System::Drawing::Rectangle annotRect)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | int32_t | Номер страницы, на которой выполнена подпись. |
| SigReason | const System::String\& | Причина подписи. |
| SigContact | const System::String\& | Контакт подписи. |
| SigLocation | const System::String\& | Местоположение подписи. |
| visible | bool | Видимость подписи. |
| annotRect | System::Drawing::Rectangle | Прямоугольник подписи. |

## См. также

* Class [String](../../../system/string/)
* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileSignature::Sign(int32_t, const System::String\&, const System::String\&, const System::String\&, bool, System::Drawing::Rectangle, const System::SharedPtr\<Forms::Signature\>\&) method


Подпишите документ подписью указанного типа.

```cpp
void Aspose::Pdf::Facades::PdfFileSignature::Sign(int32_t page, const System::String &SigReason, const System::String &SigContact, const System::String &SigLocation, bool visible, System::Drawing::Rectangle annotRect, const System::SharedPtr<Forms::Signature> &sig)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | int32_t | Номер страницы, на которой выполнена подпись. |
| SigReason | const System::String\& | Причина подписи. |
| SigContact | const System::String\& | Контакт подписи. |
| SigLocation | const System::String\& | Местоположение подписи. |
| visible | bool | Видимость подписи. |
| annotRect | System::Drawing::Rectangle | Прямоугольник подписи. |
| sig | const System::SharedPtr\<Forms::Signature\>\& | Тип подписи может быть PKCS1, PKCS7 и PKCS7Detached. |

## См. также

* Class [String](../../../system/string/)
* Class [Rectangle](../../../system.drawing/rectangle/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Signature](../../../aspose.pdf.forms/signature/)
* Class [PdfFileSignature](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
