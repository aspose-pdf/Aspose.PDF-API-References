---
title: "Clase System::Net::Http::Headers::WarningHeaderValue"
linktitle: "WarningHeaderValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::Http::Headers::WarningHeaderValue. Representa un valor del encabezado ''Warning''. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2700
url: /es/cpp/system.net.http.headers/warningheadervalue/
---
## WarningHeaderValue class


Representa un valor del encabezado 'Warning'. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class WarningHeaderValue : public System::ICloneable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| [get_Agent](./get_agent/)() | Devuelve el host adjunto a la advertencia. |
| [get_Code](./get_code/)() | Información RTTI. |
| [get_Date](./get_date/)() | Devuelve la fecha y hora de la advertencia. |
| [get_Text](./get_text/)() | Devuelve el texto de la advertencia. |
| [GetHashCode](./gethashcode/)() const override | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| static [GetWarningLength](./getwarninglength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Convierte una cadena pasada desde el índice especificado a una instancia de la clase [WarningHeaderValue](./). |
| static [Parse](./parse/)(String) | Convierte una cadena pasada a una instancia de la clase [WarningHeaderValue](./). |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<WarningHeaderValue\>\&) | Intenta convertir una cadena pasada a una instancia de la clase [WarningHeaderValue](./). |
| [WarningHeaderValue](./warningheadervalue/)(int32_t, String, String) | Construye una nueva instancia. |
| [WarningHeaderValue](./warningheadervalue/)(int32_t, String, String, DateTimeOffset) | Construye una nueva instancia. |
## Ver también

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
