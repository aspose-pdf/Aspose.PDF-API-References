---
title: "Interface ICustomSecurityHandler"
second_title: "Referência da API Aspose.PDF para .NET"
description: "Aspose.Pdf.Security.ICustomSecurityHandler interface. A interface do manipulador de segurança personalizado."
type: docs
weight: 10150
url: /pt/net/aspose.pdf.security/icustomsecurityhandler/
---
## ICustomSecurityHandler interface

A interface do manipulador de segurança personalizado.

```csharp
public interface ICustomSecurityHandler
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Filter](../../aspose.pdf.security/icustomsecurityhandler/filter/) { get; } | Obtém o nome do filtro. |
| [KeyLength](../../aspose.pdf.security/icustomsecurityhandler/keylength/) { get; } | Obtém o comprimento da chave. |
| [Revision](../../aspose.pdf.security/icustomsecurityhandler/revision/) { get; } | Obtém a revisão do manipulador ou algoritmo de criptografia. |
| [SubFilter](../../aspose.pdf.security/icustomsecurityhandler/subfilter/) { get; } | Obtém o nome do subfiltro. |
| [Version](../../aspose.pdf.security/icustomsecurityhandler/version/) { get; } | Obtém a versão do manipulador ou algoritmo de criptografia. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [CalculateEncryptionKey](../../aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/)(string) | Calcule a EncryptionKey. Geralmente a chave é calculada com base na UserKey. Você pode usar valores de EncryptionParams, que contém os parâmetros atuais no momento da chamada. Este valor é passado como argumento da chave em [`Encrypt`](./encrypt/) e [`Decrypt`](./decrypt/). |
| [Decrypt](../../aspose.pdf.security/icustomsecurityhandler/decrypt/)(byte[], int, int, byte[]) | Descriptografe o array de dados. |
| [Encrypt](../../aspose.pdf.security/icustomsecurityhandler/encrypt/)(byte[], int, int, byte[]) | Criptografe o array de dados. |
| [EncryptPermissions](../../aspose.pdf.security/icustomsecurityhandler/encryptpermissions/)(int) | Criptografe o campo de permissões do Document. O resultado será escrito no campo Perms do dicionário de criptografia. Ao abrir um Document, o valor pode ser obtido em [`EncryptionParameters`](../encryptionparameters/) via o campo Perms. Permite verificar se as permissões do Document foram alteradas. |
| [GetOwnerKey](../../aspose.pdf.security/icustomsecurityhandler/getownerkey/)(string, string) | Cria um array codificado baseado em senhas que será escrito no campo O do dicionário de criptografia. Deve depender apenas dos argumentos fornecidos. A senha do usuário pode ser calculada a partir deste campo usando a senha do proprietário. Chamado durante a criptografia para prepará‑lo e preencher o dicionário de criptografia. O valor estará disponível em [`CalculateEncryptionKey`](./calculateencryptionkey/) para obter a chave a partir da UserKey. As senhas especificadas pelo usuário ao chamar a criptografia de Document serão passadas. As senhas podem não ser especificadas ou apenas uma pode ser especificada. |
| [GetUserKey](../../aspose.pdf.security/icustomsecurityhandler/getuserkey/)(string) | Cria um array codificado baseado na senha do usuário. Este valor é tipicamente usado para verificar se a senha pertence ao usuário ou ao proprietário, e para obter a chave de criptografia. Chamado durante a criptografia para prepará‑lo e preencher o dicionário de criptografia. A senha especificada pelo usuário é passada como argumento ao chamar a criptografia de Document. |
| [Initialize](../../aspose.pdf.security/icustomsecurityhandler/initialize/)(EncryptionParameters) | Chamado para inicializar a instância atual para criptografia. Observe que ao criptografar, ela será preenchida com os dados das propriedades transferidas `ICustomSecurityHandler`, e ao abrir o Document a partir do dicionário de criptografia. Se o método for chamado durante uma nova criptografia, então [`UserKey`](../encryptionparameters/userkey/) e [`OwnerKey`](../encryptionparameters/ownerkey/) serão nulos. |
| [IsOwnerPassword](../../aspose.pdf.security/icustomsecurityhandler/isownerpassword/)(string) | Verifique se a senha é a senha do proprietário do Document. O método é chamado após Initialize. A chamada do método é usada na API PDF. |
| [IsUserPassword](../../aspose.pdf.security/icustomsecurityhandler/isuserpassword/)(string) | Verifique se a senha pertence ao usuário (senha para abrir o Document). O método é chamado após Initialize. A chamada do método é usada na API PDF. |

### Veja Também

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


