---
title: "Aspose::Pdf::XfaConverter::XfaParserOptions-klass"
linktitle: "XfaParserOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::XfaConverter::XfaParserOptions-klass. klass för att hantera relaterad datainkapsling i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.xfaconverter/xfaparseroptions/
---
## XfaParserOptions class


klass för att hantera relaterad datainkapsling.

```cpp
class XfaParserOptions : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_BasePath](./get_basepath/)() const | Hämtar basvägen. |
| [get_EmulateRequierdGroups](./get_emulaterequierdgroups/)() const | Om den här egenskapen är sann så ritas ytterligare röda rektanglar för de obligatoriska Xfa "excluded groups". Denna egenskap introducerades eftersom avsaknaden av motsvarigheter till exkluderade grupper under konvertering av Xfa-representationen av formulär till standard. Den är falsk som standard. |
| [get_PageSize](./get_pagesize/)() const | Hämtar sidans storlek. |
| [get_Signed](./get_signed/)() const | Om den här egenskapen är sann kommer dokumentet att konverteras med användning av xfa-formulärström (om den finns). Om den är falsk kommer xfa-formulärströmmen att ignoreras. Denna egenskap introducerades eftersom det inte är tydligt hur man beräknar kontrollsumman som används för att verifiera signaturen. |
| [get_UriResolver](./get_uriresolver/)() const | Hämtar URI‑upplösaren. |
| [set_BasePath](./set_basepath/)(const System::SharedPtr\<System::Uri\>\&) | Ställer in basvägen. |
| [set_EmulateRequierdGroups](./set_emulaterequierdgroups/)(bool) | Om den här egenskapen är sann så ritas ytterligare röda rektanglar för de obligatoriska Xfa "excluded groups". Denna egenskap introducerades eftersom avsaknaden av motsvarigheter till exkluderade grupper under konvertering av Xfa-representationen av formulär till standard. Den är falsk som standard. |
| [set_PageSize](./set_pagesize/)(System::Drawing::SizeF) | Ställer in sidans storlek. |
| [set_Signed](./set_signed/)(bool) | Om den här egenskapen är sann kommer dokumentet att konverteras med användning av xfa-formulärström (om den finns). Om den är falsk kommer xfa-formulärströmmen att ignoreras. Denna egenskap introducerades eftersom det inte är tydligt hur man beräknar kontrollsumman som används för att verifiera signaturen. |
| [set_UriResolver](./set_uriresolver/)(const System::SharedPtr\<Aspose::Foundation::UriResolver::UriResolver\>\&) | Ställer in URI‑upplösaren. |
| [XfaParserOptions](./xfaparseroptions/)(System::Drawing::SizeF) | Initierar en ny instans av klassen [XfaParserOptions](./). |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::XfaConverter](../)
* Library [Aspose.PDF for C++](../../)
