---
title: "Clase System::Net::ServicePointManager"
linktitle: "ServicePointManager"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::ServicePointManager. Gestiona las etapas del ciclo de vida (creación, mantenimiento y eliminación) de las instancias de la clase ServicePoint. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 3200
url: /es/cpp/system.net/servicepointmanager/
---
## ServicePointManager class


Gestiona las etapas del ciclo de vida (creación, mantenimiento y eliminación) de las instancias de la clase [ServicePoint](../servicepoint/). Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class ServicePointManager : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [get_CertificatePolicy](./get_certificatepolicy/)() | Obtiene una política de certificado. |
| static [get_CheckCertificateRevocationList](./get_checkcertificaterevocationlist/)() | Obtiene un valor que indica si el certificado debe verificarse contra la lista de revocación de la autoridad certificadora. |
| static [get_DefaultConnectionLimit](./get_defaultconnectionlimit/)() | Obtiene el número máximo de conexiones concurrentes que permiten las instancias de la clase ServicePoint. |
| static [get_DnsRefreshTimeout](./get_dnsrefreshtimeout/)() | Obtiene un tiempo de espera en milisegundos durante el cual una resolución DNS se considera válida. |
| static [get_EnableDnsRoundRobin](./get_enablednsroundrobin/)() | Obtiene un valor que indica si una resolución DNS rota entre las direcciones IP aplicables. |
| static [get_EncryptionPolicy](./get_encryptionpolicy/)() | Devuelve la política de cifrado que utiliza la instancia actual. |
| static [get_Expect100Continue](./get_expect100continue/)() | Obtiene un valor que indica si las instancias de ServicePoint-class utilizan el comportamiento 100-Continue. |
| static [get_MaxServicePointIdleTime](./get_maxservicepointidletime/)() | Obtiene el tiempo máximo inactivo de las instancias de ServicePoint-class. |
| static [get_MaxServicePoints](./get_maxservicepoints/)() | Obtiene el número máximo de instancias de ServicePoint-class que pueden ser gestionadas por la instancia actual. |
| static [get_ReusePort](./get_reuseport/)() | Obtiene un valor que indica si los sockets de conexiones de salida usan la opción 'SO_REUSE_UNICASTPORT'. |
| static [get_SecurityProtocol](./get_securityprotocol/)() | Obtiene el tipo de protocolo de seguridad utilizado por las instancias de ServicePoint-class que son gestionadas por la instancia actual. |
| static [get_ServerCertificateValidationCallback](./get_servercertificatevalidationcallback/)() | Obtiene la devolución de llamada que se usa para validar un certificado de servidor. |
| static [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | Obtiene un valor que indica si las instancias de ServicePoint-class utilizan el algoritmo de Nagle. |
| static [set_CertificatePolicy](./set_certificatepolicy/)(System::SharedPtr\<ICertificatePolicy\>) | Establece una política de certificado. |
| static [set_CheckCertificateRevocationList](./set_checkcertificaterevocationlist/)(bool) | Establece un valor que indica si el certificado debe verificarse contra la lista de revocación de la autoridad certificadora. |
| static [set_DefaultConnectionLimit](./set_defaultconnectionlimit/)(int32_t) | Establece el número máximo de conexiones concurrentes que permiten las instancias de ServicePoint-class. |
| static [set_DnsRefreshTimeout](./set_dnsrefreshtimeout/)(int32_t) | Establece un tiempo de espera en milisegundos durante el cual una resolución DNS se considera válida. |
| static [set_EnableDnsRoundRobin](./set_enablednsroundrobin/)(bool) | Establece un valor que indica si una resolución DNS rota entre las direcciones IP aplicables. |
| static [set_Expect100Continue](./set_expect100continue/)(bool) | Establece un valor que indica si las instancias de ServicePoint-class utilizan el comportamiento 100-Continue. |
| static [set_MaxServicePointIdleTime](./set_maxservicepointidletime/)(int32_t) | Establece el tiempo máximo inactivo de las instancias de ServicePoint-class. |
| static [set_MaxServicePoints](./set_maxservicepoints/)(int32_t) | Establece el número máximo de instancias de ServicePoint-class que pueden ser gestionadas por la instancia actual. |
| static [set_ReusePort](./set_reuseport/)(bool) | Establece un valor que indica si los sockets de conexiones de salida usan la opción 'SO_REUSE_UNICASTPORT'. |
| static [set_SecurityProtocol](./set_securityprotocol/)(SecurityProtocolType) | Establece el tipo de protocolo de seguridad utilizado por las instancias de ServicePoint-class que son gestionadas por la instancia actual. |
| static [set_ServerCertificateValidationCallback](./set_servercertificatevalidationcallback/)(Security::RemoteCertificateValidationCallback) | Establece la devolución de llamada que se usa para validar un certificado de servidor. |
| static [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(bool) | Establece un valor que indica si las instancias de ServicePoint-class utilizan el algoritmo de Nagle. |
| static [SetTcpKeepAlive](./settcpkeepalive/)(bool, int32_t, int32_t) | Establece el valor que indica si la opción 'Keep-Alive' está habilitada. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [DefaultNonPersistentConnectionLimit](./defaultnonpersistentconnectionlimit/) | Información RTTI. |
| static [DefaultPersistentConnectionLimit](./defaultpersistentconnectionlimit/) | El número predeterminado de conexiones persistentes. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
