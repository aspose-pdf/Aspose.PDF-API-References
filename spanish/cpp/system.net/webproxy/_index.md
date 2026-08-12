---
title: "Clase System::Net::WebProxy"
linktitle: "WebProxy"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::WebProxy. Representa un servidor proxy web http. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 3700
url: /es/cpp/system.net/webproxy/
---
## WebProxy class


Representa un servidor proxy web http. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class WebProxy : public System::Net::IWebProxy
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Address](./get_address/)() | Obtiene la dirección del servidor proxy actual. |
| [get_BypassList](./get_bypasslist/)() | Obtiene la lista de direcciones que no utilizan el servidor proxy. |
| [get_BypassProxyOnLocal](./get_bypassproxyonlocal/)() | Obtiene un valor que indica si el servidor proxy debe usarse para direcciones locales. |
| virtual [get_Credentials](./get_credentials/)() | Obtiene las credenciales que se envían al servidor proxy para autenticación. |
| [get_UseDefaultCredentials](./get_usedefaultcredentials/)() | Obtiene un valor que indica si las credenciales predeterminadas deben enviarse con las solicitudes. |
| static [GetDefaultProxy](./getdefaultproxy/)() | Devuelve el proxy que utiliza la configuración no dinámica de Internet Explorer. |
| virtual [GetProxy](./getproxy/)(System::SharedPtr\<Uri\>) | Devuelve el URI proxy para una solicitud web. |
| virtual [IsBypassed](./isbypassed/)(System::SharedPtr\<Uri\>) | Comprueba si el servidor proxy no se utiliza para el URI especificado. |
| [set_Address](./set_address/)(System::SharedPtr\<Uri\>) | Establece la dirección del servidor proxy actual. |
| [set_BypassList](./set_bypasslist/)(System::ArrayPtr\<String\>) | Establece la lista de direcciones que no utilizan el servidor proxy. |
| [set_BypassProxyOnLocal](./set_bypassproxyonlocal/)(bool) | Establece un valor que indica si el servidor proxy debe usarse para direcciones locales. |
| virtual [set_Credentials](./set_credentials/)(System::SharedPtr\<ICredentials\>) | Establece las credenciales que se envían al servidor proxy para autenticación. |
| [set_UseDefaultCredentials](./set_usedefaultcredentials/)(bool) | Establece un valor que indica si las credenciales predeterminadas deben enviarse con las solicitudes. |
| [WebProxy](./webproxy/)() | Construye una nueva instancia. |
| [WebProxy](./webproxy/)(System::SharedPtr\<Uri\>) | Construye una nueva instancia. |
| [WebProxy](./webproxy/)(System::SharedPtr\<Uri\>, bool) | Construye una nueva instancia. |
| [WebProxy](./webproxy/)(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>) | Construye una nueva instancia. |
| [WebProxy](./webproxy/)(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) | Construye una nueva instancia. |
| [WebProxy](./webproxy/)(String, int32_t) | Construye una nueva instancia. |
| [WebProxy](./webproxy/)(String) | Construye una nueva instancia. |
| [WebProxy](./webproxy/)(String, bool) | Construye una nueva instancia. |
| [WebProxy](./webproxy/)(String, bool, System::ArrayPtr\<String\>) | Construye una nueva instancia. |
| [WebProxy](./webproxy/)(String, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) | Construye una nueva instancia. |
## Ver también

* Class [IWebProxy](../iwebproxy/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
