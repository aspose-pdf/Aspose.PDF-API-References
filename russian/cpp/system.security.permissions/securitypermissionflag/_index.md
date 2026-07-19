---
title: "System::Security::Permissions::SecurityPermissionFlag перечисление"
linktitle: "SecurityPermissionFlag"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Permissions::SecurityPermissionFlag перечисление. Флаги разрешения безопасности в C++."
type: docs
weight: 300
url: /ru/cpp/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag enum


Флаги разрешения безопасности.

```cpp
enum class SecurityPermissionFlag
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| NoFlags | 0 | Нет доступа. |
| Assertion | 1 | Утвердите, что разрешение предоставлено. |
| UnmanagedCode | 2 | Вызвать неуправляемый код. |
| SkipVerification | 4 | Пропустить проверку кода. |
| Execution | 8 | Выполнить код. |
| ControlThread | 16 | Выполнять операции с потоками. |
| ControlEvidence | 32 | Контролировать или изменять доказательства CLR. |
| ControlPolicy | 64 | Просматривать и изменять политику. |
| SerializationFormatter | 128 | Сериализовать. |
| ControlDomainPolicy | 256 | Установить политику домена. |
| ControlPrincipal | 512 | Управлять объектом principal. |
| ControlAppDomain | 1024 | Управлять доменом приложения. |
| RemotingConfiguration | 2048 | Настроить удалённый вызов. |
| Инфраструктура | 4096 | Подключиться к инфраструктуре CLR. |
| BindingRedirects | 8192 | Выполнить явное перенаправление привязки. |
| AllFlags | 16383 | Неограниченный. |

## См. также

* Namespace [System::Security::Permissions](../)
* Library [Aspose.PDF for C++](../../)
