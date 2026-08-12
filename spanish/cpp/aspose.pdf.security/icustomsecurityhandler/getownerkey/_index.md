---
title: "Aspose::Pdf::Security::ICustomSecurityHandler::GetOwnerKey método"
linktitle: "GetOwnerKey"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Security::ICustomSecurityHandler::GetOwnerKey método. Crea un arreglo codificado basado en contraseñas que se escribirá en el campo O del diccionario de cifrado. Debe basarse únicamente en los argumentos pasados. La contraseña del usuario puede calcularse a partir de este campo usando la contraseña del propietario. Se llama durante el cifrado para prepararlo y rellenar el diccionario de cifrado. El valor estará disponible en CalculateEncryptionKey para obtener la clave del UserKey. Las contraseñas especificadas por el usuario al llamar al cifrado del documento serán pasadas. Puede que no se especifiquen contraseñas o que solo se especifique una en C++."
type: docs
weight: 1000
url: /es/cpp/aspose.pdf.security/icustomsecurityhandler/getownerkey/
---
## ICustomSecurityHandler::GetOwnerKey method


Crea un arreglo codificado basado en contraseñas que se escribirá en el campo O del diccionario de cifrado. Debe basarse únicamente en los argumentos pasados. La contraseña del usuario puede calcularse a partir de este campo usando la contraseña del propietario. Se llama durante el cifrado para prepararlo y rellenar el diccionario de cifrado. El valor estará disponible en [CalculateEncryptionKey](../calculateencryptionkey/) para obtener la clave del UserKey. Las contraseñas especificadas por el usuario al llamar al cifrado del documento serán pasadas. Puede que no se especifiquen contraseñas o que solo se especifique una.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Pdf::Security::ICustomSecurityHandler::GetOwnerKey(System::String userPassword, System::String ownerPassword)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| userPassword | System::String | La contraseña del usuario. |
| ownerPassword | System::String | La contraseña del propietario. |

### ReturnValue

El arreglo de la clave del propietario.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ICustomSecurityHandler](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
