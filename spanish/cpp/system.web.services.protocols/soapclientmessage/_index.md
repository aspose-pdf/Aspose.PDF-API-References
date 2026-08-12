---
title: "Clase System::Web::Services::Protocols::SoapClientMessage"
linktitle: "SoapClientMessage"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Web::Services::Protocols::SoapClientMessage. Representa los datos en una solicitud SOAP enviada o una respuesta SOAP recibida. Los objetos de esta clase solo deben ser asignados usando la función System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++."
type: docs
weight: 300
url: /es/cpp/system.web.services.protocols/soapclientmessage/
---
## SoapClientMessage class


Representa los datos en una solicitud SOAP enviada o una respuesta SOAP recibida. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SoapClientMessage : public System::Web::Services::Protocols::SoapMessage
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Action](./get_action/)() override | Devuelve un valor del atributo 'SOAPAction'. |
| [get_Client](./get_client/)() | Devuelve una instancia de la clase proxy del cliente. |
| virtual [get_OneWay](./get_oneway/)() | Devuelve un valor que indica si un cliente no espera a que el servidor termine de procesar un método. |
| [get_SoapVersion](./get_soapversion/)() override | Devuelve la versión de SOAP que se utiliza. |
| [get_Url](./get_url/)() override | Devuelve la URL del servicio XML [Web](../../system.web/). |
| [SoapClientMessage](./soapclientmessage/)(System::SharedPtr\<SoapHttpClientProtocol\>, System::SharedPtr\<SoapMethodStubInfo\>, String, System::ArrayPtr\<System::SharedPtr\<Object\>\>) | Construye una nueva instancia. |
## Ver también

* Class [SoapMessage](../soapmessage/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
