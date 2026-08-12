---
title: "System::Security::Permissions::SecurityPermission класс"
linktitle: "SecurityPermission"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Permissions::SecurityPermission класс. Класс, описывающий разрешение безопасности. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 100
url: /ru/cpp/system.security.permissions/securitypermission/
---
## SecurityPermission class


Класс, описывающий разрешение безопасности. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class SecurityPermission : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Flags](./get_flags/)() | Информация RTTI. |
| [IsUnrestricted](./isunrestricted/)() | Проверяет, является ли разрешение неограниченным. |
| [SecurityPermission](./securitypermission/)(PermissionState) | Конструктор. |
| [SecurityPermission](./securitypermission/)(SecurityPermissionFlag) | Конструктор. |
| [set_Flags](./set_flags/)(SecurityPermissionFlag) | Устанавливает флаги, связанные с разрешением. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Security::Permissions](../)
* Library [Aspose.PDF for C++](../../)
