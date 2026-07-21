---
title: "System::Globalization::RegionInfo clase"
linktitle: "RegionInfo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Globalization::RegionInfo. Proporciona información sobre la región. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2100
url: /es/cpp/system.globalization/regioninfo/
---
## RegionInfo class


Proporciona información sobre la región. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class RegionInfo : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Equals](./equals/)(SharedPtr\<Object\>) override |  |
| virtual [get_CurrencyEnglishName](./get_currencyenglishname/)() const | Obtiene el nombre en inglés de la moneda. |
| virtual [get_CurrencyNativeName](./get_currencynativename/)() const | Obtiene el nombre nativo de la moneda. |
| virtual [get_CurrencySymbol](./get_currencysymbol/)() const | Obtiene el símbolo de la moneda. |
| static [get_CurrentRegion](./get_currentregion/)() | Obtiene la región establecida en el sistema. |
| virtual [get_DisplayName](./get_displayname/)() const | Obtiene el nombre completo de la región. |
| virtual [get_EnglishName](./get_englishname/)() const | Obtiene el nombre de la región en inglés. |
| virtual [get_GeoId](./get_geoid/)() const | Obtiene el identificador único de una región. |
| virtual [get_IsMetric](./get_ismetric/)() const | Comprueba si la región utiliza el sistema métrico. |
| virtual [get_ISOCurrencySymbol](./get_isocurrencysymbol/)() const | Obtiene el símbolo ISO de la moneda. |
| virtual [get_Name](./get_name/)() const | Obtiene el nombre de la región. |
| virtual [get_NativeName](./get_nativename/)() const | Obtiene el nombre nativo de la región. |
| virtual [get_ThreeLetterISORegionName](./get_threeletterisoregionname/)() const | Obtiene el código ISO de la región de 3 letras. |
| virtual [get_ThreeLetterWindowsRegionName](./get_threeletterwindowsregionname/)() const | Obtiene el código de región de 3 letras de [Windows](../../system.windows/). |
| virtual [get_TwoLetterISORegionName](./get_twoletterisoregionname/)() const | Obtiene el código ISO de la región de 2 letras. |
| [GetHashCode](./gethashcode/)() const override | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| [operator=](./operator=/)(const RegionInfo\&) |  |
| [RegionInfo](./regioninfo/)(const String\&) | Información RTTI. |
| [RegionInfo](./regioninfo/)(int) | Constructor. |
| [RegionInfo](./regioninfo/)(const RegionInfo\&) |  |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
