---
title: "System::Web::Services::Protocols::SoapHeaderAttribute clase"
linktitle: "SoapHeaderAttribute"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Web::Services::Protocols::SoapHeaderAttribute clase. Especifica la cabecera SOAP que el método del servicio Web XML o el cliente del servicio Web XML pueden procesar. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 700
url: /es/cpp/system.web.services.protocols/soapheaderattribute/
---
## SoapHeaderAttribute class


Especifica la cabecera SOAP que el método del servicio [Web](../../system.web/) XML o el cliente del servicio [Web](../../system.web/) XML pueden procesar. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class SoapHeaderAttribute : public System::Attribute
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Direction](./get_direction/)() | Información RTTI. |
| [get_MemberName](./get_membername/)() | Obtiene el nombre de una variable miembro del servicio SOAP XML que se usa para recibir el contenido de la cabecera SOAP. |
| [get_Required](./get_required/)() | Obtiene un valor que indica si la cabecera SOAP debe ser comprendida y procesada por el servicio XML [Web](../../system.web/) receptor o el cliente del servicio XML [Web](../../system.web/). |
| [set_Direction](./set_direction/)(SoapHeaderDirection) | Establece la dirección de la cabecera SOAP. |
| [set_MemberName](./set_membername/)(String) | Establece el nombre de una variable miembro del servicio SOAP XML que se usa para recibir el contenido de la cabecera SOAP. |
| [set_Required](./set_required/)(bool) | Establece un valor que indica si la cabecera SOAP debe ser comprendida y procesada por el servicio XML [Web](../../system.web/) receptor o el cliente del servicio XML [Web](../../system.web/). |
| [SoapHeaderAttribute](./soapheaderattribute/)(String) | Construye una nueva instancia. |
## Ver también

* Class [Attribute](../../system/attribute/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
