---
title: "ICustomSecurityHandler.CalculateEncryptionKey"
second_title: "Referência da API Aspose.PDF para .NET"
description: "ICustomSecurityHandler method. Calcula a EncryptionKey. Geralmente a chave é calculada com base na UserKey. Você pode usar valores de EncryptionParams, que contém os parâmetros atuais no momento da chamada. Esse valor é passado como argumento da chave em Encrypt e Decrypt."
type: docs
weight: 60
url: /pt/net/aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/
---
## ICustomSecurityHandler.CalculateEncryptionKey method

Calcule a EncryptionKey. Geralmente a chave é calculada com base na UserKey. Você pode usar valores de EncryptionParams, que contém os parâmetros atuais no momento da chamada. Esse valor é passado como argumento da chave em [`Encrypt`](../encrypt/) e [`Decrypt`](../decrypt/).

```csharp
public byte[] CalculateEncryptionKey(string password)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| password | String | Senha inserida pelo usuário. |

### Valor de retorno

O array da chave de criptografia.

### Veja Também

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


