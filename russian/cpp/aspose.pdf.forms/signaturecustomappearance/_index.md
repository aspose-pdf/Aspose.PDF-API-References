---
title: "Aspose::Pdf::Forms::SignatureCustomAppearance класс"
linktitle: "SignatureCustomAppearance"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Forms::SignatureCustomAppearance класс. Абстрактный класс, представляющий объект пользовательского внешнего вида подписи в C++."
type: docs
weight: 2500
url: /ru/cpp/aspose.pdf.forms/signaturecustomappearance/
---
## SignatureCustomAppearance class


Абстрактный класс, представляющий объект пользовательского отображения подписи.

```cpp
class SignatureCustomAppearance : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Получает/устанавливает цвет фона. Значение по умолчанию: Transparent. |
| [get_ContactInfoLabel](./get_contactinfolabel/)() const | Получает/устанавливает метку контактной информации. Значение по умолчанию: "Contact". |
| [get_Culture](./get_culture/)() const | Получает/устанавливает значение информации о культуре. Значение по умолчанию: InvariantCulture. |
| [get_DateSignedAtLabel](./get_datesignedatlabel/)() const | Получает/устанавливает метку даты подписи. Значение по умолчанию: "Date". |
| [get_DateTimeFormat](./get_datetimeformat/)() const | Получает/устанавливает формат даты и времени. Значение по умолчанию: "yyyy.MM.dd HH:mm:ss". |
| [get_DateTimeLocalFormat](./get_datetimelocalformat/)() const | Получает/устанавливает локальный формат даты и времени. Значение по умолчанию: "yyyy.MM.dd HH:mm:ss zzz". |
| [get_DigitalSignedLabel](./get_digitalsignedlabel/)() const | Получает/устанавливает метку цифровой подписи. Значение по умолчанию: "Digitally signed by". |
| [get_DigitalSubjectFormat](./get_digitalsubjectformat/)() const | Получает/устанавливает формат порядка элементов в строке Subject. Примеры результатов: C=UK, CN=Org, O=Organization или CN=Org, C=UK, O=Organization или O=Organization. |
| [get_FontFamilyName](./get_fontfamilyname/)() const | Получает/устанавливает название семейства шрифтов. Оно должно присутствовать в документе. Значение по умолчанию: Arial. |
| [get_FontSize](./get_fontsize/)() const | Получает/устанавливает размер шрифта. Значение по умолчанию: 10. |
| [get_ForegroundColor](./get_foregroundcolor/)() const | Получает/устанавливает цвет переднего плана (цвет текста). Значение по умолчанию: Blue. |
| [get_IsForegroundImage](./get_isforegroundimage/)() const | Получает значение, указывающее, отображается ли изображение в подписи как изображение переднего плана. Значение по умолчанию: false. |
| [get_LocationLabel](./get_locationlabel/)() const | Получает/устанавливает метку местоположения. Значение по умолчанию: "Location". |
| [get_ReasonLabel](./get_reasonlabel/)() const | Получает/устанавливает метку причины. Значение по умолчанию: "Reason". |
| [get_Rotation](./get_rotation/)() const | Получает вращение подписи. |
| [get_ShowContactInfo](./get_showcontactinfo/)() const | Получает/устанавливает видимость контактной информации. Значение по умолчанию: true. |
| [get_ShowLocation](./get_showlocation/)() const | Получает/устанавливает видимость местоположения. Значение по умолчанию: true. |
| [get_ShowReason](./get_showreason/)() const | Получает/устанавливает видимость причины. Значение по умолчанию: true. |
| [get_UseDigitalSubjectFormat](./get_usedigitalsubjectformat/)() const | Получает/устанавливает состояние использования [DigitalSubjectFormat](../). |
| [set_BackgroundColor](./set_backgroundcolor/)(const System::SharedPtr\<Color\>\&) | Получает/устанавливает цвет фона. Значение по умолчанию: Transparent. |
| [set_ContactInfoLabel](./set_contactinfolabel/)(const System::String\&) | Получает/устанавливает метку контактной информации. Значение по умолчанию: "Contact". |
| [set_Culture](./set_culture/)(const System::SharedPtr\<System::Globalization::CultureInfo\>\&) | Получает/устанавливает значение информации о культуре. Значение по умолчанию: InvariantCulture. |
| [set_DateSignedAtLabel](./set_datesignedatlabel/)(const System::String\&) | Получает/устанавливает метку даты подписи. Значение по умолчанию: "Date". |
| [set_DateTimeFormat](./set_datetimeformat/)(const System::String\&) | Получает/устанавливает формат даты и времени. Значение по умолчанию: "yyyy.MM.dd HH:mm:ss". |
| [set_DateTimeLocalFormat](./set_datetimelocalformat/)(const System::String\&) | Получает/устанавливает локальный формат даты и времени. Значение по умолчанию: "yyyy.MM.dd HH:mm:ss zzz". |
| [set_DigitalSignedLabel](./set_digitalsignedlabel/)(const System::String\&) | Получает/устанавливает метку цифровой подписи. Значение по умолчанию: "Digitally signed by". |
| [set_DigitalSubjectFormat](./set_digitalsubjectformat/)(const System::ArrayPtr\<SubjectNameElements\>\&) | Получает/устанавливает формат порядка элементов в строке Subject. Примеры результатов: C=UK, CN=Org, O=Organization или CN=Org, C=UK, O=Organization или O=Organization. |
| [set_FontFamilyName](./set_fontfamilyname/)(const System::String\&) | Получает/устанавливает название семейства шрифтов. Оно должно присутствовать в документе. Значение по умолчанию: Arial. |
| [set_FontSize](./set_fontsize/)(double) | Получает/устанавливает размер шрифта. Значение по умолчанию: 10. |
| [set_ForegroundColor](./set_foregroundcolor/)(const System::SharedPtr\<Color\>\&) | Получает/устанавливает цвет переднего плана (цвет текста). Значение по умолчанию: Blue. |
| [set_IsForegroundImage](./set_isforegroundimage/)(bool) | Устанавливает значение, указывающее, отображается ли изображение в подписи как изображение переднего плана. Значение по умолчанию: false. |
| [set_LocationLabel](./set_locationlabel/)(const System::String\&) | Получает/устанавливает метку местоположения. Значение по умолчанию: "Location". |
| [set_ReasonLabel](./set_reasonlabel/)(const System::String\&) | Получает/устанавливает метку причины. Значение по умолчанию: "Reason". |
| [set_Rotation](./set_rotation/)(Aspose::Pdf::Rotation) | Устанавливает вращение подписи. |
| [set_ShowContactInfo](./set_showcontactinfo/)(bool) | Получает/устанавливает видимость контактной информации. Значение по умолчанию: true. |
| [set_ShowLocation](./set_showlocation/)(bool) | Получает/устанавливает видимость местоположения. Значение по умолчанию: true. |
| [set_ShowReason](./set_showreason/)(bool) | Получает/устанавливает видимость причины. Значение по умолчанию: true. |
| [set_UseDigitalSubjectFormat](./set_usedigitalsubjectformat/)(bool) | Получает/устанавливает состояние использования [DigitalSubjectFormat](../). |
| [SignatureCustomAppearance](./signaturecustomappearance/)() | Инициализирует новый экземпляр класса [SignatureCustomAppearance](./). |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
