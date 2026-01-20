---
title: Aspose::Pdf::Forms::SignatureCustomAppearance class
linktitle: SignatureCustomAppearance
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::SignatureCustomAppearance class. An abstract class which represents signature custon appearance object in C++.'
type: docs
weight: 2500
url: /cpp/aspose.pdf.forms/signaturecustomappearance/
---
## SignatureCustomAppearance class


An abstract class which represents signature custon appearance object.

```cpp
class SignatureCustomAppearance : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Gets/sets background color. Default value: Transparent. |
| [get_ContactInfoLabel](./get_contactinfolabel/)() const | Gets/sets contact info label. Default value: "Contact". |
| [get_Culture](./get_culture/)() const | Gets/sets culture info value. Default value: InvariantCulture. |
| [get_DateSignedAtLabel](./get_datesignedatlabel/)() const | Gets/sets date signed label. Default value: "Date". |
| [get_DateTimeFormat](./get_datetimeformat/)() const | Gets/sets datetime format. Default value: "yyyy.MM.dd HH:mm:ss". |
| [get_DateTimeLocalFormat](./get_datetimelocalformat/)() const | Gets/sets datetime local format. Default value: "yyyy.MM.dd HH:mm:ss zzz". |
| [get_DigitalSignedLabel](./get_digitalsignedlabel/)() const | Gets/sets digital signed label. Default value: "Digitally signed by". |
| [get_DigitalSubjectFormat](./get_digitalsubjectformat/)() const | Gets/sets format for order of elements in Subject string. Result examples: C=UK, CN=Org, O=Organization or CN=Org, C=UK, O=Organization or O=Organization. |
| [get_FontFamilyName](./get_fontfamilyname/)() const | Gets/sets font family name. It should be existed in the document. Default value: Arial. |
| [get_FontSize](./get_fontsize/)() const | Gets/sets font size. Default value: 10. |
| [get_ForegroundColor](./get_foregroundcolor/)() const | Gets/sets foreground color (color of text). Default value: Blue. |
| [get_IsForegroundImage](./get_isforegroundimage/)() const | Gets a value indicating whether the image in the signature appearance is drawn as a foreground image. Default value: false. |
| [get_LocationLabel](./get_locationlabel/)() const | Gets/sets location label. Default value: "Location". |
| [get_ReasonLabel](./get_reasonlabel/)() const | Gets/sets reason label. Default value: "Reason". |
| [get_Rotation](./get_rotation/)() const | Gets signature rotation. |
| [get_ShowContactInfo](./get_showcontactinfo/)() const | Gets/sets contact info visibility. Default value: true. |
| [get_ShowLocation](./get_showlocation/)() const | Gets/sets location visibility. Default value: true. |
| [get_ShowReason](./get_showreason/)() const | Gets/sets reason visibility. Default value: true. |
| [get_UseDigitalSubjectFormat](./get_usedigitalsubjectformat/)() const | Gets/sets the usage state of the [DigitalSubjectFormat](../). |
| [set_BackgroundColor](./set_backgroundcolor/)(System::SharedPtr\<Color\>) | Gets/sets background color. Default value: Transparent. |
| [set_ContactInfoLabel](./set_contactinfolabel/)(System::String) | Gets/sets contact info label. Default value: "Contact". |
| [set_Culture](./set_culture/)(System::SharedPtr\<System::Globalization::CultureInfo\>) | Gets/sets culture info value. Default value: InvariantCulture. |
| [set_DateSignedAtLabel](./set_datesignedatlabel/)(System::String) | Gets/sets date signed label. Default value: "Date". |
| [set_DateTimeFormat](./set_datetimeformat/)(System::String) | Gets/sets datetime format. Default value: "yyyy.MM.dd HH:mm:ss". |
| [set_DateTimeLocalFormat](./set_datetimelocalformat/)(System::String) | Gets/sets datetime local format. Default value: "yyyy.MM.dd HH:mm:ss zzz". |
| [set_DigitalSignedLabel](./set_digitalsignedlabel/)(System::String) | Gets/sets digital signed label. Default value: "Digitally signed by". |
| [set_DigitalSubjectFormat](./set_digitalsubjectformat/)(System::ArrayPtr\<SubjectNameElements\>) | Gets/sets format for order of elements in Subject string. Result examples: C=UK, CN=Org, O=Organization or CN=Org, C=UK, O=Organization or O=Organization. |
| [set_FontFamilyName](./set_fontfamilyname/)(System::String) | Gets/sets font family name. It should be existed in the document. Default value: Arial. |
| [set_FontSize](./set_fontsize/)(double) | Gets/sets font size. Default value: 10. |
| [set_ForegroundColor](./set_foregroundcolor/)(System::SharedPtr\<Color\>) | Gets/sets foreground color (color of text). Default value: Blue. |
| [set_IsForegroundImage](./set_isforegroundimage/)(bool) | Sets a value indicating whether the image in the signature appearance is drawn as a foreground image. Default value: false. |
| [set_LocationLabel](./set_locationlabel/)(System::String) | Gets/sets location label. Default value: "Location". |
| [set_ReasonLabel](./set_reasonlabel/)(System::String) | Gets/sets reason label. Default value: "Reason". |
| [set_Rotation](./set_rotation/)(Aspose::Pdf::Rotation) | Sets signature rotation. |
| [set_ShowContactInfo](./set_showcontactinfo/)(bool) | Gets/sets contact info visibility. Default value: true. |
| [set_ShowLocation](./set_showlocation/)(bool) | Gets/sets location visibility. Default value: true. |
| [set_ShowReason](./set_showreason/)(bool) | Gets/sets reason visibility. Default value: true. |
| [set_UseDigitalSubjectFormat](./set_usedigitalsubjectformat/)(bool) | Gets/sets the usage state of the [DigitalSubjectFormat](../). |
| [SignatureCustomAppearance](./signaturecustomappearance/)() | Inititalizes new instance of the [SignatureCustomAppearance](./) class. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
