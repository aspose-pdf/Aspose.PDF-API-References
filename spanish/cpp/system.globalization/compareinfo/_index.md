---
title: "Clase System::Globalization::CompareInfo"
linktitle: "CompareInfo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Globalization::CompareInfo. Realiza comparaciones de cadenas sensibles a la cultura. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 400
url: /es/cpp/system.globalization/compareinfo/
---
## CompareInfo class


Realiza comparaciones de cadenas sensibles a la cultura. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class CompareInfo : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Compare](./compare/)(const String\&, const String\&) const | Compara cadenas. No implementado. |
| virtual [Compare](./compare/)(const String\&, const String\&, CompareOptions) const | Compara cadenas. Solo se admiten los modos Ordinal y OrdinalIgnoreCase. |
| virtual [Compare](./compare/)(const String\&, int, int, const String\&, int, int) const | Compara una sección de una cadena con una sección de otra cadena. No implementado. |
| virtual [Compare](./compare/)(const String\&, int, const String\&, int, CompareOptions) const | Compara la sección final de una cadena con la sección final de otra cadena usando métodos de comparación de cadenas. No implementado. |
| virtual [Compare](./compare/)(const String\&, int, const String\&, int) const | Compara la sección final de una cadena con la sección final de otra cadena. No implementado. |
| virtual [Compare](./compare/)(const String\&, int, int, const String\&, int, int, CompareOptions) const | Compara una sección de una cadena con una sección de otra cadena usando métodos de comparación de cadenas. No implementado. |
| [CompareInfo](./compareinfo/)(const CompareInfo\&) | Información RTTI. |
| [Equals](./equals/)(SharedPtr\<Object\>) override |  |
| [get_LCID](./get_lcid/)() const | Obtiene el LCID de la cultura asociada con el comparador. |
| virtual [get_Name](./get_name/)() const | Obtiene el nombre de la cultura asociada con el comparador. |
| [get_Version](./get_version/)() const | Obtiene información sobre la versión de ordenación. |
| static [GetCompareInfo](./getcompareinfo/)(int, const SharedPtr\<Reflection::Assembly\>\&) | Obtiene [CompareInfo](./) asociado con la cultura especificada y usando métodos de comparación de cadenas en el ensamblado especificado. |
| static [GetCompareInfo](./getcompareinfo/)(const String\&, const SharedPtr\<Reflection::Assembly\>\&) | Obtiene [CompareInfo](./) asociado con la cultura especificada y usando métodos de comparación de cadenas en el ensamblado especificado. |
| static [GetCompareInfo](./getcompareinfo/)(int) | Obtiene [CompareInfo](./) asociado con la cultura especificada. |
| static [GetCompareInfo](./getcompareinfo/)(const String\&) | Obtiene [CompareInfo](./) asociado con la cultura especificada. |
| virtual [GetHashCode](./gethashcode/)(const String\&, CompareOptions) const | Obtiene el código hash de la cadena basado en las opciones de comparación especificadas. |
| [GetHashCode](./gethashcode/)() const override | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual [GetSortKey](./getsortkey/)(const String\&, CompareOptions) const | Obtiene el objeto [SortKey](../sortkey/) para la cadena especificada usando las opciones de comparación especificadas. |
| virtual [GetSortKey](./getsortkey/)(const String\&) const | Obtiene el objeto [SortKey](../sortkey/) para la cadena especificada. |
| virtual [IndexOf](./indexof/)(const String\&, const String\&, int, int) const | Busca una subcadena. |
| virtual [IndexOf](./indexof/)(const String\&, const String\&, int, CompareOptions) const | Busca una subcadena. Solo se admite el modo ordinal. |
| virtual [IndexOf](./indexof/)(const String\&, const String\&, int, int, CompareOptions) const | Busca una subcadena. Solo se admite el modo ordinal. |
| virtual [IndexOf](./indexof/)(const String\&, char16_t, int, int, CompareOptions) const | Busca el carácter especificado. Solo se admite el modo ordinal. |
| virtual [IndexOf](./indexof/)(const String\&, const String\&, int) const | Busca una subcadena. |
| virtual [IndexOf](./indexof/)(const String\&, char16_t) const | Busca el carácter especificado. |
| virtual [IndexOf](./indexof/)(const String\&, const String\&) const | Busca una subcadena. |
| virtual [IndexOf](./indexof/)(const String\&, char16_t, int, CompareOptions) const | Busca el carácter especificado. Solo se admite el modo ordinal. |
| virtual [IndexOf](./indexof/)(const String\&, char16_t, int, int) const | Busca el carácter especificado. |
| virtual [IndexOf](./indexof/)(const String\&, char16_t, int) const | Busca el carácter especificado. |
| virtual [IndexOf](./indexof/)(const String\&, const String\&, CompareOptions) const | Busca una subcadena. Solo se admite el modo ordinal. |
| virtual [IndexOf](./indexof/)(const String\&, char16_t, CompareOptions) const | Busca el carácter especificado. Solo se admite el modo ordinal. |
| virtual [IsPrefix](./isprefix/)(const String\&, const String\&, CompareOptions) const | Comprueba si la cadena especificada comienza con el prefijo especificado usando las opciones de comparación especificadas. |
| virtual [IsPrefix](./isprefix/)(const String\&, const String\&) const | Comprueba si la cadena especificada comienza con el prefijo especificado. |
| static [IsSortable](./issortable/)(char16_t) | Comprueba si un carácter especificado es ordenable. |
| static [IsSortable](./issortable/)(const String\&) | Comprueba si una cadena especificada es ordenable. |
| virtual [IsSuffix](./issuffix/)(const String\&, const String\&, CompareOptions) const | Comprueba si la cadena especificada termina con el sufijo especificado usando las opciones de comparación especificadas. |
| virtual [IsSuffix](./issuffix/)(const String\&, const String\&) const | Comprueba si la cadena especificada termina con el sufijo especificado. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, const String\&) const | Busca la última aparición de la subcadena especificada. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, const String\&, int, int, CompareOptions) const | Busca la última aparición de la subcadena especificada usando las opciones de comparación especificadas. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, char16_t, int, int, CompareOptions) const | Busca la última aparición del carácter especificado usando las opciones de comparación especificadas. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, const String\&, int, int) const | Busca la última aparición de la cadena especificada. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, const String\&, int, CompareOptions) const | Busca la última aparición de la cadena especificada usando las opciones de comparación especificadas. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, char16_t, int, CompareOptions) const | Busca la última aparición del carácter especificado usando las opciones de comparación especificadas. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, const String\&, int) const | Busca la última aparición de la cadena especificada. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, char16_t, int) const | Busca la última aparición del carácter especificado. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, const String\&, CompareOptions) const | Busca la última aparición de la cadena especificada usando las opciones de comparación especificadas. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, char16_t, CompareOptions) const | Busca la última aparición del carácter especificado usando las opciones de comparación especificadas. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, char16_t) const | Busca la última aparición del carácter especificado. |
| virtual [LastIndexOf](./lastindexof/)(const String\&, char16_t, int, int) const | Busca la última aparición del carácter especificado. |
| [operator=](./operator=/)(const CompareInfo\&) |  |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
