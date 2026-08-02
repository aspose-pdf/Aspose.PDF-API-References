---
title: "Aspose.Pdf.Security"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Пространство имен Aspose.Pdf.Security содержит классы, используемые для шифрования и цифровой подписи"
type: docs
weight: 210
url: /ru/net/aspose.pdf.security/
---
Пространство имён **Aspose.Pdf.Security** содержит классы, используемые для шифрования и цифровой подписи.

## Классы

| Класс | Описание |
| --- | --- |
| [CertificateEncryptionOptions](./certificateencryptionoptions/) | Представляет класс для параметров шифрования PDF документа с использованием метода шифрования на основе сертификата. Используется для открытия зашифрованных PDF документов. |
| [DsaAlgorithmInfo](./dsaalgorithminfo/) | Представляет класс для информации о алгоритме подписи DSA. |
| [EcdsaAlgorithmInfo](./ecdsaalgorithminfo/) | Представляет класс для информации о алгоритме подписи ECDSA. |
| [EncryptionParameters](./encryptionparameters/) | Представляет класс параметров шифрования. |
| [KeyedSignatureAlgorithmInfo](./keyedsignaturealgorithminfo/) | Представляет класс для информации о алгоритме подписи с ключом. |
| [RsaAlgorithmInfo](./rsaalgorithminfo/) | Представляет класс для информации о алгоритме подписи RSA. |
| [SignatureAlgorithmInfo](./signaturealgorithminfo/) | Представляет класс для информации об алгоритме подписи, включая его тип, криптографический стандарт и алгоритм хеширования дайджеста. |
| [SignatureLengthMismatchException](./signaturelengthmismatchexception/) | Представляет ошибки, возникающие при подписании PDF. Возникает, если [`SignHash`](../aspose.pdf.forms/signhash/) используется для подписи документа, и фактическая длина подписи превышает указанную в параметре [`DefaultSignatureLength`](../aspose.pdf.forms/signature/defaultsignaturelength/). |
| [TimestampAlgorithmInfo](./timestampalgorithminfo/) | Представляет класс для информации о алгоритме подписи с меткой времени. |
| [UnknownSignatureAlgorithmInfo](./unknownsignaturealgorithminfo/) | Представляет класс для информации о неизвестном алгоритме подписи. |
| [ValidationOptions](./validationoptions/) | Представляет параметры для проверки цифровой подписи в PDF документе. |
| [ValidationResult](./validationresult/) | Представляет результат процесса проверки сертификата. |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [ICustomSecurityHandler](./icustomsecurityhandler/) | Интерфейс пользовательского обработчика безопасности. |
## Перечисление

| Перечисление | Описание |
| --- | --- |
| [CryptographicStandard](./cryptographicstandard/) | Представляет доступные криптографические стандарты для защиты PDF‑документов. |
| [SignatureAlgorithmType](./signaturealgorithmtype/) | Перечисляет типы алгоритмов подписи, используемых для цифровых подписей. |
| [ValidationMethod](./validationmethod/) | Представляет перечисление, определяющее метод, используемый для проверки сертификата. |
| [ValidationMode](./validationmode/) | Указывает режим проверки для процессов проверки подписи PDF. |
| [ValidationStatus](./validationstatus/) | Представляет статус проверки сертификата. |


