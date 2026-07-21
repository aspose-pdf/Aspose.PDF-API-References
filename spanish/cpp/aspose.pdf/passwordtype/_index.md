---
title: "Aspose::Pdf::PasswordType enum"
linktitle: "PasswordType"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::PasswordType enum. Este enum representa los tipos de contraseña conocidos utilizados para documentos PDF protegidos con contraseña en C++."
type: docs
weight: 25700
url: /es/cpp/aspose.pdf/passwordtype/
---
## PasswordType enum


Este enumerado representa los tipos de contraseña conocidos utilizados para documentos PDF protegidos con contraseña.

```cpp
enum class PasswordType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | 0 | [Pdf](../) documento no está protegido con contraseña. |
| User | 1 | [Pdf](../) documento se abrió usando la contraseña de apertura del documento (acceso restringido). |
| Owner | 2 | El documento [Pdf](../) se abrió usando la contraseña de cambio de permisos (acceso completo). |
| Inaccessible | 3 | El documento [Pdf](../) está protegido con contraseña, pero tanto la contraseña de usuario como la de propietario no están vacías y ninguna de las contraseñas fue definida o la contraseña suministrada es incorrecta. Por lo tanto es imposible deducir el tipo de contraseña. |

## Ver también

* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
