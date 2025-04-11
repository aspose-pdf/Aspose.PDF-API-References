---
title: Class Signature
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Forms.Signature. Абстрактный класс, представляющий объект подписи в PDF-документе. Подписи - это поля со значениями объектов подписи, последние содержат данные, которые используются для проверки действительности документа.
type: docs
weight: 5270
url: /ru/net/aspose.pdf.forms/signature/
---
## Класс подписи

Абстрактный класс, представляющий объект подписи в PDF-документе. Подписи - это поля со значениями объектов подписи, последние содержат данные, которые используются для проверки действительности документа.

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
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | Имя человека или органа, подписывающего документ. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | Получает и устанавливает опцию, означающую, следует ли избегать оценки длины подписи. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | Массив пар целых чисел (начальный байтовый смещение, длина в байтах), который описывает точный диапазон байтов для расчета дайджеста. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | Информация, предоставленная подписантом, чтобы получатель мог связаться с подписантом для проверки подписи, например, номер телефона. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Получает/устанавливает пользовательский вид. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | Делегат для пользовательской подписи хеша документа. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | Время подписания. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | Получает или устанавливает длину по умолчанию для данных подписи в байтах. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | Имя хоста ЦП или физическое местоположение подписания. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Получает/устанавливает настройки ocsp. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | Причина подписания, например (Я согласен, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | Принудительно отображает/скрывает свойства подписи. Если ShowProperties равно true, поле подписи имеет предопределенный формат отображения (строки для представления): ------------------------------------------- Цифровая подпись от {certificate subject} Дата: {signature.Date} Причина: {signature.Reason} Местоположение: {signature.Location} ------------------------------------------- где {X} является заполнителем для значения X. Также подпись может иметь изображение, в этом случае перечисленные строки располагаются поверх изображения. ShowProperties по умолчанию равно true. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | Получает/устанавливает настройки временной метки. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | Получает/устанавливает флаг проверки ltv. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | Извлекает информацию о алгоритме подписи, используемом в подписи. |
| [Verify](../../aspose.pdf.forms/signature/verify/#verify)() | Проверяет документ относительно этой подписи и возвращает true, если документ действителен, или false в противном случае. |
| [Verify](../../aspose.pdf.forms/signature/verify/#verify_1)(ValidationOptions, out ValidationResult) | Проверяет документ относительно этой подписи и возвращает true, если документ действителен, или false в противном случае. |

### См. также

* пространство имен [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* сборка [Aspose.PDF](../../)