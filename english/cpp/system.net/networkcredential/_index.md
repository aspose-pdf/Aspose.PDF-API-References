---
title: System::Net::NetworkCredential class
linktitle: NetworkCredential
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::NetworkCredential class. Provides credentials for the password-based authentication schemes. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2900
url: /cpp/system.net/networkcredential/
---
## NetworkCredential class


Provides credentials for the password-based authentication schemes. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class NetworkCredential : public System::Net::ICredentials,
                          public System::Net::ICredentialsByHost,
                          public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Domain](./get_domain/)() | Gets the domain that verifies the credentials. |
| [get_Password](./get_password/)() | Gets the password. |
| [get_UserName](./get_username/)() | RTTI information. |
| [GetCredential](./getcredential/)(System::SharedPtr\<Uri\>, String) override | Returns credentials for the specified URI and authentication type. |
| [GetCredential](./getcredential/)(String, int32_t, String) override | Returns credentials for the specified host name, port, and authentication type. |
| [NetworkCredential](./networkcredential/)() | Constructs a new instance. |
| [NetworkCredential](./networkcredential/)(String, String) | Constructs a new instance. |
| [NetworkCredential](./networkcredential/)(String, String, String) | Constructs a new instance. |
| [set_Domain](./set_domain/)(String) | Sets the domain that verifies the credentials. |
| [set_Password](./set_password/)(String) | Sets the password. |
| [set_UserName](./set_username/)(String) | Sets the username. |
## See Also

* Class [ICredentials](../icredentials/)
* Class [ICredentialsByHost](../icredentialsbyhost/)
* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
