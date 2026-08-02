---
title: "ICustomSecurityHandler.GetUserKey"
second_title: "Referência da API Aspose.PDF para .NET"
description: "ICustomSecurityHandler method. Cria um array codificado com base na senha do usuário. Esse valor é tipicamente usado para verificar se a senha pertence ao usuário ou ao proprietário e para obter a chave de criptografia. Chamado durante a criptografia para prepará‑la e preencher o dicionário de criptografia. A senha especificada pelo usuário é passada como argumento ao chamar a criptografia do documento."
type: docs
weight: 110
url: /pt/net/aspose.pdf.security/icustomsecurityhandler/getuserkey/
---
## ICustomSecurityHandler.GetUserKey method

Cria um array codificado baseado na senha do usuário. Este valor é tipicamente usado para verificar se a senha pertence ao usuário ou ao proprietário, e para obter a chave de criptografia. Chamado durante a criptografia para prepará‑lo e preencher o dicionário de criptografia. A senha especificada pelo usuário é passada como argumento ao chamar a criptografia de Document.

```csharp
public byte[] GetUserKey(string userPassword)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| userPassword | String | A senha do usuário. |

### Valor de retorno

O array da chave do usuário.

### Veja Também

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


