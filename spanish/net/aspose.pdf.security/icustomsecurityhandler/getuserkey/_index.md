---
title: "ICustomSecurityHandler.GetUserKey"
second_title: "Aspose.PDF para .NET Referencia de API"
description: "Método ICustomSecurityHandler. Crea una matriz codificada basada en la contraseña del usuario. Este valor se usa típicamente para verificar si la contraseña pertenece al usuario o al propietario y para obtener la clave de cifrado. Se llama durante el cifrado para prepararla y rellenar el diccionario de cifrado. La contraseña especificada por el usuario se pasa como argumento al llamar al cifrado del documento."
type: docs
weight: 110
url: /es/net/aspose.pdf.security/icustomsecurityhandler/getuserkey/
---
## ICustomSecurityHandler.GetUserKey method

Crea una matriz codificada basada en la contraseña del usuario. Este valor se usa típicamente para comprobar si la contraseña pertenece al usuario o al propietario, y para obtener la clave de cifrado. Se llama durante el cifrado para prepararla y rellenar el diccionario de cifrado. La contraseña especificada por el usuario se pasa como argumento al invocar el cifrado del documento.

```csharp
public byte[] GetUserKey(string userPassword)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| userPassword | Cadena | La contraseña del usuario. |

### Valor devuelto

La matriz de la clave de usuario.

### Ver también

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


