---
title: "System::Net::Http::Headers::NameValueHeaderValue clase"
linktitle: "NameValueHeaderValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Http::Headers::NameValueHeaderValue clase. Representa un par clave/valor para usar en encabezados. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1400
url: /es/cpp/system.net.http.headers/namevalueheadervalue/
---
## NameValueHeaderValue class


Representa un par clave/valor para usar en encabezados. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class NameValueHeaderValue : public virtual System::ICloneable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static [Find](./find/)(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, String) | Busca la instancia de la clase NameValueHeaderValue en una colección por el nombre especificado. |
| [get_Name](./get_name/)() | Devuelve un nombre de la instancia actual. |
| [get_Value](./get_value/)() | Obtiene un valor de la instancia actual. |
| [GetHashCode](./gethashcode/)() const override | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| static [GetHashCode](./gethashcode/)(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) | Devuelve un código hash de todos los elementos de la colección. |
| static [GetNameValueLength](./getnamevaluelength/)(String, int32_t, System::SharedPtr\<NameValueHeaderValue\>\&) | Convierte una cadena pasada desde el índice especificado a una instancia de la clase [NameValueHeaderValue](./). |
| static [GetNameValueLength](./getnamevaluelength/)(String, int32_t, HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\>, System::SharedPtr\<NameValueHeaderValue\>\&) | Convierte una cadena pasada desde el índice especificado a una instancia de la clase [NameValueHeaderValue](./). |
| static [GetNameValueListLength](./getnamevaluelistlength/)(String, int32_t, char16_t, System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) | Convierte una cadena pasada desde el índice especificado a la colección de instancias de la clase NameValueHeaderValue y devuelve la longitud de la subcadena analizada. |
| static [GetValueLength](./getvaluelength/)(String, int32_t) | Devuelve la longitud de un valor desde el índice especificado. |
| [NameValueHeaderValue](./namevalueheadervalue/)() | Construye una nueva instancia. |
| [NameValueHeaderValue](./namevalueheadervalue/)(String) | Construye una nueva instancia. |
| [NameValueHeaderValue](./namevalueheadervalue/)(String, String) | Construye una nueva instancia. |
| static [Parse](./parse/)(String) | Convierte una cadena pasada a una instancia de la clase [NameValueHeaderValue](./). |
| [set_Value](./set_value/)(String) | Establece un valor de la instancia actual. |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static [ToString](./tostring/)(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool, System::SharedPtr\<Text::StringBuilder\>) | Devuelve una representación en cadena de la colección de instancias de la clase NameValueHeaderValue. |
| static [ToString](./tostring/)(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool) | Devuelve una representación en cadena de la colección de instancias de la clase NameValueHeaderValue. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<NameValueHeaderValue\>\&) | Intenta convertir una cadena pasada a una instancia de la clase [NameValueHeaderValue](./). |
## Ver también

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
