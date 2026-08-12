---
title: "System::Net::NetworkInformation::IPGlobalProperties class"
linktitle: "IPGlobalProperties"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::NetworkInformation::IPGlobalProperties class. Representa información sobre la conexión de red del equipo local. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() function. Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr pointer y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 200
url: /es/cpp/system.net.networkinformation/ipglobalproperties/
---
## IPGlobalProperties class


Representa información sobre la conexión de red del equipo local. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) function. Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) pointer y use este puntero para pasarlo a funciones como argumento.

```cpp
class IPGlobalProperties : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [get_DomainName](./get_domainname/)() | Devuelve el dominio en el que el equipo local está registrado. |
| virtual [get_HostName](./get_hostname/)() | Devuelve el nombre de host del equipo local. |
| static [GetIPGlobalProperties](./getipglobalproperties/)() | Información RTTI. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Net::NetworkInformation](../)
* Library [Aspose.PDF for C++](../../)
