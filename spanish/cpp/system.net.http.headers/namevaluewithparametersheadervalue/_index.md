---
title: "System::Net::Http::Headers::NameValueWithParametersHeaderValue clase"
linktitle: "NameValueWithParametersHeaderValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Http::Headers::NameValueWithParametersHeaderValue clase. Representa un par clave/valor con parámetros para usar en encabezados. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1500
url: /es/cpp/system.net.http.headers/namevaluewithparametersheadervalue/
---
## NameValueWithParametersHeaderValue class


Representa un par clave/valor con parámetros para usar en encabezados. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class NameValueWithParametersHeaderValue : public System::Net::Http::Headers::NameValueHeaderValue
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| [get_Parameters](./get_parameters/)() | Información RTTI. |
| [GetHashCode](./gethashcode/)() const override | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| static [GetNameValueWithParametersLength](./getnamevaluewithparameterslength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Convierte una cadena pasada desde el índice especificado a una instancia de la clase [NameValueWithParametersHeaderValue](./). |
| [NameValueWithParametersHeaderValue](./namevaluewithparametersheadervalue/)(String) | Construye una nueva instancia. |
| [NameValueWithParametersHeaderValue](./namevaluewithparametersheadervalue/)(String, String) | Construye una nueva instancia. |
| [NameValueWithParametersHeaderValue](./namevaluewithparametersheadervalue/)() | Construye una nueva instancia. |
| static [Parse](./parse/)(String) | Convierte una cadena pasada a una instancia de la clase [NameValueWithParametersHeaderValue](./). |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<NameValueWithParametersHeaderValue\>\&) | Intenta convertir una cadena pasada a una instancia de la clase [NameValueWithParametersHeaderValue](./). |
## Ver también

* Class [NameValueHeaderValue](../namevalueheadervalue/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
