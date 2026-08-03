---
title: "ICustomSecurityHandler.CalculateEncryptionKey"
second_title: "Aspose.PDF para .NET Referencia de API"
description: "Método ICustomSecurityHandler. Calcula la EncryptionKey. Generalmente la clave se calcula a partir de la UserKey. Puedes usar valores de EncryptionParams, que contiene los parámetros actuales en el momento de la llamada. Este valor se pasa como argumento de clave en Encrypt y Decrypt."
type: docs
weight: 60
url: /es/net/aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/
---
## ICustomSecurityHandler.CalculateEncryptionKey method

Calcula la EncryptionKey. Generalmente la clave se calcula a partir de la UserKey. Puedes usar valores de EncryptionParams, que contiene los parámetros actuales en el momento de la llamada. Este valor se pasa como argumento de clave en [`Encrypt`](../encrypt/) y [`Decrypt`](../decrypt/).

```csharp
public byte[] CalculateEncryptionKey(string password)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| password | Cadena | Contraseña introducida por el usuario. |

### Valor devuelto

La matriz de la clave de cifrado.

### Ver también

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


