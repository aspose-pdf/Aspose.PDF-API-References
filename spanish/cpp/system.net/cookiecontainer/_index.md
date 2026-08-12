---
title: "Clase System::Net::CookieContainer"
linktitle: "CookieContainer"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::CookieContainer. Proporciona un contenedor para las instancias de la clase CookieCollection. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 400
url: /es/cpp/system.net/cookiecontainer/
---
## CookieContainer class


Proporciona un contenedor para las instancias de la clase CookieCollection. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class CookieContainer : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<Cookie\>) | Agrega una cookie a la colección. |
| [Add](./add/)(System::SharedPtr\<Cookie\>, bool) | Agrega una cookie a la colección. |
| [Add](./add/)(System::SharedPtr\<CookieCollection\>) | Copia cookies de la colección especificada a la actual. |
| [Add](./add/)(System::SharedPtr\<Uri\>, System::SharedPtr\<Cookie\>) | Agrega una cookie para la URI especificada. |
| [Add](./add/)(System::SharedPtr\<Uri\>, System::SharedPtr\<CookieCollection\>) | Copia cookies de la colección especificada para la URI especificada a la colección actual. |
| [CookieContainer](./cookiecontainer/)() | Construye una nueva instancia. |
| [CookieContainer](./cookiecontainer/)(int32_t) | Construye una nueva instancia. |
| [CookieContainer](./cookiecontainer/)(int32_t, int32_t, int32_t) | Construye una nueva instancia. |
| [CookieCutter](./cookiecutter/)(System::SharedPtr\<Uri\>, String, String, bool) | Copia cookies del encabezado HTTP especificado para la URI especificada. |
| [get_Capacity](./get_capacity/)() | Obtiene la capacidad de la colección. |
| [get_Count](./get_count/)() | Devuelve el número de elementos de la colección. |
| [get_MaxCookieSize](./get_maxcookiesize/)() | Obtiene el tamaño máximo de la cookie. |
| [get_PerDomainCapacity](./get_perdomaincapacity/)() | Obtiene la capacidad de la colección por dominio. |
| [GetCookieHeader](./getcookieheader/)(System::SharedPtr\<Uri\>) | Devuelve un encabezado HTTP que contiene cookies asociadas con la URI especificada. |
| [GetCookieHeader](./getcookieheader/)(System::SharedPtr\<Uri\>, String\&) | Devuelve un encabezado HTTP que contiene cookies asociadas con la URI especificada. |
| [GetCookies](./getcookies/)(System::SharedPtr\<Uri\>) | Devuelve una colección de cookies que están asociadas con la URI especificada. |
| [InternalGetCookies](./internalgetcookies/)(System::SharedPtr\<Uri\>) | Devuelve una colección de cookies que están asociadas con la URI especificada. |
| [IsLocalDomain](./islocaldomain/)(String) | Comprueba si el dominio especificado es localhost. |
| [set_Capacity](./set_capacity/)(int32_t) | Establece la capacidad de la colección. |
| [set_MaxCookieSize](./set_maxcookiesize/)(int32_t) | Establece el tamaño máximo de la cookie. |
| [set_PerDomainCapacity](./set_perdomaincapacity/)(int32_t) | Establece la capacidad de la colección por dominio. |
| [SetCookies](./setcookies/)(System::SharedPtr\<Uri\>, String) | Copia las cookies del encabezado especificado a la colección y las asocia con el URI especificado. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [DefaultCookieLengthLimit](./defaultcookielengthlimit/) | El tamaño máximo de la cookie. |
| static [DefaultCookieLimit](./defaultcookielimit/) | Información RTTI. |
| static [DefaultPerDomainCookieLimit](./defaultperdomaincookielimit/) | El número máximo de elementos de la colección por dominio. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
