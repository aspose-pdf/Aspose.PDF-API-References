---
title: Class PKCS1
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Forms.PKCS1. Представляет объект подписи в соответствии со стандартом PKCS1. Для подписания используется алгоритм шифрования RSA и метод дайджеста SHA1.
type: docs
weight: 5170
url: /ru/net/aspose.pdf.forms/pkcs1/
---
## Класс PKCS1

Представляет объект подписи в соответствии со стандартом PKCS#1. Для подписания используется алгоритм шифрования RSA и метод дайджеста SHA-1.

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
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | Имя человека или органа, подписывающего документ. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | Получает и устанавливает опцию, означающую, следует ли избегать оценки длины подписи. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | Массив пар целых чисел (начальный смещение байта, длина в байтах), который должен описывать точный диапазон байтов для расчета дайджеста. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | Информация, предоставленная подписантом, чтобы получатель мог связаться с подписантом для проверки подписи, например, номер телефона. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Получает/устанавливает пользовательский вид. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | Делегат для пользовательской подписи хеша документа. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | Время подписания. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | Получает или устанавливает стандартную длину данных подписи в байтах. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | Имя хоста ЦП или физическое местоположение подписания. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Получает/устанавливает настройки ocsp. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | Причина подписания, такая как (Я согласен, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | Принудительно отображает/скрывает свойства подписи. Если ShowProperties равно true, поле подписи имеет предопределенный формат внешнего вида (строки для представления): ------------------------------------------- Цифровая подпись от {certificate subject} Дата: {signature.Date} Причина: {signature.Reason} Местоположение: {signature.Location} ------------------------------------------- где {X} является заполнителем для значения X. Также подпись может иметь изображение, в этом случае перечисленные строки размещаются поверх изображения. По умолчанию ShowProperties равно true. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | Получает/устанавливает настройки временной метки. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | Получает/устанавливает флаг проверки ltv. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | Извлекает информацию о алгоритме подписи, используемом в подписи. |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | Проверяет документ в отношении этой подписи и возвращает true, если документ действителен, или false в противном случае. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | Проверяет документ в отношении этой подписи и возвращает true, если документ действителен, или false в противном случае. |

### См. также

* класс [Signature](../signature/)
* пространство имен [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* сборка [Aspose.PDF](../../)