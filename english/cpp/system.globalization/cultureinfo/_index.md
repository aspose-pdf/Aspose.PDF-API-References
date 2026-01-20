---
title: System::Globalization::CultureInfo class
linktitle: CultureInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Globalization::CultureInfo class. Collection of culture-specific values and algorithms. Setter operations are only enabled on non-read-only objects. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 500
url: /cpp/system.globalization/cultureinfo/
---
## CultureInfo class


Collection of culture-specific values and algorithms. Setter operations are only enabled on non-read-only objects. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class CultureInfo : public virtual System::Object,
                    public System::IFormatProvider,
                    public System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| [ClearCachedData](./clearcacheddata/)() | Refreshes cached culture information. |
| [Clone](./clone/)() override | Clones culture info. |
| static [CreateSpecificCulture](./createspecificculture/)(const String\&) | Creates culture by name. |
| explicit [CultureInfo](./cultureinfo/)(int) | RTTI information. |
| [CultureInfo](./cultureinfo/)(int, bool) | Constructor. |
| explicit [CultureInfo](./cultureinfo/)(const String\&) | Constructor. |
| [CultureInfo](./cultureinfo/)(const String\&, bool) | Constructor. |
| [CultureInfo](./cultureinfo/)(std::nullptr_t) | Always throws ArgumentNullException. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Compares objects. |
| virtual [get_Calendar](./get_calendar/)() const | Gets calendar used by the culture. |
| virtual [get_CompareInfo](./get_compareinfo/)() const | Gets string comparer that adheres to culture rules. |
| [get_CultureTypes](./get_culturetypes/)() const | Gets bitwise joint of culture types that describe the current culture. |
| static [get_CurrentCulture](./get_currentculture/)() | Gets culture set for current thread. |
| static [get_CurrentUICulture](./get_currentuiculture/)() | Gets current thread's UI culture. |
| virtual [get_DateTimeFormat](./get_datetimeformat/)() const | Gets date format information. |
| static [get_DefaultThreadCurrentCulture](./get_defaultthreadcurrentculture/)() | Gets default culture in the current application domain. |
| static [get_DefaultThreadCurrentUICulture](./get_defaultthreadcurrentuiculture/)() | Gets default UI culture in the current application domain. |
| virtual [get_DisplayName](./get_displayname/)() const | Gets culture display name. |
| virtual [get_EnglishName](./get_englishname/)() const | Gets culture English name. |
| [get_IetfLanguageTag](./get_ietflanguagetag/)() const | Gets the RFC 4646 name for a language. |
| static [get_InstalledUICulture](./get_installeduiculture/)() | Gets culture installed with the operating system. |
| static [get_InvariantCulture](./get_invariantculture/)() | Gets invariant culture. |
| virtual [get_IsNeutralCulture](./get_isneutralculture/)() const | Checks whether the culture is neutral. |
| [get_IsReadOnly](./get_isreadonly/)() const | Checks if culture object is read-only. |
| virtual [get_KeyboardLayoutId](./get_keyboardlayoutid/)() const | Gets active input locale identifier. |
| virtual [get_LCID](./get_lcid/)() const | Gets culture identifier. |
| virtual [get_Name](./get_name/)() const | Gets culture name. |
| virtual [get_NativeName](./get_nativename/)() const | Gets culture native name. |
| virtual [get_NumberFormat](./get_numberformat/)() const | Gets number format information. |
| virtual [get_OptionalCalendars](./get_optionalcalendars/)() const | List of calendars that can be used with the culture. |
| virtual [get_Parent](./get_parent/)() const | Gets parent culture. |
| virtual [get_TextInfo](./get_textinfo/)() const | Gets text parameters used by the culture. |
| virtual [get_ThreeLetterISOLanguageName](./get_threeletterisolanguagename/)() const | Gets three-letter ISO 639-2 language code. |
| virtual [get_ThreeLetterWindowsLanguageName](./get_threeletterwindowslanguagename/)() const | Gets three-letter code for language as defined in [Windows](../../system.windows/) API. |
| virtual [get_TwoLetterISOLanguageName](./get_twoletterisolanguagename/)() const | Gets two letters ISO language name associated with culture. |
| [get_UseUserOverride](./get_useuseroverride/)() const | Gets a flag indicating whether the [CultureInfo](./) uses user-selected culture settings. |
| [GetConsoleFallbackUICulture](./getconsolefallbackuiculture/)() const | Gets alternate culture suitable for console applications. |
| static [GetCultureInfo](./getcultureinfo/)(const String\&) | Gets culture by its name. Same as CreateSpecificCulture. |
| static [GetCultureInfo](./getcultureinfo/)(const String\&, const String\&) | Gets culture by its name. |
| static [GetCultureInfo](./getcultureinfo/)(int32_t) | Gets culture by id. |
| static [GetCultureInfoByIetfLanguageTag](./getcultureinfobyietflanguagetag/)(const String\&) | Deprecated. Gets a read-only [CultureInfo](./) object by the specified RFC 4646 language tag. |
| static [GetCultures](./getcultures/)(CultureTypes) | Gets cultures that fall into specified types. |
| [GetFormat](./getformat/)(const TypeInfo\&) override | Gets format object for specific type. |
| [GetHashCode](./gethashcode/)() const override | Returns object hash code. |
| [IsInherited](./isinherited/)() const | Gets is-inherited flag. FOR INTERNAL USE. |
| [operator=](./operator=/)(const CultureInfo\&) |  |
| [operator==](./operator==/)(const CultureInfo\&) const | Compares culture parameters. |
| static [ReadOnly](./readonly/)(const CultureInfoPtr\&) | Gets a read only version of culture. |
| static [set_CurrentCulture](./set_currentculture/)(const CultureInfoPtr\&) | Sets culture for current thread. |
| static [set_CurrentUICulture](./set_currentuiculture/)(const CultureInfoPtr\&) | Sets current thread's UI culture. |
| virtual [set_DateTimeFormat](./set_datetimeformat/)(DateTimeFormatInfoPtr) | Sets date format information. |
| static [set_DefaultThreadCurrentCulture](./set_defaultthreadcurrentculture/)(const CultureInfoPtr\&) | Sets default culture in the current application domain. |
| static [set_DefaultThreadCurrentUICulture](./set_defaultthreadcurrentuiculture/)(const CultureInfoPtr\&) | Sets default UI culture in the current application domain. |
| virtual [set_NumberFormat](./set_numberformat/)(NumberFormatInfoPtr) | Gets number format information. |
| [ToString](./tostring/)() const override | Converts culture to string. |
## See Also

* Class [Object](../../system/object/)
* Class [IFormatProvider](../../system/iformatprovider/)
* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
