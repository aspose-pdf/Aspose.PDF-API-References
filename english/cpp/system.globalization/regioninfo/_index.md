---
title: System::Globalization::RegionInfo class
linktitle: RegionInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Globalization::RegionInfo class. Provides information on region. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2100
url: /cpp/system.globalization/regioninfo/
---
## RegionInfo class


Provides information on region. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class RegionInfo : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(SharedPtr\<Object\>) override |  |
| virtual [get_CurrencyEnglishName](./get_currencyenglishname/)() const | Gets currency English name. |
| virtual [get_CurrencyNativeName](./get_currencynativename/)() const | Gets currency native name. |
| virtual [get_CurrencySymbol](./get_currencysymbol/)() const | Gets currency symbol. |
| static [get_CurrentRegion](./get_currentregion/)() | Gets region set in system. |
| virtual [get_DisplayName](./get_displayname/)() const | Gets full region name. |
| virtual [get_EnglishName](./get_englishname/)() const | Gets English region name. |
| virtual [get_GeoId](./get_geoid/)() const | Gets unique identificator for a region. |
| virtual [get_IsMetric](./get_ismetric/)() const | Checks whether region uses metric system. |
| virtual [get_ISOCurrencySymbol](./get_isocurrencysymbol/)() const | Gets ISO currency symbol. |
| virtual [get_Name](./get_name/)() const | Gets region name. |
| virtual [get_NativeName](./get_nativename/)() const | Gets native region name. |
| virtual [get_ThreeLetterISORegionName](./get_threeletterisoregionname/)() const | Gets 3 letter ISO region code. |
| virtual [get_ThreeLetterWindowsRegionName](./get_threeletterwindowsregionname/)() const | Gets 3 letter [Windows](../../system.windows/) region code. |
| virtual [get_TwoLetterISORegionName](./get_twoletterisoregionname/)() const | Gets 2 letter ISO region code. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| [operator=](./operator=/)(const RegionInfo\&) |  |
| [RegionInfo](./regioninfo/)(const String\&) | RTTI information. |
| [RegionInfo](./regioninfo/)(int) | Constructor. |
| [RegionInfo](./regioninfo/)(const RegionInfo\&) |  |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
