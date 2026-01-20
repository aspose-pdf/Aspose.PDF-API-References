---
title: System::Security::Permissions::SecurityPermission class
linktitle: SecurityPermission
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Permissions::SecurityPermission class. Class that describes security permission. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.security.permissions/securitypermission/
---
## SecurityPermission class


Class that describes security permission. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SecurityPermission : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Flags](./get_flags/)() | RTTI information. |
| [IsUnrestricted](./isunrestricted/)() | Checks if permission is unrestricted. |
| [SecurityPermission](./securitypermission/)(PermissionState) | Constructor. |
| [SecurityPermission](./securitypermission/)(SecurityPermissionFlag) | Constructor. |
| [set_Flags](./set_flags/)(SecurityPermissionFlag) | Sets flags associated with permission. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Security::Permissions](../)
* Library [Aspose.PDF for C++](../../)
