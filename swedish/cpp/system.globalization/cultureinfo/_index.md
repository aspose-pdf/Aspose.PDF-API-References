---
title: "System::Globalization::CultureInfo class"
linktitle: "CultureInfo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Globalization::CultureInfo-klass. Samling av kulturspecifika värden och algoritmer. Sättaroperationer är endast aktiverade på objekt som inte är skrivskyddade. Objekt av denna klass bör endast allokeras med System::MakeObject() funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 500
url: /sv/cpp/system.globalization/cultureinfo/
---
## CultureInfo class


Samling av kulturspecifika värden och algoritmer. Sättaroperationer är endast aktiverade på objekt som inte är skrivskyddade. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class CultureInfo : public virtual System::Object,
                    public System::IFormatProvider,
                    public System::ICloneable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ClearCachedData](./clearcacheddata/)() | Uppdaterar cachad kulturinformation. |
| [Clone](./clone/)() override | Klonar kulturinformation. |
| static [CreateSpecificCulture](./createspecificculture/)(const String\&) | Skapar kultur efter namn. |
| explicit [CultureInfo](./cultureinfo/)(int) | RTTI-information. |
| [CultureInfo](./cultureinfo/)(int, bool) | Konstruktor. |
| explicit [CultureInfo](./cultureinfo/)(const String\&) | Konstruktor. |
| [CultureInfo](./cultureinfo/)(const String\&, bool) | Konstruktor. |
| [CultureInfo](./cultureinfo/)(std::nullptr_t) | Kastar alltid ArgumentNullException. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Jämför objekt. |
| virtual [get_Calendar](./get_calendar/)() const | Hämtar kalender som används av kulturen. |
| virtual [get_CompareInfo](./get_compareinfo/)() const | Hämtar strängjämförare som följer kulturregler. |
| [get_CultureTypes](./get_culturetypes/)() const | Hämtar bitvis sammanslagning av kulturyper som beskriver den aktuella kulturen. |
| static [get_CurrentCulture](./get_currentculture/)() | Hämtar kultur som är inställd för den aktuella tråden. |
| static [get_CurrentUICulture](./get_currentuiculture/)() | Hämtar den aktuella trådens UI-kultur. |
| virtual [get_DateTimeFormat](./get_datetimeformat/)() const | Hämtar datumformatinformation. |
| static [get_DefaultThreadCurrentCulture](./get_defaultthreadcurrentculture/)() | Hämtar standardkultur i den aktuella applikationsdomänen. |
| static [get_DefaultThreadCurrentUICulture](./get_defaultthreadcurrentuiculture/)() | Hämtar standard UI-kultur i den aktuella applikationsdomänen. |
| virtual [get_DisplayName](./get_displayname/)() const | Hämtar kulturens visningsnamn. |
| virtual [get_EnglishName](./get_englishname/)() const | Hämtar kulturens engelska namn. |
| [get_IetfLanguageTag](./get_ietflanguagetag/)() const | Hämtar RFC 4646-namnet för ett språk. |
| static [get_InstalledUICulture](./get_installeduiculture/)() | Hämtar kultur som är installerad med operativsystemet. |
| static [get_InvariantCulture](./get_invariantculture/)() | Hämtar invariant kultur. |
| virtual [get_IsNeutralCulture](./get_isneutralculture/)() const | Kontrollerar om kulturen är neutral. |
| [get_IsReadOnly](./get_isreadonly/)() const | Kontrollerar om kulturobjektet är skrivskyddat. |
| virtual [get_KeyboardLayoutId](./get_keyboardlayoutid/)() const | Hämtar aktivt inmatningslokalidentifierare. |
| virtual [get_LCID](./get_lcid/)() const | Hämtar kulturidentifierare. |
| virtual [get_Name](./get_name/)() const | Hämtar kulturnamn. |
| virtual [get_NativeName](./get_nativename/)() const | Hämtar kulturens inhemska namn. |
| virtual [get_NumberFormat](./get_numberformat/)() const | Hämtar information om talformat. |
| virtual [get_OptionalCalendars](./get_optionalcalendars/)() const | Lista över kalendrar som kan användas med kulturen. |
| virtual [get_Parent](./get_parent/)() const | Hämtar föräldrakultur. |
| virtual [get_TextInfo](./get_textinfo/)() const | Hämtar textparametrar som används av kulturen. |
| virtual [get_ThreeLetterISOLanguageName](./get_threeletterisolanguagename/)() const | Hämtar tresiffrig ISO 639-2 språkkod. |
| virtual [get_ThreeLetterWindowsLanguageName](./get_threeletterwindowslanguagename/)() const | Hämtar tresiffrig kod för språk enligt [Windows](../../system.windows/) API. |
| virtual [get_TwoLetterISOLanguageName](./get_twoletterisolanguagename/)() const | Hämtar tvåbokstavig ISO-språknamn som är associerat med kulturen. |
| [get_UseUserOverride](./get_useuseroverride/)() const | Hämtar en flagga som indikerar om [CultureInfo](./) använder användarvalda kulturinställningar. |
| [GetConsoleFallbackUICulture](./getconsolefallbackuiculture/)() const | Hämtar alternativ kultur som är lämplig för konsolapplikationer. |
| static [GetCultureInfo](./getcultureinfo/)(const String\&) | Hämtar kultur efter dess namn. Samma som CreateSpecificCulture. |
| static [GetCultureInfo](./getcultureinfo/)(const String\&, const String\&) | Hämtar kultur efter dess namn. |
| static [GetCultureInfo](./getcultureinfo/)(int32_t) | Hämtar kultur efter ID. |
| static [GetCultureInfoByIetfLanguageTag](./getcultureinfobyietflanguagetag/)(const String\&) | Föråldrad. Hämtar ett skrivskyddat [CultureInfo](./)-objekt enligt den angivna RFC 4646-språktaggen. |
| static [GetCultures](./getcultures/)(CultureTypes) | Hämtar kulturer som faller inom angivna typer. |
| [GetFormat](./getformat/)(const TypeInfo\&) override | Hämtar formatobjekt för specifik typ. |
| [GetHashCode](./gethashcode/)() const override | Returnerar objektets hashkod. |
| [IsInherited](./isinherited/)() const | Hämtar ärärvd-flagga. FÖR INTERNT ANVÄNDNING. |
| [operator=](./operator=/)(const CultureInfo\&) |  |
| [operator==](./operator==/)(const CultureInfo\&) const | Jämför kulturparametrar. |
| static [ReadOnly](./readonly/)(const CultureInfoPtr\&) | Hämtar en skrivskyddad version av kultur. |
| static [set_CurrentCulture](./set_currentculture/)(const CultureInfoPtr\&) | Ställer in kultur för aktuell tråd. |
| static [set_CurrentUICulture](./set_currentuiculture/)(const CultureInfoPtr\&) | Ställer in aktuell tråds UI-kultur. |
| virtual [set_DateTimeFormat](./set_datetimeformat/)(DateTimeFormatInfoPtr) | Ställer in datumformatinformation. |
| static [set_DefaultThreadCurrentCulture](./set_defaultthreadcurrentculture/)(const CultureInfoPtr\&) | Ställer in standardkultur i den aktuella applikationsdomänen. |
| static [set_DefaultThreadCurrentUICulture](./set_defaultthreadcurrentuiculture/)(const CultureInfoPtr\&) | Ställer in standard UI-kultur i den aktuella applikationsdomänen. |
| virtual [set_NumberFormat](./set_numberformat/)(NumberFormatInfoPtr) | Hämtar information om talformat. |
| [ToString](./tostring/)() const override | Konverterar kultur till sträng. |
## Se även

* Class [Object](../../system/object/)
* Class [IFormatProvider](../../system/iformatprovider/)
* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
