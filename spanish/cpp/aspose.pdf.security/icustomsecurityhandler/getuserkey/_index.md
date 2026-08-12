---
title: "Aspose::Pdf::Security::ICustomSecurityHandler::GetUserKey método"
linktitle: "GetUserKey"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Security::ICustomSecurityHandler::GetUserKey método. Crea una matriz codificada basada en la contraseña del usuario''. Este valor se utiliza típicamente para comprobar si la contraseña pertenece al usuario o al propietario, y para obtener la clave de encriptación. Llamado durante la encriptación para prepararla y rellenar el diccionario de encriptación. La contraseña especificada por el usuario se pasa como argumento al llamar a la encriptación del documento en C++."
type: docs
weight: 1100
url: /es/cpp/aspose.pdf.security/icustomsecurityhandler/getuserkey/
---
## ICustomSecurityHandler::GetUserKey method


Crea un array codificado basado en la contraseña del usuario. Este valor se usa típicamente para comprobar si la contraseña pertenece al usuario o al propietario, y para obtener la clave de cifrado. Se llama durante el cifrado para prepararlo y rellenar el diccionario de cifrado. La contraseña especificada por el usuario se pasa como argumento al invocar el cifrado del documento.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Pdf::Security::ICustomSecurityHandler::GetUserKey(System::String userPassword)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| userPassword | System::String | La contraseña del usuario. |

### ReturnValue

La matriz de la clave de usuario.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
