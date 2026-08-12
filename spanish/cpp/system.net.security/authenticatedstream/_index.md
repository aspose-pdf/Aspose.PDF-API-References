---
title: "System::Net::Security::AuthenticatedStream clase"
linktitle: "AuthenticatedStream"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Security::AuthenticatedStream clase. Contiene los métodos para pasar credenciales a través de un flujo. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 100
url: /es/cpp/system.net.security/authenticatedstream/
---
## AuthenticatedStream class


Contiene los métodos para pasar credenciales a través de un flujo. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class AuthenticatedStream : public System::IO::Stream
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [get_IsAuthenticated](./get_isauthenticated/)() const | Devuelve un valor que indica si la autenticación se ha pasado con éxito. |
| virtual [get_IsEncrypted](./get_isencrypted/)() const | Devuelve un valor que indica si los datos enviados mediante este flujo están cifrados. |
| virtual [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const | Devuelve un valor que indica si un servidor y un cliente están autenticados. |
| virtual [get_IsServer](./get_isserver/)() const | Devuelve un valor que indica si el lado local de la conexión es el servidor. |
| virtual [get_IsSigned](./get_issigned/)() const | Devuelve un valor que indica si los datos enviados mediante este flujo están firmados. |
| [get_LeaveInnerStreamOpen](./get_leaveinnerstreamopen/)() const | Información RTTI. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Un flujo sin almacenamiento subyacente. |
## Ver también

* Class [Stream](../../system.io/stream/)
* Namespace [System::Net::Security](../)
* Library [Aspose.PDF for C++](../../)
