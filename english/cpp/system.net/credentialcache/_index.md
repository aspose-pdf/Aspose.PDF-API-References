---
title: System::Net::CredentialCache class
linktitle: CredentialCache
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::CredentialCache class. Provides the credentials storage. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 600
url: /cpp/system.net/credentialcache/
---
## CredentialCache class


Provides the credentials storage. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class CredentialCache : public System::Net::ICredentials,
                        public System::Net::ICredentialsByHost
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) | Adds the specified network credentials to the cache. |
| [Add](./add/)(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) | Adds the specified network credentials to the cache. |
| [CredentialCache](./credentialcache/)() | Constructs a new instance. |
| static [get_DefaultCredentials](./get_defaultcredentials/)() | RTTI information. |
| static [get_DefaultNetworkCredentials](./get_defaultnetworkcredentials/)() | Returns the network credentials of the current user or application. |
| [GetCredential](./getcredential/)(System::SharedPtr\<Uri\>, String) override | Returns credentials for the specified URI prefix and authentication type. |
| [GetCredential](./getcredential/)(String, int32_t, String) override | Returns credentials for the specified host name, port, and authentication type. |
| [Remove](./remove/)(System::SharedPtr\<Uri\>, String) | Removes network credentials for the specified URI prefix and authentication type. |
| [Remove](./remove/)(String, int32_t, String) | Removes network credentials for the specified host name, port, and authentication type. |
## See Also

* Class [ICredentials](../icredentials/)
* Class [ICredentialsByHost](../icredentialsbyhost/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
