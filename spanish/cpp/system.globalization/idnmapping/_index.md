---
title: "System::Globalization::IdnMapping class"
linktitle: "IdnMapping"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Globalization::IdnMapping class. IdnMapping se usa para mapear nombres a Punycode. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1300
url: /es/cpp/system.globalization/idnmapping/
---
## IdnMapping class


[IdnMapping](./) used to map names to Punycode. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class IdnMapping : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Compara dos objetos [IdnMapping](./). |
| [get_AllowUnassigned](./get_allowunassigned/)() const | Obtiene la bandera que indica si se usan puntos de código no asignados en las operaciones. |
| [get_UseStd3AsciiRules](./get_usestd3asciirules/)() const | Obtiene la bandera que indica si se usan convenciones de nomenclatura estándar en las operaciones. |
| [GetAscii](./getascii/)(const String\&) const | [Convert](../../system/convert/) nombre de dominio unicode a equivalente ascii. |
| [GetAscii](./getascii/)(const String\&, int) const | [Convert](../../system/convert/) nombre de dominio unicode a equivalente ascii. |
| [GetAscii](./getascii/)(const String\&, int, int) const | [Convert](../../system/convert/) nombre de dominio unicode a equivalente ascii. |
| [GetHashCode](./gethashcode/)() const override | Obtiene el código hash para el objeto [IdnMapping](./) actual. |
| [GetUnicode](./getunicode/)(const String\&) const | [Convert](../../system/convert/) nombre de dominio ascii a equivalente unicode. |
| [GetUnicode](./getunicode/)(const String\&, int) const | [Convert](../../system/convert/) nombre de dominio ascii a equivalente unicode. |
| [GetUnicode](./getunicode/)(const String\&, int, int) const | [Convert](../../system/convert/) nombre de dominio ascii a equivalente unicode. |
| [IdnMapping](./idnmapping/)() | Información RTTI. |
| [IdnMapping](./idnmapping/)(const IdnMapping\&) |  |
| [operator=](./operator=/)(const IdnMapping\&) |  |
| [set_AllowUnassigned](./set_allowunassigned/)(bool) | Establece la bandera que indica si se usan puntos de código no asignados en las operaciones. |
| [set_UseStd3AsciiRules](./set_usestd3asciirules/)(bool) | Establece la bandera que indica si se usan convenciones de nomenclatura estándar en las operaciones. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
