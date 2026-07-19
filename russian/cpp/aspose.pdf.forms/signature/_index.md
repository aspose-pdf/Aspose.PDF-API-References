---
title: "Класс Aspose::Pdf::Forms::Signature"
linktitle: "Signature"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Forms::Signature. Абстрактный класс, представляющий объект подписи в PDF‑документе. Подписи являются полями со значениями объектов подписи, последние содержат данные, используемые для проверки действительности документа в C++."
type: docs
weight: 2400
url: /ru/cpp/aspose.pdf.forms/signature/
---
## Signature class


Абстрактный класс, представляющий объект подписи в PDF‑документе. [Подписи](../../aspose.pdf.signatures/) являются полями со значениями объектов подписи, последние содержат данные, используемые для проверки действительности документа.

```cpp
class Signature : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Authority](./get_authority/)() const | Имя лица или организации, подписывающих документ. |
| [get_AvoidEstimatingSignatureLength](./get_avoidestimatingsignaturelength/)() const | Получает и задает параметр, определяющий, следует ли избегать оценки длины подписи. |
| [get_ByteRange](./get_byterange/)() const | Массив пар целых чисел (начальное смещение в байтах, длина в байтах), описывающих точный диапазон байтов для вычисления дайджеста. |
| [get_ContactInfo](./get_contactinfo/)() const | Информация, предоставленная подписавшим, позволяющая получателю связаться с подписавшим для проверки подписи, например номер телефона. |
| [get_CustomAppearance](./get_customappearance/)() const | Получает/устанавливает пользовательское отображение. |
| [get_CustomSignHash](./get_customsignhash/)() const | Делегат для пользовательского подписания хеша документа. |
| [get_Date](./get_date/)() const | Время подписи. |
| [get_DefaultSignatureLength](./get_defaultsignaturelength/)() const | Получает значение длины данных подписи по умолчанию в байтах. |
| [get_Location](./get_location/)() const | Имя хоста CPU или физическое местоположение подписи. |
| [get_OcspSettings](./get_ocspsettings/)() const | Получает/устанавливает настройки OCSP. |
| [get_Reason](./get_reason/)() const | Причина подписи, например (Я согласен, Pip B.). |
| [get_ShowProperties](./get_showproperties/)() const | Принудительно показывать/скрывать свойства подписи. |
| [get_TimestampSettings](./get_timestampsettings/)() const | Получает/устанавливает настройки метки времени. |
| [get_UseLtv](./get_useltv/)() const | Получает/устанавливает флаг проверки LTV. |
| [GetSignatureAlgorithmInfo](./getsignaturealgorithminfo/)() | Получает информацию об алгоритме подписи, используемом в подписи. |
| [set_Authority](./set_authority/)(const System::String\&) | Имя лица или организации, подписывающих документ. |
| [set_AvoidEstimatingSignatureLength](./set_avoidestimatingsignaturelength/)(bool) | Получает и задает параметр, определяющий, следует ли избегать оценки длины подписи. |
| [set_ContactInfo](./set_contactinfo/)(const System::String\&) | Информация, предоставленная подписавшим, позволяющая получателю связаться с подписавшим для проверки подписи, например номер телефона. |
| [set_CustomAppearance](./set_customappearance/)(const System::SharedPtr\<SignatureCustomAppearance\>\&) | Получает/устанавливает пользовательское отображение. |
| [set_CustomSignHash](./set_customsignhash/)(SignHash) | Делегат для пользовательского подписания хеша документа. |
| [set_Date](./set_date/)(System::DateTime) | Время подписи. |
| [set_DefaultSignatureLength](./set_defaultsignaturelength/)(int32_t) | Устанавливает значение длины данных подписи по умолчанию в байтах. |
| [set_Location](./set_location/)(const System::String\&) | Имя хоста CPU или физическое местоположение подписи. |
| [set_OcspSettings](./set_ocspsettings/)(const System::SharedPtr\<Aspose::Pdf::OcspSettings\>\&) | Получает/устанавливает настройки OCSP. |
| [set_Reason](./set_reason/)(const System::String\&) | Причина подписи, например (Я согласен, Pip B.). |
| [set_ShowProperties](./set_showproperties/)(bool) | Принудительно показывать/скрывать свойства подписи. |
| [set_TimestampSettings](./set_timestampsettings/)(const System::SharedPtr\<Aspose::Pdf::TimestampSettings\>\&) | Получает/устанавливает настройки метки времени. |
| [set_UseLtv](./set_useltv/)(bool) | Получает/устанавливает флаг проверки LTV. |
| [Signature](./signature/)() | Инициализирует новый экземпляр класса [Signature](./). |
| [Signature](./signature/)(const System::String\&, const System::String\&) | Инициализирует новый экземпляр класса [Signature](./). |
| [Signature](./signature/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Инициализирует новый экземпляр класса [Signature](./). |
| [TryVerify](./tryverify/)(System::SharedPtr\<Security::VerificationResult\>\&) | Попробуйте проверить документ относительно этой подписи и вернуть true, если документ действителен, иначе false. |
| [TryVerify](./tryverify/)(const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) | Попробуйте проверить документ относительно этой подписи и вернуть true, если документ действителен, иначе false. |
| [TryVerify](./tryverify/)(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) | Попробуйте проверить документ относительно этой подписи и вернуть true, если документ действителен, иначе false. Проверка выполняется с использованием внешнего сертификата открытого ключа. |
| [Verify](./verify/)() | Проверяет документ относительно этой подписи и возвращает true, если документ действителен, иначе false. |
| [Verify](./verify/)(const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) | Проверяет документ относительно этой подписи и возвращает true, если документ действителен, иначе false. |
| [Verify](./verify/)(const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) | Проверяет документ относительно этой подписи и возвращает true, если документ действителен, иначе false. Проверка выполняется с использованием внешнего сертификата открытого ключа. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
