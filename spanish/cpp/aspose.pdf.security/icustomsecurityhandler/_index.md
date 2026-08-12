---
title: "Clase Aspose::Pdf::Security::ICustomSecurityHandler"
linktitle: "ICustomSecurityHandler"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Security::ICustomSecurityHandler. La interfaz de manejador de seguridad personalizado en C++."
type: docs
weight: 500
url: /es/cpp/aspose.pdf.security/icustomsecurityhandler/
---
## ICustomSecurityHandler class


La interfaz del controlador de seguridad personalizado.

```cpp
class ICustomSecurityHandler : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [CalculateEncryptionKey](./calculateencryptionkey/)(System::String) | Calcule la EncryptionKey. Generalmente la clave se calcula en base a la UserKey. Puede usar valores de EncryptionParams, que contiene los parámetros actuales en el momento de la llamada. Este valor se pasa como argumento key en [Encrypt](./encrypt/) y [Decrypt](./decrypt/). |
| virtual [Decrypt](./decrypt/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>) | Desencripte el array de datos. |
| virtual [Encrypt](./encrypt/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>) | Encripte el array de datos. |
| virtual [EncryptPermissions](./encryptpermissions/)(int32_t) | Encripte el campo de permisos del documento. El resultado se escribirá en el campo Perms del diccionario de cifrado. Al abrir un documento, el valor puede obtenerse en [EncryptionParameters](../encryptionparameters/) a través del campo Perms. Permite comprobar si los permisos del documento han cambiado. |
| virtual [get_Filter](./get_filter/)() | Obtiene el nombre del filtro. |
| virtual [get_KeyLength](./get_keylength/)() | Obtiene la longitud de la clave. |
| virtual [get_Revision](./get_revision/)() | Obtiene la revisión del manejador o del algoritmo de cifrado. |
| virtual [get_SubFilter](./get_subfilter/)() | Obtiene el nombre del subfiltro. |
| virtual [get_Version](./get_version/)() | Obtiene la versión del manejador o del algoritmo de cifrado. |
| virtual [GetOwnerKey](./getownerkey/)(System::String, System::String) | Crea un array codificado basado en contraseñas que se escribirá en el campo O del diccionario de cifrado. Debe basarse únicamente en los argumentos proporcionados. La contraseña de usuario puede calcularse a partir de este campo usando la contraseña del propietario. Se llama durante el cifrado para prepararlo y rellenar el diccionario de cifrado. El valor estará disponible en [CalculateEncryptionKey](./calculateencryptionkey/) para obtener la clave a partir de la UserKey. Se pasarán las contraseñas especificadas por el usuario al invocar el cifrado del documento. Puede que no se especifiquen contraseñas o que solo se especifique una. |
| virtual [GetUserKey](./getuserkey/)(System::String) | Crea un array codificado basado en la contraseña del usuario. Este valor se usa típicamente para comprobar si la contraseña pertenece al usuario o al propietario, y para obtener la clave de cifrado. Se llama durante el cifrado para prepararlo y rellenar el diccionario de cifrado. La contraseña especificada por el usuario se pasa como argumento al invocar el cifrado del documento. |
| virtual [Initialize](./initialize/)(System::SharedPtr\<EncryptionParameters\>) | Se llama para inicializar la instancia actual para el cifrado. [Note](../../aspose.pdf/note/) que al cifrar, se rellenará con los datos de las propiedades transferidas [ICustomSecurityHandler](./), y al abrir el documento desde el diccionario de cifrado. Si el método se llama durante un nuevo cifrado, entonces [EncryptionParameters::UserKey](../) y [EncryptionParameters::OwnerKey](../) serán nulos. |
| virtual [IsOwnerPassword](./isownerpassword/)(System::String) | Comprueba si la contraseña es la del propietario del documento. El método se llama después de Initialize. La llamada al método se usa en la API PDF. |
| virtual [IsUserPassword](./isuserpassword/)(System::String) | Comprueba si la contraseña pertenece al usuario (contraseña para abrir el documento). El método se llama después de Initialize. La llamada al método se usa en la API PDF. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Security](../)
* Library [Aspose.PDF for C++](../../)
