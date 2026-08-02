---
title: "Класс PKCS1"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Forms.PKCS1. Представляет объект подписи, соответствующий стандарту PKCS1. Для подписи используется алгоритм шифрования RSA и метод хеширования SHA1."
type: docs
weight: 5290
url: /ru/net/aspose.pdf.forms/pkcs1/
---
## PKCS1 class

Представляет объект подписи, соответствующий стандарту PKCS#1. Для подписи используется алгоритм шифрования RSA и метод дайджеста SHA-1.

```csharp
public sealed class PKCS1 : Signature
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PKCS1](pkcs1/#constructor)() | Инициализирует новый экземпляр класса `PKCS1`. |
| [PKCS1](pkcs1/#constructor_1)(Stream) | Инициализирует новый экземпляр класса `PKCS1`. |
| [PKCS1](pkcs1/#constructor_2)(Stream, string) | Инициализирует новый экземпляр класса `PKCS1`. |
| [PKCS1](pkcs1/#constructor_3)(string, string) | Инициализирует новый экземпляр класса `PKCS1`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | Имя лица или организации, подписывающих документ. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | Получает и задает параметр, определяющий, следует ли избегать оценки длины подписи. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | Массив пар целых чисел (начальное смещение в байтах, длина в байтах), описывающих точный диапазон байтов для вычисления дайджеста. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | Информация, предоставляемая подписантом, позволяющая получателю связаться с подписантом для проверки подписи, например номер телефона. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Получает/задаёт пользовательский внешний вид. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | Делегат для пользовательской подписи хеша документа. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | Время подписи. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | Получает или задает длину данных подписи по умолчанию в байтах. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | Имя хоста CPU или физическое расположение подписи. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Получает/задает настройки ocsp. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | Причина подписи, например (I agree, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | Принудительно показывать/скрывать свойства подписи. Если ShowProperties равно true, поле подписи имеет предопределённый формат отображения (строки для представления): ------------------------------------------- Digitally signed by {certificate subject} Date: {signature.Date} Reason: {signature.Reason} Location: {signature.Location} ------------------------------------------- где {X} — заполнитель для значения X. Также подпись может иметь изображение; в этом случае перечисленные строки размещаются поверх изображения. ShowProperties по умолчанию равно true. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | Получает/задает настройки метки времени. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | Получает/задает флаг проверки ltv. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | Получает информацию об алгоритме подписи, используемом в подписи. |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | Проверяет документ относительно этой подписи и возвращает true, если документ действителен, иначе false. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | Проверяет документ относительно этой подписи и возвращает true, если документ действителен, иначе false. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(X509Certificate2, ValidationOptions, out ValidationResult) | Проверяет документ относительно этой подписи и возвращает true, если документ действителен, иначе false. Проверка выполняется с использованием внешнего сертификата открытого ключа. |

### См. также

* class [Signature](../signature/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


