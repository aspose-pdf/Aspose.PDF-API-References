---
title: "Clase System::Web::Services::Protocols::SoapDocumentMethodAttribute"
linktitle: "SoapDocumentMethodAttribute"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Web::Services::Protocols::SoapDocumentMethodAttribute. Especifica que todos los mensajes SOAP enviados o devueltos por el método utilizan el formato Document. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 400
url: /es/cpp/system.web.services.protocols/soapdocumentmethodattribute/
---
## SoapDocumentMethodAttribute class


Especifica que todos los mensajes SOAP enviados o devueltos por el método utilizan el formato Document. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class SoapDocumentMethodAttribute : public System::Attribute
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Action](./get_action/)() | Información RTTI. |
| [get_Binding](./get_binding/)() | Obtiene el enlace para el cual un método de servicio web XML está implementando una operación. |
| [get_OneWay](./get_oneway/)() | Obtiene un valor que indica si un cliente no espera a que el servidor termine de procesar un método. |
| [get_ParameterStyle](./get_parameterstyle/)() | Obtiene un valor que indica si los parámetros están encapsulados dentro de un único elemento XML bajo el elemento 'Body'. |
| [get_RequestElementName](./get_requestelementname/)() | Obtiene el nombre del elemento XML asociado con la solicitud SOAP, que se define en una descripción de servicio como una operación. |
| [get_RequestNamespace](./get_requestnamespace/)() | Obtiene el espacio de nombres asociado con la solicitud SOAP. |
| [get_ResponseElementName](./get_responseelementname/)() | Obtiene el nombre del elemento XML asociado con la respuesta SOAP. |
| [get_ResponseNamespace](./get_responsenamespace/)() | Obtiene el espacio de nombres asociado con la respuesta SOAP. |
| [get_Use](./get_use/)() | Obtiene un valor que determina el método de codificación del mensaje. |
| [set_Action](./set_action/)(String) | Establece un valor del atributo 'SOAPAction'. |
| [set_Binding](./set_binding/)(String) | Establece la vinculación para la cual un método de servicio web XML está implementando una operación. |
| [set_OneWay](./set_oneway/)(bool) | Establece un valor que indica si el cliente no espera a que el servidor termine de procesar un método. |
| [set_ParameterStyle](./set_parameterstyle/)(SoapParameterStyle) | Establece un valor que indica si los parámetros están encapsulados dentro de un único elemento XML bajo el elemento 'Body'. |
| [set_RequestElementName](./set_requestelementname/)(String) | Establece el nombre del elemento XML asociado con la solicitud SOAP, que se define en una descripción de servicio como una operación. |
| [set_RequestNamespace](./set_requestnamespace/)(String) | Establece el espacio de nombres asociado con la solicitud SOAP. |
| [set_ResponseElementName](./set_responseelementname/)(String) | Establece el nombre del elemento XML asociado con la respuesta SOAP. |
| [set_ResponseNamespace](./set_responsenamespace/)(String) | Establece el espacio de nombres asociado con la respuesta SOAP. |
| [set_Use](./set_use/)(Description::SoapBindingUse) | Establece un valor que determina el método de codificación del mensaje. |
| [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)() | Construye una nueva instancia. |
| [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)(String) | Construye una nueva instancia. |
## Ver también

* Class [Attribute](../../system/attribute/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
