---
title: Enum PasswordType
second_title: Aspose.PDF for .NET API Reference
description: Enum PasswordType de Aspose.Pdf. Este enum representa los tipos de contraseña conocidos utilizados para documentos pdf protegidos por contraseña.
type: docs
weight: 8290
url: /es/net/aspose.pdf/passwordtype/
---
## Enumeración PasswordType

Este enum representa los tipos de contraseña conocidos utilizados para documentos pdf protegidos por contraseña.

```csharp
public enum PasswordType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Ninguno | `0` | El documento Pdf no está protegido por contraseña. |
| Usuario | `1` | El documento Pdf se abrió utilizando la contraseña de apertura del documento (acceso restringido). |
| Propietario | `2` | El documento Pdf se abrió utilizando la contraseña de cambio de permisos (acceso completo). |
| Inaccesible | `3` | El documento Pdf está protegido por contraseña, pero tanto las contraseñas de usuario como de propietario no están vacías y ninguna de las contraseñas fue definida o la contraseña suministrada fue incorrecta. Por lo tanto, es imposible deducir el tipo de contraseña. |

### Ver También

* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)