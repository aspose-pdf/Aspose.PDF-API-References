---
title: "ICustomSecurityHandler.GetOwnerKey"
second_title: "Aspose.PDF para .NET Referencia de API"
description: "Método ICustomSecurityHandler. Crea una matriz codificada basada en contraseñas que se escribirá en el campo O del diccionario de cifrado. Sólo debe depender de los argumentos pasados. La contraseña del usuario puede calcularse a partir de este campo usando la contraseña del propietario. Se llama durante el cifrado para prepararla y rellenar el diccionario de cifrado. El valor estará disponible en CalculateEncryptionKey para obtener la clave a partir de la UserKey. Las contraseñas especificadas por el usuario al llamar al cifrado del documento se pasarán. Puede que no se especifiquen contraseñas o que sólo se especifique una."
type: docs
weight: 100
url: /es/net/aspose.pdf.security/icustomsecurityhandler/getownerkey/
---
## ICustomSecurityHandler.GetOwnerKey method

Crea una matriz codificada basada en contraseñas que se escribirá en el campo O del diccionario de cifrado. Debe basarse únicamente en los argumentos pasados. La contraseña de usuario puede calcularse a partir de este campo usando la contraseña del propietario. Se llama durante el cifrado para prepararlo y rellenar el diccionario de cifrado. El valor estará disponible en [`CalculateEncryptionKey`](../calculateencryptionkey/) para obtener la clave del UserKey. Las contraseñas especificadas por el usuario al llamar al cifrado del documento serán pasadas. Puede que no se especifiquen contraseñas o que solo se especifique una.

```csharp
public byte[] GetOwnerKey(string userPassword, string ownerPassword)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| userPassword | Cadena | La contraseña del usuario. |
| ownerPassword | Cadena | La contraseña del propietario. |

### Valor devuelto

La matriz de la clave del propietario.

### Ver también

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


