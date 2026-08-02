---
title: "ICustomSecurityHandler.Initialize"
second_title: "Referência da API Aspose.PDF para .NET"
description: "Método ICustomSecurityHandler. Chamado para inicializar a instância atual para criptografia. Observe que, ao criptografar, será preenchido com os dados das propriedades transferidas ICustomSecurityHandler e ao abrir o documento a partir do dicionário de criptografia. Se o método for chamado durante uma nova criptografia, então UserKey e OwnerKey serão nulos."
type: docs
weight: 120
url: /pt/net/aspose.pdf.security/icustomsecurityhandler/initialize/
---
## ICustomSecurityHandler.Initialize method

Chamado para inicializar a instância atual para criptografia. Observe que, ao criptografar, será preenchido com os dados das propriedades transferidas [`ICustomSecurityHandler`](../), e ao abrir o documento a partir do dicionário de criptografia. Se o método for chamado durante uma nova criptografia, então [`UserKey`](../../encryptionparameters/userkey/) e [`OwnerKey`](../../encryptionparameters/ownerkey/) serão nulos.

```csharp
public void Initialize(EncryptionParameters parameters)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| parâmetros | EncryptionParameters | Os parâmetros de criptografia. |

### Veja Também

* class [EncryptionParameters](../../encryptionparameters/)
* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


