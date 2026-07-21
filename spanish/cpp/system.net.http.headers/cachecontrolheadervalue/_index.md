---
title: "Clase System::Net::Http::Headers::CacheControlHeaderValue"
linktitle: "CacheControlHeaderValue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::Http::Headers::CacheControlHeaderValue. Representa un valor del encabezado ''Cache-Control''. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 200
url: /es/cpp/system.net.http.headers/cachecontrolheadervalue/
---
## CacheControlHeaderValue class


Representa un valor del encabezado 'Cache-Control'. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class CacheControlHeaderValue : public System::ICloneable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CacheControlHeaderValue](./cachecontrolheadervalue/)() | Construye una nueva instancia. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| [get_Extensions](./get_extensions/)() | Devuelve la colección de los tokens de extensión de caché. |
| [get_MaxAge](./get_maxage/)() | Obtiene el valor de edad máxima en segundos que determina el tiempo durante el cual el cliente aceptará una respuesta. |
| [get_MaxStale](./get_maxstale/)() | Obtiene el valor que determina si el cliente aceptará las respuestas expiradas. |
| [get_MaxStaleLimit](./get_maxstalelimit/)() | Obtiene el valor en segundos que determina el tiempo durante el cual el cliente aceptará las respuestas expiradas. |
| [get_MinFresh](./get_minfresh/)() | Obtiene el valor que determina la vida útil de frescura. |
| [get_MustRevalidate](./get_mustrevalidate/)() | Obtiene el valor que determina si el servidor requiere revalidación de una entrada de caché cuando esta se vuelve obsoleta. |
| [get_NoCache](./get_nocache/)() | Información RTTI. |
| [get_NoCacheHeaders](./get_nocacheheaders/)() | Obtiene la colección de nombres de campo en la directiva 'no-cache' del encabezado 'Cache-Control'. |
| [get_NoStore](./get_nostore/)() | Obtiene el valor que determina si una caché no debe almacenar ninguna parte de una solicitud o respuesta HTTP. |
| [get_NoTransform](./get_notransform/)() | Obtiene el valor que determina si una caché o proxy no debe modificar ninguna parte del cuerpo de la entidad. |
| [get_OnlyIfCached](./get_onlyifcached/)() | Obtiene el valor que determina si el cliente debe usar solo entradas en caché. |
| [get_Private](./get_private/)() | Obtiene el valor que determina si el mensaje de respuesta HTTP o su parte está destinado a un solo usuario y no debe ser almacenado en caché por una caché compartida. |
| [get_PrivateHeaders](./get_privateheaders/)() | Obtiene la colección de nombres de campo en la directiva 'private' del encabezado 'Cache-Control'. |
| [get_ProxyRevalidate](./get_proxyrevalidate/)() | Obtiene el valor que determina si el servidor requiere revalidación de una entrada de caché cuando esta se vuelve obsoleta para las cachés de agentes de usuario compartidas. |
| [get_Public](./get_public/)() | Obtiene el valor que determina si una respuesta HTTP puede ser almacenada en caché por cualquier caché. |
| [get_SharedMaxAge](./get_sharedmaxage/)() | Obtiene el valor de edad máxima compartida en segundos que sobrescribe la directiva 'max-age' en el encabezado 'Cache-Control' o el encabezado 'Expires' para una caché compartida. |
| static [GetCacheControlLength](./getcachecontrollength/)(String, int32_t, System::SharedPtr\<CacheControlHeaderValue\>, System::SharedPtr\<CacheControlHeaderValue\>\&) | Convierte una cadena pasada desde el índice especificado a una instancia de la clase [CacheControlHeaderValue](./). |
| [GetHashCode](./gethashcode/)() const override | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| static [Parse](./parse/)(String) | Convierte una cadena pasada a una instancia de la clase [CacheControlHeaderValue](./). |
| [set_MaxAge](./set_maxage/)(Nullable\<TimeSpan\>) | Establece el valor de edad máxima en segundos que determina el tiempo durante el cual el cliente aceptará una respuesta. |
| [set_MaxStale](./set_maxstale/)(bool) | Establece el valor que determina si el cliente aceptará las respuestas expiradas. |
| [set_MaxStaleLimit](./set_maxstalelimit/)(Nullable\<TimeSpan\>) | Establece el valor en segundos que determina el tiempo durante el cual el cliente aceptará las respuestas expiradas. |
| [set_MinFresh](./set_minfresh/)(Nullable\<TimeSpan\>) | Establece el valor que determina la vida útil de frescura. |
| [set_MustRevalidate](./set_mustrevalidate/)(bool) | Establece el valor que determina si el servidor requiere la revalidación de una entrada de caché cuando esta se vuelve obsoleta. |
| [set_NoCache](./set_nocache/)(bool) | Establece el valor que determina si el cliente aceptará una respuesta en caché. |
| [set_NoStore](./set_nostore/)(bool) | Establece el valor que determina si una caché no debe almacenar ninguna parte de una solicitud o respuesta HTTP. |
| [set_NoTransform](./set_notransform/)(bool) | Establece el valor que determina si una caché o proxy no debe modificar ninguna parte del cuerpo de la entidad. |
| [set_OnlyIfCached](./set_onlyifcached/)(bool) | Establece el valor que determina si el cliente debe usar solo entradas en caché. |
| [set_Private](./set_private/)(bool) | Establece el valor que determina si el mensaje de respuesta HTTP o su parte está destinado a un solo usuario y no debe ser almacenado en caché por una caché compartida. |
| [set_ProxyRevalidate](./set_proxyrevalidate/)(bool) | Establece el valor que determina si el servidor requiere la revalidación de una entrada de caché cuando esta se vuelve obsoleta para las cachés compartidas de agentes de usuario. |
| [set_Public](./set_public/)(bool) | Establece el valor que determina si una respuesta HTTP puede ser almacenada en caché por cualquier caché. |
| [set_SharedMaxAge](./set_sharedmaxage/)(Nullable\<TimeSpan\>) | Establece el valor compartido de edad máxima en segundos que sobrescribe la directiva 'max-age' en el encabezado 'Cache-Control' o el encabezado 'Expires' para una caché compartida. |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<CacheControlHeaderValue\>\&) | Intenta convertir una cadena pasada a una instancia de la clase [CacheControlHeaderValue](./). |
## Ver también

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
