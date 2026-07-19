---
title: "System::Security::Cryptography::X509Certificates::X509Certificate2 класс"
linktitle: "X509Certificate2"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::X509Certificates::X509Certificate2 класс. Представляет сертификат X509. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 400
url: /ru/cpp/system.security.cryptography.x509certificates/x509certificate2/
---
## X509Certificate2 class


Представляет сертификат X509. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class X509Certificate2 : public System::Security::Cryptography::X509Certificates::X509Certificate
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Archived](./get_archived/)() const | Возвращает значение, указывающее, что сертификат архивирован. |
| [get_Extensions](./get_extensions/)() const | Возвращает коллекцию объектов расширений, связанных с сертификатом. |
| [get_FriendlyName](./get_friendlyname/)() const | Возвращает дружественное имя сертификата. |
| [get_HasPrivateKey](./get_hasprivatekey/)() const | Проверяет, имеет ли сертификат закрытый ключ. |
| [get_IssuerName](./get_issuername/)() const | Получает имя стороны, выдавшей сертификат. |
| [get_NotAfter](./get_notafter/)() const | Получает локальные дату и время, после которых сертификат более не действителен. |
| [get_NotBefore](./get_notbefore/)() const | Получает локальные дату и время, с которых сертификат становится действительным. |
| [get_PrivateKey](./get_privatekey/)() const | Получает закрытый ключ, связанный с сертификатом. |
| [get_PublicKey](./get_publickey/)() const | Получает объект [PublicKey](../publickey/) сертификата. |
| [get_RawData](./get_rawdata/)() const | Получает необработанные данные сертификата. |
| [get_SerialNumber](./get_serialnumber/)() const | Получает серийный номер сертификата. |
| [get_SignatureAlgorithm](./get_signaturealgorithm/)() const | Получает алгоритм, используемый для создания подписи сертификата. |
| [get_SubjectName](./get_subjectname/)() const | Получает имя субъекта из сертификата. |
| [get_Thumbprint](./get_thumbprint/)() const | Получает отпечаток сертификата. |
| [get_Version](./get_version/)() const | Получает версию формата сертификата. |
| static [GetCertContentType](./getcertcontenttype/)(const ByteArrayPtr\&) | Получает тип сертификата, содержащегося в указанном массиве байтов. |
| static [GetCertContentType](./getcertcontenttype/)(const String\&) | Получает тип сертификата, содержащегося в указанном файле. |
| [GetDSAPrivateKey](./getdsaprivatekey/)() const | Получает закрытый ключ [RSA](../../system.security.cryptography/rsa/);. |
| [GetDSAPublicKey](./getdsapublickey/)() const | Получает открытый ключ [RSA](../../system.security.cryptography/rsa/). |
| [GetECDsaPrivateKey](./getecdsaprivatekey/)() const | Получает закрытый ключ [RSA](../../system.security.cryptography/rsa/);. |
| [GetECDsaPublicKey](./getecdsapublickey/)() const | Получает открытый ключ [RSA](../../system.security.cryptography/rsa/). |
| [GetNameInfo](./getnameinfo/)(X509NameType, bool) const | Получает имя субъекта или издателя из сертификата. |
| [GetRSAPrivateKey](./getrsaprivatekey/)() const | Получает закрытый ключ [RSA](../../system.security.cryptography/rsa/);. |
| [GetRSAPublicKey](./getrsapublickey/)() const | Получает открытый ключ [RSA](../../system.security.cryptography/rsa/). |
| [Import](./import/)(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) override | Импортирует информацию из указанного файла сертификата. |
| [Import](./import/)(const String\&, const String\&, X509KeyStorageFlags) override | Импортирует информацию из указанного файла сертификата. |
| [Import](./import/)(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) override | Импортирует информацию из указанных данных сертификата. |
| [Import](./import/)(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) override | Импортирует информацию из указанных данных сертификата. |
| [Import](./import/)(const String\&) override | Импортирует информацию из указанного файла сертификата. |
| [Import](./import/)(const ByteArrayPtr\&) override | Импортирует информацию из указанных данных сертификата. |
| [Reset](./reset/)() override | Сбрасывает состояние сертификата. |
| [set_Archived](./set_archived/)(bool) const | Устанавливает значение, указывающее, что сертификат архивирован. |
| [set_FriendlyName](./set_friendlyname/)(const String\&) | Устанавливает дружественное имя сертификата. |
| [set_PrivateKey](./set_privatekey/)(const SharedPtr\<AsymmetricAlgorithm\>\&) | Устанавливает или очищает закрытый ключ, связанный с сертификатом. |
| [ToString](./tostring/)(bool) const override | Возвращает информацию о сертификате в текстовом формате. |
| [ToString](./tostring/)() const override | Возвращает информацию о сертификате в текстовом формате. |
| [Verify](./verify/)() const | Проверяет цепочку сертификатов. |
| [X509Certificate2](./x509certificate2/)() | Создаёт пустой объект [X509Certificate2](./). |
| [X509Certificate2](./x509certificate2/)(const String\&) | Конструктор. |
| [X509Certificate2](./x509certificate2/)(const SharedPtr\<X509Certificate\>\&) | Конструктор. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&) | Конструктор. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&, const String\&) | Конструктор. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&, const SecureStringPtr\&) | Конструктор. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) | Конструктор. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) | Конструктор. |
| [X509Certificate2](./x509certificate2/)(const String\&, const String\&) | Конструктор. |
| [X509Certificate2](./x509certificate2/)(const String\&, const SecureStringPtr\&) | Конструктор. |
| [X509Certificate2](./x509certificate2/)(const String\&, const String\&, X509KeyStorageFlags) | Конструктор. |
| [X509Certificate2](./x509certificate2/)(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) | Конструктор. |
| [X509Certificate2](./x509certificate2/)(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) | Конструктор. |
## См. также

* Class [X509Certificate](../x509certificate/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
