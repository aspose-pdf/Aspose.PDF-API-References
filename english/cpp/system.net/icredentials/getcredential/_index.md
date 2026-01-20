---
title: System::Net::ICredentials::GetCredential method
linktitle: GetCredential
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::ICredentials::GetCredential method. RTTI information in C++.'
type: docs
weight: 100
url: /cpp/system.net/icredentials/getcredential/
---
## ICredentials::GetCredential method


RTTI information.

```cpp
virtual System::SharedPtr<NetworkCredential> System::Net::ICredentials::GetCredential(System::SharedPtr<Uri> uri, String authType)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| uri | System::SharedPtr\<Uri\> | The URI for which the authentication type is provided by a client. |
| authType | String | The authentication type. |
## Remarks


Returns credentials for the specified URI and authentication type. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../../networkcredential/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [ICredentials](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
