---
title: "System::Net::Http::Headers::AuthenticationHeaderValue clase"
linktitle: "AuthenticationHeaderValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Http::Headers::AuthenticationHeaderValue clase. Representa los valores de los encabezados ''Authorization'', ''ProxyAuthorization'', ''WWW-Authenticate'' y ''Proxy-Authenticate''. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 100
url: /es/cpp/system.net.http.headers/authenticationheadervalue/
---
## AuthenticationHeaderValue class


Representa los valores de los encabezados 'Authorization', 'ProxyAuthorization', 'WWW-Authenticate' y 'Proxy-Authenticate'. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarla a funciones como argumento.

```cpp
class AuthenticationHeaderValue : public System::ICloneable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AuthenticationHeaderValue](./authenticationheadervalue/)(String) | Constructor. |
| [AuthenticationHeaderValue](./authenticationheadervalue/)(String, String) | Constructor. |
| [Clone](./clone/)() override | Información RTTI. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| [get_Parameter](./get_parameter/)() | Obtiene las credenciales que contienen la información de autenticación. |
| [get_Scheme](./get_scheme/)() | Información RTTI. |
| static [GetAuthenticationLength](./getauthenticationlength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Analiza la cadena especificada y devuelve el último índice de la representación de la cadena. |
| [GetHashCode](./gethashcode/)() const override | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| static [Parse](./parse/)(String) | Convierte una cadena proporcionada en una instancia de la clase [AuthenticationHeaderValue](./). |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<AuthenticationHeaderValue\>\&) | Intentando convertir una cadena proporcionada en una instancia de la clase [AuthenticationHeaderValue](./). |
## Ver también

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
