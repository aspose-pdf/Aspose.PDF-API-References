---
title: "Aspose::Pdf::Security::ICustomSecurityHandler::EncryptPermissions método"
linktitle: "EncryptPermissions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Security::ICustomSecurityHandler::EncryptPermissions método. Encripta el campo de permisos del documento''. El resultado se escribirá en el campo Perms del diccionario de encriptación. Al abrir un documento, el valor puede obtenerse en EncryptionParameters a través del campo Perms. Permite comprobar si los permisos del documento han cambiado en C++."
type: docs
weight: 400
url: /es/cpp/aspose.pdf.security/icustomsecurityhandler/encryptpermissions/
---
## ICustomSecurityHandler::EncryptPermissions method


Encripta el campo de permisos del documento. El resultado se escribirá en el campo Perms del diccionario de encriptación. Al abrir un documento, el valor puede obtenerse en [EncryptionParameters](../../encryptionparameters/) a través del campo Perms. Permite comprobar si los permisos del documento han cambiado.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Pdf::Security::ICustomSecurityHandler::EncryptPermissions(int32_t permissions)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| permisos | int32_t | Los permisos del documento en representación entera. |

### ReturnValue

La matriz encriptada.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
