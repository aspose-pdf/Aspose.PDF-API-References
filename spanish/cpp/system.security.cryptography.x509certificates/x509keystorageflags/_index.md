---
title: "System::Security::Cryptography::X509Certificates::X509KeyStorageFlags enum"
linktitle: "X509KeyStorageFlags"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::Cryptography::X509Certificates::X509KeyStorageFlags enum. Define cómo almacenar la clave en C++."
type: docs
weight: 2100
url: /es/cpp/system.security.cryptography.x509certificates/x509keystorageflags/
---
## X509KeyStorageFlags enum


Define cómo almacenar la clave.

```cpp
enum class X509KeyStorageFlags : int32_t
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| DefaultKeySet | 0 | Usar conjunto de claves predeterminado. |
| UserKeySet | 1 | Usar el almacén asociado al usuario en lugar del local de la máquina. |
| MachineKeySet | 2 | Usar el almacén local de la máquina en lugar del de usuario. |
| Exportable | 4 | Marca las claves importadas como exportables. |
| UserProtected | 8 | Notificar al usuario que la clave está siendo utilizada. |
| PersistKeySet | 16 | La clave se persiste al importar el certificado. |

## Ver también

* Namespace [System::Security::Cryptography::X509Certificates](../)
* Library [Aspose.PDF for C++](../../)
