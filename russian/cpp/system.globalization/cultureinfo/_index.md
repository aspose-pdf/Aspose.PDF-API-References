---
title: "System::Globalization::CultureInfo class"
linktitle: "CultureInfo"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Globalization::CultureInfo class. Коллекция значений и алгоритмов, специфичных для культуры. Операции установки доступны только для объектов, не являющихся только для чтения. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 500
url: /ru/cpp/system.globalization/cultureinfo/
---
## CultureInfo class


Коллекция значений и алгоритмов, специфичных для культуры. Операции установки доступны только для объектов, не являющихся только для чтения. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class CultureInfo : public virtual System::Object,
                    public System::IFormatProvider,
                    public System::ICloneable
```

## Методы

| Метод | Описание |
| --- | --- |
| [ClearCachedData](./clearcacheddata/)() | Обновляет кэшированную информацию о культуре. |
| [Clone](./clone/)() override | Клонирует информацию о культуре. |
| static [CreateSpecificCulture](./createspecificculture/)(const String\&) | Создаёт культуру по имени. |
| explicit [CultureInfo](./cultureinfo/)(int) | Информация RTTI. |
| [CultureInfo](./cultureinfo/)(int, bool) | Конструктор. |
| explicit [CultureInfo](./cultureinfo/)(const String\&) | Конструктор. |
| [CultureInfo](./cultureinfo/)(const String\&, bool) | Конструктор. |
| [CultureInfo](./cultureinfo/)(std::nullptr_t) | Всегда генерирует ArgumentNullException. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Сравнивает объекты. |
| virtual [get_Calendar](./get_calendar/)() const | Получает календарь, используемый культурой. |
| virtual [get_CompareInfo](./get_compareinfo/)() const | Получает сравниватель строк, соответствующий правилам культуры. |
| [get_CultureTypes](./get_culturetypes/)() const | Получает побитовое объединение типов культур, описывающих текущую культуру. |
| static [get_CurrentCulture](./get_currentculture/)() | Получает культуру, установленную для текущего потока. |
| static [get_CurrentUICulture](./get_currentuiculture/)() | Получает UI‑культуру текущего потока. |
| virtual [get_DateTimeFormat](./get_datetimeformat/)() const | Получает информацию о формате даты. |
| static [get_DefaultThreadCurrentCulture](./get_defaultthreadcurrentculture/)() | Получает культуру по умолчанию в текущем домене приложения. |
| static [get_DefaultThreadCurrentUICulture](./get_defaultthreadcurrentuiculture/)() | Получает UI‑культуру по умолчанию в текущем домене приложения. |
| virtual [get_DisplayName](./get_displayname/)() const | Получает отображаемое название культуры. |
| virtual [get_EnglishName](./get_englishname/)() const | Получает английское название культуры. |
| [get_IetfLanguageTag](./get_ietflanguagetag/)() const | Получает имя по RFC 4646 для языка. |
| static [get_InstalledUICulture](./get_installeduiculture/)() | Получает культуру, установленную в операционной системе. |
| static [get_InvariantCulture](./get_invariantculture/)() | Получает инвариантную культуру. |
| virtual [get_IsNeutralCulture](./get_isneutralculture/)() const | Проверяет, является ли культура нейтральной. |
| [get_IsReadOnly](./get_isreadonly/)() const | Проверяет, является ли объект культуры только для чтения. |
| virtual [get_KeyboardLayoutId](./get_keyboardlayoutid/)() const | Получает идентификатор активной локали ввода. |
| virtual [get_LCID](./get_lcid/)() const | Получает идентификатор культуры. |
| virtual [get_Name](./get_name/)() const | Получает имя культуры. |
| virtual [get_NativeName](./get_nativename/)() const | Получает родное название культуры. |
| virtual [get_NumberFormat](./get_numberformat/)() const | Получает информацию о формате чисел. |
| virtual [get_OptionalCalendars](./get_optionalcalendars/)() const | Список календарей, которые можно использовать с культурой. |
| virtual [get_Parent](./get_parent/)() const | Получает родительскую культуру. |
| virtual [get_TextInfo](./get_textinfo/)() const | Получает текстовые параметры, используемые культурой. |
| virtual [get_ThreeLetterISOLanguageName](./get_threeletterisolanguagename/)() const | Получает трёхбуквенный код языка ISO 639-2. |
| virtual [get_ThreeLetterWindowsLanguageName](./get_threeletterwindowslanguagename/)() const | Получает трёхбуквенный код языка, определённый в API [Windows](../../system.windows/). |
| virtual [get_TwoLetterISOLanguageName](./get_twoletterisolanguagename/)() const | Получает двухбуквенное название языка ISO, связанное с культурой. |
| [get_UseUserOverride](./get_useuseroverride/)() const | Получает флаг, указывающий, использует ли [CultureInfo](./) пользовательские настройки культуры. |
| [GetConsoleFallbackUICulture](./getconsolefallbackuiculture/)() const | Получает альтернативную культуру, подходящую для консольных приложений. |
| static [GetCultureInfo](./getcultureinfo/)(const String\&) | Получает культуру по её имени. То же, что CreateSpecificCulture. |
| static [GetCultureInfo](./getcultureinfo/)(const String\&, const String\&) | Получает культуру по её имени. |
| static [GetCultureInfo](./getcultureinfo/)(int32_t) | Получает культуру по идентификатору. |
| static [GetCultureInfoByIetfLanguageTag](./getcultureinfobyietflanguagetag/)(const String\&) | Устарело. Получает только для чтения объект [CultureInfo](./) по указанному языковому тегу RFC 4646. |
| static [GetCultures](./getcultures/)(CultureTypes) | Получает культуры, относящиеся к указанным типам. |
| [GetFormat](./getformat/)(const TypeInfo\&) override | Получает объект формата для конкретного типа. |
| [GetHashCode](./gethashcode/)() const override | Возвращает хеш‑код объекта. |
| [IsInherited](./isinherited/)() const | Получает флаг наследования. ДЛЯ ВНУТРЕННЕГО ИСПОЛЬЗОВАНИЯ. |
| [operator=](./operator=/)(const CultureInfo\&) |  |
| [operator==](./operator==/)(const CultureInfo\&) const | Сравнивает параметры культуры. |
| static [ReadOnly](./readonly/)(const CultureInfoPtr\&) | Получает только читаемую версию культуры. |
| static [set_CurrentCulture](./set_currentculture/)(const CultureInfoPtr\&) | Устанавливает культуру для текущего потока. |
| static [set_CurrentUICulture](./set_currentuiculture/)(const CultureInfoPtr\&) | Устанавливает UI‑культуру текущего потока. |
| virtual [set_DateTimeFormat](./set_datetimeformat/)(DateTimeFormatInfoPtr) | Устанавливает информацию о формате даты. |
| static [set_DefaultThreadCurrentCulture](./set_defaultthreadcurrentculture/)(const CultureInfoPtr\&) | Устанавливает культуру по умолчанию в текущем домене приложения. |
| static [set_DefaultThreadCurrentUICulture](./set_defaultthreadcurrentuiculture/)(const CultureInfoPtr\&) | Устанавливает UI‑культуру по умолчанию в текущем домене приложения. |
| virtual [set_NumberFormat](./set_numberformat/)(NumberFormatInfoPtr) | Получает информацию о формате чисел. |
| [ToString](./tostring/)() const override | Преобразует культуру в строку. |
## См. также

* Class [Object](../../system/object/)
* Class [IFormatProvider](../../system/iformatprovider/)
* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
