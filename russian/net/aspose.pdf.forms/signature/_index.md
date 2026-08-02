---
title: "Класс Signature"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Forms.Signature. Абстрактный класс, представляющий объект подписи в PDF‑документе. Подписи — это поля со значениями объектов подписи, которые содержат данные, используемые для проверки валидности документа."
type: docs
weight: 5390
url: /ru/net/aspose.pdf.forms/signature/
---
## Signature class

Абстрактный класс, представляющий объект подписи в PDF‑документе. Подписи являются полями со значениями объектов подписи, последние содержат данные, используемые для проверки действительности документа.

```csharp
public abstract class Signature
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Signature](signature/#constructor)() | Инициализирует новый экземпляр класса `Signature`. |
| [Signature](signature/#constructor_1)(Stream, string) | Инициализирует новый экземпляр класса `Signature`. |
| [Signature](signature/#constructor_2)(string, string) | Инициализирует новый экземпляр класса `Signature`. |

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
| [Verify](../../aspose.pdf.forms/signature/verify/#verify)() | Проверяет документ относительно этой подписи и возвращает true, если документ действителен, иначе false. |
| [Verify](../../aspose.pdf.forms/signature/verify/#verify_1)(ValidationOptions, out ValidationResult) | Проверяет документ относительно этой подписи и возвращает true, если документ действителен, иначе false. |
| [Verify](../../aspose.pdf.forms/signature/verify/#verify_2)(X509Certificate2, ValidationOptions, out ValidationResult) | Проверяет документ относительно этой подписи и возвращает true, если документ действителен, иначе false. Проверка выполняется с использованием внешнего сертификата открытого ключа. |

### См. также

* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


