---
title: "System::Net::Http::HttpMethod clase"
linktitle: "HttpMethod"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::Http::HttpMethod. Representa un método HTTP. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 700
url: /es/cpp/system.net.http/httpmethod/
---
## HttpMethod class


Representa un método HTTP. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class HttpMethod : public System::IEquatable<System::SharedPtr<System::Net::Http::HttpMethod>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<HttpMethod\>) override | Determina si los objetos actual y especificado son iguales. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static [get_Delete](./get_delete/)() | Devuelve el método HTTP 'DELETE'. |
| static [get_Get](./get_get/)() | Devuelve el método HTTP 'GET'. |
| static [get_Head](./get_head/)() | Devuelve el método HTTP 'HEAD'. |
| [get_Method](./get_method/)() | Devuelve una representación en cadena del método HTTP. |
| static [get_Options](./get_options/)() | Devuelve el método HTTP 'OPTIONS'. |
| static [get_Post](./get_post/)() | Devuelve el método HTTP 'POST'. |
| static [get_Put](./get_put/)() | Devuelve el método HTTP 'PUT'. |
| static [get_Trace](./get_trace/)() | Devuelve el método HTTP 'TRACE'. |
| [GetHashCode](./gethashcode/)() const override | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| [HttpMethod](./httpmethod/)(String) | Construye una nueva instancia. |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
## Ver también

* Class [IEquatable](../../system/iequatable/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
