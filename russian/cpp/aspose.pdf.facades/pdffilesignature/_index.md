---
title: "Aspose::Pdf::Facades::PdfFileSignature класс"
linktitle: "PdfFileSignature"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileSignature класс. Представляет класс для подписи pdf‑файла с сертификатом на C++."
type: docs
weight: 2500
url: /ru/cpp/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature class


Представляет класс для подписания PDF‑файла сертификатом.

```cpp
class PdfFileSignature : public Aspose::Pdf::Facades::SaveableFacade
```

## Методы

| Метод | Описание |
| --- | --- |
| [BindPdf](./bindpdf/)(System::String) override | Связывает [Pdf](../../aspose.pdf/) файл для редактирования. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Связывает [Pdf](../../aspose.pdf/) поток для редактирования. |
| [Certify](./certify/)(int32_t, const System::String\&, const System::String\&, const System::String\&, bool, System::Drawing::Rectangle, const System::SharedPtr\<Forms::DocMDPSignature\>\&) | Заверить документ подписью MDP. Такие данные, как причина подписи, контакт и место, должны быть предоставлены соответствующими свойствами объекта Signature sig. |
| [Certify](./certify/)(const System::String\&, const System::SharedPtr\<Forms::DocMDPSignature\>\&) | Заверить документ подписью MDP, размещённой в уже существующем поле подписи. Перед подписью поле подписи должно быть пустым, то есть поле не должно содержать словарь подписи. Таким образом, pdf‑документ уже содержит поле подписи; вам не нужно указывать место для нанесения подписи, соответствующая страница и прямоугольник берутся из поля подписи, найденного по имени подписи (см. параметр sigName). |
| [Close](./close/)() override | Закрывает фасад. |
| [ContainsSignature](./containssignature/)() | Проверяет, имеет ли pdf цифровую подпись или нет. |
| [ContainsUsageRights](./containsusagerights/)() | Проверяет, имеет ли pdf права использования или нет. |
| [CoversWholeDocument](./coverswholedocument/)(const System::String\&) | Проверяет, охватывает ли подпись весь документ. |
| [CoversWholeDocument](./coverswholedocument/)(const System::SharedPtr\<SignatureName\>\&) | Проверяет, охватывает ли подпись весь документ. |
| [ExtractCertificate](./extractcertificate/)(const System::String\&) | Извлекает единственный сертификат X.509 подписи в виде потока. |
| [ExtractCertificate](./extractcertificate/)(const System::SharedPtr\<SignatureName\>\&) | Извлекает единственный сертификат X.509 подписи в виде потока. |
| [ExtractImage](./extractimage/)(const System::String\&) | Извлекает изображение подписи. |
| [ExtractImage](./extractimage/)(const System::SharedPtr\<SignatureName\>\&) | Извлекает изображение подписи. |
| [get_IsCertified](./get_iscertified/)() | Получает флаг, определяющий, сертифицирован ли документ или нет. |
| [get_IsLtvEnabled](./get_isltvenabled/)() | Получает флаг включённого LTV. |
| [get_SignatureAppearance](./get_signatureappearance/)() const | Устанавливает или получает графическое отображение подписи. Значение свойства представляет имя файла изображения. |
| [get_SignatureAppearanceStream](./get_signatureappearancestream/)() const | Устанавливает или получает графическое отображение подписи. Значение свойства представляет поток изображения. |
| [GetAccessPermissions](./getaccesspermissions/)() | Возвращает значение прав доступа сертифицированного документа по типу подписи MDP. |
| [GetBlankSignatureNames](./getblanksignaturenames/)() | Получает имена всех пустых полей подписи. |
| [GetBlankSignNames](./getblanksignnames/)() | Получает имена всех пустых полей подписи. |
| [GetContactInfo](./getcontactinfo/)(const System::String\&) | Получает контактную информацию подписи. |
| [GetContactInfo](./getcontactinfo/)(const System::SharedPtr\<SignatureName\>\&) | Получает контактную информацию подписи. |
| [GetDateTime](./getdatetime/)(const System::String\&) | Получает дату и время подписи. |
| [GetDateTime](./getdatetime/)(const System::SharedPtr\<SignatureName\>\&) | Получает дату и время подписи. |
| [GetLocation](./getlocation/)(const System::String\&) | Получает местоположение подписи. |
| [GetLocation](./getlocation/)(const System::SharedPtr\<SignatureName\>\&) | Получает местоположение подписи. |
| [GetReason](./getreason/)(const System::String\&) | Получает причину подписи. |
| [GetReason](./getreason/)(const System::SharedPtr\<SignatureName\>\&) | Получает причину подписи. |
| [GetRevision](./getrevision/)(const System::String\&) | Получает ревизию подписи. |
| [GetRevision](./getrevision/)(const System::SharedPtr\<SignatureName\>\&) | Получает ревизию подписи. |
| [GetSignatureNames](./getsignaturenames/)(bool) | Получает имена всех непустых подписей. |
| [GetSignaturesInfo](./getsignaturesinfo/)() | Получает информацию обо всех алгоритмах подписей, присутствующих в PDF‑документе. |
| [GetSignerName](./getsignername/)(const System::String\&) | Получает имя лица или организации, подписывающих PDF‑документ. |
| [GetSignerName](./getsignername/)(const System::SharedPtr\<SignatureName\>\&) | Получает имя лица или организации, подписывающих PDF‑документ. |
| [GetSignNames](./getsignnames/)(bool) | Получает имена всех непустых подписей. |
| [GetTotalRevision](./gettotalrevision/)() | Получает общую ревизию. |
| [IsContainSignature](./iscontainsignature/)() | Проверяет, имеет ли pdf цифровую подпись или нет. |
| [IsCoversWholeDocument](./iscoverswholedocument/)(const System::String\&) | Проверяет, охватывает ли подпись весь документ. |
| [PdfFileSignature](./pdffilesignature/)() | Конструктор класса [PdfFileSignature](./). |
| [PdfFileSignature](./pdffilesignature/)(const System::String\&) | Конструктор класса [PdfFileSignature](./). |
| [PdfFileSignature](./pdffilesignature/)(const System::String\&, const System::String\&) | Конструктор класса [PdfFileSignature](./). |
| [PdfFileSignature](./pdffilesignature/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Инициализирует новый объект [PdfFileSignature](./) на основе *document*. |
| [PdfFileSignature](./pdffilesignature/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) | Инициализирует новый объект [PdfFileSignature](./) на основе *document*. |
| [RemoveSignature](./removesignature/)(const System::String\&) | Удалить подпись по имени подписи. |
| [RemoveSignature](./removesignature/)(const System::SharedPtr\<SignatureName\>\&) | Удалить подпись по имени подписи. |
| [RemoveSignature](./removesignature/)(const System::String\&, bool) | Удаляет подпись по имени подписи. |
| [RemoveSignature](./removesignature/)(const System::SharedPtr\<SignatureName\>\&, bool) | Удаляет подпись по имени подписи. |
| [RemoveSignatures](./removesignatures/)() | Удаляет все подписи. |
| [RemoveUsageRights](./removeusagerights/)() | Удаляет запись прав использования. |
| [Save](./save/)(System::String) override | Сохраняет полученный PDF в файл. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Сохраняет полученный PDF в поток. |
| [Save](./save/)() | Сохраните подписанный PDF‑файл. Имя выходного файла должно быть указано заранее с помощью соответствующего конструктора [PdfFileSignature](./). |
| [set_SignatureAppearance](./set_signatureappearance/)(const System::String\&) | Устанавливает или получает графическое отображение подписи. Значение свойства представляет имя файла изображения. |
| [set_SignatureAppearanceStream](./set_signatureappearancestream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Устанавливает или получает графическое отображение подписи. Значение свойства представляет поток изображения. |
| [SetCertificate](./setcertificate/)(const System::String\&, const System::String\&) | Установите файл сертификата и пароль для процедуры подписи. |
| [Sign](./sign/)(int32_t, const System::String\&, const System::String\&, const System::String\&, bool, System::Drawing::Rectangle) | Создайте подпись в PDF‑документе. |
| [Sign](./sign/)(int32_t, const System::String\&, const System::String\&, const System::String\&, bool, System::Drawing::Rectangle, const System::SharedPtr\<Forms::Signature\>\&) | Подпишите документ подписью указанного типа. |
| [Sign](./sign/)(int32_t, bool, System::Drawing::Rectangle, const System::SharedPtr\<Forms::Signature\>\&) | Подпишите документ подписью указанного типа. |
| [Sign](./sign/)(const System::String\&, const System::String\&, const System::String\&, const System::String\&, const System::SharedPtr\<Forms::Signature\>\&) | Подпишите документ подписью указанного типа, размещённой в уже существующем поле подписи. Перед подписью поле подписи должно быть пустым, то есть не должно содержать словарь подписи. Таким образом, PDF‑документ уже содержит поле подписи, вам не нужно указывать место для нанесения подписи; соответствующая страница и прямоугольник берутся из поля подписи, найденного по имени подписи (см. параметр SigName). |
| [Sign](./sign/)(int32_t, const System::String\&, const System::String\&, const System::String\&, const System::String\&, bool, System::Drawing::Rectangle, const System::SharedPtr\<Forms::Signature\>\&) | Подпишите документ подписью указанного типа, размещённой в уже существующем поле подписи. Перед подписью PDF‑документ уже должен содержать поле подписи; соответствующая страница и прямоугольник берутся из поля подписи, найденного по имени подписи (см. параметр SigName). |
| [Sign](./sign/)(const System::String\&, const System::SharedPtr\<Forms::Signature\>\&) | Подпишите документ подписью указанного типа, размещённой в уже существующем поле подписи. Перед подписью поле подписи должно быть пустым, то есть не должно содержать словарь подписи. Таким образом, PDF‑документ уже содержит поле подписи, вам не нужно указывать место для нанесения подписи; соответствующая страница и прямоугольник берутся из поля подписи, найденного по имени подписи (см. параметр SigName). Такие данные, как причина подписи, контакт и место, должны быть заданы соответствующими свойствами объекта Signature sig. |
| [TryExtractCertificate](./tryextractcertificate/)(const System::SharedPtr\<SignatureName\>\&, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&) | Извлекает единственный сертификат X.509 подписи. |
| [TryExtractCertificate](./tryextractcertificate/)(const System::SharedPtr\<SignatureName\>\&, System::SharedPtr\<System::IO::Stream\>\&) | Извлекает единственный сертификат X.509 подписи в виде потока. |
| [TryVerifySignature](./tryverifysignature/)(const System::SharedPtr\<SignatureName\>\&, System::SharedPtr\<Security::VerificationResult\>\&) | Попробуйте проверить действительность подписи. |
| [TryVerifySignature](./tryverifysignature/)(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) | Попробуйте проверить действительность подписи. |
| [TryVerifySignature](./tryverifysignature/)(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) | Попробуйте проверить действительность подписи. Проверка выполняется с использованием внешнего сертификата открытого ключа. |
| [TryVerifySignature](./tryverifysignature/)(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, System::SharedPtr\<Security::VerificationResult\>\&) | Попробуйте проверить действительность подписи. Проверка выполняется с использованием внешнего сертификата открытого ключа. |
| [VerifySignature](./verifysignature/)(const System::String\&) | Проверяет действительность подписи. |
| [VerifySignature](./verifysignature/)(const System::SharedPtr\<SignatureName\>\&) | Проверяет действительность подписи. |
| [VerifySignature](./verifysignature/)(const System::String\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) | Проверяет действительность подписи. |
| [VerifySignature](./verifysignature/)(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) | Проверяет действительность подписи. |
| [VerifySignature](./verifysignature/)(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) | Проверяет действительность подписи. Проверка выполняется с использованием внешнего сертификата открытого ключа. |
| [VerifySignature](./verifysignature/)(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&) | Проверяет действительность подписи. Проверка выполняется с использованием внешнего сертификата открытого ключа. |
| [VerifySigned](./verifysigned/)(const System::String\&) | Проверяет действительность подписи. Метод устарел и будет удалён в версии 25.1. Вместо него используйте метод VerifySignature. |
## См. также

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
