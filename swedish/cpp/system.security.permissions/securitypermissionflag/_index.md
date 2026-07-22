---
title: "System::Security::Permissions::SecurityPermissionFlag enum"
linktitle: "SecurityPermissionFlag"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Permissions::SecurityPermissionFlag enum. Flaggor för säkerhetsbehörighet i C++."
type: docs
weight: 300
url: /sv/cpp/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag enum


Flaggor för säkerhetsbehörighet.

```cpp
enum class SecurityPermissionFlag
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| NoFlags | 0 | Ingen åtkomst. |
| Påstående | 1 | Påstå att behörigheten är beviljad. |
| UnmanagedCode | 2 | Anropa ohanterad kod. |
| SkipVerification | 4 | Hoppa över kodverifiering. |
| Execution | 8 | Kör kod. |
| ControlThread | 16 | Utför operationer på trådar. |
| ControlEvidence | 32 | Styr eller ändra CLR-bevis. |
| ControlPolicy | 64 | Visa och ändra policy. |
| SerializationFormatter | 128 | Serialisera. |
| ControlDomainPolicy | 256 | Ställ in domänpolicy. |
| ControlPrincipal | 512 | Styr principal-objektet. |
| ControlAppDomain | 1024 | Styr applikationsdomän. |
| RemotingConfiguration | 2048 | Konfigurera fjärrkommunikation. |
| Infrastructure | 4096 | Anslut till CLR-infrastrukturen. |
| BindingRedirects | 8192 | Utför explicit bindningsomdirigering. |
| AllFlags | 16383 | Obegränsad. |

## Se även

* Namespace [System::Security::Permissions](../)
* Library [Aspose.PDF for C++](../../)
