---
title: "System::Web::Services::Protocols::SoapMessage clase"
linktitle: "SoapMessage"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Web::Services::Protocols::SoapMessage clase. Representa el mensaje SOAP. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1000
url: /es/cpp/system.web.services.protocols/soapmessage/
---
## SoapMessage class


Representa el mensaje SOAP. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class SoapMessage : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CollectHeaders](./collectheaders/)(System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, SoapHeaderDirection) | Establece la colección interna de las cabeceras SOAP. |
| [FindHeader](./findheader/)(System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, const TypeInfo\&) | Encuentra el mapeo de la cabecera por el tipo de cabecera especificado. |
| virtual [get_Action](./get_action/)() | Devuelve un valor del atributo 'SOAPAction'. |
| [get_ContentEncoding](./get_contentencoding/)() | Obtiene un valor del encabezado 'Content-Encoding'. |
| [get_ContentType](./get_contenttype/)() | Obtiene un valor del encabezado 'Content-Type'. |
| [get_Exception](./get_exception/)() | Obtiene la excepción que se lanza por el método del servicio XML [Web](../../system.web/). |
| [get_Headers](./get_headers/)() | Devuelve la colección de los encabezados SOAP. |
| [get_InParameters](./get_inparameters/)() | Obtiene los parámetros que se pasan al método del servicio XML [Web](../../system.web/). |
| [get_IsSoap12](./get_issoap12/)() | Devuelve un valor que indica si se usa la versión 1.2 de SOAP. |
| [get_OutParameters](./get_outparameters/)() | Obtiene los parámetros de salida que se pasan al método del servicio XML [Web](../../system.web/). |
| virtual [get_SoapVersion](./get_soapversion/)() | Devuelve la versión de SOAP que se utiliza. |
| [get_Stage](./get_stage/)() | Obtiene la etapa de procesamiento de un mensaje SOAP. |
| [get_Stream](./get_stream/)() | Obtiene el flujo que contiene los datos del mensaje SOAP. |
| virtual [get_Url](./get_url/)() | Devuelve la URL del servicio XML [Web](../../system.web/). |
| [GetInParameterValue](./getinparametervalue/)(int32_t) | Obtiene el valor del parámetro de entrada en el índice especificado. |
| [GetOutParameterValue](./getoutparametervalue/)(int32_t) | Obtiene el valor del parámetro de salida en el índice especificado. |
| [GetReturnValue](./getreturnvalue/)() | Obtiene el valor de retorno del método del servicio XML [Web](../../system.web/). |
| [set_ContentEncoding](./set_contentencoding/)(String) | Establece un valor del encabezado 'Content-Encoding'. |
| [set_ContentType](./set_contenttype/)(String) | Establece un valor del encabezado 'Content-Type'. |
| [set_InParameters](./set_inparameters/)(System::ArrayPtr\<System::SharedPtr\<Object\>\>) | Establece los parámetros que se pasan al método del servicio XML [Web](../../system.web/). |
| [set_InternalStream](./set_internalstream/)(System::SharedPtr\<System::IO::Stream\>) | Establece el flujo que contiene los datos del mensaje SOAP. |
| [set_OutParameters](./set_outparameters/)(System::ArrayPtr\<System::SharedPtr\<Object\>\>) | Establece los parámetros de salida que se pasan al método del servicio XML [Web](../../system.web/). |
| [SetException](./setexception/)(SoapException) | Establece la excepción que se lanza por el método del servicio XML [Web](../../system.web/). |
| [SetHeaders](./setheaders/)(System::SharedPtr\<SoapHeaderCollection\>) | Establece la colección de los encabezados SOAP. |
| [SetStage](./setstage/)(SoapMessageStage) | Establece la etapa de procesamiento del mensaje SOAP. |
| [SetStream](./setstream/)(System::SharedPtr\<System::IO::Stream\>) | Establece el flujo que contiene los datos del mensaje SOAP. |
| [SoapMessage](./soapmessage/)() | Construye una nueva instancia. |
| [UpdateHeaderValues](./updateheadervalues/)(System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>) | Actualiza la colección interna de los encabezados SOAP. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
