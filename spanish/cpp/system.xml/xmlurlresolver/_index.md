---
title: "Clase System::Xml::XmlUrlResolver"
linktitle: "XmlUrlResolver"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::XmlUrlResolver. Resuelve recursos XML externos nombrados por un Identificador Uniforme de Recursos (URI) en C++."
type: docs
weight: 4100
url: /es/cpp/system.xml/xmlurlresolver/
---
## XmlUrlResolver class


Resuelve recursos XML externos nombrados mediante un Identificador Uniforme de Recursos (URI).

```cpp
class XmlUrlResolver : public System::Xml::XmlResolver
```

## Métodos

| Método | Descripción |
| --- | --- |
| [GetEntity](./getentity/)(SharedPtr\<Uri\>, String, const TypeInfo\&) override | Asocia un URI a un objeto que contiene el recurso real. |
| [ResolveUri](./resolveuri/)(SharedPtr\<Uri\>, String) override | Resuelve el URI absoluto a partir del URI base y relativo. |
| [set_CachePolicy](./set_cachepolicy/)(const SharedPtr\<Net::Cache::RequestCachePolicy\>\&) | Establece la política de caché para el objeto WebRequest subyacente. |
| [set_Credentials](./set_credentials/)(SharedPtr\<Net::ICredentials\>) override | Establece las credenciales utilizadas para autenticar solicitudes web. |
| [set_Proxy](./set_proxy/)(const SharedPtr\<Net::IWebProxy\>\&) | Establece el proxy de red para el objeto WebRequest subyacente. |
| [XmlUrlResolver](./xmlurlresolver/)() | Inicializa una nueva instancia de la clase [XmlUrlResolver](./). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [XmlResolver](../xmlresolver/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
