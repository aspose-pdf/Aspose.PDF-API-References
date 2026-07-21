---
title: "System::Globalization::StringInfo class"
linktitle: "StringInfo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Globalization::StringInfo class. Divisor para iterar a través de las partes de la cadena. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 2400
url: /es/cpp/system.globalization/stringinfo/
---
## StringInfo class


Divisor para iterar a través de las partes de la cadena. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class StringInfo : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Equals](./equals/)(SharedPtr\<Object\>) override |  |
| [get_LengthInTextElements](./get_lengthintextelements/)() const | Obtiene el número de elementos de texto en el objeto [StringInfo](./). |
| [get_String](./get_string/)() const | Obtiene el valor del objeto [StringInfo](./). |
| [GetHashCode](./gethashcode/)() const override | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| static [GetNextTextElement](./getnexttextelement/)(const String\&) | Obtiene el primer elemento en la cadena especificada. |
| static [GetNextTextElement](./getnexttextelement/)(const String\&, int) | Obtiene el elemento en el índice especificado de la cadena especificada. |
| static [GetTextElementEnumerator](./gettextelementenumerator/)(const String\&) | Crea un enumerador para iterar a través de los caracteres de la cadena. |
| static [GetTextElementEnumerator](./gettextelementenumerator/)(const String\&, int) | Crea un enumerador para iterar a través de los caracteres de la cadena comenzando en el índice especificado. |
| [operator=](./operator=/)(const StringInfo\&) |  |
| static [ParseCombiningCharacters](./parsecombiningcharacters/)(const String\&) | Obtiene los índices de los caracteres base, los sustitutos altos y los caracteres de control. |
| [set_String](./set_string/)(const String\&) | Establece el valor del objeto [StringInfo](./). |
| [StringInfo](./stringinfo/)() | Información RTTI. |
| [StringInfo](./stringinfo/)(const String\&) | Constructor. |
| [StringInfo](./stringinfo/)(const StringInfo\&) |  |
| [SubstringByTextElements](./substringbytextelements/)(int) const | Obtiene una subcadena de elementos de texto desde el elemento de texto especificado hasta el último elemento de texto. |
| [SubstringByTextElements](./substringbytextelements/)(int, int) const | Obtiene una subcadena de elementos de texto desde el elemento de texto especificado hasta el número especificado de elementos de texto. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
