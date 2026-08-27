---
title: "ICustomSecurityHandler.GetOwnerKey"
second_title: "Referência da API Aspose.PDF para .NET"
description: "ICustomSecurityHandler method. Cria um array codificado com base nas senhas que será escrito no campo O do dicionário de criptografia. Deve depender apenas dos argumentos passados. A senha do usuário pode ser calculada a partir deste campo usando a senha do proprietário. Chamado durante a criptografia para prepará‑la e preencher o dicionário de criptografia. O valor estará disponível em CalculateEncryptionKey para obter a chave a partir da UserKey. As senhas especificadas pelo usuário ao chamar a criptografia do documento serão passadas. As senhas podem não ser especificadas ou apenas uma pode ser especificada."
type: docs
weight: 100
url: /pt/net/aspose.pdf.security/icustomsecurityhandler/getownerkey/
---
## ICustomSecurityHandler.GetOwnerKey method

Cria um array codificado com base nas senhas que será escrito no campo O do dicionário de criptografia. Deve depender apenas dos argumentos passados. A senha do usuário pode ser calculada a partir deste campo usando a senha do proprietário. Chamado durante a criptografia para prepará‑lo e preencher o dicionário de criptografia. O valor estará disponível em [`CalculateEncryptionKey`](../calculateencryptionkey/) para obter a chave a partir da UserKey. As senhas especificadas pelo usuário ao chamar a criptografia de documento serão passadas. As senhas podem não ser especificadas ou apenas uma pode ser especificada.

```csharp
public byte[] GetOwnerKey(string userPassword, string ownerPassword)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| userPassword | String | A senha do usuário. |
| ownerPassword | String | A senha do proprietário. |

### Valor de retorno

O array da chave do proprietário.

### Veja Também

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


