---
title: Enum PasswordType
second_title: Aspose.PDF for .NET API Reference
description: Enum PasswordType do Aspose.Pdf. Este enum representa os tipos de senha conhecidos usados para documentos PDF protegidos por senha
type: docs
weight: 8290
url: /pt/net/aspose.pdf/passwordtype/
---
## Enumeração PasswordType

Este enum representa os tipos de senha conhecidos usados para documentos PDF protegidos por senha.

```csharp
public enum PasswordType
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Nenhum | `0` | O documento PDF não está protegido por senha. |
| Usuário | `1` | O documento PDF foi aberto usando a senha de abertura do documento (acesso restrito). |
| Proprietário | `2` | O documento PDF foi aberto usando a senha de alteração de permissões (acesso total). |
| Inacessível | `3` | O documento PDF está protegido por senha, mas tanto as senhas de usuário quanto de proprietário não estão vazias e nenhuma das senhas foi definida ou a senha fornecida estava incorreta. Portanto, é impossível deduzir o tipo da senha. |

### Veja Também

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)