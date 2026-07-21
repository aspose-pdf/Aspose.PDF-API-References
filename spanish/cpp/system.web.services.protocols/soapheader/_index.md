---
title: "System::Web::Services::Protocols::SoapHeader class"
linktitle: "SoapHeader"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Web::Services::Protocols::SoapHeader class. Representa el contenido del encabezado SOAP. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 600
url: /es/cpp/system.web.services.protocols/soapheader/
---
## SoapHeader class


Representa el contenido del encabezado SOAP. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class SoapHeader : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Actor](./get_actor/)() | Obtiene el URI del destinatario del encabezado SOAP cuando se usa la versión 1.1 de SOAP. |
| [get_DidUnderstand](./get_didunderstand/)() | Obtiene un valor que indica si el encabezado SOAP se procesa correctamente. |
| [get_EncodedMustUnderstand](./get_encodedmustunderstand/)() | Obtiene el valor del atributo 'mustUnderstand' cuando se usa la versión 1.1 de SOAP. |
| [get_EncodedMustUnderstand12](./get_encodedmustunderstand12/)() | Obtiene el valor del atributo 'mustUnderstand' cuando se usa la versión 1.2 de SOAP. |
| [get_EncodedRelay](./get_encodedrelay/)() | Obtiene una representación en cadena del valor del atributo 'relay'. |
| [get_MustUnderstand](./get_mustunderstand/)() | Obtiene un valor que indica si el encabezado SOAP debe ser comprendido. |
| [get_Relay](./get_relay/)() | Obtiene el valor del atributo 'relay'. |
| [get_Role](./get_role/)() | Obtiene el URI del destinatario del encabezado SOAP cuando se usa la versión 1.2 de SOAP. |
| [set_Actor](./set_actor/)(String) | Establece el URI del destinatario del encabezado SOAP cuando se usa la versión 1.1 de SOAP. |
| [set_DidUnderstand](./set_didunderstand/)(bool) | Establece un valor que indica si el encabezado SOAP se procesa correctamente. |
| [set_EncodedMustUnderstand](./set_encodedmustunderstand/)(String) | Establece el valor del atributo 'mustUnderstand' cuando se usa la versión 1.1 de SOAP. |
| [set_EncodedMustUnderstand12](./set_encodedmustunderstand12/)(String) | Establece el valor del atributo 'mustUnderstand' cuando se usa la versión 1.2 de SOAP. |
| [set_EncodedRelay](./set_encodedrelay/)(String) | Establece una representación en cadena del valor del atributo 'relay'. |
| [set_MustUnderstand](./set_mustunderstand/)(bool) | Establece un valor que indica si el encabezado SOAP debe ser comprendido. |
| [set_Relay](./set_relay/)(bool) | Establece el valor del atributo 'relay'. |
| [set_Role](./set_role/)(String) | Establece el URI del destinatario del encabezado SOAP cuando se usa la versión 1.2 de SOAP. |
| [SoapHeader](./soapheader/)(System::SharedPtr\<Xml::XmlElement\>) | Construye una nueva instancia. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
