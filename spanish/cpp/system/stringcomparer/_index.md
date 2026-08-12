---
title: "Clase System::StringComparer"
linktitle: "StringComparer"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::StringComparer. Compara cadenas usando diferentes modos de comparación. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 6200
url: /es/cpp/system/stringcomparer/
---
## StringComparer class


Compara cadenas usando diferentes modos de comparación. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class StringComparer : public virtual System::Object,
                       public System::Collections::Generic::IComparer<String>,
                       public System::Collections::Generic::IEqualityComparer<String>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Compare](./compare/)(args_type, args_type) const override | Compara dos cadenas usando la configuración actual. |
| static [Create](./create/)(const System::SharedPtr\<System::Globalization::CultureInfo\>\&, bool) | Crea un comparador específico de cultura. |
| [Equals](./equals/)(String, String) const override | Comprueba si dos cadenas son iguales usando la configuración actual. |
| static [get_CurrentCulture](./get_currentculture/)() | Singleton del comparador de cultura actual. |
| static [get_CurrentCultureIgnoreCase](./get_currentcultureignorecase/)() | Singleton del comparador de cultura actual que ignora mayúsculas/minúsculas. |
| static [get_InvariantCulture](./get_invariantculture/)() | Singleton del comparador de cultura invariante. |
| static [get_InvariantCultureIgnoreCase](./get_invariantcultureignorecase/)() | Singleton del comparador de cultura invariante que ignora mayúsculas/minúsculas. |
| static [get_Ordinal](./get_ordinal/)() | Singleton de comparador ordinal. |
| static [get_OrdinalIgnoreCase](./get_ordinalignorecase/)() | Singleton de comparador ordinal que ignora mayúsculas. |
| [GetHashCode](./gethashcode/)(String) const override | Obtiene el código hash de la cadena. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [args_type](./args_type/) | Información RTTI. |
## Ver también

* Class [Object](../object/)
* Class [IComparer](../../system.collections.generic/icomparer/)
* Class [IEqualityComparer](../../system.collections.generic/iequalitycomparer/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
