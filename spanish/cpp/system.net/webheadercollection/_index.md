---
title: "System::Net::WebHeaderCollection class"
linktitle: "WebHeaderCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::WebHeaderCollection. Representa la colección de encabezados del protocolo. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 3600
url: /es/cpp/system.net/webheadercollection/
---
## WebHeaderCollection class


Representa la colección de encabezados del protocolo. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class WebHeaderCollection : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(String, String) | Agrega el par especificado del nombre del encabezado y el valor del encabezado a la colección. |
| [Add](./add/)(HttpResponseHeader, String) | Agrega el par especificado del encabezado y el valor del encabezado a la colección. |
| [Add](./add/)(HttpRequestHeader, String) | Agrega el par especificado del encabezado y el valor del encabezado a la colección. |
| [AllKeys](./allkeys/)() | Devuelve una colección de nombres de encabezados que están almacenados en la colección. |
| [get_Count](./get_count/)() const | Devuelve un número de elementos en la colección. |
| [get_Keys](./get_keys/)() | Devuelve una colección de nombres de encabezados que están almacenados en la colección. |
| [GetKey](./getkey/)(int) | Devuelve una clave en el índice especificado. |
| [GetValues](./getvalues/)(String) | Devuelve la colección de los valores de encabezado. |
| [idx_get](./idx_get/)(HttpRequestHeader) | Obtiene el valor del encabezado usando el encabezado especificado de la solicitud. |
| [idx_get](./idx_get/)(HttpResponseHeader) | Obtiene el valor del encabezado usando el encabezado especificado de la respuesta. |
| [idx_get](./idx_get/)(String) | Obtiene el valor del encabezado usando el nombre de encabezado especificado. |
| [idx_set](./idx_set/)(HttpRequestHeader, String) | Establece el valor del encabezado del encabezado especificado. |
| [idx_set](./idx_set/)(HttpResponseHeader, String) | Establece el valor del encabezado usando el encabezado especificado de la respuesta. |
| [idx_set](./idx_set/)(String, String) | Establece el valor del encabezado usando el nombre de encabezado especificado. |
| static [IsRestricted](./isrestricted/)(const String\&) | Prueba si el encabezado HTTP especificado puede establecerse para la solicitud. |
| [Remove](./remove/)(String) | Elimina el encabezado por el nombre de encabezado especificado. |
| [Remove](./remove/)(HttpResponseHeader) | Elimina el encabezado especificado de la respuesta. |
| [Remove](./remove/)(HttpRequestHeader) | Elimina el encabezado especificado de la solicitud. |
| [Set](./set/)(String, String) | Establece el valor del encabezado especificado. |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| [WebHeaderCollection](./webheadercollection/)() | Construye una nueva instancia. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
