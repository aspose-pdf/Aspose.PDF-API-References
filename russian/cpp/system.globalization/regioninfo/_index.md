---
title: "System::Globalization::RegionInfo класс"
linktitle: "RegionInfo"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Globalization::RegionInfo class. Предоставляет информацию о регионе. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2100
url: /ru/cpp/system.globalization/regioninfo/
---
## RegionInfo class


Предоставляет информацию о регионе. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class RegionInfo : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Equals](./equals/)(SharedPtr\<Object\>) override |  |
| virtual [get_CurrencyEnglishName](./get_currencyenglishname/)() const | Получает английское название валюты. |
| virtual [get_CurrencyNativeName](./get_currencynativename/)() const | Получает родное название валюты. |
| virtual [get_CurrencySymbol](./get_currencysymbol/)() const | Возвращает символ валюты. |
| static [get_CurrentRegion](./get_currentregion/)() | Получает регион, установленный в системе. |
| virtual [get_DisplayName](./get_displayname/)() const | Получает полное название региона. |
| virtual [get_EnglishName](./get_englishname/)() const | Получает английское название региона. |
| virtual [get_GeoId](./get_geoid/)() const | Получает уникальный идентификатор региона. |
| virtual [get_IsMetric](./get_ismetric/)() const | Проверяет, использует ли регион метрическую систему. |
| virtual [get_ISOCurrencySymbol](./get_isocurrencysymbol/)() const | Получает ISO-символ валюты. |
| virtual [get_Name](./get_name/)() const | Получает название региона. |
| virtual [get_NativeName](./get_nativename/)() const | Получает родное название региона. |
| virtual [get_ThreeLetterISORegionName](./get_threeletterisoregionname/)() const | Получает трехбуквенный ISO‑код региона. |
| virtual [get_ThreeLetterWindowsRegionName](./get_threeletterwindowsregionname/)() const | Получает трехбуквенный [Windows](../../system.windows/) код региона. |
| virtual [get_TwoLetterISORegionName](./get_twoletterisoregionname/)() const | Получает двухбуквенный ISO‑код региона. |
| [GetHashCode](./gethashcode/)() const override | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| [operator=](./operator=/)(const RegionInfo\&) |  |
| [RegionInfo](./regioninfo/)(const String\&) | Информация RTTI. |
| [RegionInfo](./regioninfo/)(int) | Конструктор. |
| [RegionInfo](./regioninfo/)(const RegionInfo\&) |  |
| [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
