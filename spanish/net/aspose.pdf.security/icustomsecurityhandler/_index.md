---
title: "Interfaz ICustomSecurityHandler"
second_title: "Aspose.PDF para .NET Referencia de API"
description: "Interfaz Aspose.Pdf.Security.ICustomSecurityHandler. La interfaz del controlador de seguridad personalizado"
type: docs
weight: 10150
url: /es/net/aspose.pdf.security/icustomsecurityhandler/
---
## ICustomSecurityHandler interface

La interfaz del controlador de seguridad personalizado.

```csharp
public interface ICustomSecurityHandler
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Filter](../../aspose.pdf.security/icustomsecurityhandler/filter/) { get; } | Obtiene el nombre del filtro. |
| [KeyLength](../../aspose.pdf.security/icustomsecurityhandler/keylength/) { get; } | Obtiene la longitud de la clave. |
| [Revision](../../aspose.pdf.security/icustomsecurityhandler/revision/) { get; } | Obtiene la revisión del controlador o del algoritmo de cifrado. |
| [SubFilter](../../aspose.pdf.security/icustomsecurityhandler/subfilter/) { get; } | Obtiene el nombre del subfiltro. |
| [Version](../../aspose.pdf.security/icustomsecurityhandler/version/) { get; } | Obtiene la versión del controlador o del algoritmo de cifrado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CalculateEncryptionKey](../../aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/)(string) | Calcula la EncryptionKey. Generalmente la clave se calcula en base a la UserKey. Puedes usar valores de EncryptionParams, que contiene los parámetros actuales en el momento de la llamada. Este valor se pasa como argumento de clave en [`Encrypt`](./encrypt/) y [`Decrypt`](./decrypt/). |
| [Decrypt](../../aspose.pdf.security/icustomsecurityhandler/decrypt/)(byte[], int, int, byte[]) | Descifra la matriz de datos. |
| [Encrypt](../../aspose.pdf.security/icustomsecurityhandler/encrypt/)(byte[], int, int, byte[]) | Cifra la matriz de datos. |
| [EncryptPermissions](../../aspose.pdf.security/icustomsecurityhandler/encryptpermissions/)(int) | Cifra el campo de permisos del documento. El resultado se escribirá en el campo Perms del diccionario de cifrado. Al abrir un documento, el valor puede obtenerse en [`EncryptionParameters`](../encryptionparameters/) a través del campo Perms. Permite comprobar si los permisos del documento han cambiado. |
| [GetOwnerKey](../../aspose.pdf.security/icustomsecurityhandler/getownerkey/)(string, string) | Crea una matriz codificada basada en contraseñas que se escribirá en el campo O del diccionario de cifrado. Debe basarse únicamente en los argumentos proporcionados. La contraseña de usuario puede calcularse a partir de este campo usando la contraseña del propietario. Se llama durante el cifrado para prepararla y rellenar el diccionario de cifrado. El valor estará disponible en [`CalculateEncryptionKey`](./calculateencryptionkey/) para obtener la clave a partir de la UserKey. Las contraseñas especificadas por el usuario al invocar el cifrado del documento se pasarán. Puede que no se especifiquen contraseñas o que solo se especifique una. |
| [GetUserKey](../../aspose.pdf.security/icustomsecurityhandler/getuserkey/)(string) | Crea una matriz codificada basada en la contraseña del usuario. Este valor se usa típicamente para comprobar si la contraseña pertenece al usuario o al propietario, y para obtener la clave de cifrado. Se llama durante el cifrado para prepararla y rellenar el diccionario de cifrado. La contraseña especificada por el usuario se pasa como argumento al invocar el cifrado del documento. |
| [Initialize](../../aspose.pdf.security/icustomsecurityhandler/initialize/)(EncryptionParameters) | Se llama para inicializar la instancia actual para el cifrado. Ten en cuenta que al cifrar, se rellenará con los datos de las propiedades transferidas `ICustomSecurityHandler`, y al abrir el documento desde el diccionario de cifrado. Si el método se llama durante un nuevo cifrado, entonces [`UserKey`](../encryptionparameters/userkey/) y [`OwnerKey`](../encryptionparameters/ownerkey/) serán nulos. |
| [IsOwnerPassword](../../aspose.pdf.security/icustomsecurityhandler/isownerpassword/)(string) | Comprueba si la contraseña es la del propietario del documento. El método se llama después de Initialize. La llamada al método se usa en la API PDF. |
| [IsUserPassword](../../aspose.pdf.security/icustomsecurityhandler/isuserpassword/)(string) | Comprueba si la contraseña pertenece al usuario (contraseña para abrir el documento). El método se llama después de Initialize. La llamada al método se usa en la API PDF. |

### Ver también

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


