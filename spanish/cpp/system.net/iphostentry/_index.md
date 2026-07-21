---
title: "Clase System::Net::IPHostEntry"
linktitle: "IPHostEntry"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::IPHostEntry. Representa información sobre una dirección de host de internet. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2600
url: /es/cpp/system.net/iphostentry/
---
## IPHostEntry class


Representa información sobre una dirección de host de internet. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class IPHostEntry : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_AddressList](./get_addresslist/)() | Obtiene la colección de direcciones IP del host. |
| [get_Aliases](./get_aliases/)() | Obtiene la colección de alias del host. |
| [get_HostName](./get_hostname/)() const | Información RTTI. |
| [IPHostEntry](./iphostentry/)() | Construye una nueva instancia. |
| [set_AddressList](./set_addresslist/)(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>) | Establece una colección de direcciones IP del host. |
| [set_Aliases](./set_aliases/)(System::ArrayPtr\<String\>) | Establece una colección de alias del host. |
| [set_HostName](./set_hostname/)(String) | Establece el nombre del host. |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
