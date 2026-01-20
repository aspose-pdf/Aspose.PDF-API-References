---
title: System::Security::Permissions::SecurityPermissionFlag enum
linktitle: SecurityPermissionFlag
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Permissions::SecurityPermissionFlag enum. Flags of security permission in C++.'
type: docs
weight: 300
url: /cpp/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag enum


Flags of security permission.

```cpp
enum class SecurityPermissionFlag
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| NoFlags | 0 | No access. |
| Assertion | 1 | Assert that permission is given. |
| UnmanagedCode | 2 | Call unmanaged code. |
| SkipVerification | 4 | Skip code verification. |
| Execution | 8 | Execute code. |
| ControlThread | 16 | Perform operations on threads. |
| ControlEvidence | 32 | Control or alter CLR evidence. |
| ControlPolicy | 64 | View and change policy. |
| SerializationFormatter | 128 | Serialize. |
| ControlDomainPolicy | 256 | Set domain policy. |
| ControlPrincipal | 512 | Control principal object. |
| ControlAppDomain | 1024 | Control application domain. |
| RemotingConfiguration | 2048 | Configure remoting. |
| Infrastructure | 4096 | Plug into CLR infrastructure. |
| BindingRedirects | 8192 | Perform explicit binding redirection. |
| AllFlags | 16383 | Unrestricted. |

## See Also

* Namespace [System::Security::Permissions](../)
* Library [Aspose.PDF for C++](../../)
