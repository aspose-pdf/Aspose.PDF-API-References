---
title: "Aspose::Pdf::Forms::SignatureCustomAppearance-klass"
linktitle: "SignatureCustomAppearance"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms::SignatureCustomAppearance-klass. En abstrakt klass som representerar signaturens anpassade utseendeobjekt i C++."
type: docs
weight: 2500
url: /sv/cpp/aspose.pdf.forms/signaturecustomappearance/
---
## SignatureCustomAppearance class


En abstrakt klass som representerar signaturens anpassade utseendeobjekt.

```cpp
class SignatureCustomAppearance : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Hämtar/sätter bakgrundsfärg. Standardvärde: Transparent. |
| [get_ContactInfoLabel](./get_contactinfolabel/)() const | Hämtar/sätter etikett för kontaktinformation. Standardvärde: "Contact". |
| [get_Culture](./get_culture/)() const | Hämtar/sätter kulturinfo-värde. Standardvärde: InvariantCulture. |
| [get_DateSignedAtLabel](./get_datesignedatlabel/)() const | Hämtar/sätter etikett för signeringsdatum. Standardvärde: "Date". |
| [get_DateTimeFormat](./get_datetimeformat/)() const | Hämtar/sätter datum/tid-format. Standardvärde: "yyyy.MM.dd HH:mm:ss". |
| [get_DateTimeLocalFormat](./get_datetimelocalformat/)() const | Hämtar/sätter lokalt datum/tid-format. Standardvärde: "yyyy.MM.dd HH:mm:ss zzz". |
| [get_DigitalSignedLabel](./get_digitalsignedlabel/)() const | Hämtar/sätter etikett för digital signatur. Standardvärde: "Digitally signed by". |
| [get_DigitalSubjectFormat](./get_digitalsubjectformat/)() const | Hämtar/sätter format för ordning av element i Subject-strängen. Resultatexempel: C=UK, CN=Org, O=Organization eller CN=Org, C=UK, O=Organization eller O=Organization. |
| [get_FontFamilyName](./get_fontfamilyname/)() const | Hämtar/sätter teckensnittsfamiljens namn. Det bör finnas i dokumentet. Standardvärde: Arial. |
| [get_FontSize](./get_fontsize/)() const | Hämtar/sätter teckenstorlek. Standardvärde: 10. |
| [get_ForegroundColor](./get_foregroundcolor/)() const | Hämtar/sätter förgrundsfärg (textens färg). Standardvärde: Blue. |
| [get_IsForegroundImage](./get_isforegroundimage/)() const | Hämtar ett värde som indikerar om bilden i signaturens utseende ritas som en förgrundsbild. Standardvärde: false. |
| [get_LocationLabel](./get_locationlabel/)() const | Hämtar/sätter etikett för plats. Standardvärde: "Location". |
| [get_ReasonLabel](./get_reasonlabel/)() const | Hämtar/sätter etikett för anledning. Standardvärde: "Reason". |
| [get_Rotation](./get_rotation/)() const | Hämtar signaturrotation. |
| [get_ShowContactInfo](./get_showcontactinfo/)() const | Hämtar/sätter synlighet för kontaktinformation. Standardvärde: true. |
| [get_ShowLocation](./get_showlocation/)() const | Hämtar/sätter synlighet för plats. Standardvärde: true. |
| [get_ShowReason](./get_showreason/)() const | Hämtar/sätter synlighet för anledning. Standardvärde: true. |
| [get_UseDigitalSubjectFormat](./get_usedigitalsubjectformat/)() const | Hämtar/sätter användningstillståndet för [DigitalSubjectFormat](../). |
| [set_BackgroundColor](./set_backgroundcolor/)(const System::SharedPtr\<Color\>\&) | Hämtar/sätter bakgrundsfärg. Standardvärde: Transparent. |
| [set_ContactInfoLabel](./set_contactinfolabel/)(const System::String\&) | Hämtar/sätter etikett för kontaktinformation. Standardvärde: "Contact". |
| [set_Culture](./set_culture/)(const System::SharedPtr\<System::Globalization::CultureInfo\>\&) | Hämtar/sätter kulturinfo-värde. Standardvärde: InvariantCulture. |
| [set_DateSignedAtLabel](./set_datesignedatlabel/)(const System::String\&) | Hämtar/sätter etikett för signeringsdatum. Standardvärde: "Date". |
| [set_DateTimeFormat](./set_datetimeformat/)(const System::String\&) | Hämtar/sätter datum/tid-format. Standardvärde: "yyyy.MM.dd HH:mm:ss". |
| [set_DateTimeLocalFormat](./set_datetimelocalformat/)(const System::String\&) | Hämtar/sätter lokalt datum/tid-format. Standardvärde: "yyyy.MM.dd HH:mm:ss zzz". |
| [set_DigitalSignedLabel](./set_digitalsignedlabel/)(const System::String\&) | Hämtar/sätter etikett för digital signatur. Standardvärde: "Digitally signed by". |
| [set_DigitalSubjectFormat](./set_digitalsubjectformat/)(const System::ArrayPtr\<SubjectNameElements\>\&) | Hämtar/sätter format för ordning av element i Subject-strängen. Resultatexempel: C=UK, CN=Org, O=Organization eller CN=Org, C=UK, O=Organization eller O=Organization. |
| [set_FontFamilyName](./set_fontfamilyname/)(const System::String\&) | Hämtar/sätter teckensnittsfamiljens namn. Det bör finnas i dokumentet. Standardvärde: Arial. |
| [set_FontSize](./set_fontsize/)(double) | Hämtar/sätter teckenstorlek. Standardvärde: 10. |
| [set_ForegroundColor](./set_foregroundcolor/)(const System::SharedPtr\<Color\>\&) | Hämtar/sätter förgrundsfärg (textens färg). Standardvärde: Blue. |
| [set_IsForegroundImage](./set_isforegroundimage/)(bool) | Sätter ett värde som indikerar om bilden i signaturens utseende ritas som en förgrundsbild. Standardvärde: false. |
| [set_LocationLabel](./set_locationlabel/)(const System::String\&) | Hämtar/sätter etikett för plats. Standardvärde: "Location". |
| [set_ReasonLabel](./set_reasonlabel/)(const System::String\&) | Hämtar/sätter etikett för anledning. Standardvärde: "Reason". |
| [set_Rotation](./set_rotation/)(Aspose::Pdf::Rotation) | Sätter signaturrotation. |
| [set_ShowContactInfo](./set_showcontactinfo/)(bool) | Hämtar/sätter synlighet för kontaktinformation. Standardvärde: true. |
| [set_ShowLocation](./set_showlocation/)(bool) | Hämtar/sätter synlighet för plats. Standardvärde: true. |
| [set_ShowReason](./set_showreason/)(bool) | Hämtar/sätter synlighet för anledning. Standardvärde: true. |
| [set_UseDigitalSubjectFormat](./set_usedigitalsubjectformat/)(bool) | Hämtar/sätter användningstillståndet för [DigitalSubjectFormat](../). |
| [SignatureCustomAppearance](./signaturecustomappearance/)() | Initierar en ny instans av klassen [SignatureCustomAppearance](./). |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
