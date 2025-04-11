---
title: Class PKCS7Detached
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Forms.PKCS7Detached. Представляет объект PKCS7, который соответствует спецификации PKCS7 в Internet RFC 2315 PKCS 7 Cryptographic Message Syntax Version 1.5. Оригинальный подписанный дайджест сообщения по диапазону байтов документов включен как обычное поле PKCS7 SignedData. В поле PKCS7 SignedData не должно быть инкапсулировано никаких данных.
type: docs
weight: 5190
url: /ru/net/aspose.pdf.forms/pkcs7detached/
---
## Класс PKCS7Detached

Представляет объект PKCS#7, который соответствует спецификации PKCS#7 в Internet RFC 2315, PKCS #7: Cryptographic Message Syntax, Version 1.5. Оригинальный подписанный дайджест сообщения по диапазону байтов документа включен как обычное поле PKCS#7 SignedData. В поле PKCS#7 SignedData не должно быть инкапсулировано никаких данных.

```csharp
public sealed class PKCS7Detached : Signature
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PKCS7Detached](pkcs7detached/#constructor)() | Инициализирует новый экземпляр класса `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_1)(DigestHashAlgorithm) | Инициализирует новый экземпляр класса `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_2)(Stream) | Инициализирует новый экземпляр класса `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_3)(Stream, DigestHashAlgorithm) | Инициализирует новый экземпляр класса `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_4)(Stream, string) | Инициализирует новый экземпляр класса `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_6)(string, string) | Инициализирует новый экземпляр класса `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_5)(Stream, string, DigestHashAlgorithm) | Инициализирует новый экземпляр класса `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_7)(string, string, DigestHashAlgorithm) | Инициализирует новый экземпляр класса `PKCS7Detached`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | Имя человека или органа, подписывающего документ. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | Получает и устанавливает опцию, означающую, следует ли избегать оценки длины подписи. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | Массив пар целых чисел (начальный байтовый смещение, длина в байтах), который должен описывать точный диапазон байтов для расчета дайджеста. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | Информация, предоставленная подписантом, чтобы позволить получателю связаться с подписантом для проверки подписи, например, номер телефона. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Получает/устанавливает пользовательский вид. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | Делегат для пользовательской подписи хеша документа. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | Время подписания. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | Получает или устанавливает стандартную длину для данных подписи в байтах. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | Имя хоста ЦП или физическое местоположение подписания. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Получает/устанавливает настройки ocsp. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | Причина подписания, такая как (Я согласен, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | Принудительно отображает/скрывает свойства подписи. Если ShowProperties равно true, поле подписи имеет предопределенный формат отображения (строки для представления): ------------------------------------------- Цифровая подпись от {субъект сертификата} Дата: {signature.Date} Причина: {signature.Reason} Местоположение: {signature.Location} ------------------------------------------- где {X} является заполнителем для значения X. Также подпись может иметь изображение, в этом случае перечисленные строки размещаются поверх изображения. По умолчанию ShowProperties равно true. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | Получает/устанавливает настройки временной метки. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | Получает/устанавливает флаг проверки ltv. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | Извлекает информацию о алгоритме подписи, используемом в подписи. |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | Проверяет документ относительно этой подписи и возвращает true, если документ действителен, или false в противном случае. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | Проверяет документ относительно этой подписи и возвращает true, если документ действителен, или false в противном случае. |

### См. также

* класс [Signature](../signature/)
* пространство имен [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* сборка [Aspose.PDF](../../)