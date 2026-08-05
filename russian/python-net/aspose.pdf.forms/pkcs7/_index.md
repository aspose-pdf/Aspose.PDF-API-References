---
title: "PKCS7"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Представляет объект PKCS#7, соответствующий спецификации PKCS#7 в Internet RFC 2315, <br/>            PKCS #7: Cryptographic Message Syntax, версия 1.5.<br/>            Хеш SHA1 диапазона байтов документа инкапсулируется в поле PKCS#7 SignedData."
type: docs
weight: 190
url: /ru/python-net/aspose.pdf.forms/pkcs7/
---

## PKCS7 class

Представляет объект PKCS#7, соответствующий спецификации PKCS#7 в Internet RFC 2315, <br/>            PKCS #7: Cryptographic Message Syntax, версия 1.5.<br/>            Хеш SHA1 диапазона байтов документа инкапсулируется в поле PKCS#7 SignedData.

Тип PKCS7 раскрывает следующие члены:
## Конструкторы
| Имя | Описание |
| :- | :- |
| PKCS7() | Инициализирует новый экземпляр класса [PKCS7](/pdf/python-net/aspose.pdf.forms/pkcs7/). |
| PKCS7(pfx, password) | Инициализирует новый экземпляр класса PKCS7 |
| PKCS7(pfx, password) | Инициализирует новый экземпляр класса PKCS7 |
## Свойства
| Имя | Описание |
| :- | :- |
| custom_appearance | Получает/устанавливает пользовательский внешний вид. |
| authority | Имя лица или организации, подписывающих документ. |
| date | Время подписи. |
| location | Имя хоста CPU или физическое местоположение подписи. |
| reason | Причина подписи, например (I agreeРІР‚В¦). |
| contact_info | Информация, предоставленная подписантом, позволяющая получателю связаться с подписантом <br/>            для проверки подписи, например номер телефона. |
| byte_range | Массив пар целых чисел (начальное смещение в байтах, длина в байтах) <br/>             который описывает точный диапазон байтов для вычисления дайджеста. |
| timestamp_settings | Получает/устанавливает настройки timestamp. |
| ocsp_settings | Получает/устанавливает настройки ocsp. |
| use_ltv | Получает/устанавливает флаг проверки ltv. |
| show_properties | Принудительно показывать/скрывать свойства подписи.<br/>            Если ShowProperties равно true, поле подписи имеет предопределённый формат отображения (строки для представления):<br/>            -------------------------------------------<br/>            Digitally signed by {certificate subject}<br/>            Date: {signature.Date}<br/>            Reason: {signature.Reason}<br/>            Location: {signature.Location}<br/>            -------------------------------------------<br/>            где {X} — заполнитель для значения X. Также подпись может содержать изображение; в этом случае перечисленные строки размещаются поверх изображения.<br/>            ShowProperties по умолчанию равно true. |
## Методы
| Имя | Описание |
| :- | :- |
| verify() | Проверяет документ относительно этой подписи и возвращает true, если документ действителен <br/>            или иначе false. |

### См. также

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

