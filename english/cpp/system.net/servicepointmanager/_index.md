---
title: System::Net::ServicePointManager class
linktitle: ServicePointManager
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::ServicePointManager class. Manages the lifecycle stages (creating, maintaining, and deleting) of the ServicePoint class instances. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 3200
url: /cpp/system.net/servicepointmanager/
---
## ServicePointManager class


Manages the lifecycle stages (creating, maintaining, and deleting) of the [ServicePoint](../servicepoint/) class instances. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ServicePointManager : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [get_CertificatePolicy](./get_certificatepolicy/)() | Gets a certificate policy. |
| static [get_CheckCertificateRevocationList](./get_checkcertificaterevocationlist/)() | Gets a value that indicates if the certificate must be checked against the certificate authority revocation list. |
| static [get_DefaultConnectionLimit](./get_defaultconnectionlimit/)() | Gets the maximum number of concurrent connections that are allowed by the ServicePoint-class instances. |
| static [get_DnsRefreshTimeout](./get_dnsrefreshtimeout/)() | Gets a timeout in milliseconds during which a DNS resolution is considered valid. |
| static [get_EnableDnsRoundRobin](./get_enablednsroundrobin/)() | Gets a value that indicates if a DNS resolution rotates among the applicable IP addresses. |
| static [get_EncryptionPolicy](./get_encryptionpolicy/)() | Returns the encryption policy that is used by the current instance. |
| static [get_Expect100Continue](./get_expect100continue/)() | Gets a value that indicates if the ServicePoint-class instances use the 100-Continue behavior. |
| static [get_MaxServicePointIdleTime](./get_maxservicepointidletime/)() | Gets the maximum idle time of the ServicePoint-class instances. |
| static [get_MaxServicePoints](./get_maxservicepoints/)() | Gets the maximum number of the ServicePoint-class instances that can be managed by the current instance. |
| static [get_ReusePort](./get_reuseport/)() | Gets a value that indicates if the output connections sockets use the 'SO_REUSE_UNICASTPORT' option. |
| static [get_SecurityProtocol](./get_securityprotocol/)() | Gets the security protocol type used by the ServicePoint-class instances that are managed by the current instance. |
| static [get_ServerCertificateValidationCallback](./get_servercertificatevalidationcallback/)() | Gets the callback that is used to validate a server certificate. |
| static [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | Gets a value that indicates if the ServicePoint-class instances use the Nagle algorithm. |
| static [set_CertificatePolicy](./set_certificatepolicy/)(System::SharedPtr\<ICertificatePolicy\>) | Sets a certificate policy. |
| static [set_CheckCertificateRevocationList](./set_checkcertificaterevocationlist/)(bool) | Sets a value that indicates if the certificate must be checked against the certificate authority revocation list. |
| static [set_DefaultConnectionLimit](./set_defaultconnectionlimit/)(int32_t) | Sets the maximum number of concurrent connections that are allowed by the ServicePoint-class instances. |
| static [set_DnsRefreshTimeout](./set_dnsrefreshtimeout/)(int32_t) | Sets a timeout in milliseconds during which a DNS resolution is considered valid. |
| static [set_EnableDnsRoundRobin](./set_enablednsroundrobin/)(bool) | Sets a value that indicates if a DNS resolution rotates among the applicable IP addresses. |
| static [set_Expect100Continue](./set_expect100continue/)(bool) | Sets a value that indicates if the ServicePoint-class instances use the 100-Continue behavior. |
| static [set_MaxServicePointIdleTime](./set_maxservicepointidletime/)(int32_t) | Sets the maximum idle time of the ServicePoint-class instances. |
| static [set_MaxServicePoints](./set_maxservicepoints/)(int32_t) | Sets the maximum number of the ServicePoint-class instances that can be managed by the current instance. |
| static [set_ReusePort](./set_reuseport/)(bool) | Sets a value that indicates if the output connections sockets use the 'SO_REUSE_UNICASTPORT' option. |
| static [set_SecurityProtocol](./set_securityprotocol/)(SecurityProtocolType) | Sets the security protocol type used by the ServicePoint-class instances that are managed by the current instance. |
| static [set_ServerCertificateValidationCallback](./set_servercertificatevalidationcallback/)(Security::RemoteCertificateValidationCallback) | Sets the callback that is used to validate a server certificate. |
| static [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(bool) | Sets a value that indicates if the ServicePoint-class instances use the Nagle algorithm. |
| static [SetTcpKeepAlive](./settcpkeepalive/)(bool, int32_t, int32_t) | Sets the value that indicates if the 'Keep-Alive' option is enabled. |
## Fields

| Field | Description |
| --- | --- |
| static [DefaultNonPersistentConnectionLimit](./defaultnonpersistentconnectionlimit/) | RTTI information. |
| static [DefaultPersistentConnectionLimit](./defaultpersistentconnectionlimit/) | The default number of persistent connections. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
