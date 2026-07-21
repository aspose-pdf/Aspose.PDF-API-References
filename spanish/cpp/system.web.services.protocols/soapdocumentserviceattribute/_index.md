---
title: "Clase System::Web::Services::Protocols::SoapDocumentServiceAttribute"
linktitle: "SoapDocumentServiceAttribute"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Web::Services::Protocols::SoapDocumentServiceAttribute. Establece el formato predeterminado para las solicitudes y respuestas SOAP. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++."
type: docs
weight: 500
url: /es/cpp/system.web.services.protocols/soapdocumentserviceattribute/
---
## SoapDocumentServiceAttribute class


Establece el formato predeterminado para las solicitudes y respuestas SOAP. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SoapDocumentServiceAttribute : public System::Attribute
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_ParameterStyle](./get_parameterstyle/)() | Información RTTI. |
| [get_RoutingStyle](./get_routingstyle/)() | Obtiene un valor que muestra cómo se enrutan los mensajes SOAP al servicio. |
| [get_Use](./get_use/)() | Obtiene el formato de los parámetros. |
| [set_ParameterStyle](./set_parameterstyle/)(SoapParameterStyle) | Establece un valor que indica si los parámetros están encapsulados dentro de un único elemento XML bajo el elemento 'Body'. |
| [set_RoutingStyle](./set_routingstyle/)(SoapServiceRoutingStyle) | Establece un valor que muestra cómo se enrutan los mensajes SOAP al servicio. |
| [set_Use](./set_use/)(Description::SoapBindingUse) | Establece el formato de los parámetros. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/)() | Construye una nueva instancia. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/)(Description::SoapBindingUse) | Construye una nueva instancia. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/)(Description::SoapBindingUse, SoapParameterStyle) | Construye una nueva instancia. |
## Ver también

* Class [Attribute](../../system/attribute/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
