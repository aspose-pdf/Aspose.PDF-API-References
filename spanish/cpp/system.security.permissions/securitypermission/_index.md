---
title: "System::Security::Permissions::SecurityPermission clase"
linktitle: "SecurityPermission"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Permissions::SecurityPermission clase. Clase que describe el permiso de seguridad. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 100
url: /es/cpp/system.security.permissions/securitypermission/
---
## SecurityPermission class


Clase que describe el permiso de seguridad. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class SecurityPermission : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Flags](./get_flags/)() | Información RTTI. |
| [IsUnrestricted](./isunrestricted/)() | Comprueba si el permiso es sin restricciones. |
| [SecurityPermission](./securitypermission/)(PermissionState) | Constructor. |
| [SecurityPermission](./securitypermission/)(SecurityPermissionFlag) | Constructor. |
| [set_Flags](./set_flags/)(SecurityPermissionFlag) | Establece los indicadores asociados al permiso. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Security::Permissions](../)
* Library [Aspose.PDF for C++](../../)
