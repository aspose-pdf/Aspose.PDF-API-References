---
title: System::Net::Security::AuthenticationLevel enum
linktitle: AuthenticationLevel
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Security::AuthenticationLevel enum. WebRequest-specific authentication flags in C++.'
type: docs
weight: 300
url: /cpp/system.net.security/authenticationlevel/
---
## AuthenticationLevel enum


WebRequest-specific authentication flags.

```cpp
enum class AuthenticationLevel
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | No authentication is required for the client and server. |
| MutualAuthRequested | 1 | The request does not fail if the server is not authenticated. |
| MutualAuthRequired | 2 | The current application will receive 'IOException' when the server is not authenticated. |

## See Also

* Namespace [System::Net::Security](../)
* Library [Aspose.PDF for C++](../../)
